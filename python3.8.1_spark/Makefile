VERSION=3.8.1_spark
NAME=decibel/python-checks

default: build

tag:
	docker tag $(NAME) $(NAME):$(VERSION)
	docker tag $(NAME) $(NAME):latest
	#git tag $(VERSION)

push:
	#git push --tags
	docker push $(NAME):$(VERSION)
	docker push $(NAME):latest

build:
	docker build -t $(NAME) .

all:
	@echo "Makefile needs your attention"


