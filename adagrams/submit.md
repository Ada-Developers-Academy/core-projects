# Submit: Adagrams

## Submit Project for Grading

<!-- prettier-ignore-start -->
### !challenge
* type: testable-project
* id: b8a12109-a8d6-40d4-b7f7-900e32cd8962
* title: Fork URL for Grading
* upstream: https://github.com/AdaGold/adagrams-py
* validate_fork: false
* points: 0
* topics: python, python-oop
##### !question

How to submit using Git for the first time:

1. Go into your project folder `$ cd adagrams-py`
1. Confirm that your project was a fork from the original project repo:
    - Run `$ git remote -v`
    - Confirm that `origin` has a value of _**your own**_ project repo. Your GitHub username should be in the path of `origin`
1. Make a commit with all of the project files:
    - Add all files to staging with `$ git add -A`
    - Make a commit with a meaningful commit message `$ git commit -m "Your message here"`
1. Push your project commit to your own project repo
    - Run `$ git push` or `$ git push origin main`
1. Get the URL of _**your own**_ project repo.

Place the URL of your project repo here.

##### !end-question
##### !placeholder

The URL to your project repo on GitHub: https://github.com/<your-username>/<project-name>

##### !end-placeholder
### !end-challenge
<!-- prettier-ignore-end -->

## Submit Project for Feedback

Instructors provide code feedback through pull requests.

<!-- prettier-ignore-start -->
### !challenge
* type: short-answer
* id: 5b90babb-bd0c-4bde-8eac-7b92a3623d86
* title: Pull Request for Feedback
* points: 3
* topics: python, python-oop
##### !question

How to make a Pull Request on GitHub for the first time:

1. Go to your project repo on GitHub, typically `https://github.com/<your-username>/<project-name>`
1. Navigate to the Pull Requests tab
1. Begin a new pull request by clicking "New Pull Request"
1. Configure this PR so it compares your project against Ada's:
    - **base repository** is `<some-ada-repo>/<project-name>`
    - **base** is `main`
    - **head repository** is `<your-username>/<project-name>`
    - **compare** is `main`
1. Add more details by clicking "Create pull request":
    - For the PR title, include:
        - Your class name
        - Your name
        - Ex: "Octothorpes - Simon D."
1. Finish this PR by clicking "Create pull request"
1. Grab the URL of this PR, typically `https://github.com/<some-ada-repo>/<project-name>/pulls`

Place the URL of the pull request here.

##### !end-question
##### !placeholder

The URL to your team pull request: https://github.com/<some-ada-repo>/<project-name>/pulls

##### !end-placeholder
##### !answer

/.+/

##### !end-answer
### !end-challenge
<!-- prettier-ignore-end -->
