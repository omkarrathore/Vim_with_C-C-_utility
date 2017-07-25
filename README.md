#updated @ 2017,July 25
for Cvim_v2
This is the utility include some extra features to create, compile and run any C/C++ file and also can be used instead of vim command .

About Cvim command :

Eariler command can only be used to create only Cplusplus file but now
this command can be use instead of vim command to edit/create any kind of file

Usage  :
commandName  fileName  [-option]

option : 
-c to create file with extension .c
-cp to create file with extension .cpp
-h to create file with extension .h

Note 
1 ~ If a file is already existed ( with fileName and with any of these extension (.c/.cpp/.h) ) then it will open the existed file .
2 ~ If options is not specified for extension then create a file with name of a file as specified at fileName .

About Crun command :
Eariler command can complile Cplusplus file only but it can complie C file also

Usage :
commandName  fileName

# gitProject
This is simple file for C/C++ program to give feel like IDE in terminal .
Just do some editing :=
  ->Change Author Name in Cvim
  ->Change the compiler in Run from g++ -std=c++11 to your C/C++ compiler
  ->For making C file replace .cpp to .c everywhere in Cvim and Run file
 Add this File into your directory /usr/bin
 Now Let's start using this commands
  -> Cvim // I am creating a file of c++ 
  --> Cvim hi // this command will create a file hi.cpp and initilaize with some parameters
  ---> Type your code in hi.cpp and Save it 
  -> Now complie and run your file using Run command
  --> Run hi.cpp


