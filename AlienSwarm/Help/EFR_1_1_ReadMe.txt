														-13 Feb 2007-


						E S C A P E   F R O M   R H E A

						      expansion pack for

				     The Telic Campaign, AlienSwarm/UnrealTournament2004




INTRODUCTION

The 'Escape From Rhea' Campaign continues right where Telic left your unfortunate squad of brave marines:
stuck in the heart of the xenomorph brain lair, surrounded by pointy teeth and esurient growls in the dark.
Utilize all your wits and cunning, your best team tactics, and an array of deadly new gadgets to overcome
the neverending onslaught of angry aliens and insidious farewell presents left by the shady Telic
corporation in order to lead your soldiers to victory, fame, booze'n'babes, and, most important, continued existence.

Expect no less than:

    * Another unique campaign with 6 new missions: "...Careful, they could be anywhere!"

    * Varied mission environments:
      - a daring escape from an infested mining complex
      - a furious fight through bug swarming drainage trenches
      - a bold infiltration into a heavily fortified missile bunker
      - a nerve racking hunt in Telic's derelict xeno-zoology compound
      - a hazardous rescue from the open desert of Rhea

    * Brand spanking new equipment items: "...Peace, through superior firepower!"
      landmines, personal shields, parasite removal kits, and the powerful AKIRA laser sentrygun

    * New interactive objects, NPCs, mission objectives, custom triggers, and more.

    * Original music, sounds, models, textures, and artwork


An entire new level of challenge, situations that require active cooperation from the whole team,
and vibrant non-stop action: that's AlienSwarm - Escape from Rhea!




INSTALLATION

System Requirements

    ('Escape from Rhea' will NOT run if you lack any of the following!)

    * A computer that meets the minimum system requirements for UT2004
    * Unreal Tournament 2004 - Updated with the latest patch
    * Alien Swarm 1.3+
    * 'The Telic Campaign' - AlienSwarm Expansion Pack!

Installing EFR

    To install EFR, just unpack the contents of the zip file to your UT2004/ folder,
    making sure that you keep the directory structure intact when extracting the files.

For manual installation...

	*.u and *.int files 	go in UT2004/Alienswarm/System
	*.ut2 files 		go in UT2004/Alienswarm/Maps
	*.utx files 		go in UT2004/Alienswarm/Textures
	*.uax files 		go in UT2004/Alienswarm/Sounds
	*.usx files 		go in UT2004/Alienswarm/Staticmeshes
	*.ukx files 		go in UT2004/Alienswarm/Animations
	*.ogg files 		go in UT2004/Music


The EFR mutator is a subclass of the Telic mutator. This means every aspect of a Telic game,
like the extra stimpacks for all marines, the Telic equipment, the no-friendly fire award
and so on, is also automatically added to an EFR game. In short, you must not run the
EFR mutator in addition to the Telic mutator. The EFR mutator alone handles everything.

In general, custom equipment is added to a game either by an actor in the map, or by a mutator,
with the mutator overruling the actor. This means if you play EFR maps without the mutator on,
you'll still have the custom EFR equip. Non EFR maps that are run without the mutator will not
include the EFR equipment. The helmets/air tank system is handled by map actors as well, so you
can still play maps with hazard volumes without the mutator.

Otherwise the EFR mutator behaves identical to the Telic mutator, and the same rules apply,
and you can therefore simply consult the Telic online manual for more detailed explanations.


Server admins should add the following line to the serverpackages list in the AlienSwarm.ini:

	ServerPackages=AoEFRCode


To start a single map with the EFR mutator, enter something like this in the console:

	open Ao-EFR1-Phoenix?mutator=AoEFRCode.mutEFR




NEW EQUIPMENT


- Parasite Removal Kit

  A single 200ml dose of enzymatically attenuated SN2 agent - a simple and brutal,
  yet effective way of dealing with infestations yourself when no field medic is
  around to take care of the bug. Terribly carcinogenic, but that's likely to be the
  least of your problems when you have need for a shot of this stuff. The intense pain
  caused by the poisoning usually results in an adrenaline rush that might increase
  combat abilities for a short duration of time, frequent use is rumored to induce
  aggressive behavior though.


- AT309 Landmines

  With the number of powered exoskeltons on the battlefield increasing, the bulky AT309
  anti-personal mine was created to effectively combat those heavily armored troops.
  It employs a massive, shaped VDX composite charge that is capable of punching through
  several inches of metal plating and even the toughest of xenomorph carapaces, if need be.
  The pack comes with the necessary tools for defusal, but only highly skilled demomen should
  attempt to disarm mines, which don't have an IAF identity beacon. Extreme caution and use
  of a hand scanner is advised when moving through mined areas.


- Telic-Matsumoto WarBot 'AKIRA'

  The AKIRA system was designed to phase out the stalwart SynTek sentries that have been
  used by the IAF for more than three decades. It is fitted with a terribly expensive fifty
  megawatt pulsed fiber laser that makes an ordinary vulcan cannon look like a popgun.
  Be aware that this model is an early release candidate: the AKIRA will require years of work
  before serial production readiness.


- Personal Barrier Field Generator

  While being arguably the biggest breakthrough of the decade in military engineering,
  'shieldbelts' have rarely been seen in action yet for obvious reasons: grossly expensive to
  manufacture, easy to damage, unreliable when used on the move, and unable to operate
  continuously due to excessive power consumption and almost unbearable strain being put on
  both device and user. Moreover, the shield doesn't offer much protection against ordinary
  explosives or natural hazards, further limiting it's usefulness in combat. Still, it may buy
  you those precious seconds for reloading your gun in the face of otherwise certain death.




MODIFIED TELIC EQUIPMENT:


- Electronic Sentrykit Mk-2

  ...The recently updated design additionally features a short-range remote control.


- ION Helmet Lamp Mk-2

  ...Now with extended battery life!




MISSIONS:


- PHOENIX

  Design:	Donator
  Brief:	Elvis has been defeated, your job here is done.
		Now fight your way back out through the infested mining complex.
  Threat:	Hazard
  Location:	Brain Lair 


- NIGHTMARE

  Design:	Donator
  Brief:	A huge increase in mobile bio-readings was just detected.
		Find the source of these readings and eliminate it.
  Threat:	Unknown
  Location:	Coolant Reservoir


- TRENCHWAR

  Design:	Donator
  Brief:	The swarm uses the storm sewer system to access the surface of the planet.
		Seal off their tunnels to aid your escape.
  Threat:	Soldier
  Location:	Drain System


- BUNKER

  Design:	Donator / Sniper1
  Brief:	The Telic corporation is attempting to fire a missile at the Actaeon.
  Threat:	Code Red
  Location:	Missile Silo


- SPECIMEN

  Design:	Donator
  Brief:	The IAF science department requests that you bring back several live
		'spiderbug' specimens for an in-depth analysis.
  Threat:	Arachnid
  Location:	Xeno-Zoology


- BEGGAR'S POINT

  Design:	Donator / NoData / Sniper1
  Brief:	Search for other survivors in the sandstorm and defend them until you can be extracted.
  Threat:	Off Scale
  Location:	Outlands





LINKS & CONTACT

- BCG Forum - For all things AlienSwarm
http://forums.blackcatgames.com/

- EFR and TELIC Manuals, Help, Screenshots, News and More
http://www.telic-campaign.com/

- Developers' eMail
info@telic-campaign.com




TEAM

- DONATOR	Coder, Lead Mapper
- SNIPER1	Modeling, Level Design, Textures, Cowboy Pilot
- BUTTERS	Coding, Creative Support
- NODATA	Level Design, AS 1.32 Tester
- STEROIDS	Music

- BETA TESTERS	DelXander, Felix, Fuzzy Bunny, Killer-Mk1, lightfoot,
		Moses2k, NoData, reemulmyu, x-newbie...


Special Thanks To

Dalai and BCG, for AlienSwarm





						  have fun playing!
						---------------------
						The Telic Corporation

