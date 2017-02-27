## Tiny-Compiler ##

# To run the compiler as well as the language you need to do the following:
Download TWS.zip 
Unzip it to a directory.
Open teminal(mac or linux, does not support windows).
Go to your directory.
Go to tws/.
Run make
Go to tws/tiny and run make 
Run command chmod +x tc(you don't need to do it if tc is already executable)
And you are good to go!

# Some sample tiny programs are there in tests folder as well as some complex test cases in test-progs folder

# To run these test cases you need:
Go to tiny directory.
Use command ./tc tests/filename or ./tc test-progs/filename, where tests and test-progs are the directories and filename is the name of file you want to execute.
Done!

# NOTE: 
Before running any test case, open it first(in any editor you want) and read the comments describing what the test case does and what are the inputs(if any) and outputs, will help you a lot!
Some test cases might give a parse error as the compiler is supposed to give for some test cases.
Its preferable to run test cases in test-progs/pr4 as there were some changes made in the code in later stages which might generate some errors in other test cases.
