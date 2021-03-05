# How to Submit

<iframe src="https://adaacademy.hosted.panopto.com/Panopto/Pages/Embed.aspx?pid=951c36b9-b2dc-4c19-a299-acd9017a9d49&autoplay=false&offerviewer=true&showtitle=true&showbrand=false&start=0&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>

## How to Submit a Project

Unless there are other directions, the typical flow for submitting a project is
1. Getting all project code into your project repo on GitHub
1. Getting the URL of that repo

### Getting Code onto GitHub the First Time

1. Go into your project folder `$ cd project-name`
1. Confirm that your project was a fork from the original project repo:
    - Run `$ git remote -v`
    - Confirm that `origin` has a value of _**your own**_ project repo. Your GitHub username should be in the path of `origin`
1. Make a commit with all of the project files:
    - Add all files to staging with `$ git add -A`
    - Make a commit with a meaningful commit message `$ git commit -m "Your message here"`
1. Push your project commit to your own project repo
    - Run `$ git push` or `$ git push origin main`

### Getting Code onto GitHub

Use your git skills to make a git history and push it up!

### Navigating GitHub and Getting the URL

1. Navigate to github.com and log in
1. Navigate to your repositories with either method:
    - Navigate to your GitHub profile, typically `https://github.com/<your-username>`, and navigate to the "Repositories" tab
    - Click your profile icon on the top right, and select "your repositories" in the drop down menu
1. Find your project repo
1. Get the URL from the browser, typically `https://github.com/<your-username>/<project-name>`

## How to Make a Pull Request

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

Pull requests will determine if they can be automatically merged or not. In this curriculum, it doesn't matter. Create the pull request whether or not it can be automatically merged.