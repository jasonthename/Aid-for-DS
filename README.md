<h1>Counting words in Sentence</h1>
Steps:<br>1. Take a string as input.<br>
2. Using for loop search for a empty space in between the words in the string.  
3. Consecutively increment a variable. This variable gives the count of number of words.

Code(Not mine -  Credit: https://www.sanfoundry.com/c-program-count-words-in-sentence/): 

<br>#include <stdio.h><br>
#include <string.h><br>
    void main()<br>
    {<br>
    char s[200];<br>
    int count = 1, i;<br>
    printf("enter the string\n");<br>
    scanf("%[^\n]s", s);<br>
    for (i = 0;s[i] != '\0';i++)<br>
    {<br>
    if (s[i] == ' ')<br>
    count++;<br>
    }<br>
    printf("number of words in given string are: %d\n", count);<br>
    }<br>

 &nbsp;**Warning: Remember to make changes so it won't look plagarised lol**
<h2>Circular Linked List Program</h2>
<p>Again, this is not mine but taken from some annoying website with ads that tried to block me from getting the code okay :-/
<br><br> Code can be found at: https://repl.it/@jasonthename/Aid-for-DS-Assignment

**WARNING: This is not mine but you may need to make changes here also**
 <br>You can also do Google Searches on Circular Linked Lists for more info.
