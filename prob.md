# Introduction

We are going to use Scratch to make a dice shaker. Scratch will pick a random number between 1 and 6 and we will store the number of times each number appears. We are going to store the total number of rolls  in a new type of block called a list.

![screenshot](images/6dice.gif)

# Step 1: Random number generator

## Activity Checklist

+ Start a new project.
+ Click on the **stage** next to the sprite and switch to the `Backdrops` tab, and then click the `Choose Backdrop from library` button and choose any backdrop. Delete the original blank backdrop.
+ Create a variable called roll under Variables (Orange blocks)
+ Create this script under Backgrounds **(not against Sprite1)**:

![screenshot](images/1.gif)

## Test your project

Click the green flag.

+ Does the cat say a random number each time the green flag is clicked?
+ What happens if we select a random number between 1 and 10? 

## Save your project

# Step 2: Using Loops to Automate

Next, we want to roll the dice automatically. To do this we use something called a Loop. A loop runs any code inside it until it reaches a certain finishing point. In this case, it will set roll to a random number between 1 and 6 and then the sprite will output that value.  It will repeat the code 10 times.

+ Click on the stage icon and make the code look like the following:
![screenshot](images/looped_dice_roll.png)

## Test your project

Click the green flag.

+ Click the green flag. 
+ What can we do to speed it up?

## Save your project

# Step 3: Store the Dice rolls inside a list.

A list allows objects to be stored inside a big structure. Think of it like a fabulous coat with thousands of pockets. You can put water in one pocket, sweets in another, maths homework in another, your dog in another, a caravan in another, an ant in another, a large number in another. We are just going to use 6 pockets and going to store numbers in them. Each of the 6 pockets will contain the total number of dice rolls we have seen for that number (e.g. we have seen number 1, 3 times, so we put the number 3 into the pocket labelled 1).

Ask your teacher to demonstrate the dice and cups sorter.

## Activity Checklist

+ Make sure you are still clicked on the Background tab.
+ Create a list called Dice_Rolls underneath lists in the Orange variables blocks list. Make sure Dice_Rolls applies to all sprites.
+ Modify the code so that it looks like the following.
![screenshot](images/14.gif)
+ Click on the + inside the stage area of the screen until 6 boxes are shown. The + icon is next to the length in bottom left corner of the grey box. See screenshot below.  This shows totals for how many rolls of each of 1,2,3,4,5 and 6 have been observed.
![screenshot](images/15.gif)

## Test your project

Click the green flag.

+ How do this code work? The code in the list works by taking the item at position (1 to 6) and increasing it by one.
+ How many 1's did you roll [ ]? How many 6's did you roll [  ]. Is this what you would expect?
+ How many 6's would you expect to roll if you increased the repeat value to 100? Why would it be a good idea to use 100 rolls instead of some other number ?
+ What happens when you click the green flag twice. We need to fix this:

![screenshot](images/8.gif)


## Test your project

Click the green flag.

+ Does this fix the project?
+ How many even numbers did you roll? Is this what you expected?

## Save your project

# Step 5: Extension. Draw a graph of the probability.

We can draw a simple graph in Scratch using the X and Y position system (co-ordinates)

## Activity Checklist

+ Modify a sprite, giving it an appropriate costume.
+ Line up the sprites horizontally such that each one is equally spaced.
+ Check that the following code is used for the stage:
![screenshot](images/8.gif)
+ When the game is finished (we are outside of the repeat 100 loop), then the stage broadcasts "Finished". If the sprite is listening for "Finished" it can move itself vertically. Ensuring that you are clicked on the Sprite, use the following code:

![screenshot](images/16.gif)

+ Duplicate the sprite, dragging it's position horizontally and then changing the Script to say item to 2 instead of 1. 
+ Repeat the process for 3,4,5 and 6. You should now have 6 sprites.
![screenshot](images/6_side_dice_sprites.png)

## Test your project

Click the green flag.

+ Do the sprites move vertically up ?
+ Does the graphical result reflect the numbers in the list?

## Save your project 

# Step 6:  Extension work: Extend to two dice

It is possible to extend this to two dice, adding the total on each dice together. For example 6 + 6 = 12. We would increase our 12 score by 1.

![screenshot](images/12sided_dice_stage_script2.gif)
