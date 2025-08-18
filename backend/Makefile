.PHONY: setup format lint test coverage-report run-dev run-prod build

PROJECT_PATH=.

setup:
	@npm install
	@npm run migrate
	@npm run seed

format:
	@npm run format

lint: BLACK_OPTIONS := --check
lint: format
	@npm run lint

test:
	@npm run test

coverage-report:
	@npm run coverage

run-dev:
	@npm run dev

run-prod:
	@npm run start

build:
	@npm run build