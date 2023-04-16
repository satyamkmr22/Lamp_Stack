# Details

Rename this file in the format `yourRollNumber_solution.md` (example, `220000_solution.md`) and submit the solution in the Google form link provided 
*** https://forms.gle/RZtKpFcKfrWrYYxF9 ***


## Your zeroth approach below

Reasoning - The file is named zeroth.c indicates that it is to be run in the c compiler.After fixing the error given by the compiler.(int ved[] was defined as integer array but has characters as well as integers stored in it which was an error). So by commenting out that part, we get the output as type "man" command in linux, which gives the output below.Also, the c code has a clue "#define clue_of_1 not ROT13 try all".This was a clue for checking for ROT CIPHERS.
The c program gives output-"The answer of this challenge is output of "man" when run on the terminal, copy the exact output".

```
 Answer - "What manual page do you want?"
 
 ```

## Your first approach below (first.txt)

Reasoning - Since the clue was not checking ROT13 but this gave clue for checking other possibilities of ROT CIPHER.So by adding each letter of the given text in "first.txt" by 8 in a cyclic manner we see that a logical sentence is being created.Also it was written in the hint for strings.txt "the alphabets are to be to rotated further" For example-"a" was replaced with "i", "b" was replaced with "j" and so on..
Likewise "s" was replaced with "a", "t" was replaced with "b","u" was replaced with "c" and so on. I got this idea with the help of ROT CLUE which adds a number to the alphabet and prints that character.

```
ANSWER-"NOICEE you did crack a rotation encryption on your own. The following is a clue for the next puzzle: CLASS of that INPUT"

```


## Your second approach below (strings.txt)

Reasoning - In accordance with the clue given in the previous statement.I simply downloaded the file named "Lamp_Stack_Task.zip" and extracted it in linux command shell.(The file Lamp_Stack_Task.zip was left unsed in the question till this time and also here comes the possiblity of existence of "strings.txt" in the unzipped folder of this zip file.)This created a file named "Lamp_Stack_task" when extracted.Now by using the command "grep "example" /home/user/documents/*.txt" in the command panel we got the location of the file which contained the password string(8dc2evcCSSc4kUy).
Location of all the strings in file strings.txt is;
1-8dc2evcCSSc4kUy-"./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/eleven.txt","./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/final.txt"(password)
2-TqMuGims7vlJtno-"./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/final.txt","./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/ten.txt"
3-ORNwuwGtKDLydge-"./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/five.txt"
4-g4JoMqFZyat9vd5-"./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/eight.txt","./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/final.txt"
5-kPVEQPc6ZN8x2jn-"./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/seven.txt","./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/final.txt"
6-DabAWF1UenBD2W-"./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/three.txt","./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/five.txt"
7-kw4QLNylm2inErX-"./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/final.txt","./Downloads/Lamp_Stack_task/question_mark/Lamp_Stack/six.txt"
So on trying the password I got password "eleven.txt" for extracting the fourth.zip file.

```
ANSWER-Answer to the problem is password for the fourth.zip folder which is "eleven.txt".

```

## Your third approach below (fourth.zip)

Reasoning - From the password recieved by the previous result we extracted the file in linux command shell by using the command "cd / source" and then by "unzip fourth.zip".By these two commands we were able to get the file named "get_in" which contained different text files amoung which we have to search DevOps{...} string.
Again by using "grep" command to find the text in multiple folder using linux command shell, I found the string's location.This string was found in "./Downloads/get_in/4/2_inner/0.txt.
And the string contained "y0ur3_4w350m3_4nd_0ne_5t3p_c1053r" inside it

```
ANSWER-0ur3_4w350m3_4nd_0ne_5t3p_c1053r

```

---

- Name :SATYAM KUMAR
- Roll :220983
- GitHub username:satyamkmr22
- Discord username:satyamkmr22#3790


## Do not tamper below this line

---

Q29yZSB0ZWFtIGtvIGZha2UgZG8=
