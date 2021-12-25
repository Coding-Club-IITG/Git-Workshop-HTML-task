# Project Description
My About Me Site :)

# How to Contribute

### First of all download git form here https://git-scm.com/downloads
 [Check out set up guide here](https://docs.github.com/en/get-started/quickstart/set-up-git)
 
## Now Check out these steps on how to create your pull request

## 1. Forking a repository
![1](https://user-images.githubusercontent.com/77429149/147363476-b231fd1c-b125-4ce1-8169-121bdfb27a49.jpg)

Fork the repository by clicking the fork button on the top of the page. Forking a repository allows you to freely experiment with changes without affecting the original project.


## 2. Cloning a repository
Once the repository is forked. Now you need to clone it. Cloning means having the files of repository locally on your computer.To clone, click on the clone button and copy the HTTPS link.
![2](https://user-images.githubusercontent.com/77429149/147363540-4f9ca0ed-aa6e-4313-8850-b217384cb5f1.jpg)

Open the git bash and run this command  
``` git clone https://github.com/codingiitg/Codepeak-beginner-HTML-task.git ```

![4](https://user-images.githubusercontent.com/77429149/147363728-b3bd7b4c-44b9-4823-9f35-fc5473fc4b7e.jpg)


## 3. Creating a branch
It is advised to create a new branch. Create a branch using the git checkout command ``` git checkout -b [Your Branch Name] ```
![5](https://user-images.githubusercontent.com/77429149/147363857-58dc7629-30b5-46c8-92ed-a37e0bae1b0b.jpg)


## 4. Make changes and commit it.
Now you can head over to issue section and choose an issue in which you are comfortable and work according to that issue. And make the required changes in the project.

Execute ```git status``` and you’ll be able to see the changes. Add those changes to the branch you just created using the ```git add .``` command. 
Comit the changes by running ```git commit -m "Write what changes you made" ```

## 5. Push changes to GitHub.
Before pushing the changes to GitHub, you need to identify the remote’s name.In general remote's name is "origin" but you can confirm it using ```$ git remote```command.
After identifyication remote name, now you are ready to push all of your updated work to the GitHub repo in the form of a Pull Request, run the following command: 
``` git push origin [Your Branch Name] ```

## 6. Creating a pull request on github.
This is the final step, go back to the github repository.you’ll see a button “Compare & pull request” and click it. Provide some decription of the changes you made.
And then just submit your pull request by clicking on "create pull request".

## Congrats! You successfully created your first PR :smiley:
