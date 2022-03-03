The 'pwd' command print the absolute path name of the current working directory.
#!/bin/bash
pwd

The above bash script print the current working directory

#!/bin/bash
ls
The above bash script prints out the contents list of the current directory

#!/bin/bash
cd
The above bash script changes the working directory to the home directory

#!/bin/bash
ls -l
The above bash script print out directory content in long format

#!/bin/bash
ls -al
The above bash script print out hidden files

#!/bin/bash
ls -an
The above bash script display content in long format, user and group IDs displayed numerically and hidden files

#!/bin/bash
mkdir my_first_directory /tmp/
The above bash script create a directory named my_first_directory in the /tmp/ directory

#!/bin/bash
mv /tmp/betty /tmp/my_first_directory
The above bash script move the file betty from /tmp/ to /tmp/my_first_directory

#!/bin/bash
rm -r /tmp/my_first_directory/betty
The above bash script delete the file betty

#!/bin/bash
rm -r /tmp/my_first_directory
The above bash script delete the directory - my_first_directory

#!/bin/bash
cd -
The above bash script changes the working directory to the previous one

#!/bin/bash
ls -al. ../boot
The above bash script list all hidden files in current directory and parent directory and the /boot directory

#!/bin/bash
file/tmp/iamafile
The above bash script print the file in the /tmp directory

#!/bin/bash
ln -s /bin/ls--ls--
The above bash script create a symbolic link to /bin/ls

#!/bin/bash
cp *.html ..
The above bash script copy all the HTML files in current working directory to the parent working directory
