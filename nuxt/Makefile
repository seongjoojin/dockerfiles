.PHONY: build install run down

build: 
	docker-compose build

install:
	docker-compose run --rm nuxt yarn create nuxt-app

run:
	docker-compose up

down:
	docker-compose down