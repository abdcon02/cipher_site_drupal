# Cipher Drupal Site
### Created by Connor Abdelnoor
#### For an Assessment at Epicodus on: </br> May 22 2015

###Purpose
To build a encryption cypher in PHP and turn it into a custom Drupal module. </br>
Includes: </br>
A custom form with 3 inputs. One input is be a shift value, one is be a direction, and the third is be the phrase to be encrypted. Then a user is redirected to a second page to show the result - the encoded phrase.
</br>
* The shift value is the number of places to shift each letter over.
* The shift direction is direction added to the shift value. For example: "a" with a shift value of 1 and a direction of right would become "b". A shift direction of "left" with a shift value of 1 would turn "b" into "a".
* If the shift amount takes you over the bounds of the alphabet then cycle back to the beginning. For example: a shift value of 3 with the direction of right would turn "z" into "c".

###Drupal Technologies

Custom Modules
* Cipher module created with PHP

######Find out more about Drupal in the file: [Drupal.txt](README.txt) 

###License

Copyright (c) 2015 Connor Abdelnoor
[MIT](https://gist.github.com/abdcon02/0a856bcb7bf738ebc1ee)
