---
title: Home
layout: home
nav_order: 1
youtubeId: 3hYWITmHs2Q
---

# Gaming Security Experiments

This website is the homepage for accessing the resources related to the experiments conducted on online game system security, aiming to better understand network-level cheating and seeking for detection techniques. 

## First phase of the experiments
The goal of this phase is to validate the online game used for the experimentations. The game leveraged is [Unreal Engine's](https://www.unrealengine.com/en-US?sessionInvalidated=true) sample game: [Lyra](https://dev.epicgames.com/documentation/en-us/unreal-engine/lyra-sample-game-in-unreal-engine), which is a team shooter game. The aspects to evaluate are related to the playability and the smoothness of the game in an online, large scale environment. This is to have a ground truth about the operation of the game before proceeding to planned modifications.

## Second phase of the expeiments 
The objective is to collect traces of cheats usage under realistic gameplay conditions with players from globally distributed regions. The cheats are enaled directly within the game as “super powers” that players can use. When they do, this is logged. The goal is to generate labeled datasets with benign and cheating traffic that we, and other researchers, could use to develop and test cheating detection techniques.

## The Game

The game is a modified version of the Lyra Starter Game template from Epic Games / Unreal Engine that includes the execution of cheats as "super-powers" for experimental purposes.  
A video demonstration is available [here](https://youtu.be/3hYWITmHs2Q).

{% include youtubePlayer.html id=page.youtubeId %}



The installation guidelines are detailed at [get started](/set_up/) and the gameplay is described in [Gameplay Description](/gameplay.md) pages.
