# Selsius
Save Editor Library  
Selsius is an abstract save editor project capable of quickly creating powerful save editors.  

## Main Philosophy
Defining an entire save editor based on two things. (1) A list of hex values and what they represent in game. (2) Defined addresses and what they represent in game.  
Allowing defined addresses to be any value (including illegal values).  There are some illegal limitations, however, such as (A) A 2-byte address cannot assume a value greater than 65,535. (B) A string with a defined charset cannot contain characters which are not elements of the charset. (C) Hex values cannot assume values for non-valid (or undefined) hex values. (D) Etc.  
Allowing mass importing/exporting of data blocks.  This ability mimics a "New Game Plus" option and gives the user the complete freedom to begin anew and mass import game parameters as wanted.  

## Portability
In order to acheive the absolute highest level of portability, the language used in this project was obviously java.  
Selsius is compiled into an executable JAR file.  

## Necessary Files
The files needed are the latest release executable JAR file "Selsius.jar."  
Since this is a "Library" of save editors, each save editor is called a "Book."  You must have a directory named "books" which any games you wish to be able to edit. Each book contains a minimum version of Selsius required to run.  If a book does not show up on Selsius you must replace it with a more up-to-date book.  

## Optional Files
Every book has the option of using assets (i.e. PNG images).  These are not required, and since most of these are copyrighted assets they will NOT be provided here.  

## Running Selsius
You must install java if you have not done so previously.  Instructions how to install java:  [https://www.java.com/en/download/help/download_options.xml]  
As it's name implies, an executable JAR file can be executed simply by double clicking it.  
If once chooses, this can also be launched from command line by typing the following:  java -jar Selsius.jar  

## Launching a Book
When you first start Selius you will be greeted by the sarcasm label explaining the simple fact that using some illegal values may irrevocably damage a save file.  This sarcasm label can be removed if you upgrade to Pro.  (Sarcasm)
Click which book you would like to launch.  

## Win!
Edit what so ever your heart desires.  You must save all your work as a separate save file.  (Or technically speaking you COULD overwrite the original file by selecting it when choosing a name for the new save file...but why would you want to do that?  See Sarcasm label)  