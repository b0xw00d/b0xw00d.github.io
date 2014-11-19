<!-- This template is in markdown, not html, so
  it will not render beautifully when you copy and
  paste it into your github.io site, but it will at
  least be published. Next week you'll be creating a
  blog template using HTML and CSS and you'll be able
  to copy and paste the blog posts from week 1 in there
  to make them pretty next week.

  For now, please replace the title, subtitle (if desired),
  and date with the text you would like. Markdown is pretty
  simple, so you can just feel free to type. =) You'll want
  to delete this chunk of a comment as well. -->


Chase Nutile's DBC Technical Blog

Week 1

11/19/2014

This week I learned all about git and github at DBC.  Both are useful version control tools for web developers.  I'll do my best to clearly share what I've learned with you here.  Bear with me now!

I'll start with version control.  Version control is a system for storing and sorting different iterations (versions) of a project.  This is helpful because it allows multiple people to be working on their own copies of the same files.  It also allows users to save older versions of code which they can revert back to, if needed.  Basically, if a mistake is made that breaks the project there are earlier, working versions the program.

So git is especially useful in helping users to keep track of changes they've made to a project!  Great!  Now how do you use it?  I started by forking the project I wanted to use into my own github profile, then cloning it to my computer.  Forking a project is, essentially, making an exact copy of it that lives on your profile.  That way you can make changes without affecting the original files.  This fork will live on the web (your github profile).

In order to make changes on you computer, you need to clone this fork in your terminal, using git.  That will give you a local (on your hard drive) copy of the project so you can open it in Sublime and mess around a bit.  Any changes made can be saved as commits.  If you'd like to view all the changes made to a file, the commit history is available to you by typing: git log; in the proper directory.  To add your commits to the main project you'll have to "push" it back to github.  This is done using: git push [REMOTENAME] [BRANCHNAME];.  To check your remote names, you can type: git remote -v;.

To track changes that have been made to the master branch of the project you can "pull" them from github with a "pull request".  This can be done with the following command in terminal: git pull [REMOTENAME] [BRANCHNAME];.  After running that code you can see what other coders have pushed to the project since your last pull.

It's helpful to have both local and remote copies of these projects and the changes you've made for the sake of collaboration.  These also serve as a backup files.

I've learned a lot about git and github over the past couple of days and it's all pretty new to me.  I am by no means an expert.  I hope this was all clear enough though!  Thanks for reading!


