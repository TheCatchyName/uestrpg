Check with your DM if he's ok with using the Racial Feats (Note the difference as feat selection is available as an alternative to ability point gain.)
If you want to enable PHB content, enable the WOTC Content checkbox. 
Note that it has to stay enabled for any options you select to remain. 
This is the current limitations of the workaround I have implemented to bypass the hardcoding of the system reference document into Aurora Builder (and also to allow players the freedom to use other features as well).
Also note that any git updates to core content will not be reflected if you have auto update turned on, as I have set the value of the version of these files to 9.0.0, which means they will always seem to be "up to date".
However, if something updates and starts breaking things or showing up in places they are not supposed to be, please alert me.

Agility == Dexterity
Endurance == Constitution
Willpower == Wisdom
Personality == Charisma

Vanilla Elements that are deleted:
Classes
    Sorcerer
        All Vanilla Archetypes (due to removal of sorcerer point and spell slot system)

Vanilla elements that remain:
    Classes
        Barbarian #
            Path of the Berserker
            Path of the Totem Warrior
        Sorcerer
            Wild Magic*
    Feats**
    Languages*
    Races
        All Races*


* Disabled by default. Enable by checking the WOTC Content Checkbox.
** Disabled by default. Enable by checking the WOTC Feats Checkbox.
# PHB Files edited. Updating will break some changes I have made.

Compatibility
Most classes can make use of archetypes that are added by other expansions, especially if they do not cast spells.

Compatible with other expansions:
    Classes
        Barbarian
        Sorcerer (I enabled the ability to choose other archetypes when using a UESTRPG sorcerer. Take note that sorcery points and spell slots no longer exist. However, if your archetype does not make use of these, they would be compatible. Make sure to check "Enable WOTC Content" for Sorcerous Origins to be selectable.)



FAQ:

Can you add xx Class/Archetype/Feature/Spell?

You can do it for yourself, if you read up on the Aurora Builder documentations. 
I will not be adding anything that is outside of UESTRPG's books, for now.

How do I make xx compatible with the Classes/Races here?

Make sure you give the proper grants in the Classes and Races you want to add.
More information can be found in the Aurora Builder documentations.

Why did you remove xx?

It wasn't in the UESTRPG book. I've deleted the original references to speed up loading time.
Although many classes and archetypes can work with some tweaking, I have decided to focus purely on converting the book into digital format.


My weapon proficiency list is so cluttered!

Due to Aurora Builder's limitations, I cannot create a custom category called "Short Blades" and assign proficiency to your character. 
The intent is for such categories to work in the way "Simple Weapons" and "Martial Weapons" work in PHB.
Thus, individually assigning the weapon proficiency is the current workaround.
If you want to reduce the clutter, just manually erase all the entries in the box after generating your character sheet.