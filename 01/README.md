# Intro to Web Design &amp; Computer Principles | NYU | Spring 2019
## Assignment 1
There are two parts to this assignment. The first involves using your command line interface (CLI) to practice the commands we learned in the first few weeks of the semester.

The second involves editing and moving files local to your machine onto a remote server, in this case, NYU’s i6 server.

### Before You Begin
Note the file `answers-file-for-assignment-01--NETID.txt`. Make a copy of this file anywhere on your machine, replacing `NETID` with your NYU NetID. For example, my copied file would be called `answers-file-for-assignment-01--rav317.txt`.

Put your first name, last name, and NetID number on the first line of the copied file, after the hash character (`#`). 

This is the file in which you’ll be adding your answers to the questions below, and it’s also the file you’ll submit via NYU Classes.

### Part 1
Launch your CLI and navigate to the root of this assignment’s folder, which is called `1`.

1. What is the output of `head index.html`?
2. What is the output of `head -1 index.html`?
3. What is the output of `tail README.md`?
4. What is the difference between the `cat` and `more` commands?
5. What is the command to clear your CLI?
6. What is the command to take you home, regardless of where in your file system the command is run?
7. In the **Before You Begin** section above, what is the command to copy the file using `cp`?
8. What is the command to create a new, empty file called `file`?
9. How do you recursively remove all files and folders from `folder` without interaction from the CLI?
10. Explain the difference between `./` and `../`.

### Part 2
You should have received an email from `helpdesk@cims.nyu.edu` with the subject **Welcome to Courant**. That message should contain valuable information about accessing NYU’s i6 servers, which is required for this part of the assignment. Here are some important items.

| Item            | Value                               |
|----------------:|-------------------------------------|
| *Host*          | `i6.cims.nyu.edu`                   |
| *User*          | `Your NYU NetID`                    |
| *Password*      | `Courant-issued`\*                  |
| *URL*           | `https://i6.cims.nyu.edu/~netid`    |
| *Web Directory* | `public_html`                       |

\*If you need to reset your i6 password, visit [https://cims.nyu.edu/webapps/content/systems/resources/i6/resetpassword](https://cims.nyu.edu/webapps/content/systems/resources/i6/resetpassword).

1. Open `index.html` in Atom. Replace the content in all caps with the content it’s requesting. Save the file when you’re done.
2. Using `scp`, copy `index.html` to the `public_html` folder of your account on the i6 server, then open a browser and navigate to your web site on the i6 server. You should see your new web page.
3. Log in to your i6 account.
4. `cd` to the `public_html` folder.
5. Make a folder called `css`.
6. Log out of i6.
8. Using `scp` again, copy `style.css` to the `css` folder.
9. Revisit your i6 web page, refreshing the browser. Does it look different?
10. Add the URL to your i6 web site to the **Part 2** section of the `answers-file-for-assignment-01--NETID.txt`

## Submission
Submit `answers-file-for-assignment-01--NETID.txt` via NYU Classes. Remember to replace `NETID` with your NYU NetID.

## Grading
This is a pass/fail assignment, with each numbered item worth 5 points.
