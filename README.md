# Braytech
_Translations for Braytech.org_

## Contributing translations TL;DR

1.  Fork the repo

2.  Add translations by changing the lines started with 🦘 (delete roo emoji after translation)

3.  Create a pull request

## Contributing translations in two detailed guides

#### GitHub

1. First of all if you don't have a github account __create a github account__

2. You can't make changes directly to this repository, so you have to __fork it to your page__

   ![Fork repo](https://i.ibb.co/4Pk6FGX/2021-01-25-03-16-24.png)

3. You can edit translations online or mirror repo files to your PC.

### Online aka easy translation (option 1)

#### Update your repo with last files from parent repo

4. Before every contribution you have to update your repo with origin one. 
You should open you repo and on top of it there will be some sort of this:

   ![needupdate](https://i.ibb.co/pyjzsP2/2021-01-25-05-34-22.png)
   
5. Click pull request. And it will show you **There isn’t anything to compare.**
That's OK. Pay attention. It is trying you merge your branch into the origin one. But you branch is behind.
Just a little bit below this text there is a link to *switch the base*. Click it.

   ![switchit](https://i.ibb.co/yBJmMSF/2021-01-25-05-42-09.png)

Now you see lots of changes.   

6. Click **Create pull request** and type a title to it. Anything. "update" will be okay. 
Click once more time **Create pull request**, scroll down, click **Merge pull request** and **Confirm**.

7. Now you have all files up to date.

#### Translation, commit and pull

8. Open the folder with you language and click on translation file.
On top right angle find an edit icon and click it.

   ![editfile](https://i.ibb.co/yBCysL6/2021-01-25-05-22-18.png)

9. Find the line with 🦘, translate it, make sure to delete english text and roo emoji, repeate.

10. Now you have to save and commit changes. Commit is the name of a single contribution to the repo. At the bottom of the page you will find a section where you can title changes and text short description. Below that select `Create a new branch for this commit and start a pull request.` and commit changes.

11. You will be shown where you are going to transfer data and the list of lines changed.
You have to click button **Create pull request** and then you can text short title and description. Press button **Create** once more after that.
There have to be line *These branches can be automatically merged.* If not consult Tom or translation team in [discord.braytech.org](https://discord.braytech.org)

### Local aka geek (option 2)

List numbers are started from 4 as online list is ignored

#### VS Code

4. There are different softwares used to work with git on PC, we recommend [VS Code](https://code.visualstudio.com/) as an all-in-one tool.

5. After installing and opening VSCode select **Clone repository**

   ![Clone repo](https://i.ibb.co/x6h5TWf/2021-01-25-03-31-17.png)

6. Here you have an ability to auth your VS Code app with git account. Use it.

   ![Auth](https://i.ibb.co/b3gCXmS/2021-01-25-03-34-24.png)

7. Then click on the repo name (it will be like yourGitAccountName/braytech.org-translations) and select thw folder on your PC where to save the repo files.

   ![Repo list](https://i.ibb.co/jzGH96d/2021-01-25-03-34-36.png)

8. After loading the files VS Code will suggect you actions in right bottom angle on the app. Click "Open".

#### Git Graph

9. Here I advise you to install extention **Git Graph**. It will help you a lot to understand the flow of changes.
Click on "extentions" tab on left and search for `git graph` then click install. 

   ![gitgraph](https://i.ibb.co/Wgchg77/2021-01-25-03-43-00.png)

10. Here you will have a new icon in explorer tab. Click on it.

    ![gitgraphicon](https://i.ibb.co/7GFnN2p/2021-01-25-03-47-38.png)

11. You see the history on all changes to this repository. Who, when and the subject itself.

#### Configuring git

12. Now you need to configure git in order to make everything easy. Top right angle of git graph tab has a settings icon.

    ![gitgraphsettings](https://i.ibb.co/9vqwtwT/2021-01-25-03-55-51.png)

13. Two important areas here.

14. First of all **User Details**. 
You have to set your git account name so that other users can correlate your git account to your commits.
You may not set email if you want it to be private. If you do, anyone can see it.

    ![gituser](https://i.ibb.co/2nWbH6D/2021-01-25-04-04-47.png)

15. Second, but very important. I advise you to add to **Remote Configuration** this repo (right now you have only your fork there). This will allow you to be aware of changes in parent repo. Use button "Add remote" and fill the "Fetch URL" filed with `https://github.com/justrealmilk/braytech.org-translations`
Also I advise you to rename remotes so that you can easily identify them. Use "Edit" button for that.

    ![remotegit](https://i.ibb.co/0fswtSD/2021-01-25-04-15-54.png)

16. Not so important, but very usefull. **Pull Request Creation**
Click "Configure", set source to your fork and destination to toms. Second step just for checking data. Save.

    ![pull](https://i.ibb.co/Tq5kmXh/2021-01-25-04-54-22.png)

17. All the settings we did are handled by VS Code and stored in project folder. So you do not have to repeate them every time you open Vs Code.

#### Update your repo with last files from parent repo

18. From here I'm going to tell about the translation process.

19. First af all, when you decide you update few lines, you have to check if there are any new lines in repo. 
This can be done by clickling fetch buttom in top right angle of git graph.

    ![fetch](https://i.ibb.co/WVykrsp/2021-01-25-04-35-15.png)

20. After that you have to merge the last avaliable commit (this is the name of a single contribution to the repo) to your branch.
Click right mouse button on branch label and select "Merge into current branch".
This will bring the last data from tom's repo to the brach in your fork so you can start translation.

    ![mergecommit](https://cdn.discordapp.com/attachments/604182196319944704/770585175260266536/unknown.png)

Here you uncheck creating commit and then merge.

    ![mergeconfirm](https://media.discordapp.net/attachments/604182196319944704/770585327651913768/unknown.png)

#### Translation and commit

21. Find the line with 🦘, translate it, make sure to delete english text and roo emoji, repeate. Save file.

22. On the left panel (explorer -> Source Control) you will see that there are uncommited changes in files.
You should click "stage changes" (1 on image), add short description to the changes (2) and then click commit button (3).

    ![commit](https://i.ibb.co/2j15n25/2021-01-25-04-48-37.png)

23. Click Synchronize changes n the left bottom angle of VS Code. This will bring your commit to your github web account.

    ![sync](https://i.ibb.co/3rst2Qv/2021-01-25-04-59-22.png)

#### Pull request to parent repo

24. Now you have to send your commits to this repo. In line 16 we were configuring pull requests, so now you can just use it.
Click right mouse button on your branch label in git graph and select "Create pull request".
You may be asked a question if you want to push branch first you can do that (this is almost the same as sync buttom from line 23) and then a web browser page will be opened.

25. On the web page you will be shown from which branch to which you are going to transfer data, the list of commits affected and lines changed.
You have to click button **Create pull request** and then you can text short title and description. Press button **Create** once more after that.
There have to be line *These branches can be automatically merged.* If not consult Tom or translation team in [discord.braytech.org](https://discord.braytech.org)

26. Now you have just to wait until Tom checks it and confirms the merge.

## Contacts

* [discord.braytech.org](https://discord.braytech.org)
