.PHONY: build

all: build run

build:
	docker build -t my-prometheus .

run:
	docker run -p 9090:9090 my-prometheus