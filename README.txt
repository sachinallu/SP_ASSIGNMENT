##################################

Name:Sachin.R

USN:1PI12IS092

QUESTION NO:02

#################################

QUESTION:
Write a sign up program for a user that asks the user to enter a USERNAME,PASSWORD and NAME are written into file in the following format:
			username1,password1,name1

		username2,password2,name2
	
		......

################################

EXECUTION STEPS:

Code is written in C.
Since we used command line arguments to take input so to run the code we use
 
$ ./a.out -f <input_file> -l <log_file> 
where input_file is the file that contains data and the log.txt is the file where record of all activities and events that happen in a program.
#################################

VALIDATIONS:

1.Username should have characters no between 3 to 21

2.Password should have characters no between 3 to 15 

3.It will not allow duplicate Username

#################################

