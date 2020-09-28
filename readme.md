allows you to use docker to control you command line versions of php

install: 
1. mv ./bin/find_php_rc to your bin path (~/bin/find_php_rc)
2. give +x permissions to find_php_rc
	test by running find_php_rc (will provide 5.6 as default version
3. add alias.bash to .zshrc or .bashrc 

4. run php --verison
	system will download docker and install (only needs to do this once)
	then will output version

5. to change version in project, add a file .phprc to the folder that contains the targeted version (add 7.4 for 7.4)



