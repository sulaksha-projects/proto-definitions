PRODUCT_PROTO_FILE=product.proto
PRODUCT_OUT_DIR=../generated/product

generate-product:
	protoc \
		--go_out=$(PRODUCT_OUT_DIR) \
		--go-grpc_out=$(PRODUCT_OUT_DIR) \
		--go_opt=paths=source_relative \
		--go-grpc_opt=paths=source_relative \
		$(PRODUCT_PROTO_FILE)

.PHONY: generate-product
