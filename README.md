# Test-Monster
<?xml version="1.0" encoding="UTF-8"?>
<compendium version="5">
	<monster>
		<name>Baba Lysaga</name>
		<size>M</size>
		<type>humanoid (human, shapechanger), curse of strahd</type>
		<alignment>chaotic evil</alignment>
		<ac>15 (natural armor)</ac>
		<hp>120 (16d8+48)</hp>
		<speed>30 ft.</speed>
		<str>18</str>
		<dex>10</dex>
		<con>16</con>
		<int>20</int>
		<wis>17</wis>
		<cha>13</cha>
		<save>Wis +7</save>
		<skill>Arcana +13, Religion +13</skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune></immune>
		<conditionImmune></conditionImmune>
		<senses></senses>
		<passive>13</passive>
		<languages>Abyssal, Common, Draconic, Dwarvish, Giant</languages>
		<cr>11</cr>
		<trait>
			<name>Shapechanger</name>
			<text>Baba Lysaga can use an action to polymorph into a swarm of insects (flies) or back into her true form. While in swarm form, she has a walking speed of 5 feet and a flying speed of 30 feet. Anything she is wearing transforms with her, but nothing she is carrying does.</text>
		</trait>
		<trait>
			<name>Blessing of Mother Night</name>
			<text>Baba Lysaga is shielded against divination magic, as though protected by a nondetection spell.</text>
		</trait>
		<trait>
			<name>Spellcasting</name>
			<text>Baba Lysaga is a 16th-level spellcaster. Her spellcasting ability is Intelligence (spell save DC 17, +9 to hit with spell attacks). Baba Lysaga has the following wizard spells prepared:</text>
			<text />
			<text>&#8226; Cantrips (at will): acid splash, fire bolt, light, mage hand, prestidigitation</text>
			<text />
			<text>&#8226;1st level (4 slots): detect magic, magic missile, sleep, witch bolt</text>
			<text />
			<text>&#8226;2nd level (3 slots): crown of madness, enlarge/reduce, misty step</text>
			<text />
			<text>&#8226;3rd level (3 slots): dispel magic, fireball, lightning bolt</text>
			<text />
			<text>&#8226;4th level (3 slots): blight, Everard's black tentacles, polymorph</text>
			<text />
			<text>&#8226;5th level (2 slots): cloudkill, geas, scrying</text>
			<text />
			<text>&#8226;6th level (1 slot): programmed illusion, true seeing</text>
			<text />
			<text>&#8226;7th level (1 slot): finger of death, mirage arcane</text>
			<text />
			<text>&#8226;8th level (1 slot): power word stun</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>Baba Lysaga makes three attacks with her quarterstaff</text>
		</action>
		<action>
			<name>Quarterstaff</name>
			<text>Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 7 (1d6+4) bludegoning damage, or 8 (1d8+4) bludgeoning damage if wielded with two hands.</text>
			<attack>One Handed|8|1d6+4</attack>
			<attack>Two Handed|8|1d8+4</attack>
		</action>
		<action>
			<name>Summon Swarms of Insects (Recharges after a Short or Long Rest)</name>
			<text>Baba Lysaga summons 1d4 swarms of insects. A summoned swarm appears in an unoccupied space within 60 feet of Baba Lysaga and acts as her ally. It remains until it dies or until Baba Lysaga dismisses it as an action.</text>
		</action>
		<spells>acid splash, fire bolt, light, mage hand, prestidigitation, detect magic, magic missile, sleep, witch bolt, crown of madness, enlarge/reduce, misty step, dispel magic, fireball, lightning bolt, blight, Everard's black tentacles, polymorph, cloudkill, geas, scrying, programmed illusion, true seeing, finger of death, mirage arcane, power word stun</spells>
		<slots>4,3,3,3,2,1,1,1,0</slots>
	</monster>
	<monster>
		<name>Baba Lysaga's Creeping Hut</name>
		<size>G</size>
		<type>construct, curse of strahd</type>
		<alignment>unaligned</alignment>
		<ac>16 (natural armor)</ac>
		<hp>263 (17d10+85)</hp>
		<speed>30 ft.</speed>
		<str>26</str>
		<dex>7</dex>
		<con>20</con>
		<int>1</int>
		<wis>3</wis>
		<cha>3</cha>
		<save>Con +9, Wis +0, Cha +0</save>
		<skill></skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune>poison, psychic</immune>
		<conditionImmune>blinded, charmed, deafened, exhaustion, frightened, paralyzed, petrified, prone</conditionImmune>
		<senses>blindsight 120 ft. (blind beyond this radius)</senses>
		<passive>6</passive>
		<languages>-</languages>
		<cr>11</cr>
		<trait>
			<name>Constructed Nature</name>
			<text>An animated object doesn't require air, food, drink, or sleep.</text>
			<text>	The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.</text>
		</trait>
		<trait>
			<name>Antimagic Susceptibility</name>
			<text>The hut is incapacitated while the magic gem that animates it is in the area of an antimagic field. If targeted by dispel magic, the hut must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.</text>
		</trait>
		<trait>
			<name>Siege Monster</name>
			<text>The hut deals double damage to objects and structures.</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>The hut makes three attacks with its roots. It can replace one of these attacks with a rock attack.</text>
		</action>
		<action>
			<name>Root</name>
			<text>Melee Weapon Attack: +12 to hit, reach 60 ft., one target. Hit: 30 (4d10+8) bludgeoning damage.</text>
			<attack>Root|12|4d10+8</attack>
		</action>
		<action>
			<name>Rock</name>
			<text>Ranged Weapon Attack: +12 to hit, range 120 ft., one target. Hit: 21 (3d8+8) bludegoning damage.</text>
			<attack>Rock|12|3d8+8</attack>
		</action>
		<spells></spells>
	</monster>
	<monster>
		<name>Broom of Animated Attack</name>
		<size>S</size>
		<type>construct, curse of strahd</type>
		<alignment>unaligned</alignment>
		<ac>15 (natural armor)</ac>
		<hp>17 (5d6)</hp>
		<speed>0 ft., fly 50 ft. (hover)</speed>
		<str>10</str>
		<dex>17</dex>
		<con>10</con>
		<int>1</int>
		<wis>5</wis>
		<cha>1</cha>
		<save></save>
		<skill></skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune>poison, psychic</immune>
		<conditionImmune>blinded, charmed, deafened, exhaustion, frightened, paralyzed, petrified, poisoned, prone</conditionImmune>
		<senses>blindsight 30 ft. (blind beyond this radius)</senses>
		<passive>7</passive>
		<languages></languages>
		<cr>1/4</cr>
		<trait>
			<name>Constructed Nature</name>
			<text>An animated object doesn't require air, food, drink, or sleep.</text>
			<text>	The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.</text>
		</trait>
		<trait>
			<name>Antimagic Susceptibility</name>
			<text>The broom is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the broom must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.</text>
		</trait>
		<trait>
			<name>False Appearance</name>
			<text>While the broom remains motionless and isn't flying, it is indistinguishable from a normal broom.</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>The broom makes two melee attacks.</text>
		</action>
		<action>
			<name>Broomstick</name>
			<text>Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4+3) bludgeoning damage.</text>
			<attack>Broomstick|5|1d4+3</attack>
		</action>
		<reaction>
			<name>Animated Attack</name>
			<text>If the broom is motionless and a creature grabs hold of it, the broom makes a Dexterity check contested by the creature's Strength check. If the broom wins the contest, it flies out of the creature's grasp and makes a melee attack against it with advantage on the attack roll.</text>
		</reaction>
		<spells></spells>
	</monster>
<monster>
		<name>Barovian Witch</name>
		<size>M</size>
		<type>humanoid (human), curse of strahd</type>
		<alignment>chaotic evil</alignment>
		<ac>10</ac>
		<hp>16 (3d8+3)</hp>
		<speed>30 ft.</speed>
		<str>7</str>
		<dex>11</dex>
		<con>13</con>
		<int>14</int>
		<wis>11</wis>
		<cha>12</cha>
		<save></save>
		<skill>Arcana +4, Perception +2</skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune></immune>
		<conditionImmune></conditionImmune>
		<senses>darkvision 60 ft.</senses>
		<passive>12</passive>
		<languages>Common</languages>
		<cr>1/2</cr>
		<trait>
			<name>Spellcasting</name>
			<text>The witch is a 3rd-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 12, +4 to hit with spell attacks). The witch has the following wizard spells prepared:</text>
			<text />
			<text>&#8226; Cantrips (at will): mage hand, prestidigitation, ray of frost</text>
			<text />
			<text>&#8226;1st level (4 slots): ray of sickness, sleep, Tasha's hideous laughter</text>
			<text />
			<text>&#8226;2nd level (2 slots): alter self, invisibility</text>
		</trait>
		<action>
			<name>Claws (Requires Alter Self)</name>
			<text>Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6+1) slashing damage. This attack is magical.</text>
			<attack>Claws|3|1d6+1</attack>
		</action>
		<action>
			<name>Dagger</name>
			<text>Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 2 (1d4) piercing damage.</text>
			<attack>Dagger|2|1d4</attack>
		</action>
		<spells>mage hand, prestidigitation, ray of frost, ray of sickness, sleep, Tasha's hideous laughter, alter self, invisibility</spells>
		<slots>4,2,0,0,0,0,0,0,0</slots>
	</monster>
	<monster>
		<name>Ezmerelda d'Avenir</name>
		<size>M</size>
		<type>humanoid (human), curse of strahd</type>
		<alignment>chaotic good</alignment>
		<ac>17 (studded leather armor +1)</ac>
		<hp>82 (11d8+33)</hp>
		<speed>30 ft.</speed>
		<str>14</str>
		<dex>19</dex>
		<con>16</con>
		<int>16</int>
		<wis>11</wis>
		<cha>17</cha>
		<save>Wis +3</save>
		<skill>Acrobatics +7, Arcana +6, Deception +9, Insight +3, Medicine +3, Perception +6, Performance +6, Sleight of Hand +7, Stealth +7, Survival +6</skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune></immune>
		<conditionImmune></conditionImmune>
		<senses></senses>
		<passive>16</passive>
		<languages>Common, Elvish</languages>
		<cr>8</cr>
		<trait>
			<name>Special Equipment</name>
			<text>In addition to her magic armor and weapons, Ezmerelda has two potions of greater healing, six vials of holy water, and three wooden stakes.</text>
		</trait>
		<trait>
			<name>Spellcasting</name>
			<text>Ezmerelda is a 7th-level spellcaster. Her spellcasting ability is Intelligence (spell save DC 14, +6 to hit with spell attacks). Ezmerelda has the following wizard spells prepared:</text>
			<text />
			<text>&#8226; Cantrips (at will): fire bolt, light, mage hand, prestidigitation</text>
			<text />
			<text>&#8226;1st level (4 slots): protection from good and evil, magic missile, shield</text>
			<text />
			<text>&#8226;2nd level (3 slots): darkvision, knock, mirror image</text>
			<text />
			<text>&#8226;3rd level (3 slots): clairvoyance, lightning bolt, magic circle</text>
			<text />
			<text>&#8226;4th level (1 slot): greater invisibility</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>Ezmerelda makes three attacks: two with her +1 rapier and one with her +1 handaxe or her silvered shortsword.</text>
		</action>
		<action>
			<name>Rapier +1</name>
			<text>Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 9 (1d8+5) piercing damage.</text>
			<attack>Rapier|8|1d8+5</attack>
		</action>
		<action>
			<name>Handaxe +1</name>
			<text>Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one creature. Hit: 6 (1d6+3) slashing damage.</text>
			<attack>Hand Axe|6|1d6+3</attack>
		</action>
		<action>
			<name>Silvered Shortsword</name>
			<text>Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6+4) piercing damage.</text>
			<attack>Shortsword|7|1d6+4</attack>
		</action>
		<action>
			<name>Curse (Recharges after a Long Rest)</name>
			<text>Ezmerelda targets one creature that she can see within 30 feet of her. The target must succeed on a DC 14 Wisdom saving throw or be cursed. While cursed, the target has vulnerability to one type of damage of Ezmerelda's choice. The curse lasts until ended with a greater restoration spell, a remove curse spell, or similar magic. When the curse ends, Ezmerelda takes 3d6 psychic damage.</text>
		</action>
		<action>
			<name>Evil Eye (Recharges after a Short or Long Rest)</name>
			<text>Ezmerelda targets one creature that she can see within 10 feet of her and casts one of the following spells on the target (save DC 14), requiring neither somatic nor material components to do so: animal friendship, charm person, or hold person. If the target succeeds on the initial saving throw, Ezmerelda is blinded until the end of her next turn. Once a target succeeds on a saving throw against this effect, it is immune to the Evil Eye power of all Vistani for 24 hours.</text>
		</action>
		<spells>fire bolt, light, mage hand, prestidigitation, protection from evil and good, magic missile, shield, darkvision, knock, mirror image, clairvoyance, lightning bolt, magic circle, greater invisibility</spells>
		<slots>4,3,3,1,0,0,0,0,0</slots>
	</monster>
	<monster>
		<name>Guardian Portrait</name>
		<size>M</size>
		<type>construct, curse of strahd</type>
		<alignment>unaligned</alignment>
		<ac>5 (natural armor)</ac>
		<hp>22 (5d8)</hp>
		<speed>0 ft.</speed>
		<str>1</str>
		<dex>1</dex>
		<con>10</con>
		<int>14</int>
		<wis>10</wis>
		<cha>10</cha>
		<save></save>
		<skill></skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune>poison</immune>
		<conditionImmune>charmed, exhaustion, frightened, grappled, paralyzed, petrified, poisoned, prone, restrained</conditionImmune>
		<senses>darkvision 60 ft.</senses>
		<passive>10</passive>
		<languages>Common, plus up to two other languages</languages>
		<cr>1</cr>
		<trait>
			<name>Constructed Nature</name>
			<text>An animated object doesn't require air, food, drink, or sleep.</text>
			<text>	The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.</text>
		</trait>
		<trait>
			<name>Antimagic Susceptibility</name>
			<text>The portrait is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the portrait must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.</text>
		</trait>
		<trait>
			<name>Innate Spellcasting</name>
			<text>The portrait's innate spellcasting ability os Intelligence (spell save DC 12). The portrait can innately cast the following spells, requiring no material components:</text>
			<text />
			<text>	3/day each: counterspell, crown of madness, hypnotic pattern, telekinesis</text>
		</trait>
		<trait>
			<name>False Appearance</name>
			<text>While the figure in the portrait remains motionless, it is indistinguishable from a normal painting.</text>
		</trait>
		<spells>counterspell, crown of madness, hypnotic pattern, telekinesis</spells>
	</monster>
<monster>
		<name>Izek Strazni</name>
		<size>M</size>
		<type>humanoid (human), curse of strahd</type>
		<alignment>neutral evil</alignment>
		<ac>14 (studded leather armor)</ac>
		<hp>112 (15d8+45)</hp>
		<speed>30 ft.</speed>
		<str>18</str>
		<dex>15</dex>
		<con>16</con>
		<int>10</int>
		<wis>9</wis>
		<cha>15</cha>
		<save></save>
		<skill>Intimidation +8, Perception +2</skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune></immune>
		<conditionImmune></conditionImmune>
		<senses></senses>
		<passive>12</passive>
		<languages>Common</languages>
		<cr>5</cr>
		<trait>
			<name>Brute</name>
			<text>A melee weapon deals one extra die of its damage when Izek hits with it (included in the attack).</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>Izek makes two attacks with his battleaxe.</text>
		</action>
		<action>
			<name>Battleaxe</name>
			<text>Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13 (2d8+4) slashing damage, or 15 (2d10+4) when used with two hands.</text>
			<attack>One Handed|7|2d8+4</attack>
			<attack>Two Handed|7|2d10+4</attack>
		</action>
		<action>
			<name>Hurl Flame</name>
			<text>Ranged Spell Attack: +5 to hit, range 60 ft., one target. Hit: 10 (3d6) fire damage. If the target is a flammable object that isn't being worn or carried, it catches fire.</text>
			<attack>Flame|5|3d6</attack>
		</action>
		<spells></spells>
	</monster>
	<monster>
		<name>Madam Eva</name>
		<size>M</size>
		<type>humanoid (human), curse of strahd</type>
		<alignment>chaotic neutral</alignment>
		<ac>10</ac>
		<hp>88 (16d8+16)</hp>
		<speed>20 ft.</speed>
		<str>8</str>
		<dex>11</dex>
		<con>12</con>
		<int>17</int>
		<wis>20</wis>
		<cha>18</cha>
		<save>Con +5</save>
		<skill>Arcana +7, Deception +8, Insight +13, Intimidation +8, Perception +9, Religion +7</skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune></immune>
		<conditionImmune></conditionImmune>
		<senses></senses>
		<passive>19</passive>
		<languages>Abyssal, Common, Elvish, Infernal</languages>
		<cr>10</cr>
		<trait>
			<name>Spellcasting</name>
			<text>Madam Eva is a 16th-level spellcaster. Her spellcasting ability is Wisdom (spell save DC 17, +9 to hit with spell attacks). Madam Eva has the following cleric spells prepared:</text>
			<text />
			<text>&#8226; Cantrips (at will): light, mending, sacred flame, thaumaturgy</text>
			<text />
			<text>&#8226;1st level (4 slots): bane, command, detect evil and good, protection from evil and good</text>
			<text />
			<text>&#8226;2nd level (3 slots): lesser restoration, protection from poison, spiritual weapon</text>
			<text />
			<text>&#8226;3rd level (3 slots): create food and water, speak with dead, spirit guardians</text>
			<text />
			<text>&#8226;4th level (3 slots): divination, freedom of movement, guardians of faith</text>
			<text />
			<text>&#8226;5th level (2 slots): greater restoration, raise dead</text>
			<text />
			<text>&#8226;6th level (1 slot): find the path, harm, true seeing</text>
			<text />
			<text>&#8226;7th level (1 slot): fire storm, regenerate</text>
			<text />
			<text>&#8226;8th level (1 slot): earthquake</text>
		</trait>
		<action>
			<name>Dagger</name>
			<text>Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 2 (1d4) piercing damage.</text>
			<attack>Dagger|4|1d4</attack>
		</action>
		<action>
			<name>Curse (Recharges after a Long Rest)</name>
			<text>Madam Eva targets one creature that she can see within 30 feet of her. The target must succeed on a DC 17 Wisdom saving throw or be cursed. While cursed, the target is blinded and deafened. The curse lasts until ended with a greater restoration spell, a remove curse spell, or similar magic. When the curse ends, Madam Eva takes 5d6 psychic damage.</text>
		</action>
		<action>
			<name>Evil Eye (Recharges after a Short or Long Rest)</name>
			<text>Madam Eva targets one creature that she can see within 10 feet of her and casts one of the following spells on the target (save DC 17), requiring neither somatic nor material components to do so: animal friendship, charm person, or hold person. If the target succeeds on the initial saving throw, Madam Eva is blinded until the end of her next turn. Once a target succeeds on a saving throw against this effect, it is immune to the Evil Eye power of all Vistani for 24 hours.</text>
		</action>
		<spells>light, mending, sacred flame, thaumaturgy, bane, command, detect evil and good, protection from evil and good, lesser restoration, protection from poison, spiritual weapon, create food and water, speak with dead, spirit guardians, divination, freedom of movement, guardians of faith, greater restoration, raise dead, find the path, harm, true seeing, fire storm, regenerate, earthquake</spells>
		<slots>4,3,3,3,2,1,1,1,0</slots>
	</monster>
	<monster>
		<name>Mongrelfolk</name>
		<size>M</size>
		<type>humanoid (mongrelfolk), curse of strahd</type>
		<alignment>any alignment</alignment>
		<ac>11 (natural armor)</ac>
		<hp>26 (4d8+8)</hp>
		<speed>20 ft.</speed>
		<str>12</str>
		<dex>9</dex>
		<con>15</con>
		<int>9</int>
		<wis>10</wis>
		<cha>6</cha>
		<save></save>
		<skill>Deception +2, Perception +2, Stealth +3</skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune></immune>
		<conditionImmune></conditionImmune>
		<senses></senses>
		<passive>12</passive>
		<languages>Common</languages>
		<cr>1/4</cr>
		<trait>
			<name>Extraordinary Feature</name>
			<text>The mongrelfolk has one of the following extraordinary features, determined randomly by rolling a d20 or chosen by the DM:</text>
			<text>	</text>
			<text>1-3 &#8212; Amphibious: The mongrelfolk can breathe air and water.</text>
			<text />
			<text>4-9 &#8212; Darkvision: The mongrelfolk has darkvision out to a range of 60 feet.</text>
			<text />
			<text>10 &#8212; Flight: The mongrelfolk has leathery wings and a flying speed of 40 feet.</text>
			<text />
			<text>11-15 &#8212; Keen Hearing and Smell: The mongrelfolk has advantage on Wisdom (Perception) checks that rely on hearing or smell.</text>
			<text />
			<text>16-17 &#8212; Spider Climb: The mongrelfolk can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.</text>
			<text />
			<text>18-19 &#8212; Standing Leap: The mongrelfolk's long jump is up to 20 feet and its high jump up to 10 feet, with or without a running start.</text>
			<text />
			<text>20 &#8212; Two-Headed: The mongrelfolk has advantage on Wisdom (Perception) checks and on saving throws against being blinded, charmed, deafened, frightened, stunned, or knocked unconscious.</text>
		</trait>
		<trait>
			<name>Mimicry</name>
			<text>The mongrelfolk can mimic any sounds it has beard, including voices. A creature that hears the sounds can tell they are imitations with a successful DC 12 Wisdom (Insight) check.</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>The mongrelfolk makes two attacks: one with its bite and one with its claw or dagger.</text>
		</action>
		<action>
			<name>Bite</name>
			<text>Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4+1) piercing damage.</text>
			<attack>Bite|3|1d4+1</attack>
		</action>
		<action>
			<name>Claw</name>
			<text>Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4+1) slashing damage.</text>
			<attack>Claw|3|1d4+1</attack>
		</action>
		<action>
			<name>Dagger</name>
			<text>Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 3 (1d4+1) piercing damage.</text>
			<attack>Dagger|3|1d4+1</attack>
		</action>
		<spells></spells>
	</monster>
	<monster>
		<name>Phantom Warrior</name>
		<size>M</size>
		<type>undead, curse of strahd</type>
		<alignment>any alignment</alignment>
		<ac>16</ac>
		<hp>45 (6d8+18)</hp>
		<speed>30 ft.</speed>
		<str>16</str>
		<dex>11</dex>
		<con>16</con>
		<int>8</int>
		<wis>10</wis>
		<cha>15</cha>
		<save></save>
		<skill>Perception +2, Stealth +4</skill>
		<resist>bludgeoning, piercing, and slashing from nonmagical attacks</resist>
		<vulnerable></vulnerable>
		<immune>cold, necrotic, poison</immune>
		<conditionImmune>charmed, exhaustion, frightened, grappled, paralyzed, petrified, poisoned, prone, restrained</conditionImmune>
		<senses>darkvision 60 ft.</senses>
		<passive>12</passive>
		<languages>any languages it knew in life</languages>
		<cr>1</cr>
		<trait>
			<name>Ethereal Sight</name>
			<text>The phantom warrior can see 60 feet into the Ethereal Plane when it is on the Material Plane, and vice versa.</text>
		</trait>
		<trait>
			<name>Incorporeal Movement</name>
			<text>The phantom warrior can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.</text>
		</trait>
		<trait>
			<name>Spectral Armor and Shield</name>
			<text>The phantom warrior's AC accounts for its spectral armor and shield.</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>The phantom warrior makes two attacks with its spectral longsword.</text>
		</action>
		<action>
			<name>Spectral Longsword</name>
			<text>Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8+3) force damage.</text>
			<attack>Spectral Longsword|5|1d8+3</attack>
		</action>
		<action>
			<name>Etherealness</name>
			<text>The phantom warrior enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Border Ethereal, and vice versa, yet it can't affect or be affected by anything on the other plane.</text>
		</action>
		<spells></spells>
	</monster>
	<monster>
		<name>Pidlwick II</name>
		<size>S</size>
		<type>construct, curse of strahd</type>
		<alignment>neutral evil</alignment>
		<ac>14 (natural armor)</ac>
		<hp>10 (3d6)</hp>
		<speed>30 ft.</speed>
		<str>10</str>
		<dex>14</dex>
		<con>11</con>
		<int>8</int>
		<wis>13</wis>
		<cha>10</cha>
		<save></save>
		<skill>Performance +3</skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune>poison</immune>
		<conditionImmune>paralyzed, petrified, poisoned</conditionImmune>
		<senses></senses>
		<passive>11</passive>
		<languages>understands Common but doesn't speak and can't read or write</languages>
		<cr>1/4</cr>
		<trait>
			<name>Ambusher</name>
			<text>During the first round of combat, Pidlwick II has advantage on attack rolls against any creature that hasn't had a turn yet.</text>
		</trait>
		<action>
			<name>Club</name>
			<text>Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4) bludgeoning damage.</text>
			<attack>Club|2|1d4</attack>
		</action>
		<action>
			<name>Dart</name>
			<text>Ranged Weapon Attack: +4 to hit, range 20/60 ft., one target. Hit: 4 (1d4+2) piercing damage.</text>
			<attack>Dart|4|1d4+2</attack>
		</action>
		<spells></spells>
	</monster>
	<monster>
		<name>Rahadin</name>
		<size>M</size>
		<type>humanoid (elf), curse of strahd</type>
		<alignment>lawful evil</alignment>
		<ac>18 (studded leather)</ac>
		<hp>135 (18d8+54)</hp>
		<speed>35 ft.</speed>
		<str>14</str>
		<dex>22</dex>
		<con>17</con>
		<int>15</int>
		<wis>16</wis>
		<cha>18</cha>
		<save>Con +7, Wis +7</save>
		<skill>Deception +8, Insight +7, Intimidation +12, Perception +11, Stealth +14</skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune></immune>
		<conditionImmune></conditionImmune>
		<senses>darkvision 60 ft.</senses>
		<passive>21</passive>
		<languages>Common, Elvish</languages>
		<cr>10</cr>
		<trait>
			<name>Deathly Choir</name>
			<text>Any creature within 10 feet of Rahadin that isn't protected by a mind blank spell hears in its mind the screams of the thousands of people Rahadin has killed. As a bonus action, Rahadin can force all creatures that can hear the screams to make a DC 16 Wisdom saving throw. Each creature takes 16 (3d10) psychic damage on a failed save, or half as much damage on a successful one.</text>
			<attack>Deathly Choir||3d10</attack>
		</trait>
		<trait>
			<name>Fey Ancestry</name>
			<text>Rahadin has advantage on saving throws against being charmed, and magic can't put him to sleep.</text>
		</trait>
		<trait>
			<name>Innate Spellcasting</name>
			<text>Rahadin's innate spellcasting ability is Intelligence. He can innately cast the following spells, requiring no components:</text>
			<text />
			<text>3/day: misty step, phantom steed</text>
			<text />
			<text>1/day: magic weapon, nondetection</text>
		</trait>
		<trait>
			<name>Mask of the Wild</name>
			<text>Rahadin can attempt to hide even when he is only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena.</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>Rahadin attacks three times with his scimitar, or twice with his poisoned darts.</text>
		</action>
		<action>
			<name>Scimitar</name>
			<text>Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 9 (1d6+6) slashing damage.</text>
			<attack>Scimitar|10|1d6+6</attack>
		</action>
		<action>
			<name>Poisoned Dart</name>
			<text>Ranged Weapon Attack: +10 to hit, range 20/60 ft., one target. Hit: 8 (1d4+6) piercing damage plus 5 (2d4) poison damage.</text>
			<attack>Poisoned Dart|10|1d4+6+2d4</attack>
		</action>
		<spells>misty step, phantom steed, magic weapon, nondetection</spells>
	</monster>
	<monster>
		<name>Rictavio</name>
		<size>M</size>
		<type>humanoid (human), curse of strahd</type>
		<alignment>lawful good</alignment>
		<ac>12 (leather armor)</ac>
		<hp>77 (14d8+14)</hp>
		<speed>30 ft.</speed>
		<str>9</str>
		<dex>12</dex>
		<con>13</con>
		<int>16</int>
		<wis>18</wis>
		<cha>16</cha>
		<save>Con +4, Wis +7</save>
		<skill>Arcana +9, Insight +7, Medicine +7, Perception +7, Religion +6, Sleight of Hand +4</skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune></immune>
		<conditionImmune></conditionImmune>
		<senses></senses>
		<passive>17</passive>
		<languages>Abyssal, Common, Elvish, Infernal</languages>
		<cr>5</cr>
		<trait>
			<name>Special Equipment</name>
			<text>In addition to his sword cane, Rictavio wears a hat of disguise and a ring of mind shielding, and he carries a spell scroll of raise dead.</text>
		</trait>
		<trait>
			<name>Spellcasting</name>
			<text>Rictavio is a 9th-level spellcaster. His spellcasting ability is Wisdom (spell save DC 15, +7 to hit with spell attacks). Rictavio has the following cleric spells prepared:</text>
			<text />
			<text>&#8226; Cantrips (at will): guidance, light, mending, thaumaturgy</text>
			<text />
			<text>&#8226;1st level (4 slots): cure wounds, detect evil and good, protection from evil and good, sanctuary</text>
			<text />
			<text>&#8226;2nd level (3 slots): augury, lesser restoration, protection from poison</text>
			<text />
			<text>&#8226;3rd level (3 slots): magic circle, remove curse, speak with dead</text>
			<text />
			<text>&#8226;4th level (3 slots): death ward, freedom of movement</text>
			<text />
			<text>&#8226;5th level (1 slot): dispel evil and good</text>
		</trait>
		<trait>
			<name>Undead Slayer</name>
			<text>When Rictavio hits an undead with a weapon attack, the undead takes an extra 10 (3d6) damage of the weapon's type.</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>Rictavio makes two attacks with his sword cane.</text>
		</action>
		<action>
			<name>Sword Cane</name>
			<text>Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d6+1) bludgeoning damage (wooden cane) or piercing damage (silvered sword).</text>
			<attack>Sword Cane|4|1d6+1</attack>
		</action>
		<spells>guidance, light, mending, thaumaturgy, cure wounds, detect evil and good, protection from evil and good, sanctuary, augury, lesser restoration, protection from poison, magic circle, remove curse, speak with dead, death ward, freedom of movement, dispel evil and good</spells>
		<slots>4,3,3,3,1,0,0,0,0</slots>
	</monster>
	<monster>
		<name>Strahd's Animated Armor</name>
		<size>M</size>
		<type>construct, curse of strahd</type>
		<alignment>lawful evil</alignment>
		<ac>21 (natural armor)</ac>
		<hp>112 (15d8+45)</hp>
		<speed>30 ft.</speed>
		<str>17</str>
		<dex>13</dex>
		<con>16</con>
		<int>9</int>
		<wis>10</wis>
		<cha>9</cha>
		<save></save>
		<skill>Perception +3</skill>
		<resist>cold, fire</resist>
		<vulnerable></vulnerable>
		<immune>lightning, poison</immune>
		<conditionImmune>blinded, charmed, deafened, exhaustion, frightened, paralyzed, petrified, poisoned</conditionImmune>
		<senses>blindsight 60 ft. (blind beyond this radius)</senses>
		<passive>13</passive>
		<languages>understands Common but can't speak</languages>
		<cr>6</cr>
		<trait>
			<name>Constructed Nature</name>
			<text>An animated object doesn't require air, food, drink, or sleep.</text>
			<text>	The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.</text>
		</trait>
		<trait>
			<name>Antimagic Susceptibility</name>
			<text>The armor is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the armor must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.</text>
		</trait>
		<trait>
			<name>False Appearance</name>
			<text>While the armor remains motionless, it is indistinguishable from a normal suit of armor.</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>The armor makes two melee attacks or uses Shocking Bolt twice.</text>
		</action>
		<action>
			<name>Greatsword</name>
			<text>Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10 (2d6+3) slashing damage plus 3 (1d6) lightning damage.</text>
			<attack>|6|2d6+3+1d6</attack>
		</action>
		<action>
			<name>Shocking Bolt</name>
			<text>Ranged Spell Attack: +4 to hit (with advantage on the attack roll if the target is wearing armor made of metal), range 60 ft., one target. Hit: 10 (3d6) lightning damage.</text>
			<attack>|4|3d6</attack>
		</action>
		<spells></spells>
	</monster>
	<monster>
		<name>Strahd von Zarovich</name>
		<size>M</size>
		<type>undead (shapechanger), curse of strahd</type>
		<alignment>lawful evil</alignment>
		<ac>16 (natural armor)</ac>
		<hp>144 (17d8+68)</hp>
		<speed>30 ft.</speed>
		<str>18</str>
		<dex>18</dex>
		<con>18</con>
		<int>20</int>
		<wis>15</wis>
		<cha>18</cha>
		<save>Dex +9, Wis +7, Cha +9</save>
		<skill>Arcana +15, Perception +12, Religion +10, Stealth +14</skill>
		<resist>necrotic; bludgeoning, piercing, and slashing from nonmagical attacks</resist>
		<vulnerable></vulnerable>
		<immune></immune>
		<conditionImmune></conditionImmune>
		<senses>darkvision 120 ft.</senses>
		<passive>22</passive>
		<languages>Abyssal, Common, Draconic, Elvish, Giant, Infernal</languages>
		<cr>15</cr>
		<trait>
			<name>Shapechanger</name>
			<text>If Strahd isn't in running water or sunlight, he can use his action to polymorph into a Tiny bat, a Medium wolf, or a Medium cloud of mist, or back into his true form.</text>
			<text>	While in bat or wolf form, Strahd can't speak. In bat form, his walking speed is 5 feet, and he has a flying speed of 30 feet. In wolf form, his walking speed is 40 feet. His statistics, other than his size and speed, are unchanged. Anything he is wearing transforms with him, but nothing he is carrying does. He reverts to his true form if he dies.</text>
			<text>	While in mist form, Strahd can't take any actions, speak, or manipulate objects. He is weightless, has a flying speed of 30 feet, can hover, and can enter a hostile creature's space and stop there. In addition, if air can pass through a space, the mist can do so without squeezing, and he can't pass through water. He has advantage on Strength, Dexterity, and Constitution saving throws, and it is immune to all nonmagical damage, except the damage he takes from sunlight.</text>
		</trait>
		<trait>
			<name>Legendary Resistance (3/Day)</name>
			<text>If Strahd fails a saving throw, he can choose to succeed instead.</text>
		</trait>
		<trait>
			<name>Misty Escape</name>
			<text>When he drops to 0 hit points outside his coffin, Strahd transforms into a cloud of mist (as in the Shapechanger trait) instead of falling unconscious, provided that he isn't in running water or sunlight. If he can't transform, he is destroyed.</text>
			<text>	While he has 0 hit points in mist form, he can't revert to his vampire form, and he must reach his coffin within 2 hours or be destroyed. Once in his coffin, he reverts to his vampire form. He is then paralyzed until he regains at least 1 hit point. After spending 1 hour in his coffin with 0 hit points, he regains 1 hit point.</text>
		</trait>
		<trait>
			<name>Regeneration</name>
			<text>Strahd regains 20 hit points at the start of his turn if he has at least 1 hit point and isn't in running water or sunlight. If he takes radiant damage or damage from holy water, this trait doesn't function at the start of his next turn.</text>
		</trait>
		<trait>
			<name>Spellcasting</name>
			<text>Strahd is a 9th-level spellcaster. His spellcasting ability is Intelligence (spell save DC 18, +10 to hit with spell attacks). Strahd has the following wizard spells prepared:</text>
			<text />
			<text>&#8226; Cantrips (at will): mage hand, prestidigitation, ray of frost</text>
			<text />
			<text>&#8226;1st level (4 slots): comprehend languages, fog cloud, sleep</text>
			<text />
			<text>&#8226;2nd level (3 slots): detect thoughts, gust of wind, mirror image</text>
			<text />
			<text>&#8226;3rd level (3 slots): animate dead, fireball, nondetection</text>
			<text />
			<text>&#8226;4th level (3 slots): blight, greater invisibility, polymorph</text>
			<text />
			<text>&#8226;5th level (1 slot): animate objects, scrying</text>
		</trait>
		<trait>
			<name>Spider Climb</name>
			<text>Strahd can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.</text>
		</trait>
		<trait>
			<name>Vampire Weaknesses</name>
			<text>Strahd has the following flaws. </text>
			<text>	Forbiddance: He can't enter a residence without an invitation from one of the occupants.</text>
			<text>	Harmed by Running Water: He takes 20 acid damage if he ends his turn in running water.</text>
			<text>	Stake to the Heart: If a piercing weapon made of wood is driven into his heart while he is incapacitated in his coffin, he is paralyzed until the stake is removed.</text>
			<text>	Sunlight Hypersensitivity: While in sunlight, Strahd takes 20 radiant damage at the start of his turn, and he has disadvantage on attack rolls and ability checks.</text>
		</trait>
		<action>
			<name>Multiattack (Vampire Form Only)</name>
			<text>Strahd makes two attacks, only one of which can be a bite attack.</text>
		</action>
		<action>
			<name>Unarmed Strike (Vampire Form Only)</name>
			<text>Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. Hit: 8 (1d8+4) bludgeoning damage, plus 14 (4d6) necrotic damage. If the target is a creature, Strahd can grapple it (escape DC 18) instead of dealing the bludgeoning damage.</text>
			<attack>|9|1d8+4+4d6</attack>
		</action>
		<action>
			<name>Bite (Bat or Vampire Form Only)</name>
			<text>Melee Weapon Attack: +9 to hit, reach 5 ft., one willing creature, or a creature that is grappled by Strahd, incapacitated, or restrained. Hit: 7 (1d6+4) piercing damage plus 10 (3d6) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and Strahd regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if  its hit point maximum is reduced to 0. A humanoid slain in this way and then buried in the ground rises the following night as a vampire spawn under Strahd's control.</text>
			<attack>|9|1d6+4+3d6</attack>
		</action>
		<action>
			<name>Charm</name>
			<text>Strahd targets one humanoid he can see within 30 ft. of him. If the target can see Strahd, the target must succeed on a DC 17 Wisdom saving throw against this magic or be charmed. The charmed target regards Strahd as a trusted friend to be heeded and protected. The target isn't under Strahd's control, but it takes Strahd's requests and actions in the most favorable way and lets Strahd bite it.</text>
			<text>	Each time Strahd or his companions do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until Strahd is destroyed, is on a different plane of existence than the target, or takes a bonus action to end the effect.</text>
		</action>
		<action>
			<name>Children of the Night (1/day)</name>
			<text>Strahd magically calls 2d4 swarms of bats or swarms rats, provided that the sun isn't up. While outdoors, Strahd can call 3d6 wolves instead. The called creatures arrive in 1d4 rounds, acting as allies of Strahd and obeying his spoken commands. The beasts remain for 1 hour, until Strahd dies, or until he dismisses them as a bonus action.</text>
		</action>
		<legendary>
			<name></name>
			<text>Strahd can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time, and only at the end of another creature's turn. Strahd regains spent legendary actions at the start of his turn.</text>
		</legendary>
		<legendary>
			<name>Move</name>
			<text>Strahd moves up to his speed without provoking opportunity attacks.</text>
		</legendary>
		<legendary>
			<name>Unarmed Strike</name>
			<text>Strahd makes one unarmed strike.</text>
		</legendary>
		<legendary>
			<name>Bite (Costs 2 Actions)</name>
			<text>Strahd makes one bite attack.</text>
		</legendary>
		<spells>mage hand, prestidigitation, ray of frost, comprehend languages, fog cloud, sleep, detect thoughts, gust of wind, mirror image, animate dead, fireball, nondetection, blight, greater invisibility, polymorph, animate objects, scrying</spells>
		<slots>4,3,3,3,1,0,0,0,0</slots>
	</monster>
	<monster>
		<name>Strahd Zombie</name>
		<size>M</size>
		<type>undead, curse of strahd</type>
		<alignment>unaligned</alignment>
		<ac>8</ac>
		<hp>30 (4d8+12)</hp>
		<speed>20 ft.</speed>
		<str>13</str>
		<dex>6</dex>
		<con>16</con>
		<int>3</int>
		<wis>6</wis>
		<cha>5</cha>
		<save>Wis +0</save>
		<skill></skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune>poison</immune>
		<conditionImmune>poisoned</conditionImmune>
		<senses>darkvision 60 ft.</senses>
		<passive>8</passive>
		<languages>understands the languages it knew in life but can't speak</languages>
		<cr>1</cr>
		<trait>
			<name>Loathsome Limbs</name>
			<text>Whenever the zombie takes at least 5 bludgeoning or slashing damage at one time, roll a d20 to determine what else happens to it: </text>
			<text />
			<text>1-8: One leg is severed from the zombie if it has any legs left.</text>
			<text />
			<text>9-16: One arm is severed from the zombie if it has any arms left.</text>
			<text />
			<text>17-20: The zombie is decapitated.</text>
			<text />
			<text>	If the zombie is reduced to 0 hit points, all parts of it die. Until then, a severed part acts on the zombie's initiative and has its own action and movement. A severed part has AC 8. Any damage it takes is subtracted from the zombie's hit points.</text>
			<text>	A severed leg is unable to attack and has a speed of 5 feet.</text>
			<text>	A severed arm has a speed of 5 feet and can make one claw attack on its turn, with disadvantage on the attack roll. Each time the zombie loses an arm, it loses a claw attack.</text>
			<text>	If its head is severed, the zombie loses its bite attack and its body is blinded unless the head can see it. The severed head has a speed of 0 feet. It can make a bite attack but only against a target in its space.</text>
			<text>	The zombie's speed is halved if it's missing a leg. If it loses both legs, it falls prone. If it has both arms, it can crawl. With only one arm, it can still crawl, but its speed is halved. With no arms or legs, its speed is 0, and it can't benefit from bonuses to speed.</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>The zombie makes three attacks: one with its bite and two with its claws.</text>
		</action>
		<action>
			<name>Bite</name>
			<text>Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4+1) piercing damage.</text>
			<attack>Bite|3|1d4+1</attack>
		</action>
		<action>
			<name>Claw</name>
			<text>Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6+1) slashing damage.</text>
			<attack>Claw|3|1d6+1</attack>
		</action>
		<spells></spells>
	</monster>
<monster>
		<name>Tree Blight</name>
		<size>H</size>
		<type>plant, curse of strahd</type>
		<alignment>neutral evil</alignment>
		<ac>15 (natural armor)</ac>
		<hp>149 (13d12+65)</hp>
		<speed>30 ft.</speed>
		<str>23</str>
		<dex>10</dex>
		<con>20</con>
		<int>6</int>
		<wis>10</wis>
		<cha>3</cha>
		<save></save>
		<skill></skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune></immune>
		<conditionImmune>blinded, deafened</conditionImmune>
		<senses>blindsight 60 ft. (blind beyond this radius)</senses>
		<passive>10</passive>
		<languages>understands Common and Druidic but doesn't speak</languages>
		<cr>7</cr>
		<trait>
			<name>False Appearance</name>
			<text>While the blight remains motionless, it is indistinguishable from a dead tree.</text>
		</trait>
		<trait>
			<name>Siege Monster</name>
			<text>The blight deals double damage to objects and structures.</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>The blight makes four attacks: two with its branches and two with its grasping roots, If it has a target grappled, the blight can also make a bite attack against the target as a bonus action.</text>
		</action>
		<action>
			<name>Bite</name>
			<text>Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 19 (3d8+6) piercing damage.</text>
			<attack>Bite|9|3d8+6</attack>
		</action>
		<action>
			<name>Branch</name>
			<text>Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit (3d6+6) bludgeoning damage.</text>
			<attack>Branch|9|3d6+6</attack>
		</action>
		<action>
			<name>Grasping Root</name>
			<text>Melee Weapon Attack: +9 to hit, reach 15 ft., one creature not grappled by the blight. Hit: the target is grappled (escape DC 15). Until the grapple ends, the target takes 9 (1d6+6) bludgeoning damage at the start of each of its turns. The root has AC 15 and can be severed by dealing 6 slashing damage or more to it at once. Cutting the root doesn't hurt the blight but ends the grapple.</text>
			<attack>Grasping Root|9|1d6+6</attack>
		</action>
		<spells></spells>
	</monster>
	<monster>
		<name>Vladimir Horngaard</name>
		<size>M</size>
		<type>undead, curse of strahd</type>
		<alignment>lawful evil</alignment>
		<ac>17 (half plate)</ac>
		<hp>192 (16d8+64)</hp>
		<speed>30 ft.</speed>
		<str>18</str>
		<dex>14</dex>
		<con>18</con>
		<int>13</int>
		<wis>16</wis>
		<cha>18</cha>
		<save>Str +7, Con +7, Wis +6, Cha +7</save>
		<skill></skill>
		<resist>necrotic, psychic</resist>
		<vulnerable></vulnerable>
		<immune>poison</immune>
		<conditionImmune>charmed, exhaustion, frightened, paralyzed, poisoned, stunned</conditionImmune>
		<senses>darkvision 60 ft.</senses>
		<passive>13</passive>
		<languages>Common, Draconic</languages>
		<cr>7</cr>
		<trait>
			<name>Regeneration</name>
			<text>Vladimir regains 10 hit points at the start of his turn. If he takes fire or radiant damage, this trait doesn't function at the start of his next turn. Vladimir's body is destroyed only if he starts his turn with 0 hit points and doesn't regenerate.</text>
		</trait>
		<trait>
			<name>Rejuvenation</name>
			<text>When Vladimir's body is destroyed, his soul lingers. After 24 hours, the soul inhabits and animates another corpse on the same plane of existence and regains all its hit points. While the soul is bodiless, a wish spell can be used to force the soul to go to the afterlife and not return.</text>
		</trait>
		<trait>
			<name>Turn Immunity</name>
			<text>Vladimir is immune to effects that turn undead.</text>
		</trait>
		<trait>
			<name>Vengeful Tracker</name>
			<text>Vladimir knows the distance to and direction of any creature against which it seeks revenge, even if the creature and Vladimir are on different planes of existence. If the creature being tracked by Vladimir dies, Vladimir knows.</text>
		</trait>
		<action>
			<name>Multiattack</name>
			<text>Vladimir makes two fist attacks or two attacks with his +2 Greatsword.</text>
		</action>
		<action>
			<name>Fist</name>
			<text>Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11 (2d6+4) bludgeoning damage. If the target is a creature against which Vladimir has sworn vengeance, the target takes an extra 14 (4d6) bludgeoning damage. Instead of dealing damage, Vladimir can grapple the target (escape DC 14) provided the target is Large or smaller.</text>
			<attack>Fist|7|2d6+4</attack>
		</action>
		<action>
			<name>Greatsword +2</name>
			<text>Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 20 (4d6+4) slashing damage. Against Strahd, Vladimir deals an extra 14 (4d6) slashing damage with this weapon.</text>
			<attack>Greatsword|9|4d6+4</attack>
		</action>
		<action>
			<name>Vengeful Glare</name>
			<text>Vladimir targets one creature he can see within 30 feet of him and against which he has sworn vengeance. The target must make a DC 15 Wisdom saving throw. On a failure, the target is paralyzed until Vladimir deals damage to it, or until the end of Vladimir's next turn. When the paralysis ends, the target is frightened of Vladimir for 1 minute. The frightened target can repeat the saving throw at the end of each of its turns, with disadvantage if it can see Vladimir, ending the frightened condition on itself on a success.</text>
		</action>
		<spells></spells>
	</monster>
	<monster>
		<name>Wereraven</name>
		<size>M</size>
		<type>humanoid (human, shapechanger), curse of strahd</type>
		<alignment>lawful good</alignment>
		<ac>12</ac>
		<hp>31 (7d8)</hp>
		<speed>30 ft., fly 50 ft. in raven and hybrid forms</speed>
		<str>10</str>
		<dex>15</dex>
		<con>11</con>
		<int>13</int>
		<wis>15</wis>
		<cha>14</cha>
		<save></save>
		<skill>Insight +4, Perception +6</skill>
		<resist></resist>
		<vulnerable></vulnerable>
		<immune>bludgeoning, piercing, and slashing from nonmagical attacks not made with silvered weapons</immune>
		<conditionImmune></conditionImmune>
		<senses></senses>
		<passive>16</passive>
		<languages>Common (can't speak in raven form)</languages>
		<cr>2</cr>
		<trait>
			<name>Shapechanger</name>
			<text>The wereraven can use its action to polymorph into a raven-humanoid hybrid or into a raven, or back into its human form. Any equipment it is wearing or carrying isn't transformed. It reverts to its human form if it dies.</text>
		</trait>
		<trait>
			<name>Mimicry</name>
			<text>The wereraven can mimic simple sounds it has heard, such as a person whispering, a baby crying, or an animal chittering. A creature that hears the sounds can tell they are imitations with a successful DC 10 Wisdom (Insight) check.</text>
		</trait>
		<action>
			<name>Multiattack (Human or Hybrid Form Only)</name>
			<text>The wereraven makes two weapon attacks, one of which can be with its hand crossbow.</text>
		</action>
		<action>
			<name>Beak (Raven or Hybrid Form Only)</name>
			<text>Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1 piercing damage in raven form, or 4 (1d4+2) piercing damage in hybrid form. If the target is humanoid, it must succeed on a DC 10 Constitution saving throw or be cursed with wereraven lycanthropy.</text>
			<attack>Beak (Raven Form)|4|1</attack>
			<attack>Beak (Hybrid Form)|4|1d4+2</attack>
		</action>
		<action>
			<name>Shortsword (Humanoid or Hybrid Form Only)</name>
			<text>Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6+2) piercing damage.</text>
			<attack>Shortsword|4|1d6+2</attack>
		</action>
		<action>
			<name>Hand Crossbow (Humanoid or Hybrid Form Only)</name>
			<text>Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit: 5 (1d6+2) piercing damage.</text>
			<attack>Hand Crossbow|4|1d6+2</attack>
		</action>
		<spells></spells>
	</monster>
</compendium>
