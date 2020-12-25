# raw_dwarf_meat


just some stupid public repo of modified raw files for dwarf fortress

... for now, this ONLY includes modified files.

# Wish list:

* Pegmatite veins and proper gem association with them
* Corrections re: mass/melting points for new minerals in 0.1.0 and 0.1.1
* Implementation of some better tileset graphics from Kafine
* giant editions of some domestic animals? chickens, ducks, etc

# Change log:

## version 0.1.17 ~~ 'further vocabulary VI'

* more language stuff, a lot of which is job and worker related, introducing a basic language system
  * wherein:
    * in dwarven, (word) is the job and (word)it is the worker
    * in elven, (word) is the job and (word)we is the worker
    * in goblin, (word) is the job and (word)ux is the worker
    * in human, (word) is the job and (word)ith is the worker
  * thus adding more words:
    * AMBUSH and AMBUSHER
    * APPRAISE and APPRAISER
    * BOWYER (to supplement and repair BOW)
    * BREWER (to supplement BREW)
    * BURNER (to supplement BURN)
    * CAP (not a job or a worker)
    * CARE and CARETAKER (unique case as both are nouns and verbs at the same time)
    * CARPENTER and CARPENTRY
    * CARVE and CARVER
    * CLEANER (to supplement CLEAN)
    * CLERK (job AND worker... I'll come back and fix this)
    * CLOTH and CLOTHIER (couldn't think of a verb on this one)
    * COMEDIAN (to supplement COMEDY)
    * CONSOLE and CONSOLER
    * CONVERSE and CONVERSATIONALIST
    * CRAFTER (to supplement CRAFT)
    * DESIGN and DESIGNER
    * DISSECT and DISSECTOR
    * DYER (to supplement DYE)
    * ENGINE and ENGINEER
    * ENGRAVE and ENGRAVER
    * FARMER (to supplement FARM)
    * made minor adjustments to existing FISH_NOUN and FISH_VERB to make the latter linguistically consistent with JOB/WORKER additions
    * FLAT
    * FLATTER and FLATTERER
    * made minor adjustments to existing GROW(er) and GROWTH to make both linguistically coinsistent with JOB/WORKER additions
    * HERB and HERBALIST
    * HUNT and HUNTER
    * INTIMIDATE and INTIMIDATOR (and, technically, 'timid')
    * LEATHER and LEATHERWORKER (but not leatherworking because it's not really a verb?)
    * LIAR (to supplement LIE)
    * LYE (but no lye maker, thanks)
    * MACE
    * MASON and MASONRY (seriously... it wasn't in there already???)
    * MECHANIC (to supplement mechanism)
    * MILK and MILKER
    * MILL and MILLER
    * MINER (to supplement MINE)
    * NEGOTIATE and NEGOTIATOR
    * OPERATE and OPERATOR
    * ORGANIZER (to supplement ORGANIZE)
    * PACIFY, PACIFIER, and PACIFIST
    * POTASH
    * PROSPECT and PROSPECTOR 
    * PUMP
    * RECORD (didn't feel like trying to make record keeper a word)
    * SEEK and SEEKER
    * SLATE MINERAL and SLATE TOOL (nother work or worker) 
    * SOAPER (to supplement SOAP)
    * STALK PLANT (not a job or worker, just a plant part)
    * THRESHER (to supplement GRAIN)
    * TRADER (to supplement TRADE)
    * TRAIN NOUN, TRAIN VERB and TRAINER
    * TRAPPER (to supplement TRAP)
    * WEAPON (leaving off smith, etc since that's a word already)
    * WEAVER (to supplement and fix a past addition of WEAVE)
    * WOODWORKER (to supplement WOOD)
    * WRESTLE and WRESTLER
  * and fixing some exisiting words to fit the job/worker system i'm slowing implementing
    * COBBLE and COBBLER adjusted
    * WORSHIP and WORSHIPPER adjusted
  * also fixed FELDSPAR calling itself felspar in game

## version 0.1.16 ~~ 'a major merger II'

* Something ELSE happened (much later) on the way to version 47.04...
  * Reorganized all the language files by FIXING 47.04's lack of having its newly defined word COMPANY actually in any of the languages, and alphabetizing and separating out the new words I made in the past
  * Re-added ye olde Katherinite back as Kathentine/Kathenstone
  * compared and contrasted changes to animals and objects so that neither 47.04's content nor RDM's content got lost (included adding a lot of MAMMAL tags and re-removing moose and deer in favor of their new versions.)

## version 0.1.15 ~~ 'repair the stones'

* Something happened on the way to version 42.06...
  * Fixed pretty much ALL the tiles in layer stones as they got seriously changed
* Included init files to avoid future merger confusion
* Included one phoebus-based art file to avoid future merger confusion 

## version 0.1.14 ~~ 'a major merger I'

* So, yeah... version 42.04

## version 0.1.13 ~~ 'further vocabulary V'

* on a whim, decided to add to the language files (dont tell me what to do!):
  * Adding adjective 'ruinous' to the verb RUIN_V
  * Fixed PLANET's adjective to be planetary (as opposed to plantary)
  * CIVIL (adj)
  * CIVILIZATION (n,a,v)
  * COBBLE (n,a,v)
  * COBBLER (n)
  * COBBLESTONE (n)
  * Added adjective for TEAR (as in, eyes)
  * TORN (n(tear),a,v)
  * WEAVE (n,a,v)
  * Added 'confederate' as adjective to CONFEDERACY and moved verb away from that to CONFEDERATION instead
  * FEDERATION (federal)
  * SIMPLISTIC (adj)
  * HEGEMONY (separate from HEMEGON) (n,a)
  * UNIT (n,a)
  * FASTING (as in, to fast)
  * FAST (slow already available)
  * VITREOUS (adj, glassy texture)
  * VITRIOL (n,adj, bitter/cruel)
  * HIDE, HIDING (was HIDE, now retasked from hiding/hidden), and uh... TANNER
  * HONE (adj,v, to improve)
  * SHARP (adj)
  * SHARPEN (adj,v)
  * INDIGNITY (n,a)
  * REVOLT (n,v) (combat) not to be confused with REVOLTING (re: disgust)
  * INSULATE (a,v) including insular
  * PHANTASM (n,a); also added adjective to PHANTOM
  * CONTEMPTUOUS (a) as an alternative to CONTEMPT(ible)
  * ORGANISM (n,a) not to be confused with ORGAN
  * Adjusted MORTAL and IMMORTAL to be more useful, including verbage for the latter
  * FATEFUL (a) added as alternative to FATE(d)
  * GLASS (n,a)
  * Added [THE_COMPOUND_ADJ] to all the adjectives related to stony descriptions (granite, etc) and added OBSIDIAN
  * LODGE_ACTION (a,v) to lodge something in something
  * LODGE_PLACE (n,v) a lodge or to lodge for the night somewhere
  * Tinkered a fair bit with the language files in and aroudn terms for nations; confederacy through hegemony, so they had, in most languages, similarities to one another

## version 0.1.12 ~~ 'further vocabulary IV'

* on a whim, decided to add to the language files (because reasons):
  * REPTILE 
  * TURTLE (snake, serpent, lizard already present)
  * AMPHIBIAN
  * OLM (toad, frog already present)
  * SALAMANDER

## version 0.1.11 ~~ 'further vocabulary III'

* on a whim, decided to add to the language files (because reasons):
  * COLONY
  * NEAR & FAR
  * CRYPTIC
  * FRUITFUL (translations take a cue from FRUIT)
  * UNJUST & INJUSTICE (with cues from JUST)
  * MISER
  * SMELT (translation take a cue from MELT)
  * NOBILITY (translations take a cue from NOBLE)
  * SINGULAR (takes a cue from SINGLE)
  * RAPT & RAPTURE
  * SCENE
  
## version 0.1.10 ~~ 'better vocabulary I'

* um... so... yeah
  * I went through the ENTIRE language file and fixed things ups
  * It's not complete, but it is MORE complete than the originals
  * There may be some err

## version 0.1.9 ~~ 'further vocabulary II'

* on a whim, decided to add to the language files (because reasons):
  * PROXIMITY
  * APPROXIMATE
  * LEGAL
  * ILLEGAL
  * CRIME
  * CRIMINAL
  * COURT
  * COURTSHIP

## version 0.1.8 ~~ 'further vocabulary I'

* on a whim, decided to add to the language files:
  * Buttes (the flat topped hills)
  * Contracts (legal AND physical)
  * Expansions (physical)
  * Crags
  * Forges

## version 0.1.7 ~~ 'of sweeping changes and deer'

* added a lot of toys as well as some made by Kafine
* added new pants by Kafine
* added halla, white-tailed, and moose with standard, dread, holy, and giant versions
* fixed up creature variations AND style of creature development for easier moving forward
* retired the idea of titanic creatures
* fixed a slew of small bugs in creature coloration
* fixed application of jasper minerals to sedimentary layers

## version 0.1.6 ~~ 'the first amphibian'

* added 'true frog' (Ranidae) generic construct
  * added the WOOD frog as the first speciation of this construct, along with concurrent graphics
  * the process of this creation is detailed in a youtube tutorial here: https://www.youtube.com/watch?v=vyAuIfajzFg

## version 0.1.5 ~~ 'up with 2014!'

* fixed entity_default.txt to be compatible with DF2014

## version 0.1.4 ~~ 'dread titanic wild holy birds'

* added WILDS and WILDERNESS to all languages and symbolism
* massively altered GIANT creature variation (probably toning their size down a bit)
* added DREAD, HOLY, and TITANTIC (probably bigger than old giant variants, rare, and prone to claiming lairs) creature variations
* created a more modular way to define a base 'mythically generic' creature from which procedural species (and their creature variations) can be derived
  * added 'thrush' family of birds in this manner
    * added ROBIN, DUSKY THRUSH, and VEERY species and their corresponding nonhumanoid variations

## version 0.1.3 ~~ 'feldspar'

* added FELDSPAR (which is a primary constituent of most ROCK but also a mineral unto itself (like quartz or mica, etc))
* added AMAZONITE (which is a varity of feldspar, just like but somewhat greener than microcline)
* added FELDSPAR, MICROCLINE, AMAZONITE, and ORTHOCLASE to all languages and symbolisms
* altered DEAD STAR again to be FORGED STAR instead... sorry about the indecision
* tentatively removed the ability to play as a goblin in adventure mode until more comfortable with those configs

## version 0.1.2 ~~ 'kafine restoration'

* rescued some of Kafine's good graphics and redistributed them in a more advanceable way.  This will make it easier to fill out gaps, and perhaps even wend our way to a complete kafine tileset that can run indepedently from others if desired... you know, someday.
* modified one phoebus and one kohaku file to comment out the replaced items just in case you are using the phoebus tileset (which kafine's work is in, but was, in turn, heavily commented out.)

## version 0.1.1 ~~ 'speaking of which'

* fixed up the whole 'cold' star thing across all files and languages
* added DECEIVE, DIRK, AEGIS, KRYSS, and KEEP (noun) to all languages and symbolisms
* added CHALCOPYRITE and BORNITE as rarer and more colurful copper/iron ore morphologies

## version 0.1.0 ~~ 'of copper and conflict'

* Added azurite and covellite (colorful varieties/pseudomorphs of malachite)
* Added meteorite (in two forms, 'ancient' fallen star and 'cold star' (for a more recent meteorite))
* Added the Aegis (a larger shield)
* Added the Dirk (narrow slender dagger)
* Added the Kryss (serpentine wavy dagger)
* Adjusted which races can use these (also goblin blow-gunners)
* Added a few words to the langauges (magma, lava, various gems and minerals, etc)
* Added a few more food descriptors
