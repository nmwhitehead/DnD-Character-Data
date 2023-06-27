# DnD-Character-Data

Back in 2017, there was an article written on [FiveThirtyEight](https://fivethirtyeight.com/features/is-your-dd-character-rare/) about how popular each of the Class and Race mixes were in D&D 5th Edition, acording to dndbeyond, the most popular site for creating D&D characters online. I, like many, was disapointed to discover that in a world filled with Elven Druids, Gnomes Warlocks, and Goliath Barbarians the most popular race and class mix was boring old Human Fighter. I wanted to dig deeper into this disappointing data, but struggled to find the data source, so I instead turned to Kaggle, where I found a [dataset claiming to have 1.2 miilion character from dndbeyond](https://www.kaggle.com/datasets/maximebonnin/dnd-characters-test), and even though it's more like half a mllion after remvoing duplicates, that's still a lot of characters.

As a heads up if you are trying to follow my code to recreate it, 'Data Cleaner.ipynb' references data that is not available in this repository, as it is over twice the size allowed by GitHub for upload.
That data is available on the [Kaggle](https://www.kaggle.com/datasets/maximebonnin/dnd-characters-test) page where I found the data, if you would like to recreate the data from scratch. I did remove some rozs that were taking up too much space as I had no plan to use them. 

In order to get more information, I broke the data down a little more, looking at just the distribution of chosen Class and Chosen Race.
As a side note, the drop off in both bar charts (Aarakocra to Tabaxi in Race and Druid to Blood Hunter in Class) are where charaters stop being free of charge.

![image](https://github.com/nmwhitehead/DnD-Character-Data/assets/54327232/5e29df99-c1cb-4930-a350-a42fe2ca594c)

Upon closer inspection we do see that the lead that human has over the other races is much greater than the lead fighter has, with rogue sitting at a close second, and many other classes being not too far behind. My main thought upon seehing this is that these are all probably first time players. Fighter, rogue, and ranger all feel like kinda basic, first attempt character types. The "I don't know how this game works so let's play something simple" type characters.

I wanted to dig deeper on this, but "Is Players First Character" was unfortunately not a data point that was available. The closest I could think was that first time D&D players would probably want to start with low level characters. I am very much of the opinion that you should start with level 3 characters the first time you play, since level 1 characters just can't really do anything yet, and the characterts don't really step up their game until levels 3 or 5. I checked Google to see if there was any data on comnmnon starting levels, but all I found was multiple pages of people asking what a good starting level was, and most were suggesting 1 or 2, with the occassional 3. So, I decided to see what was the most common race and class by starting level, and found it's human at every level, which just disapoints me so much.


![image](https://github.com/nmwhitehead/DnD-Character-Data/assets/54327232/3fd0f033-66ac-43f4-a309-0239a6bedc48)

On the bright side, the choice of fighter as a character class does stop being the most popular at higher levels. By level 16, wizard surpasses rogue and fighter and becomes the most popular class.

The reason for this is simple. At higher levels, the abilities granted to magic users are far more interesting and far more versatile than the skills granted to a high level fighter. At level 20, a fighter can attack 3 more times per turn. That's a lot of attacks, and a lot of damage, but it's still just swinging a weapon. At level 20 a wizrd can now learn up to 9th level spells, and while they can only cast 1 9th level spell a day, you don't have to do much after cast a Metor Swarm on an enemy encampment. 7th level, which gives you two spell slots, has spells like Delayed Blast Fireball for leaving traps, Teleport for escaping with your group, and Reverse Gravity for...removal purposes. And that's not even looking at all of the other levels. My point being, it's understandable that wizard is more popular for people starting at a higher level.

But this does also return me to my point that it is likely not first time players that are starting these higher level characters. You don't want to start your first play with a massive arsonal of crazy spells. You want to start as an adventruer with a sword. So it's crazy to me that humans are still the most common race when you could be a humnoid bird, or the element of fire shaped like a person, but I digress.
