# crt_training_jul26
This repository is basically for my training session. We learn C program and try to solve problems. This is for 3rd yr student. This is for placement purpose and we will trained by Nitin sir
APP INSTALLATIONS:
vs code development notepad++ quick notes git to run git commands git desktop GUI App for Git mingw python node

CCC Trainer Nithin Repo Link: github.com/neelmyna/gitam_cdsa_jul26

Download mingw from sourceforge.net Double click the steup file and start installation Under Basic setup: Select the check boxes: mingw-base-32 gcc g++ And CLick -> Mark for installation Top list corner -> Installation tab -> Click Apply changes Click -> Apply (Installation starts)

In C drive, you must have folder: mingw Copy the path C:\mingw\bin

Add this to the Environment variables: Windows search: Edit Environment Variables Click the button -> Environment variables On top of the list double click path Click new and paste the path (C:\mingw\bin) Click ok ok ok Now reopen the cmd.exe and now you just be able to find the CLI/command/App Link To Register: https://tinyurl.com/nhcc8fp9

The Coding Practice has been successfully enabled on the SkillGraph LMS Platform.

Portal Access: https://quiz.skillgraph.school/login

Student Instructions
Log in to the portal.
Email ID: Use the same email ID that was registered on the SkillGraph LMS.
Password: Use the password you created during the registration process.
Go to Upcoming Quizzes to access the assessment.
Coding problems are available under the Coding Goals section. Students can view and solve the coding problems from the Ongoing section.
Important Note
Only students who have registered on the SkillGraph portal can access the coding practice.
Students must solve the coding problems using the same LeetCode ID that they provided during SkillGraph registration.
Ensure that the LeetCode ID entered during registration is correct, as it will be used to track coding progress.
Support Ticket
If students face any issues while accessing the portal or during coding practice, they should raise a Support Ticket along with a clear screenshot of the issue.

GIT HUB COMMANDS: Configuation commands:

$> git config --global user.name "neelmyna"

$> git config --global user.email "abc@xyz.com"

Lets Start C Programming
my_first_program.c

#include<stdio.h>
#define MAX_STUDENT_COUNT 60

int main() {
    int user_count = 0;
    // reading the user given student count
    if(user_count <= MAX_STUDENT_COUNT)
         // do something

    puts("I lovce C programming");
}

Explanation of the above code:
int puts(char const*);

OPTIONS WITH GCC:
gcc my_first_program.c
The above code will pre-process, compile (syntax cheking, translation and interpretation) and lastly liking and we get the executable (application/program) Note: The default executable file a.exe

gcc -E my_first_program.c
The above will stop after pre-processing. Thus the pre-processed code still human readable.

gcc -c p1.c
Stop after compilation. Thus we get object code. Note: Object code is machine specific/dependent. Thus the above command will generate object file.

DAY2 WEDNESDAY 29-07-2026

int main()
{
int num1 = 0, num2 = 10, num3 = 5;
num2++;
printf("Num1=%d, Num2=%d, Num3=%d \n", num1, num2, num3);
++num2;
printf("Num1=%d, Num2=%d, Num3=%d \n", num1, num2, num3);
num1 = num3--;
printf("Num1=%d, Num2=%d, Num3=%d \n", num1, num2, num3);
num2 = --num1;
printf("Num1=%d, Num2=%d, Num3=%d \n", num1, num2, num3);
num3 = num1++ + ++num1;
printf("Num1=%d, Num2=%d, Num3=%d \n", num1, num2, num3);
}
int main() {
    int x = 8, y = 13, z = -5;

    if(x++ >= y && --z != y--) {
        puts("I like to Climb Mountains");
    }
    else {
        puts("I like to participate in Tour De Farce");
    }
    printf("%d  %d  %d", x, y, z);
}
int main()
{
    int x = 8, y = 13, z = -5;

    if (x++ != y && --z == y-- & y == z || z-- != x--)
    {
        puts("I like to Climb Mountains");
    }
    else
    {
        puts("I like to participate in Tour De Farce");
    }
    printf("%d  %d  %d", x, y, z);
}

