build:
	mvn package
	cp target/test-resolution-type-bool-1.0.jar ./test-build.jar
	go run ../../../tools/local-image/main.go $(PWD)
