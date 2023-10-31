*meow
*woof
*mooo
_________________________________________________________________________________________________
LAB REPORT 1

CD
![Image](cdSectionLab1.PNG)
![Image](cdEmptyArglab1.png)

1. no argument, working directory was simply the home directory because i was working within there, because there was no argument the directory was never changed because i didnt tell the program what directory to switch to, this is not an error! However, when I cd to lecture1, then ran cd w no argument it simply backed up one level to the home directory. this is not an error. 
2. run w directory, when the command was run i changed the directory from simply the repository to lecture1, my output was that i was working within the lecture1 directory as evidenced by my next command line. this makes sense because id told the program to work within the lecture1 directory, this is not an error!
3. run w file, it was within the lecture1 directory when i tried to run w Hello.java, then i changed directory to messages and tried to run the txt files. i got the error outputs because i passed in a file name as arguments, but you can't work within a file and that argument isn't accepted for the cd command (literally tells you it changes to a directory), so this is an error!


LS
![Image](lsSectionLab1.PNG)
![Image](lsSectionLab1pt2.PNG)
1. no argument, i was in the messages directory when i ran this so the output was a list of the text files with "hello world" in a couple different languages because those were the files within the messages directory, and the ls command lists the contents in a directory, so this is not an error!
2. directory, i did this twice. the first time (picture 1) i was working within the messages directory, and it gave me an error message that said it could not access the file or directory. that is because i was already in there and it was looking for a directory within the one i was already in. however, in picture 2 i backed out using cd .., and when i worked within the lecture1 directory, and ran ls messages the terminal successfully listed the text files within messages
3. run w file, in picture 1 under ls i was in the messages directory and ran ls en-us.txt. it outputted the contents of the file which is simply itself, this is not an error

   
CAT
![Image](catsectionlab1.PNG)
![Image](catsectionlab1pt2.PNG)
1. no argument, i was in the messages directory and it simply returned my cursor down the terminal and let me type within the terminal freely- that is where i tried to run cat messages and then it simply reprinted what id typed. this is not an error
2. run w directory, in the first picture you can see it says no such file or directory which is not error message when i ran it within the messages directory. however, i backed out to just the repository (picture 2) and found the cat lecture 1 outputted a descritpion of lecture1 as a directory. when i tried to run cat messages, i got a message that said there is no such file or directory, this is not an error. I suppose cat only works on the first layer and didn't search the lecture1 directory for the messages directory another layer deeper.
3. run w file, in picture 1 under cat i was in the messages directory and i ran cat en-us.txt, which printed the contents of the file to the terminal because id passed the file name as an argument into the command. this is not an error



______________________________________________________________________________________________________
Lab Report 2

PART 1

![Image](labreport2SC1.png)

This calls the `handlerequest` method, and the relevant fields are `r` and `num`. `r` changed from "1. mew" to "1. mew \n 2. hellooo", and n changed from 1 to 2. The url i typed in was passed in, the path was "/add-message?=hellooo". all fields changed. 

![Image](LabReport2SC2.png)

This calls the `handlerequest` method, and the relevant fields are `r` and `num`. `r` changed from "1. mew \n 2. hellooo" to "1. mew \n 2. hellooo \n 3. okayipullup", and n changed from 2 to 3. The url i typed in was passed in, the path was "/add-message?=okayipullup". all fields changed. 

below is my code for StringServer!
![Image](LabReport2SC3.png)

![Image](LabReport2SC4.png)

PART 2
![Image](LabReport2SCPrivLogin.png)
![Image](LabReport2SCPublicLogin.png)
![Image](LabReport2SCLogin.png)

PART 3
I didn't know that you could remotely connect to a computer, that was new to me. My understanding for the most part was that we run things from the coputer we are physically on, so learning how to do that conceptually was cool. I suppose, specifically the ssh command and the process of logging into my cs15l account
/Users/taniafrank/.ssh/id_rsa.pub

