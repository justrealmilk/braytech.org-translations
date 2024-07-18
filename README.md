# Braytech
_Translations for Braytech.org_

This file describes how to contributing translations to this repo. It has three guides:
- **TL;DR** for experienced users;
- **online a.k.a. easy translation** for newbies who want to help but not to dig into git stuff;
- **with local repo a.k.a. pro geek** for newbies who are ready for everything.


## Contributing translations TL;DR

1.  Fork the repo.

2.  Add translations by changing the lines started with 🦘 (delete roo emoji after translation).

3.  Create a pull request.


## Contributing translations online a.k.a. easy translation

1. First of all if you don't have a GitHub account __create a GitHub account__.

2. In this repo open the folder with you language and click on translation file.
On top right angle find an edit icon and click it.

   ![editfile](https://i.ibb.co/LvySBnX/2021-01-26-12-06-05.png)

3. Find the line with 🦘 and translate it. Make sure to delete english text and roo emoji when done. Repeat.

4. At the bottom of the page you will find a section where you can title changes and provide a short description. After that press "**Propose changes**" button.

   ![propose changes](https://i.ibb.co/vdFKgr2/2021-01-26-12-10-35.png)

5. You will be shown where you are going to transfer data and the list of lines changed.
You need to click **Create pull request** button.
You should see *These branches can be automatically merged* line. If not, ask Tom or translation team in [discord.braytech.org](https://discord.braytech.org)
Press **Create pull request** button once more after that.

6. Wait until Tom checks it and confirms the merge.

## Contributing translations with local repo a.k.a. pro geek

#### GitHub

1. First of all if you don't have a GitHub account __create a GitHub account__.

2. You can't make changes directly to this repository, so you need to __fork it to your page__.

   ![Fork repo](https://i.ibb.co/4Pk6FGX/2021-01-25-03-16-24.png)

3. You can edit translations online or download repo files to your PC.

#### VS Code

4. There're different software used to work with git on PC, we recommend [VS Code](https://code.visualstudio.com/) as an all-in-one tool.

5. After installing and opening VSCode select **Clone repository**.

   ![Clone repo](https://i.ibb.co/x6h5TWf/2021-01-25-03-31-17.png)

6. Here you can sign into your GitHub account. Do it.

   ![Auth](https://i.ibb.co/b3gCXmS/2021-01-25-03-34-24.png)

7. Then click on the repo name (it will be like yourGitAccountName/braytech.org-translations) and select a folder on your PC where to save the repo files.

   ![Repo list](https://i.ibb.co/jzGH96d/2021-01-25-03-34-36.png)

8. After downloading the files VS Code will suggect you actions in right bottom corner. Click "Open".

#### Git Graph

9. Here I recommend you to install **Git Graph** extention. It will help you a lot to understand the flow of changes.
Click on "Extentions" tab on left and search for `git graph` then click "Install".

   ![gitgraph](https://i.ibb.co/Wgchg77/2021-01-25-03-43-00.png)

10. Here you'll see a new icon in explorer tab. Click on it.

    ![gitgraphicon](https://i.ibb.co/7GFnN2p/2021-01-25-03-47-38.png)

11. You see the history of all changes to this repository. Who, when and the subject itself.

#### Configuring git

12. Now you need to configure git in order to make everything easy. Top right corner of git graph tab has a settings icon.

    ![gitgraphsettings](https://i.ibb.co/9vqwtwT/2021-01-25-03-55-51.png)

13. Two important areas here.

14. First of all **User Details**.
You need to set your GitHub account name so that other users can match your GitHub account to your commits.
You may not set email if you want it to be private. If you do, anyone can see it.

    ![gituser](https://i.ibb.co/2nWbH6D/2021-01-25-04-04-47.png)

15. The second, but no less important. I recommend you to add **Remote Configuration** to this repo (right now you have only your fork there). This will allow you to be aware of changes in parent repo. Use button "Add remote" and fill the "Fetch URL" filed with `https://github.com/justrealmilk/braytech.org-translations`
Also I advise you to rename remotes so that you can easily identify them. Use "Edit" button for that.

    ![remotegit](https://i.ibb.co/0fswtSD/2021-01-25-04-15-54.png)

16. Not so important, but very usefull. **Pull Request Creation**.
Click "Configure" and set source to your fork and destination to toms. Second step just for checking data. Save.

    ![pull](https://i.ibb.co/Tq5kmXh/2021-01-25-04-54-22.png)

17. All the settings we did are handled by VS Code and stored in the project folder. So you do not have to repeat them every time you open VS Code.

#### Update your repo with last files from parent repo

18. From here on I'm going to tell about the translation process.

19. First af all, when you decide you update few lines, you need to check if there're any new lines in repo.
This can be done by clickling fetch buttom in top right corner of git graph.

    ![fetch](https://i.ibb.co/WVykrsp/2021-01-25-04-35-15.png)

20. After that you need to merge the last avaliable commit (this is the name of a single contribution to the repo) to your branch.
Click right mouse button on branch label and select "Merge into current branch".
This will bring the last data from tom's repo to the brach in your fork so you can start translation.

    ![mergecommit](https://cdn.discordapp.com/attachments/604182196319944704/770585175260266536/unknown.png)

    Here you uncheck creating commit and then merge.

    ![mergeconfirm](https://media.discordapp.net/attachments/604182196319944704/770585327651913768/unknown.png)

#### Translation and commit

21. Find the line with 🦘 and translate it. Make sure to delete english text and roo emoji when done. Repeat. Save file.

22. On the left panel (Explorer -> Source Control) you'll see that there are unstaged changes in files.
You should click "Stage Changes" (1 on the image below), add short description to the changes (2) and then click "Commit" button (3).

    ![commit](https://i.ibb.co/2j15n25/2021-01-25-04-48-37.png)

23. Click Synchronize changes in the left bottom corner of VS Code. This'll bring your commit to your GitHub web account.

    ![sync](https://i.ibb.co/3rst2Qv/2021-01-25-04-59-22.png)

#### Pull request to parent repo

24. Now you need to send your commits to this repo. In line 16 we were configuring pull requests, so now you can just use it.
Click right mouse button on your branch label in git graph and select "Create Pull Request".
You may be asked a question if you want to push branch first you can do that (this is almost the same as sync buttom from line 23) and then a web browser page will be opened.

25. On the web page you'll be shown from which branch to which you are going to transfer data, the list of commits affected and lines changed.
You need to click button **Create pull request** and then you can text short title and description.
There have to be line *These branches can be automatically merged.* If not consult Tom or translation team in [discord.bray.tech](https://discord.bray.tech)
Press button **Create pull request** once more after that.

26. Now all there's left for you to do is to wait until Tom checks it and confirms the merge.

## Contacts

* [discord.bray.tech](https://discord.bray.tech)
