# assignment2-Kothalachinta
Lab2_Assignment
# Haritha Kothalachinta
###### The British Museum
The __Rosetta stone__ is the Museum's most popular exhibit.The Rosetta Stone bears the priestly decree concerning Ptolemy V in three blocks of text in three different languages.The Parthenon Marbles,Sutton Hoo mask,ship burial collection and the __Egyptian mummies__ are the must see exhibits in the museum.

----
Routemap to the British Museum from the LCY Airport 
The closest airport to the British Museum is the London City Airport which is 7.7 miles away.
Directions from LCY Airport to the British Museum through road :
* Head northwest on Hartmann Rd toward Camel Rd
* Take A1020, Lower Lea Crossing, Aspen Way/A1261, A1203 to Bloomsbury PI in Holborn
* Drive to Great Russell St and then your destination will be on your right

### Few other must visit locations around the museum include the following :
-Tower Bridge
-Churchill War Rooms
-National Gallery 

**[Link to AboutMe](AboutMe.md)**

------------------------------------

# Famous places to visit in India 

India is a diversified country with multiple regions and religions.So,we have many opportunities to explore the place and go for adventurous trecks.Below is a list of the cities and most visited places in here :

|City Name|Location to Visit|Time Spent|
--- |--- |--- |
|Banglore |Bannerghatta National Park |6 hrs|
|Rajasthan |Jaisalmer |2 hrs|
|Kashmir |Dal Lake |10 hrs|

--------------------------

# Pithy Quotes

> Life is a journey, not a destination.
>> _Ralph Waldo Emerson_

>To suceed in life, you need two things: ignorance and confidence.
>> _Mark Twain_


--------------------------

# Code Fencing

> Sass - Fix a Number to N Digits
>> https://stackoverflow.com/questions/2221167/javascript-formatting-a-rounded-number-to-n-decimals
```

@function to-fixed($float, $digits: 2) {
  $sass-precision: 5;
  
  @if $digits > $sass-precision {
    @warn "Sass sets default precision to #{$sass-precision} digits, and there is no way to change that for now."
    + "The returned number will have #{$sass-precision} digits, even if you asked for `#{$digits}`."
    + "See https://github.com/sass/sass/issues/1122 for further informations.";
  }
  
  $pow: pow(10, $digits);
  @return round($float * $pow) / $pow;
}
```

**[Link to code snippet](https://css-tricks.com/snippets/sass/fix-number-n-digits/)**








