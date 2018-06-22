## Github
At the start of the semester, Titus Wormer was one of the first lecturers that gave a lecture about the use of Github and Git. During the minor, I've learned to use both but as the end of the final project approaches, I can tell with certainty that I've learned the value that Git and Github add to a project.

### Git versus Github
It is really important to know that Git and Github are different systems. Git is a version control system that tracks your files in a working directory where GitHub is a social platform where people can push their files to. 

### Novice
When the minor started it was difficult for me to follow along and keep track of my files. Stubbornly I kept on saving my files locally and made backups by hand.

### Why Github is nice to use
As I've explained earlier, Github is a social platform where you can push your Git versions too. So when you want to use Github you need to initialize Git in your working directory. Below I've written a couple of easy to follow steps on how to set up your Git together with Github. (I work on a MacBook, the steps below are meant for the terminal.)

#### Step 1:
First, you'll need to navigate to the project directory from which you will start working.  You can do this by opening your terminal and write down the command.  <pre>cd Documents/Projects/scheepvaart-museum/</pre>
This is the path for me, yours can be totally different.

#### Step 2: 
When you're inside the folder you can initialize the version control with the command: <pre>git init</pre> now whenever you change a file inside this folder the version control will keep an eye out for the changes.

#### Step 3: 
Everyone once in a while you need to commit your changes, this will be your roadmap for future references. By using the command: <pre>git add .</pre>
You add every changed file to the stage. Then if you run the command <pre>git commit -m</pre>  You are prompted with a question to add a commit message. Keep these messages short and useful.

These are the three steps you need to do in order for Git to keep track of your files. The next step would be to add them to your Github repo. But before I dive into that I will explain how useful Github is with group projects. The best way to explain would be to use my own project as an example.

#### The use of Github inside a group project
Since a lot of people are going to be working on different bits of code it would be hard to keep track of this manually. Git can track all your files locally but when different people need to use the same code this becomes a bit more complicated.

This is where Github (and the next steps) come in. As a group, you can set up a repo and add everyone that needs access to the project. Once initialize every user can clone that repo to their own computer. Whenever someone writes new pieces of code they can push their changes to the repo and Github will keep track of these files. When a different user "pulls" your changes to their directory. The files get updated.
Github shows all the changes made by every user so it's really easy to see who did what. As a failsafe, you can change some of the settings so that every commit to the group project needs to be reviewed by one of the members. This ensures that code doesn't conflict with each other.

#### Step 4
<pre>git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY</pre>
This will clone the Github repo to your local machine.

#### Step 5
Whenever you've written some code repeat the steps and you'll be committing to Github.

## Conclusion
First starting with Git and Github can be challenging, for me it was partly being too stubborn to grasp the concept cause it felt like to much trouble.
With the last project, I didn't have a choice and was forced to learn all the bits needed to commit code to the project branch. This made me realize that working with Git and Github is a big help during my projects.