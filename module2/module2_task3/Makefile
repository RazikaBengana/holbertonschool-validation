help:## Show command help
	@fgrep -h "##" $(MAKEFILE_LIST) | fgrep -v fgrep | sed -e 's/\\$$//' | sed -e 's/\##//'

build:## Compile source code of the application to a binary name awesome.api
	@go get github.com/gorilla/mux
	@make lint >/dev/null 2>&1 && go build || exit -1

run:## Run the application in background and write logs in awesome-api.log
	@./awesome-api >./awesome-api.log 2>&1 &

stop:## Stop the application
	@kill "$(shell pgrep awesome-api)" 2>/dev/null &

clean:## Stop the application and delete awesome-api and awesome.log
	@make stop && rm -rf awesome-api awesome-api.log coverage-units.out coverage-integrations.out

test:## Test to ensure expected beahaviour
	@make unit-tests
	@make integration-tests

lint:## Test lint on the files
	@golangci-lint run

unit-tests:## Run Golang uni tests
	@go test -v -short -coverprofile=coverage-units.out

integration-tests:## Run Golang integration tests
	@go test -v -coverprofile=coverage-integrations.out
