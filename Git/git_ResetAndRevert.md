--> Undo the changes made to a file in local work area. 

 git checkout {filename} 

 git checkout .	: For all files. 


--> Unstage the changes.

	--> To get back a file to local work area from staging area.

 git reset HEAD {filename}


--> Undo the recent commit to previous commit.

	--> This will remove the files and commit history too.

 git reset HEAD~1
