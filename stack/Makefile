# phony rules
.PHONY: build
build:
	@docker run --rm -it -v E:/goDsa/stack/:/go/src test-go bash -c "go build -o go-test stack.go"

.PHONY: build-image
build-image:
	@docker build -t=test-go . 

.PHONY: run
run:
	@docker run --rm -it -v E:/goDsa/stack/:/go/src test-go bash -c "go run stack.go"
