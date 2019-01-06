## More languages

Now we can go to countries that speak Spanish or English. Let's add another one now.
To see the list of languages that you can translate to, click the drop down box from the `translate`{:class="block3extensions"} code block. Be sure to check the Speech to Text languages too if you'd like to hear the translations with the correct pronunciation.

--- task ---
Let's add French, as its flag is easy to draw and it's used in a lot of countries around the world.
First let's duplicate the spain sprite so that we can reuse its code!
Right click on the spain flag sprite in the list of sprites under the stage and click duplicate.
--- /task ---
--- task ---
Next lets choose a new costume for the france sprite. I'm going to draw this one as it's not too difficult. Then delete the old costume.
![The French flag in the costume editor](images/franceSprite.png)
--- /task ---
--- task ---
Finally, change the code so that it sets the `language`{:class="block3data"} variable and the Text to Speech `set language to`{:class="block3extensions"} code blocks to French instead of Spanish.
Your france flag sprite's code should now look like the following:
```blocks3
when this sprite clicked
+ set [language v] to [French]
+ set language to [French) v] :: extension
say [\[Hello\] in (language)] for (2) secs :: extension
switch backdrop to [Beach Malibu v]

when backdrop switches to [Beach Malibu v]
hide

when backdrop switches to [Wall 1 v]
show
```
--- /task ---
--- task ---
Add Italian to your phrasebook. 

--- hints ---
--- hint ---
First duplicate a sprite with most of the code (French also has most of the flag!), then choose or draw a costume and finally change the language in the sprite's language code blocks.
--- /hint ---
--- hint ---
The code for the new yes sprite looks like this:
```blocks3
when this sprite clicked
+ set [language v] to [Italian]
+ set language to [Italian) v] :: extension
say [\[Hello\] in (language)] for (2) secs :: extension
switch backdrop to [Beach Malibu v]

when backdrop switches to [Beach Malibu v]
hide

when backdrop switches to [Wall 1 v]
show
```
--- /hint ---
--- /hints ---
--- /task ---