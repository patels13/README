# What is README?

README allows users to input a text (e.g. a sentence) into a program that will generate images based on parsing of the text using NLP. The idea is for the parser in README to be able to recognize certain “trigger” words in the sentences inputted. Trigger words are words that the program will be able to generate images from. For example, the word “tree” is a trigger word for the program to generate an image of a tree. There can be multiple trigger words in a sentence and each will be generated in the same “canvas” in order to create a “scene” (a visual representation of the sentence). README will essentially translate text into images.

In order to be able to put the computer-generated images in their proper locations in order to construct a real visual (non-abstract) “scene”, README will also have to be able to parse the semantic meaning in the sentences. Using NLP algorithms, README will be able to interpret the locations (coordinates on the canvas) of the generated images on the canvas relative to other objects.

# Background and Motivation

Over the last couple of years, there has been an increase in websites that allow people to write their own stories online. Authors can upload text documents and manage chapters they’ve written with ease. However, there are some authors who wish to add pictures to their stories in order to emphasize important scenes, but lack the art skills to draw their own pictures. Collaborating with an actual artist for their story is often not an option for a number of reasons (scheduling/deadline conflicts, difference in vision of the plot and characters, etc.), and up until now, there haven’t been any other methods for authors to incorporate pictures  in their stories except to learn how to draw on their own.

README aims to help authors create pictures to go along with their stories by taking in a line of text or a paragraph and using the important parts of speech to generate a picture to go along with the text. We hope that README will not only become a useful tool for online authors, but also a tool for the general public to use. 

README has the potential to address many problems in society in a number of different ways, such as:

- Motivation for kids to write more often
- Helps in learning a new language
- Helping those with aphantasia get the visuals they are unable to produce themselves
- Saving time for readers by giving pictures of words they may not know
- Aids with word definitions in online dictionaries

# How to get started

## Step 1: Preliminary things
Make sure to have these things installed in your machine: Java IDE (we use IntelliJ and have only tested our code on IntelliJ), and Processing 3. 

## Step 2: README code
Clone the repo

## Step 3: Setting up project
Open up IntelliJ. Go to File -> New -> Project. Make sure to use Java version > 1.8 for the SDK. Click 'next' until you see 'Project name' and 'Project location'. For the 'Project location', enter the path of the cloned repo. Click Finish. Now you should have the project set up in IntelliJ.

## Step 4: Use Processing library
Include Processing core.jar as an external library. Go to File -> Project Structure -> Libraries. Click the green plus button on the left and add your processing core.jar (should be in wherever your Processing 3 is installed). Click 'OK'.

## Step 5: Use pos-tagger library
Go to File -> Project Structure -> Libraries. Add each of the .jar files in lib (namely slf4-api.jar, slf4-simple.jar, and stanford-postagger.jar to your library (same steps as in Step 4). When you have added all 3, click 'OK'.

## Step 6: Running the code
Next to the green arrow button (for running code), click on the rectangular button and go to 'Edit Configurations...". Click on the green plus button on the far left and click on 'Application'. For the 'main class' text field, put main.Main. Click 'OK'. Now when you click the green arrow, you should be able to run the program!
