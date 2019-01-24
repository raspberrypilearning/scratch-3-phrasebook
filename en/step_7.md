## More phrases

You have one phrase translated now — excellent! But that's not enough for a phrasebook, so add some more phrases.

--- task ---
It's easiest to duplicate the toilet sprite, because most of the code you need for other phrases is the same. 

To duplicate the toilet sprite, right-click on it in the list of sprites below the Stage and then click on **duplicate**.
![How to duplicate a sprite](images/duplicateSprite.png)
--- /task ---
--- task ---

"Yes" and "no" are useful words to know in other languages.

Represent "No", use the red cross costume for the duplicated sprite. Change the costume of the new sprite to Button5-b by clicking on the sprite, then clicking on the Costumes tab (1), and then clicking on the **Choose a Costume** button on the bottom left (2). Then delete the old costume by clicking its **x** (3).

![How to change a sprite's costume](images/changeCostume.png)
--- /task ---
--- task ---
Change the sprite's name to 'no' in the sprite information panel below the Stage.
--- /task ---
--- task ---
Finally, in the 'no' sprite's `translate`{:class="block3extensions"} code blocks, change "Where are the toilets?" to "No". See the changes below:

![No sprite](images/noSmall.png)
```blocks3
when this sprite clicked
- say (translate (Where are the toilets?) to (language):: extension) for (2) secs
+ say (translate (No) to (language):: extension) for (2) secs

when this sprite clicked
- speak(translate(Where are the toilets?) to (language)::extension) ::extension
+ speak(translate(No) to (language)::extension) ::extension
```
--- /task ---
--- task --- 
Add some more phrases to your phrasebook!

Start by adding "Yes".

--- hints ---
--- hint ---
First duplicate a sprite with most of the code, then choose a suitable costume (button4 perhaps?), and finally change the phrase in that sprite's `translate`{:class="block3extensions"} code blocks.
--- /hint ---
--- hint ---
The code for your new 'yes' sprite should look like this:

![Yes sprite](images/yesSmall.png)
```blocks3
when backdrop switches to [Wall 1 v]
hide

when backdrop switches to [Beach Malibu v]
show

when this sprite clicked
say (translate (Yes) to (language):: extension) for (2) secs

when this sprite clicked
speak(translate(Yes) to (language)::extension) ::extension
```
--- /hint ---
--- /hints ---
--- /task ---
