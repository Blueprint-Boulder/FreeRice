# FreeRice
Learn how to use Git/Github while helping out the UN World Food Programme!

## Prerequisites

To complete this workshop, you must create a Github account and install Git locally. Here are some instructions/resources for reference:

**Install Git**: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

**Create a Github Account**: https://github.com/join

## High Level Idea
While learning how to use Git, we might as well get some 'free rice' for the UN World Food Programme while we're at it (there are quotations around 'free rice' because what we're actually doing is playing a game that uses ads to generate the equivalent amount of money to buy the rice that our score reflects and donates it to the UN WFP, but I digress 😌). So, we will go to freerice.com, play for however long each of we would like, and then add the number of rice grains we have contributed to an ongoing list. Let's see what kind of impact Blueprint can have!

## Instructions
1. Download the code locally. You do this by clicking the green 'Code' button, copying the HTTPS link, and then using the `git clone` command in your terminal. Your command should look like this: 
```
git clone https://github.com/blueprintboulder/FreeRice.git
```

2. Go to https://freerice.com/categories/english-vocabulary. Play for however much time you'd like, and make note of your score at the end (if you'd rather not play, please use 0 as your score to keep our tally accurate!)

3. Go inside the `FreeRice` folder (our repository) using the `cd` command in your terminal: `cd FreeRice`

4. Create a new 'branch' (i.e. new copy of the repository for you to make changes without affecting other people) by choosing a branch name and running the following command:
```
git checkout -b your_unique_branch_name
```

5. Update `rice_tally.txt` using your favorite text editor: on a new line, add your score (and whatever nice note you want to add for future Blueprint folks 💕) and save the file.

5. We are now going to 'add' the change we made to the batch of changes we want to contribute to the repo. Do this with:
```
git add rice_tally.txt
```

6. 'Commit' these changes (i.e. add them to the version control record), and leave a note about the changes you're making:
```
git commit -m "Add your commit message here"
```

7. Try to update the repository by 'pushing' these changes to Github. Run the command:
```
git push --set-upstream origin your_unique_branch_name
```

8. You should now see your new branch on Github -- yay! Time to merge these changes into the main branch: select your branch, and click 'Pull Request'.

9. Leave a pull request message if you'd like, and then click 'Create Pull Request'.

10. If there are no conflicts with the base branch, click 'Merge Pull Request'. Then click 'Delete Branch'.

And you're done! Thanks for completing the workshop!

## More Resources

Want to learn more about Git and Github? Here are some great resources!

- Handbooks, command sheets, and a lot more: https://try.github.io/
- Git/Github/Linux beginners workshop by our very own @Oceanestars:
  - Blog post: https://sonder-blog.herokuapp.com/Git-Tutorial.html
  - Github repo: https://github.com/Oceanestars/TestPullRequest
- Github docs: https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/git-and-github-learning-resources

Happy learning!
