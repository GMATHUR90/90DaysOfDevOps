# Day-3 of 90daysofdevops

[data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%27400%27%20height=%27400%27/%3e](data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%27400%27%20height=%27400%27/%3e)

[data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%27200%27%20height=%27200%27/%3e](data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%27200%27%20height=%27200%27/%3e)

Welcome to Day 3 of the #90DaysOfDevOps challenge. Today we will be exploring 
some more basic Linux commands that are essential for any DevOps 
engineer. These commands will help you navigate and manage your Linux 
system efficiently. So, let's dive in!!!

### a) To view the content of the file

`cat <filename> # To view the content of any text file.`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686754421512/0a37d242-dd28-4013-ac88-369e1af1ffc5.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686754421512/0a37d242-dd28-4013-ac88-369e1af1ffc5.png?auto=compress,format&format=webp)

### b) To change the access permissions of files

`chmod 777 <filename> # To provide all access including read,write 
                     #and execute`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686755297530/481031e2-49cc-47a0-bb8e-d13e0ddcea97.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686755297530/481031e2-49cc-47a0-bb8e-d13e0ddcea97.png?auto=compress,format&format=webp)

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686755324733/2e5f5100-e670-4479-82aa-0260570b9fc4.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686755324733/2e5f5100-e670-4479-82aa-0260570b9fc4.png?auto=compress,format&format=webp)

### c) To check which commands you have run till now.

`history  # To check command which was previously run`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686755410853/a9304caa-71e4-4ba7-9cbc-b4199bdf2e7c.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686755410853/a9304caa-71e4-4ba7-9cbc-b4199bdf2e7c.png?auto=compress,format&format=webp)

### d) To remove a directory/ Folder.

`rmdir <Directory> # To remove a directory`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686807718001/618e8688-187f-4f8a-a543-bf4d4731db88.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686807718001/618e8688-187f-4f8a-a543-bf4d4731db88.png?auto=compress,format&format=webp)

### e)To create a fruits.txt file and view the content

`touch <file.txt> # To create a file
echo "Content to be added in file" > file.txt #To add content in a file
cat <filename.txt> # To view the content of any text file.`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686809651641/e4e5e2d1-7c37-4d48-8466-34ca86aa6724.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686809651641/e4e5e2d1-7c37-4d48-8466-34ca86aa6724.png?auto=compress,format&format=webp)

Since no content in Colors.txt why it prints nothing .

### f) Add content in fruit's.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.

`vim filename.txt # Create a text file and add content in it
cat filename.txt # To view the content of any text file.`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686809743543/0947821a-544a-4998-84a6-5fb29b494fc5.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686809743543/0947821a-544a-4998-84a6-5fb29b494fc5.png?auto=compress,format&format=webp)

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686808269700/693f07b4-3ff5-495a-945f-09e8b99bd4e6.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686808269700/693f07b4-3ff5-495a-945f-09e8b99bd4e6.png?auto=compress,format&format=webp)

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686809859406/8fd77316-554c-4ca1-b189-9d6ce80962d9.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686809859406/8fd77316-554c-4ca1-b189-9d6ce80962d9.png?auto=compress,format&format=webp)

### g) To Show only the top three fruits from the file.

`head -n 3 filename # To show top three content in the file`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686808488270/7baee72e-abee-4e60-99fb-5657e3ce44f3.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686808488270/7baee72e-abee-4e60-99fb-5657e3ce44f3.png?auto=compress,format&format=webp)

### h) Show only the bottom three fruits from the file.

`tail -n 3 filename # To show bottom 3 content from the file`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686808627896/34c112a7-8647-47cf-9013-5b96f277518a.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686808627896/34c112a7-8647-47cf-9013-5b96f277518a.png?auto=compress,format&format=webp)

### i) To create another file Colors.txt and to view the content.

`touch <file.txt> # To create a file 
cat <filename.txt> # To view the content of any text file.`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686808806966/6a5da632-ccbb-4346-8edf-aa979375ff97.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686808806966/6a5da632-ccbb-4346-8edf-aa979375ff97.png?auto=compress,format&format=webp)

Since no content in Colors.txt why it prints nothing .

### j)Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, and Grey.

`echo -e "Red\nPink\nWhite\nBlack\nBlue\nOrange\nPurple\nGrey" > filename.txt`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686809172942/a31f6f33-015e-41e7-8098-3c702b7e8139.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686809172942/a31f6f33-015e-41e7-8098-3c702b7e8139.png?auto=compress,format&format=webp)

### k) To find the difference between fruits.txt and Colors.txt files.

`diff <firstfile.txt> <secondfile.txt> #The diff command will show 
                                      # the lines that are different 
                                      #between the two files, 
                                      #highlighting any changes made.`

![https://cdn.hashnode.com/res/hashnode/image/upload/v1686810014162/8e41bd11-3ef9-469e-8659-b805775b913f.png?auto=compress,format&format=webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1686810014162/8e41bd11-3ef9-469e-8659-b805775b913f.png?auto=compress,format&format=webp) 
