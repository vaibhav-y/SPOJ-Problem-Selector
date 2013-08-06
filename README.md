SPOJ-Problem-Selector
======
_Ever had problem selecting which problem to do on SPOJ?_

It just got solved, as easy as 1, 2, 3!

License
=====
Although not mine to release. I believe that this code should be release under an [MIT License](http://opensource.org/licenses/MIT)

Usage
======
>Here's one way to run the python application, you are free to choose between:

1. ` ./spojprobchooser `
2. ` python spojprobchooser.py `


>Using IDLE or any other IDE on Windows should be fine too

>Here's some quick screenshoots using IDLE (Because cmd is too bland :) )

Run Module

![alt-text][img1]

Choose an appropriate option

![alt-text][img2]

Get set, go!

![alt-text][img3]

[img1]: http://i.imgur.com/0idMuY6.png "Input username"
[img2]: http://i.imgur.com/Y42445i.png "Choose an appropriate option"
[img3]: http://i.imgur.com/oGkV5sl.png "Get set, go!"

***
#For the Developers who will be interested in contributing

+ getspojDB.py gets the list of problems available on SPOJ.pl adn stores it in the file SPOJPROB.

+ getuserDB.py gets the activity list of each and every user on SPOJ and stores it in SPOJDIFF. It contains the problem and difficulty level.

+ Time taken by the script varies from user to user.

+ spojuserdatagetter.py gets the activity of one user!

+ spojprobchooser.py uses an exponential difficulty mapping system, to emphasis, large differences, among higher ranks properly.

***

#To-do

1. Refactor into various modules
2. Revise the scoring system further
3. Improve readability
4. Equivalent Ruby fork?