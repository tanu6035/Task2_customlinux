internsctl is a custom Linux command designed to provide a set of functionalities. This command offers the following features:

Version Information
Help Documentation
CPU Information
Memory Information
Create New User
Displays Users list 

All the commands are made in git bash using bash script.

how to run the above command in gitbash:
1.check the version of internsctl, run:  ./internactl --version
2. To display information as help to users ,run : ./internsctl --help
3. To display CPU information of the system , run: ./internsctl cpu getinfo
4. To display memory information of the system , run : ./internsctl memory getinfo
5. To create new user run: ./internsctl user create <username>
6. To display all users in the system, run: ./internsctl users list
