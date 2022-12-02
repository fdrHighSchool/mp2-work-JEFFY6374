# Letter Grade
#### Respond to the following:

1. Write a plan for the following extension:
  * Attach a "+" on their grade if the grade ends in a 7, 8 or 9 (eg: 78 -> C+, 89 -> B+)
  * Attach a "-" on their grade if the grade ends in a 0, 1 or 2 (eg: 92 -> A-, 61 -> D-)

    * substring the second number, for example if the score is 98, you substring out the 8. Then create a method saying if the substringed number is greater than or equal to 7, it gives a +, else if its less than or equal to 2, it gives a -. 


2. Discuss how you would make sure 100 is not misrepresented as an A-.
  * You can create a separate method to create this when you are creating your + and -. 


3. Discuss how you would make sure grades that are an F are not mislabeled as F- or F+ (eg: 49 -> F+ and 52 -> F-)
  * When writing the letter grade, you can make python read it as less than or equal for both ranges from 0-50. 
