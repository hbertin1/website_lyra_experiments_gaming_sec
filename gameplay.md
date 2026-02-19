---
title: Gameplay Description
layout: default
nav_order: 3
youtubeId: aahZulqsmoI
---

# Gameplay Description 

## Synopsis 

Unreal CheatNet is an online third-person multiplayer shooter built on the Lyra framework, where two teams fight in a team deathmatch. The objective is to be the first team to reach 30 eliminations.

The particularity of Unreal CheatNet lies in its integration of traditional unfair mechanics (cheats) as superpowers within the game. At the beginning of the match, players have one of the three primary abilities reproducing a real-world cheating technique: a lag-switch,  a fixed delay, and the third one a player-targeted DDoS attack. To preserve playability and balance of the game, abilities are tied to a cooldown, preventing cheat spamming.

Players can also collect power-ups scattered throughout the map. These powerups represent single use powerful client-side cheats, such as a *wallhack*, an *aimbot* and a *hit redirection*. Players can have their main ability as well as a powerup, consumed on use, equipped at the same time.
  
Matches take place on a custom map designed specifically for this project. The visual design of Unreal CheatNet follows a sci-fi and magical aesthetic, with influences of the game *Warframe*. The map itself includes magical elements, including portals and rune-based barriers. Powerups are represented as spell books. 

## Description of the cheats

The game enables the use of 6 cheats that are included as super-powers and available to the user.

The user select one main ability which is available periodically (a reload time is needed after using the ability).

- *Lag-Switch:* the attacker temporarily halts outgoing network traffic to the server, resulting in artificially increased latency and desynchronization that prevents opponents from reacting in time to the attacker's game actions.
- *Player-targeted Distributed Denial-of-Service (DDoS):* The attacker floods the victim's network bandwidth with excessive traffic, preventing them from reliably receiving and sending network information and causing increased latency and packet loss. The effects of this attack are simulated within our game to avoid actually performing a DDoS attack on the player's bandwidth.
- *Fixed-Delay:* The attacker adds a slight continuous artificial delay into their outgoing network traffic, resulting in the attacker's actions being delayed on the victim side without causing significant desynchronization.

The other cheats are powerups that can be collected on the map at pick-up locations.
- *Aimbot:* A cheat that automatically controls the player's aim to lock onto opponents.
- *Wallhacks:* A cheat that enables to observe opponents through the walls or other obstacles.
- *Hit-Redirection:* A packet-tampering attack, in which the result of a missed shot transmitted to the server is altered to redirect the shot as a successful hit against an opponent.


A video detailing the effects of the cheats can be found [here](https://youtu.be/aahZulqsmoI). 


{% include youtubePlayer.html id=page.youtubeId %}