# Notes-app

Dependencies:
   yargs - npm install yargs
   chalk - npm install chalk@2.4.2
   
   
 yargs - Yargs helps to build interactive command line tools, by parsing arguments and generating an elegant user interface. 
 chalk - It helps to customize the color of the output of the command-line output
         It helps to improve the quality of the output by providing several color options like for warning message red color and many more
         

commands to run and description:

  🔹node app.js list -> list the existing notes title
  🔹node app.js read --title="nodejs" -> This is for example only. value of title should be the existing title of notes. otherwise it throw NOTE NOT FOUND
  🔹node app.js add --title="a" --body="b" -> [Value of title is heading of the notes and value of body is content of the notes. Both title and body is required while running add command. if not, it throws missing requirements error. if we try to add the notes with existing title, it will return NOTE TITLE TAKEN command]
  🔹node app.js remove --title="a" -> [remove the notes with that title only. if you mention non-existing title it will return NO NOTE FOUND, otherwise it will return the command as NOTE REMOVED ]

Note: if we run the command without providing the required properties for add, read or remove commands. It will show the brief information about that particular command like what are the required properties need to be add for getting the correct output
for example: node app.js add/node app.js remove/node app.js read

Exception : node app.js list command is exception from this case. Because it doesn't have any required properties to get the output. Just run the command is enough to get the actual output
    
  


 
   
