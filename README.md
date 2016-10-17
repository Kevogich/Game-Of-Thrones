# The War Of The Five Kings, A Dataset

This repo contains a dataset of the battles in the War of the Five Kings from George R.R. Martin's A Song Of Ice And Fire series.

This small side project came about because outside [of] [Crisis.net](http://crisis.net) and [Ushahidi.com](http://ushahidi.com) I have been looking for a small-n dataset to use as a data science teaching tool. While "non-fiction" datasets are, frankly, more interesting, they also come with the mess, complications, and grey-areas associated with the real world. On the other end of the spectrum, randomly generated datasets can be difficult to use as a teaching tool because their outputs (e.g. visualizations or analyses) are meaningless. So, instead of generating a dataset from random-values, the George R.R. Martin series provides ample source material to create a dataset that is both fictional and with (for anyone that has read the series) built-in context. Also, I had a few hours to kill in an airport.


## Codebook

This readme file acts as the codebook for the dataset.

### Level Of Observation:
- The battles of the War of the Five Kings

### Variables:

- **name:** String variable. The name of the battle.
- **year:** Numeric variable. The year of the battle.
- **battle_number:** Numeric variable. A unique ID number for the battle.
- **attacker_king:** Categorical. The attacking king.For example, "Joffrey/Tommen Baratheon" is coded as such because one king follows the other in the Iron Throne.
- **defender_king:** Categorical variable. The defender's king.
- **attacker_1:** String variable. Major house attacking.
- **attacker_outcome:** Categorical variable. The outcome from the perspective war.
- **battle_type:** Categorical variable. A classification of the battle's primary type. Categories:
    - pitched\_battle: Armies meet in a location and fight. This is also the baseline category.
    - ambush: A battle where stealth or subterfuge was the primary means of attack.
    - siege: A prolonged of a fortied position.
    - razing: An attack against an undefended position
- **major_death:** Binary variable. If there was a death of a major figure during the battle.
- **major_capture:** Binary variable. If there was the capture of the major figure during the battle.
- **attacker_size:** Numeric variable. The size of the attacker's force. No distinction is made between the types of soldiers such as cavalry and footmen.
- **defender_size:** Numeric variable. The size of the defenders's force. No distinction is made between the types of soldiers such as cavalry and footmen.
- **attacker_commander:** String variable. Major commanders of the attackers. Commander's names are included without honoric titles and commandders are seperated by commas.
- **defender_commander:** String variable. Major commanders of the defener. Commander's names are included without honoric titles and commandders are seperated by commas.
- **summer:** Binary variable. Was it summer?
- **location:** String variable. The location of the battle.
- **region:** Categorical variable. The region where the battle takes place. Categories: Beyond the Wall, The North, The Iron Islands, The Riverlands, The Vale of Arryn, The Westerlands, The Crownlands, The Reach, The Stormlands, Dorne
- **note:** String variable. Coding notes regarding individual observations.

### Source:

- [A Wiki of Fire and Ice's War Of The Five Kings](http://awoiaf.westeros.org/index.php/War_of_the_Five_Kings) page on the war and the pages of individual battles. Data collected August 17, 2014 at 4:30am-ish.


### Are you a huge ASOIAF fan?

HELL YEAH !  I just love data too - all data.

### Working on...

Outcome of Danny's Westeros Invasion 

 [This data is mirrored and can be queried via API here](https://www.exversion.com/data/view/YVCREKZP14Y2XXC)
