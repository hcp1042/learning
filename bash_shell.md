 ~ stands for home directory
 
 \# for comment
 
 cat - reads files sequentially, writing them to standard output
 
 man - 'manual' 
 
 use ctrl + c to stop the program
 
 **Flag**
 
 good practice to put flag before file and other input
 
 good practice to have a space between flag and its parameter
 
 
 \> Redirect output to another file
 
 | pipeline, ways to connect inputs
 
 
 wildcard \* match 0 or more characters
 ? matches exactly one character
 
 [...] matches any one of the characters inside the square brackets
 {...,...} matches either element in the bracket


wc  -l count line

cut    select certain fields from data
grep   select certain rows

sort -r for reverse sort

uniq



**Batch Processing**


Environment variable

To see all use 'set'

echo    -  check value of env variable, add $ sign before variable


To create a shell variable, you simply assign a value to a name:

training=seasonal/summer.csv

without any spaces before or after the = sign




**Loop**

for var in list; do command $var; done

can use pipe in the do part

remember to add dollar sign when retriving the value of a variable


can use single quote or double quote around file names

can also assign multiple commands for a loop, need to separate commands with semicolon



### Creating new tools

nano - text editor, ^o to save, ^x to quit

save commands to xxx.sh, bash xxx.sh to run


pass filenames to scripts    "$@" to bear the name passed from the command line



