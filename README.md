# testing git
# test 2

# after messing around with git, I found out that when you run 
# `git remote add origin git@github.com:kevin5112/<repository name>`
# it basically will add the remote repo on github and link it to your local machine.
# you add the `origin` because it's an alias so you don't have to type out the whole name

# additionally that means you can do 
# `git push -u git@github.com:kevin5112/<repository name> master`
# note here you don't use the alias origin where as you normally would just do
# `git push -u origin master`
# the `-u` flag just means set-upstream, meaning to set up your local branch to the remote repository so you can push

