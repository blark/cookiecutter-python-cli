## What is this?

A default template for a new CLI project, written in Python.  Deals with all
the boilerplate involved in the setuptools setup, etc.

## How do I use this?

Here's my preferred way to awesomeness:

1. Start by installing `pipsi`.  It's awesome.
   [Instructions here.](https://github.com/mitsuhiko/pipsi#readme)
2. Now install Cookiecutter:
   `$ pipsi install cookiecutter`.
3. Now use Cookiecutter to create your brand new project:
   `$ cd ~/Desktop && cookiecutter https://github.com/nvie/cookiecutter-python-cli.git`

## How to answer these questions?

When running Cookiecutter, you'll need to provide some values.
Here's what they're for:

* `project_name` -- "My Tool"   (Used for marketing.  Keep it short and capitalize accordingly.)
* `repo_name` -- "mytool"  (Name of the GitHub repo.)
* `script_name` -- "my-tool"  (Binary of the script, i.e. what people will run on the command line.)
* `package_name` -- "my_tool"  (Name of the Python module/package used internally.)

