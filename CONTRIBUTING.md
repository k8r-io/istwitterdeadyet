# Contributing

## Setup
1. Follow instructions [here](https://gohugo.io/getting-started/installing) to install Hugo
2. Sign up for a Github account if you haven't already and login to Github
3. Fork this repo
4. `git clone <forked repo URL>`
5. `cd istwitterdeadyet`
6. `git submodule init`
7. `git submodule update`

## Start the local server
1. `hugo server -D`
2. Visit [http://localhost:1313/](http://localhost:1313/) on your browser

## Adding an event
1. Create a new `.md` file in `content/events/` with your favorite text editor and copy the text from one of the other `.md` files
2. Change the text in the `.md` file so it reflects the desired content
3. You can edit an existing event by editing its respective `.md` file
4. Refresh the page in your browser to see changes

## Creating a pull request
1. `git checkout -b <branch name>`
2. `git add .`
3. `git commit -m "<description of changes>"`
4. `git push --set-upstream origin <branch name>`
5. Go [here](https://github.com/tmcarr/istwitterdeadyet.git) and create a new Pull Request.
6. Wait for approval and then merge your Pull Request
7. Your changes will be up on [https://istwitterdeadyet.info](https://istwitterdeadyet.info) shortly
