# Personal academic website

A very minimal example

## To run locally

1. fork the repository by hitting the **Fork**-button on the top right and pick your profile
1. clone the repository with `git clone git@github.com:username/digieast.github.io.git`
2. `cd digieast.github.io`
2. edit the content of .md files or create new ones
3. edit the links to pages & css files in `_layouts/default.html`
4. edit the _config.yml and change the baseurl to match your future repository. It may be `http://username.github.io/`
4. run `jekyll serve --watch --baseurl ''` to build the site locally and to react to your edits

## To run it in your username.github.io

Once your are happy with how it looks like:

1. create a new repository `username.github.io` at GitHub
2. reset the remote for your project `git remote set-url origin git@github.com:username/username.github.io.git`
3. add new files to git using `git add --all`
4. stage and commit the changes with `git commit -a -m "message comes here"`
5. push the first time `git push -u origin master`

## Update your remote site

1. add, remove, change files
2. add new files to git using `git add --all`
3. stage and commit the changes with `git commit -a -m "message comes here"`
4. push the committed change `git push`
