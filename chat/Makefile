PROTO_DIR=proto
OUT_DIR=.

PROTO_FILES=$(wildcard $(PROTO_DIR)/*.proto)

generate:
	protoc \
		--go_out=$(OUT_DIR) \
		--go-grpc_out=$(OUT_DIR) \
		--go_opt=paths=source_relative \
		--go-grpc_opt=paths=source_relative \
		$(PROTO_FILES)

.PHONY: generate
