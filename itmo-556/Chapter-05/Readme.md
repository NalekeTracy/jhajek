# Chapter 5
## Part 1

1. Open a terminal, cd to the Documents directory. Issue the pwd command to find your present working directory (or current location).

![Present working directory](PWD.png)


2. In the Documents directory, use the mkdir command to create a directory named: class-notes

![classnote creation](Class-note.png)


3. cd into the class-notes directory. Issue the command to show your present working directory.

![PWD for classnote](class_note_PWD.png)


4. Create the a directory named distros in the class-notes directory. Once created take a screen shot of the output of the ls command in the distros directory

![Distros creation](distros.png)


5. Under the distros directory create a directory named: BSD

![BSD creation](BSD.png)


6. Under the distros directory create a directory named: Debian

![Debian creation](Debian.png)


7. Under the distros directory create a directory named: redhat

![redhat creation](redhat.png)


8. In the directory BSD use the command to create a file: Create three files names: oracle-linux.txt, openbsd.txt, and netbsd.txt

![BSD txt](BSD_file_txt.png)


9. In the directory Debian use the command to create a file: Create three three names: ubuntu.txt, freebsd.txt, and xubuntu.txt

![Debian txt](Debian_txt_file.png)


10. In the directory redhat use the command to create a file: Create three files names: fedora.txt, rhel.txt, and debian.txt

![redhat txt](redhat_txt_file.png)


11. cd to the distro directory and create a file named: omnios.txt

![Omnios txt](omnios_txt_file.png)


12. In the text files created you will notice that a few of them are out of place, such as debian.txt is in the redhat folder. Issue the command to move the text files to the correct locations and show a directory listing before and after the move command. (Hint: ls mv ls)

![debian txt move](MV_debian.txt.png)


13. Use the mv command to rename the redhat directory to have an uppercase "R"


![Redhat change](change_redhat_to_Redhat.png)


14. Use the rm command to delete the oracle-linux.txt file

![Oracle removal](rm_oracle_frm_BSD.png)


15. Use the mkdir command to create a directory in the distros directory named: illumos and move the omnios.txt file into the illumos directory


![illumos creation](Illumos.png)

![omnios move](mv_omni_txt.png)


16. What would be the command to cd from your current location to the relative path of ./distros/BSD directory using a relative path?

![BSD relative path](CD_BSD.png)


17. What would be the command to change directory from your current location to the Redhat directory using a relative path?

![Redhat relative path](CD_Redhat.png)


18. What would be the command to change directory to your HOME directory using the relative path?

![root home](root_path.png)


19. What would be the command to change directory from your HOME directory to the debian directory using a relative path?

![root to debian](Root_path_debian.png)


20. What would be the command, using an absolute path to change from your current directory to the /etc/ssh/ directory?

![ETC](etc_ssh.png)


# Part 2


1. Use the man command to figure out how to display the format of the date command as month, day, year combined to look like: 10152021

![Date format](correct_date_format-1.png)


2. Using the file on Ubuntu: /var/log/syslog, Type the command to display the last 10 lines of this file

![Last 10 lines](last_10_lines-1.png)


3. Using the file on Ubuntu: /var/log/syslog Type the command to display the first 10 lines of this file

![First 10 lines](first_10_lines-1.png)


4. Using the file on Ubuntu: /var/log/syslog, Using the man command on the previous question, find how to display the last 25 lines of this file

![Last 25 lines](last_25_lines-1.png)


6. Using the file on Ubuntu: /var/log/syslog, Type the command to display the entire contents of this file backwards (last line to first)

![System log tac](tac_syslog-1.png)


7. Using the file on Ubuntu: /var/log/syslog,  Use one of the commands to allow for paging through one of these commands (hit 'q' to quit the paging command)


![Syslog pager](less_syslog.png)


8. Change directory to the Documents folder under your HOME directory and issue the command to Git clone the textbook source code. Issue the command: git clone https://github.com/jhajek/Linux-text-book-part-1.git. (Hint: You may have to use your distro package manager to install the git tool)

![git install](git_install.png)


9. Issue the cd command to change directory into Linux-text-book-part-1 and then issue the command to display what type of file ./title/metadata.yaml is.

![meta data](git_install.png)


10. Issue that same command to display what type of file Appendix-A is.

![Appendix metadeta](git_install.png)


11. Using in the book source code, under files > chapter-05 > sample-script: copy the file sample-command to your home directory. Use the command to the give the script execute permission +x. Issue the ls -l sample-script/sample-command command to show the permissions of just the sample-command file


![execute permit](sample-command-execute-permit.png)


12. Move the file sample-command to the location /usr/local/bin (Note: you will need to add the sudo command in front to give yourself root privileges to move a file to this location)


![move to usr](move-sample-command-1.png)



13. From the command line (any location) execute the command: sample-command, and if succesful you will receive a message of success



![sample command works](sample-command-mv.png)


14. Execute the ssh-keygen command on the command line (from any location) and accept all the default values (just hit enter for now, we will cover RSA in depth later in the text). This command generates two files that are part of an RSA keypair, located in ~/.ssh

![ssh keygen](ssh-keygen-1.png)


15. cd into the directory ~/.ssh and type the command to show the long listing of the directory.

![ssh keygen files](ssh-files.png)


16. From the textbook sample code > Files > Chapter-05 > sample-scripts > copy the file date-time-script.sh to your home directory. cd to your home directory and execute the shell script you just copied (which will print out the current datetime) with the command: ./date-time-script.sh. You get an error message stating permission is denied: Explain why?

![date time script](date-time-script-mv.png)

The above happened because the script lacks execution permission. this permission can be found in the next question.


17. Type the command to grant execute permission for ./date-time-script.sh

![date time script permission](date-time-script-permission.png)



18. From the cloned textbook sample code under the directory files > Chapter-05 > sample-textfiles, issue the command to display the content of the distro-list.txt to the screen

![distros move](distros-txt-mv.png)


19. Issue the command using a relative path to copy the file distro-list.txt to the distros directory you made under the class-notes folder
Issue the command to show the listing of the distros directory and show that the file was copied

![distros directory](ls-distros-directory.png)


20. In the cloned class textbook directory, Linux-text-book-part-1, issue the command to delete the Mobi directory and its contents, under output

![delete mobile](<mobi delete-1.png>)


21. Issue the command make a cp of the entire directory Linux-text-book-part-1 and all sub-directories to a directory named textbook-copy located in your HOME directory.


![copy linux textbook](Copy_linux_textbook_to_textbook.png)


22. Issue the command to delete the directory Linux-text-book-part-1 and its sub-directories in one command (recursively).



![delete linux textbook](delete_linux_textbook_directory.png)