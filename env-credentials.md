# Using .env for Database Credentials

## Why is it more secure to use a .env file?
Storing credentials in a .env file instead of hardcoding them in the codebase prevents sensitive information from being exposed in version control. It reduces the risk of accidental leaks.

## How does python-dotenv simplify managing environment variables?
`python-dotenv` allows us to load environment variables easily into Python scripts or Jupyter Notebooks. This makes it easier to manage credentials securely and change them without modifying the code.
