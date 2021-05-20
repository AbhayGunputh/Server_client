# CLIENT-SERVER PROJECT
## Steps to execute the program

## >>NOTE: Place all the 20 files in the save folder and start execution <<
Main program files to execute
``` sh
Server.c
Client.c
```
## Step 1
- Open 2 terminals windows at the same time
- In the first terminal window: 
    - Type "chmod u+x server.c" to give the user permission to execute the file
    - Type "./server" to run the program
- In the second terminal window:
    - Type "chmod u+x client.c" to give the user permission to execute the file
    - Type "./client" to run the program

## Step 2
- In the second terminal window(Client)
    - Choose an option between 1, 2 and 3
    -  The first one is to download a file from the server
    -  The second one will give the list of files available on the server
    -  The third one will delete a file from the server

## Step 3 [To download a file from the server]
- It will show all the files available on the server and in which languages they are available

| PROGRAMMING LANGUAGES | Addition | Substraction | Multiplication | Division |
| ------ | ------ | ------ | ------ | ------ |
| C Programming |  ✔️ |  ✔️|  ✔️|✔️ 
| Python | ✔️ | ✔️ |  ✔️|  ✔️
| C++ | ✔️ |  ✔️|  ✔️|✔️️ 
| BASH | ✔️ | ✔️|   ✔️|  ✔️
```sh
- The user will have to choose a Programming language first
- The user will have to choose a Program to download
- After inserting the program to download, the connection will break because the programing is using TCP/IP
- The downloaded file will store as "received" file
- It will contain all the instructions how to execute the program
```
# Supppose the user wants to see all the available files on the server, he will have to run both script on both terminals again. 
## Step 1
- Now, the user will have to choose 2
- But now, the connection has break immediately.
## Step 2
- Now the received file is in a bash script. The user will have to execute the file to get all the available files on the server

# Supppose the user wants to delete a file on the server, he will have to run both script on both terminals again. 
## Step 1
- Now, the user will have to choose 3
## Step 2
- All the available files will be displayed on the terminal
- The user will have to enter the name of the file he wish to delete from the server
- After inserting the name of the file and press enter, the file will be deleted from the server
- The deleted file will be in the TRASH
- If the user wants the file back, he can copy the code from the TRASH and paste it in the editor, save it and execute.






[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
