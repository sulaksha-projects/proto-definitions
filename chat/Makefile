PROTO_FILE=chat.proto
OUT_DIR=.

generate:
	protoc \
		--go_out=$(OUT_DIR) \
		--go-grpc_out=$(OUT_DIR) \
		--go_opt=paths=source_relative \
		--go-grpc_opt=paths=source_relative \
		$(PROTO_FILE)

.PHONY: generate
