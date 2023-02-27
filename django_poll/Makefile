.PHONY: dev
dev: ## Start python app in development mode
	pip install -r requirements.txt
	python3 mysite/manage.py runserver

.PHONY: help
help:
	@grep -E '^[a-zA-Z_-]+:.*?## .*$$' $(MAKEFILE_LIST) | awk 'BEGIN {FS = ":.*?## "}; {printf "\033[36m%-30s\033[0m %s\n", $$1, $$2}'