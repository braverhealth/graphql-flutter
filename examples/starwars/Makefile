CC=dart
CC_UI=flutter


default: fmt dep
	@echo "This example now expects an external GraphQL server at localhost:3000"


dep:
	$(CC_UI) pub get

fmt:
	$(CC_UI) format .
	$(CC_UI) analyze .

clean:
	$(CC_UI) clean
