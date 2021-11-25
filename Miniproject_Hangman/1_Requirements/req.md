## TITLE : HANGMAN 

## DESCRIPTION : 

Hangman is a simple word guessing game.
Players try to figure out an unknown word by guessing letters. If too
many letters which do not appear in the word are guessed, the player is
hanged (and loses). 

## REQUIREMENTS : 

## Identifying requirements: 
## 4 W and 1H: 

Mobile flash games(Android,Ios), Pc flash games, easy access to
applications, security. SWOT analysis: Strength is it can be accessible
to mobile and pc with basic minimum requirments, with or without
internet

## SWOT ANALYSIS :

## Strengths
      
       (1) The Players mastery in understanding the meaning of words 
       (2) The Players mastery in spelling words
       (3) The Players mastery in pronouncing the words


## Weaknesses

        The alternative versions do seem to involve some peril, but there is no reason why the game should.
        
        
## Opportunities

        (1) Hangman boasts a number of educational benefits.
        (2) Can be implemented in Mind games.
        
        
## Threats
       
       Other Similar Apllications.
       
      
        

## LOW LEVEL REQUIRMENTS : 

=\>Memory: 1 MB. =\>Graphics Card: ATI FireGL
T2-128. =\>CPU: Intel Atom Z510. =\>File Size: 200 MB. =\>OS: Windows 7
or Greater.

## Functional Requirements : 

1. Starting the Application Allow the user to
enter on the command line the IP address of a remote computer that is
running a Hangman Word Server. If the user doesn't provide an IP
address, use as a default the address "localhost." At the start of each
game the application will request a word from the Hangman Word Server
specified by IP address. The word obtained from the Word Server will be
designated as the "hidden" word the player tries to guess. If no
connection can be made to a Word Server on the given IP address display
an error message on the console "Apparently no hangman word server is
running at <IP address>." If a word is obtained from the Word Server,
game play begins by offering the player their first turn. 2. Playing the
game At each turn the application will display a visual indicator of how
many letters are in the hidden word and if any of the letters have been
correctly guessed they are shown in the proper position in which they
appear in the word. The application will display a "guess count" which
shows how many incorrect guesses the player has made. An incorrect guess
is guessing a letter which is not in the hidden word. The application
will allow the player to enter a letter. If the letter entered is not
between A and Z display a message "Invalid move" and allow the player to
guess again (without penalty). When the player enters a valid letter the
application will check to see if the game is over and if not will
continue to the next turn. 3. Ending the game The player wins by
correctly guessing all the letters in the hidden word. The player loses
if he/she makes seven incorrect guesses. If the player wins the
application will display a congratulatory message. If the player loses
the application will display a consolation message and will reveal the
hidden word. When the game is over (either win or loss) the application
will offer the player an opportunity to begin another game. If the
player indicates they want to play again, a new game is started. If the
player indicates they do not want to play again, the application is
terminated. Note: there is no way for a player to request termination of
play during the middle of a game.

  
## Non Functional Requirements :
  
Operating Constraints 1. The program requires the JRE v1.4 with Swing from Sun Microsystems. Platform
constraints 1. The program requires a 486 or higher processor with 16
Megabytes of RAM and 5 Megabytes of available hard drive space.
Modifiability 1. If it is desired to change the number of turns in a
game, the developer will be able to make the required changes in \< 1
person-hours. Adaptability 1. The user must be able to specify an
alternate user interface at execution time on the command line. 2. Any
alternate user interface must be able to "plug in" at run time without
recompiling the application. 3. Any alternate user interface must
implement the HangmanUI interface provided by Dr. Dalbey (see External
Interfaces). Portability 1. The program will run on Win 95/98/XP and Red
Hat Linux 9. Reliability 1. Since the program is purely for recreation
and involves no user data, reliability is of low importance. Security 1.
The program will not access any user data files or programs. 2. The
program will not alter or replace any system files. Usability 1. A new
user should be able to play a complete game of hangman in less than ten
minutes. 2. A new user should commit less than one error in use of the
game (e.g. selecting the wrong letter) every ten minutes. 3. A user who
is familiar with the rules of Hangman be able to correctly operate the
program without any written documentation. Testability 1. (optional) If
the user provides an IP address of zero then skip getting a word from
the Word Server and use a default word "calpoly" as the hidden word.
Deployment 1. The program is to be deployed as executable java bytecode
files (".class" files) that must fit on a 1.2M flexible disk. They must
use no specific java package.
