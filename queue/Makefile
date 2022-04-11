# phony rules
.PHONY: build
build:
	@docker run --rm -it -v E:/goDsa/queue/:/go/src test-go bash -c "go build -o go-test queue.go"

.PHONY: build-image
build-image:
	@docker build -t=test-go . 

.PHONY: run
run:
	@docker run --rm -it -v E:/goDsa/queue/:/go/src test-go bash -c "go run queue.go"
