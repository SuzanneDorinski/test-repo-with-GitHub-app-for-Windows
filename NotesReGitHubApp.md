##Notes to myself about using the GitHub app for Windows 8.1.

As far as I can tell, the GitHub app for Windows is designed
to be used so that you can skip the Git Bash command line 
completely.

If one can use the GitHub app for windows with a repo already
created in Git Bash, I am stumped on how to do it.

So, what is the GitHub app good for?  If you create a new repo
on GitHub, you can use the GitHub app to clone the repo to your
pc.  

The app will clone the repo to
C:\Users\your-user-name\Documents\GitHub\RepoNamefromGitHub

You can add files to your local repo, and then use the GitHub 
app to push them to the repo on GitHub.  

It appears that the app handles all the commit commands in the
background.  What's really great about the app is that it can
store your credentials, so that it's easy to push your changes
up to your GitHub account if you have two-factor authentication
enabled on your GitHub account.

Recall that if you have two-factor authentication enabled on 
your GitHub account, using Git Bash to submit the git push 
command will prompt you for your user name and password.  BUT 
you type your special token instead of your password, and the
token is really long, and if you are doing the git push while
using RStudio, you need to remember that the prompt dialogues 
may show up in RStudio rather than the Git Bash window.  

And also note that the special token that you type in is NOT 
the token from the authentication app.  Nope, it's the token 
you use when calling the GitHub API.
