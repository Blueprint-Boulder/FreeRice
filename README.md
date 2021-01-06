# FreeRice
Learn how to use Git/Github while helping out the UN World Food Programme!

## High Level Idea
While learning how to use Git, we might as well get some 'free rice' for the UN World Food Programme while we're at it (there are quotations around 'free rice' because what we're actually doing is playing a game that uses ads to generate the equivalent amount of money to buy the rice that our score reflects and donates it to the UN WFP, but I digress 😌). So, we will go to freerice.com, play for however long each of we would like, and then add the number of rice grains we have contributed to an ongoing list. Let's see what kind of impact Blueprint can have!

## Instructions
1. Download the code locally. You do this by clicking the green 'Code' button, copying the HTTPS link, and then using the `git clone` command in your terminal. Your command should look like this: 
```
> git clone https://github.com/blueprintboulder/FreeRice.git
```

2. Go to https://freerice.com/categories/english-vocabulary. Play for however much time you'd like, and make note of your score at the end (if you'd rather not play, please use 0 as your score to keep our tally accurate!)

3. Go inside the `FreeRice` folder (our repository) using the `cd` command in your terminal: `cd FreeRice`

4. Update `rice_tally.txt` using your favorite text editor: on a new line, add your score (and whatever nice note you want to add for future Blueprint folks 💕) and save the file.

5. We are now going to 'add' the change we made to the batch of changes we want to contribute to the repo. Do this with:
```
git add rice_tally.txt
```

6. 'Commit' these changes (i.e. add them to the version control record), and leave a note about the changes you're making:
```
git commit -m "Add your commit message here"
```

7. CONTINUE HERE
