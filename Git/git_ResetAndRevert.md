--> Undo the changes made to a file in local work area. 
 git checkout {filename} 
 git checkout .	: For all files. 

--> Undo the recent commit to previous commit.
	--> This will remove the files and commit history too.
 git reset HEAD~1
