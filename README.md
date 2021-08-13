
### Git and GitHub activity - Forking and pull request
- Login to your GitHub account
- Access Lavina’s repository from the link below
    https://github.com/lavinagithub/jwd6testprofiles
- Fork his repository on GitHub. Use the  button - top right
- In your Terminal, create a new folder in Documents called gen6
    ``` mkdir Documents/gen6 ```
- Move into the folder 
    ``` cd gen6``` 
- From the terminal , clone the forked repository from GitHub within the gen5 folder
    ```  git clone https://github.com/{yourusername}/jwd6testprofiles ``` 
- Navigate into the cloned directory
  ``` cd jwd6testprofiles``` 
- List the contents of the directory
    ```  ls -al``` 
- Add your image file in the images directory in Finder/Folder explorer
- From the terminal, create a new file in your directory and name it yournameprofile.html
  ``` touch yournameprofile.html``` 
- Edit the file yournameprofile.html in VSCode and save the file (Edit your image, image alt, name and role) - see file code at the end of the page
```
<!DOCTYPE html>
<html lang="en">
 <head>
   <meta charset="UTF-8" />
   <meta http-equiv="X-UA-Compatible" content="IE=edge" />
   <meta name="viewport" content="width=device-width, initial-scale=1.0" />
   <link href="css/styles.css" rel="stylesheet" />
   <title>JWD6 - Profiles</title>
 </head>
 <body>
   <div class="card">
     <img src="./images/lavinapic.png" alt="Lavina" style="width: 100%" />
     <h1>Lavina</h1>
     <p class="role">Instructor, JWD06</p>
     <p>Generation, Australia</p>
     <p><a href="index.html"><< Home</a></p>
   </div>
 </body>
</html>
```

- Check the status of the directory
     ``` git status``` 
- Add the new file to the staging area
     ```  git add .``` 
- Commit the changes 
    ``` git commit -m "Editing my profile details"``` 
    ``` git log ``` 
- You will see the SHA and log message for the latest commit
- Push the file into the forked Github main repo
    ```  git push``` 
- Go to GitHub and create a pull request on Lavina’s repo
- Lavina will review your pull request and merge your files to her main repo
