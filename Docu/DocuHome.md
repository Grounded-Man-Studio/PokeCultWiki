[Page WikiHome]:https://github.com/Grounded-Man-Studio/PokeCultWiki
[Page TutorialHome]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Tutorials/TutorialHome.md
[Page GameGuide]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Walkthrough/Walkthrough.md

[Tut Docu OOPStyle]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/DesignPrinciples/CSStyleOOP.md
[Tut Docu FullClasses]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/DesignPrinciples/FullClasses.md
[Tut Docu FullMod]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/DesignPrinciples/FullModding.md
[Tut Docu SystemsBased]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/DesignPrinciples/Systems%20Based%20Design.md
[Tut Docu UnifyCore]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/DesignPrinciples/UnifiedCoreCode.md

[System OOP]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/OOP/OOPSys.md
[System Collect]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/Collect/CollectSys.md
[System SystemsCore]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/SystemsCore/SystemsCoreSys.md
[System Debug]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/Debug/DebugSys.md
[System FilePaths]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/FilePaths/FilePathsSys.md
[System Data]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/Data/DataSys.md
[System Versions]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/Versions/VersionsSys.md
[System Geometry]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/Geometry/GeometrySys.md
[System Graphics]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/Graphics/GraphicsSys.md
[System Input]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/Input/InputSys.md
[System Saves]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/Saves/SavesSys.md
[System GameData]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/GameData/GameDataSys.md
[System Tests]:https://github.com/Grounded-Man-Studio/PokeCultWiki/blob/main/Docu/Systems/Tests/TestsSys.md

# Script Side Documentation Home

Welcome to the documentation for the Code Side as provided by AMT LLC's FueledByOCHD. This section is used to help users know more about his custom code and the unique way that his style of code is designed and maintained. Our goal for providing this section is to allow players to understand how the system is set up so they can extend out the game to provide thier own experience.

## Section Navi

- Design Principles
	- [CS Style OOP Extention][Tut Docu OOPStyle]
	- [Full Object Classes][Tut Docu FullClasses]
	- [Systems Based Design][Tut Docu SystemsBased]
	- [Unification of Core Game Code][Tut Docu UnifyCore]
	- [Core Extentions Modding Design][Tut Docu FullMod]
- Systems
	- [CS OOP Extend System][System OOP]
	- [Collections Classes System][System Collect]
	- [Debugging System][System Debug]
	- [File Paths System][System FilePaths]
	- [Data System][System Data]
	- [Versions System][System Versions]
	- [Geometry System][System Geometry]
	- [Graphics System][System Graphics]
	- [Input System][System Input]
	- [Saves System][System Saves]
	- [Game Data System][System GameData]
	- [Script Functionality Tests][System Tests]

## Site Quick Navigation

- [Home][Page WikiHome]
	- [Game Walkthrough][Page GameGuide]
	- [Modding Tutorials][Page TutorialHome]

## Script Documentation Introduction

Welcome to the core code side documentation, there are a few things that you should know right away, this **ONLY** covers the code provided by FueledByOCHD and doesn't cover anything from Pokemon Essentials which has not been overhauled yet for those tutorials please check [Essentials Wiki][Page PokeEssWiki], nor does it cover any information on the information of the currently non-unified plugins for Essentials for those you will have to look around the internet and hope they have info.

Fueled's goal for this overhaul is to provide a cleaner and more dynamic based development while working to do the minimal ammount of work with RPG Maker XP to do development or modding. We should note that the current progress of the overhaul is in a very raw and likely slightly unstable due to its young life. However we have systems in place so that if something breaks or doesnt work as intended Fueled will be able to fix the issue without having to dig though all the different plugins and things looking for issues. However this young stage also means many issues may be result of some of the plugins that have not been built into the core.

Now to explain the code side of the overhaul the overhaul uses [Systems Based Design][Tut Docu SystemsBased] to provide a naturally dynamic foundation along with [Full Object Classes][Tut Docu FullClasses] to allow the XP system to feel more like a game engine. Fueled's experience results in the [CS Style OOP Extention][Tut Docu OOPStyle] and many of the class definitions that are designed to allow the system to be more modding friendly and bypass many of the basic limits of XP unless you have extensive programming knowledge and experience. 

Many of the basic systems also are designed towards making the experience for users to be smoother and cleaner for our users both in game and modding that makes players want to return.

## Endgoal A breath of life

Fueled's goals for the overhaul include keeping things playable durring the overhaul so development of the main game content can be worked on along side the overhaul while also aiming to make the whole game feel more alive and less static. Many of the goals down the road include NPC's with a custom conversation system, scripted game events (not using the default xp) and more. 

We are working towards and end goal of the world being way more interesting to be playing in while still having a pokemon style game. 
