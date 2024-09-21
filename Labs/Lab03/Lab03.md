## Lab 03

- Name:Himani
- Email:himani.3@wright.edu

## Part 1 Answers

1. `ssh` command before configuring `config` file:
2. HostName:2350
3. User:ubuntu
4. IdentityFile:
5. `~/.ssh/config` contents:

```
Paste your config file entry here.  By placing it between these 
triple quote sets GitHub will make this look like a block of code
```

6. `ssh` command after configuring an entry in the `config` file:ssh 2350

## Part 2 Answers

1. `printenv HOME > thishouse`
   - Explanation: saves path of the home directory in thishouse
2. `cat doesnotexist 2>> hush.txt`
   - Explanation: prints error in hush.txt
3. `cat nums.txt | sort -n >> all_nums.txt`
   - Explanation: stores the sorted nums in ascending order
4. `cat << "DONE" > here.txt`
   - Explanation: takes input in terminal and saves in here.txt
5. `ls -lt ~ | head`
   - Explanation: sort first 10 fikes of home directory
6. `history | grep ".md"`
   - Explanation: search for history with string .md

## Part 3

Verify that `roll` made it to your GitHub repository for this course and is in your `Lab03` folder.  No answers will be written here unless you would like to leave a note to the TAs

## Part 4 - Retrospective Answers

1. Where and when did it go wrong while working on your script tasks?
> issues with inputs
2. Was anything familiar working with a new language compared to one you are used to?
> loops and contidional statements
3. Did you write good `commit` messages that refer to what tasks were completed at each commit?  What would you improve?
> yes

## Part 5 Answers

1. PATH =echo $PATH
2. To set condition to `true`, I need to...
3. Command(s):echo 'export PATH="/home/ubuntu/ceg2350f24-Himanii27/Lab03.$PATH"' >> ~/.profile
4. PATH =echo $PATH
   - Difference:there is a path now which was not there before
5. Command(s):source ~/.profile
6. Commands & modification explanations: it adds directory to path
7. Script permission breakdown
   - User
      - must be: owner of the scripts
      - has permissions to:execute
   - Group
      - must be:part of group owning the script
      - has permissions to:execute 
   - Other
      - has permissions to:execute

## Extra Credit

1. Note here *what* you did to the script for the extra credit.
