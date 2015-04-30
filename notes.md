##notes

- meaning of add command may not be clear to the uninitiated -- I thought maybe it would create the file for you in the project folder, or maybe you could move it in there from elsewhere
- I created the readme.md folder in my project folder and ran git add, but it didn't work:
C:\Users\mbradley\desktop\megan-test [master +3 ~0 -0 !]> git add readme.md
fatal: pathspec 'readme.md' did not match any files

tried nav to hidden .git folder and ran again:
C:\Users\mbradley\desktop\megan-test [master +3 ~0 -0 !]> git add readme.md
fatal: pathspec 'readme.md' did not match any files

Doug: should make it clear what path you should run it from

screenshots are great but hard to follow exactly - everything must be typed, and especially on small screens it's very easy to leave something out

a combination of screenshots and copyable screens for commands would be helpful

also, explain what "git remote" does -- that sets the remote branch? do you have to use it every time?

what does "Changes not staged for commit" mean? how do you stage?
 -- OK, so you have to use git add again, apparently, for each changed file