#GIT COMMANDS

```git init```

```git status``` _(if the file was not added, the filename color will red)_
	
```git add filename.ext```

```git status(if the file was not added, the filename color will green)```

```git commit -m 'Description here'```

##Now we will create a new repository on github and clone it on the computer in the project directory

```git clone https://www.github.com/MartinoSoyen/EasyLife.git```_(Remember the .git extension at the end of the file)_

##We will talk now about the ```git push``` command. !! Notice that before making a git push you have to make the **git add and the ```git commit``` to make your unpushed files ready to be uploaded
#Here is how to use the _git push_ command

```git push origin branchName``` _git push orgin master_

##To recommit a filename that has already been added use

```$git commit -a -m "any description you want to add"``` _The -a parameter makes this possible but it is only used on files that have already been added via the $git add command_



##To remove a file in the github repository

$git rm filename.ext or $git rm --cached filename.ext

_To remove all files run_ ```git rm --cached -r```