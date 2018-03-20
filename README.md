# Code Jam 1

This is the repository for all code relating to our first code jam, in March 2018. Participants should fork this repository, and submit their code in a pull request.

**This code jam runs from the 23rd of March to the 25th of March, measured using the UTC timezone.** Make sure you open your pull request by then. Once the deadline is up, stop pushing commits - we will not accept any submissions made after this date.

## How To Participate

First things first - set up your repository. Read [this guide on our site](https://pythondiscord.com/info/jams) for information on how to set yourself up for a code jam.
Remember, only one teammate needs to fork the repository - everyone else should be granted access to that fork as a contributor, so that they can work on it directly.

Make sure you have the following things installed:

* Python 3.6 or later (installed with the PATH option enabled if you're on Windows)
* Pip - make sure you can run `pip` in a terminal or command prompt
* Pipenv - you can install this by running `pip install pipenv` in a terminal or command prompt
    * Like before, make sure you can run `pipenv` in a terminal or command prompt

Next up, install the project dependencies with `pipenv sync --dev` - this will also create a virtualenv for you automatically. If you need to edit your environment
to add or remove packages, you can use `pipenv install packagename` and `pipenv uninstall packagename`, and the `Pipfile`s will be updated for you automatically. Your
team members should run `pipenv sync --dev` again if you do this.

To get access to a shell, use `pipenv shell`. You can use `pipenv run filename.py` to run a Python file, or `pipenv run python -m module` to run a module instead.

**Make sure you use Pipenv** - if you do not, your dependencies won't be available to your project.

If you'd like to run or debug your code from within your IDE or editor, take a look at the output of `pipenv install --dev`. You'll notice that it gives you the path
to the virtual environment it's created - For example, `/home/username/.virtualenvs/code-jam-1-FgMl5Zkj`. You can add the interpreter from your virtualenv to your
IDE or editor as an interpreter. You'll find it in the `Scripts` directory - for example, `/home/username/.virtualenvs/code-jam-1-FgMl5Zkj/Scripts/python.exe`.

If you need help with any of this, feel free to ask on the server.

## The Task

There will be no details on the task available until the code jam is about to start. However, we can tell you that you will be provided with a template project to work on this month. We will also be providing automatic linting using Travis CI. This will test your pull requests only, so we recommend that you open your pull request as soon as you've pushed a commit to your project.

This month's theme is: **Snakes**.
