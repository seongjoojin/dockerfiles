.PHONY: build install run down

build: 
	docker-compose build

install:
	docker-compose run --rm next yarn create next-app next

run:
	docker-compose up

down:
	docker-compose down