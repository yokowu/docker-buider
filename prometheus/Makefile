.PHONY: build

all: build run

build:
	docker build -t my-prometheus .

run:
	docker run -d -p 9090:9090 --net=host my-prometheus