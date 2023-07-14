# initialize a git repository
initialize_git:
	@echo "Initializing git..."
	git init

# install dependencies and pre-commit
install:
	@echo "Installing dev requirements..."
	poetry add -D tox
	poetry add -D pdoc
	poetry add -D pre-commit
	poetry run pre-commit install

# activate virtual environment
activate:
	@echo "Activating virtual environment"
	poetry shell

# setup project
setup: initialize_git install

# view API documentation
docs_view:
	@echo View API documentation...
	poetry run pdoc src -h localhost -p 8082

# save API documentation
docs_save:
	@echo Save documentation to docs...
	poetry run pdoc src -o docs

# delete all compiled Python files
clean:
	find . -type f -name "*.py[co]" -delete
	find . -type d -name "__pycache__" -delete
	rm -rf .pytest_cache

# export requirements
export_requirements:
	@echo Exporting requirements...
	poetry export -f requirements.txt --output requirements.txt --without-hashes