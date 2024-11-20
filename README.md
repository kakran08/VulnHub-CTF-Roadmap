 # CTF Difficulty Cheatsheet (Vulnhub)
 
 This cheatsheet is aimed at CTF players and beginners to help them sort Vulnhub Labs on the basis of their difficulty. We have performed and compiled this list based on our experience.

# Instructions to use this repository:

### 1. Fork this repository to your own GitHub account

### 2. Clone the forked repository to your local machine

By running the following command after replacing your username:

```sh
git clone https://github.com/kakran08/CTF-Roadmap
```

### 3. To start tracking your progress, you can use this command to clear the rooms list:

```sh
sed -i 's/☑/☐/g' README.md
```

This command will replace '☑' with '☐' in the `README.md` file.

### 4. Keep track of which machines you have completed

Mark completed machines with '☑' in the `README.md` file.

### 5. [Optional] Optimize your progress tracking with machines in progress or stopped

You can use emojis inside the `Status` column, for example:

- '⏳' for machines in progress
- '🔴' for machines stopped (depends on other tasks, depends on knowledge from other rooms)

### 6. Make any changes you want and push them to your forked repo

By using the following commands:

```sh
git add .
git commit -m "Your commit message"
git push origin main
```

### 7. You can sync your forked repo with the upstream repo with:

```sh
# Stash your changes if you have any
git stash

# Add the upstream repo
git remote add upstream https://github.com/migueltc13/TryHackMe

# Pull the changes from the upstream repo
git pull upstream main

# Recover your stashed files if you have any
git stash pop
```

<!-- ☐  Not Started-->
<!-- ☑ Marjed Done -->
<!-- ⏳ In Progress-->
<!-- 🔴 Stopped-->

Table of Contents
 ================= 
* [Easy](#easy)
* [Medium](#medium)
* [Hard](#hard)

<a name="easy"></a>
##  Easy [⤴](#table-of-contents)
| S. No. | Machine Name | Status | Writeups |
| --- | --- | --- | --- |
| 1. | [ LAMPSecurity: CTF 4](https://www.hackingarticles.in/hack-the-lampsecurity-ctf4-ctf-challenge/) | ☐ | |
| 2. | [ LAMPSecurity: CTF 5](https://www.hackingarticles.in/hack-the-lampsecurity-ctf-5-ctf-challenge/) | ☐ | |
| 3. | [ LAMPSecurity: CTF 7](https://www.hackingarticles.in/hack-the-lampsecurity-ctf-7-ctf-challenge/) | ☐ | |
| 4. | [ Holynix: v1](https://www.hackingarticles.in/hack-the-holynix-v1-boot-2-root-challenge/) | ☐ | |
| 5. | [ pWnOS -1.0](https://www.hackingarticles.in/hack-the-pwnos-1-0-boot-to-root/) | ☐ | |
| 6. | [ pWnOS -2.0](https://www.hackingarticles.in/hack-the-pwnos-2-0-boot-2-root-challenge/) | ☐ | |
| 7. | [ DE-ICE:S1.120](https://www.hackingarticles.in/hack-the-de-ice-s1-120-vm-boot-to-root/) | ☐ | |
| 8. | [ Hackademic-RTB1](https://www.hackingarticles.in/hack-the-hackademic-rtb1-vm-boot-to-root/) | ☐ | |
| 9. | [ Tr0ll 1](https://www.hackingarticles.in/hack-the-troll-1-vm-boot-to-root/) | ☐ | |
| 10. | [ 21 LTR: Scene1](https://www.hackingarticles.in/hack-the-21ltr-scene-1-vm-boot-to-root/) | ☐ | |
| 11. | [ Kioptrix : Level 1.1](https://www.hackingarticles.in/hack-the-kioptrix-level-2-boot2root-challenge/) | ☐ | |
| 12. | [ Kioptrix : Level 1.2](https://www.hackingarticles.in/hack-the-kioptrix-level-1-2-boot2root-challenge/) | ☐ | |
| 13. | [ Kioptrix : Level 1.3](https://www.hackingarticles.in/hack-the-kioptrix-level-1-3-boot2root-challenge/) | ☐ | |
| 14. | [ Kioprtix: 5](https://www.hackingarticles.in/hack-the-kioptrix-5-ctf-challenge/) | ☐ | |
| 15. | [ SecOS: 1](https://www.hackingarticles.in/hack-the-secos1-ctf-challenge/) | ☐ | |
| 16. | [ Stapler](https://www.hackingarticles.in/hack-stapler-vm-ctf-challenge/) | ☐ | |
| 17. | [ SickOS 1.1](https://www.hackingarticles.in/hack-sickos-1-1-vm-ctf-challenge/) | ☐ | |
| 18. | [ SickOS 1.2](https://www.hackingarticles.in/hack-the-sickos-1-2-vm-ctf-challenge/) | ☐ | |
| 19. | [ Simple](https://www.hackingarticles.in/hack-simple-vm-ctf-challenge/) | ☐ | |
| 20. | [ Kevgir](https://www.hackingarticles.in/hack-kevgir-vm-ctf-challenge/) | ☐ | |
| 21. | [ Milnet](https://www.hackingarticles.in/hack-milnet-vm-ctf-challenge/) | ☐ | |
| 22. | [ Minotaur](https://www.hackingarticles.in/hack-minotaur-vm-ctf-challenge/) | ☐ | |
| 23. | [ Nullbyte](https://www.hackingarticles.in/hack-nullbyte-vm-ctf-challenge/) | ☐ | |
| 24. | [ VulnOS: 1](https://www.hackingarticles.in/hack-the-vulnos-1-ctf-challenge/) | ☐ | |
| 25. | [ VulnOS: 2.0](https://www.hackingarticles.in/hack-the-vulnos-2-0-vm-ctf-challenge/) | ☐ | |
| 26. | [ Freshly](https://www.hackingarticles.in/hack-freshly-vm-ctf-challenge/) | ☐ | |
| 27. | [ Sedena](https://www.hackingarticles.in/hack-sedna-vm-ctf-challenge/) | ☐ | |
| 28. | [ Nightmare](https://www.hackingarticles.in/hack-the-box-nightmare-walkthrough/) | ☐ | |
| 29. | [ Orcus](https://www.hackingarticles.in/hack-orcus-vm-ctf-challenge/) | ☐ | |
| 30. | [ Billu : B0x](https://www.hackingarticles.in/hack-billu-b0x-vm-boot2root-challenge/) | ☐ | |
| 31. | [ Moria 1.1](https://www.hackingarticles.in/hack-moria-1-1-ctf-challenge/) | ☐ | |
| 32. | [ Lazysysadmin](https://www.hackingarticles.in/hack-lazysysadmin-vm-ctf-challenge/) | ☐ | |
| 33. | [ Bulldog](https://www.hackingarticles.in/hack-bulldog-vm-boot2root-challenge/) | ☐ | |
| 34. | [ BTRSys:dv 2.1](https://www.hackingarticles.in/hack-btrsys-v2-1-vm-boot2root-challenge/) | ☐ | |
| 35. | [ BTRSys 1](https://www.hackingarticles.in/hack-btrsys1-vm-boot2root-challenge/) | ☐ | |
| 36. | [ RickdiculouslyEasy](https://www.hackingarticles.in/hack-rickdiculouslyeasy-vm-ctf-challenge/) | ☐ | |
| 37. | [ Dina](https://www.hackingarticles.in/hack-dina-vm-ctf-challenge/) | ☐ | |
| 38. | [ Born2Root](https://www.hackingarticles.in/hack-born2root-vm-ctf-challenge/) | ☐ | |
| 39. | [ G0rmint](https://www.hackingarticles.in/hack-g0rmint-vm-ctf-challenge/) | ☐ | |
| 40. | [ Basic penetration](https://www.hackingarticles.in/hack-the-basic-penetration-vm-boot2root-challenge/) | ☐ | |
| 41. | [ BSides Vancuver: 2018](https://www.hackingarticles.in/hack-the-bsides-vancouver2018-vm-boot2root-challenge/) | ☐ | |
| 42. | [ Toppo:1](https://www.hackingarticles.in/hack-the-toppo1-vm-ctf-challenges/) | ☐ | |
| 43. | [ Billu Box 2](https://www.hackingarticles.in/hack-billu-b0x-vm-boot2root-challenge/) | ☐ | |
| 44. | [ Basic Pentesting : 2](https://www.hackingarticles.in/hack-the-basic-pentesting2-vm-ctf-challenge/) | ☐ | |
| 45. | [ FourAndSix : 2](https://www.hackingarticles.in/fourandsix-2-vulnhub-walkthrough/) | ☐ | |
| 46. | [ Jarbas : 1](https://www.hackingarticles.in/hack-the-jarbas-1-ctf-challenge/) | ☐ | |
| 47. | [ Lampiao : 1](https://www.hackingarticles.in/hack-the-lampiao-1-ctf-challenge/) | ☐ | |
| 48. | [ Fowsniff : 1](https://www.hackingarticles.in/fowsniff-1-vulnhub-walkthrough/) | ☐ | |
| 49. | [ Typhoon : 1.02](https://www.hackingarticles.in/typhoon-1-02-vulnhub-walkthrough/) | ☐ | |
| 50. | [ DC-1](https://www.hackingarticles.in/dc-1-vulnhub-walkthrough/) | ☐ | |
| 51. | [ SP eric](https://www.hackingarticles.in/sp-eric-vulnhub-lab-walkthrough/) | ☐ | |
| 52. | [ DC-2](https://www.hackingarticles.in/dc-2-walkthrough/) | ☐ | |
| 53. | [ DC-3](https://www.hackingarticles.in/dc-3-walkthrough/) | ☐ | |
| 54. | [ Born2Root2](https://www.hackingarticles.in/born2root-2-vulnhub-walkthrough/) | ☐ | |
| 55. | [ Sputnik 1](https://www.hackingarticles.in/sputnik-1-vulnhub-walkthrough/) | ☐ | |
| 56. | [ PumpkinGarden](https://www.hackingarticles.in/pumpkingarden-vulnhub-walkthrough/) | ☐ | |
| 57. | [ PumpkinFestival](https://www.hackingarticles.in/mission-pumpkin-v1-0-pumpkinfestival-vulnhub-walkthrough/) | ☐ | |
| 58. | [ hackme1](https://www.hackingarticles.in/hackme-1-vulnhub-walkthrough/) | ☐ | |
| 59. | [ Sunset](https://www.hackingarticles.in/sunset-vulnhub-walkthrough/) | ☐ | |
| 60. | [ Ted:1](https://www.hackingarticles.in/ted1-vulnhub-walkthrough/) | ☐ | |
| 61. | [ dpwwn: 1](https://www.hackingarticles.in/dpwwn-1-vulnhub-walkthrough/) | ☐ | |
| 62. | [ The Library:2](https://www.hackingarticles.in/the-library2-vulnhub-walkthrough/) | ☐ | |
| 63. | [ WestWild: 1.1](https://www.hackingarticles.in/westwild-1-1-vulnhub-walkthorugh/) | ☐ | |
| 64. | [ dpwwn:2](https://www.hackingarticles.in/dpwwn2-vulnhub-walkthrough/) | ☐ | |
| 65. | [ Broken: Gallery](https://www.hackingarticles.in/broken-gallery-vulnhub-walkthrough/) | ☐ | |
| 66. | [ GrimTheRipper:1](https://www.hackingarticles.in/grimtheripper-1-vulnhub-walkthrough/) | ☐ | |
| 67. | [ Hack The Kioptrix Level-1](https://www.hackingarticles.in/hack-the-kioptrix-level-1/) | ☐ | |
| 68. | [ Seattle](https://www.hackingarticles.in/hack-seattle-vm-ctf-challenge/) | ☐ | |
| 69. | [ Zorz](https://www.hackingarticles.in/hack-zorz-vm-ctf-challenge/) | ☐ | |
| 70. | [ Pentester Lab: SQL Injection to Shell 1](https://www.hackingarticles.in/hack-pentester-lab-sql-injection-shell-vm/) | ☐ | |
| 71. | [ Quaoar](https://www.hackingarticles.in/hack-quaoar-vm-ctf-challenge/) | ☐ | |
| 72. | [ Pluck](https://www.hackingarticles.in/hack-pluck-vm-ctf-challenge/) | ☐ | |
| 73. | [ H.A.S.T.E.](https://www.hackingarticles.in/hack-h-s-t-e-vm-ctf-challenge/) | ☐ | |
| 74. | [ Vulnhub Pentester Lab: S2-052](https://www.hackingarticles.in/hack-the-vulnhub-pentester-lab-s2-052/) | ☐ | |
| 75. | [ unknowndevice64 v2.0](https://www.hackingarticles.in/unknowndevice64-v2-0-vulnhub-walkthrough/) | ☐ | |
| 76. | [ Cewlkid:1](https://www.hackingarticles.in/cewlkid-1-vulnhub-walkthrough/) | ☐ | |
| 77. | [ West Wild:2](https://www.hackingarticles.in/westwild-2-vulnhub-walkthrough/) | ☐ | |
| 78. | [ Sunset: dawn](https://www.hackingarticles.in/sunset-dawn-vulnhub-walkthrough/) | ☐ | |
| 79. | [ Misdirection 1](https://www.hackingarticles.in/misdirection-1-vulnhub-walkthrough/) | ☐ | |
| 80. | [ bossplayersCTF 1](https://www.hackingarticles.in/bossplayersctf-1-vulnhub-walkthrough/) | ☐ | |
| 81. | [ Connect The Dots:1](https://www.hackingarticles.in/connect-the-dots1-vulnhub-walkthough/) | ☐ | |
| 82. | [ Sar](https://www.hackingarticles.in/sar-vulnhub-walkthrough/) | ☐ | |
| 83. | [ My File Server:1](https://www.hackingarticles.in/my-file-server-1-vulnhub-walkthrough/) | ☐ | |
| 84. | [ Sahu](https://www.hackingarticles.in/sahu-vulnhub-walkthrough/) | ☐ | |
| 85. | [ Geisha:1](https://www.hackingarticles.in/geisha1-vulnhub-walkthrough/) | ☐ | |
| 86. | [ Katana](https://www.hackingarticles.in/katana-vulnhub-walkthrough/) | ☐ | |
| 87. | [ mhz_cxf:c1f](https://www.hackingarticles.in/mhz_cxf-c1f-vulnhub-walkthrough/) | ☐ | |
| 88. | [ Nyx:1](https://www.hackingarticles.in/nyx-1-vulnhub-walkthrough/) | ☐ | |
| 89. | [ Android4](https://www.hackingarticles.in/hack-the-android4-walkthrough-ctf-challenge/) | ☐ | |
| 90. | [ Dc:7](https://www.hackingarticles.in/dc7-vulnhub-walkthrough/) | ☐ | |
| 91. | [ Hacker Fest: 2019](https://www.hackingarticles.in/hacker-fest-2019-vulnhub-walkthrough/) | ☐ | |
| 92. | [ EVM:1](https://www.hackingarticles.in/evm-1-vulnhub-walkthrough/) | ☐ | |
| 93. | [ Me and My Girlfreind:1](https://www.hackingarticles.in/me-and-my-girlfreind1-vulnhub-walkthrough/) | ☐ | |
| 94. | [ DevRandom CTF:1.1](https://www.hackingarticles.in/devrandom-ctf1-1-vulnhub-walkthrough/) | ☐ | |
| 95. | [ Sumo:1](https://www.hackingarticles.in/sumo-1-vulnhub-walkthrough/) | ☐ | |
| 96. | [ Victim:1](https://www.hackingarticles.in/victim1-vulnhub-walkthrough/) | ☐ | |
| 97. | [ eLection:1](https://www.hackingarticles.in/election-1-vulnhub-walkthorugh/) | ☐ | |
| 98. | [ Sunset:decoy](https://www.hackingarticles.in/sunset-decoy-vulnhub-walkthrough/) | ☐ | |
| 99. | [ CyberSploit:1](https://www.hackingarticles.in/cybersploit-1-vulnhub-walkthrough/) | ☐ | |
| 105. | [ Loly:1](https://www.hackingarticles.in/loly-1-vulnhub-walkthrough/) | ☐ | |
| 100. | [ Sunset:Twilight](https://www.hackingarticles.in/sunset-twilight-vulnhub-walkthrough/) | ☐ | |
| 101. | [ Sunset:Midnight](https://www.hackingarticles.in/sunset-midnight-vulnhub-walkthrough/) | ☐ | |
| 102. | [ Chili:1](https://www.hackingarticles.in/chili-1-vulnhub-walkthrough/) | ☐ | |
| 103. | [ Healthcare:1](https://www.hackingarticles.in/healthcare-1-vulnhub-walkthrough/) | ☐ | |
| 104. | [ ShellDredd #1 Hannah](https://www.hackingarticles.in/shelldredd-1-hannah-vulnhub-walkthrough/) | ☐ | |
| 105. | [ Mercury](https://www.hackingarticles.in/mercury-vulnhub-walkthrough/) | ☐ | |
| 106. | [ HA: Narak:](https://www.hackingarticles.in/ha-narak-vulnhub-walkthrough/) | ☐ | |

<a name="medium"></a>
## Medium [⤴](#table-of-contents)
| S. No. | Machine Name | Status | Writeups |
| --- | --- | --- | --- |
| 1. | [ LAMPSecurity: CTF 8](https://www.hackingarticles.in/hack-the-lampsecurity-ctf8-ctf-challenge-2/) | ☐ | |
| 2. | [ Xerxes:1](https://www.hackingarticles.in/xerxes-1-vulnhub-walkthrough/) | ☐ | |
| 3. | [ DE-ICE:S1.140](https://www.hackingarticles.in/hack-the-de-ice-s1-140-boot-to-root/) | ☐ | |
| 4. | [ Hackademic-RTB2](https://www.hackingarticles.in/hack-the-hackademic-rtb2-boot2root/) | ☐ | |
| 5. | [ Tr0ll 2](https://www.hackingarticles.in/hack-the-tr0ll-2-boot2root-challenge/) | ☐ | |
| 6. | [ Skytower](https://www.hackingarticles.in/hack-the-skytower-ctf-challenge/) | ☐ | |
| 7. | [ PwnLab](https://www.hackingarticles.in/penetration-testing-pwnlab-ctf-challenge/) | ☐ | |
| 8. | [ Mr. Robot](https://www.hackingarticles.in/hack-mr-robot-vm-ctf-challenge/) | ☐ | |
| 9. | [ Droopy](https://www.hackingarticles.in/hack-droopy-vm-ctf-challenge/) | ☐ | |
| 10. | [ Sydney](https://www.hackingarticles.in/hack-sydney-vm-ctf-challenge/) | ☐ | |
| 11. | [ Skydog](https://www.hackingarticles.in/hack-skydog-vm-ctf-challenge/) | ☐ | |
| 12. | [ Tommyboy](https://www.hackingarticles.in/hack-tommyboy-vm-ctf-challenge/) | ☐ | |
| 13. | [ Fristileaks](https://www.hackingarticles.in/hack-fristileaks-vm-ctf-challenge/) | ☐ | |
| 14. | [ Spyder Sec](https://www.hackingarticles.in/hack-spydersec-vm-ctf-challenge/) | ☐ | |
| 15. | [ Acid](https://www.hackingarticles.in/hack-acid-vm-ctf-challenge/) | ☐ | |
| 16. | [ Lord of the Root](https://www.hackingarticles.in/hack-lord-root-vm-ctf-challenge/) | ☐ | |
| 17. | [ Acid Reloaded](https://www.hackingarticles.in/hack-acid-reloaded-vm-ctf-challenge/) | ☐ | |
| 18. | [ Hackday Albania](https://www.hackingarticles.in/hack-hackday-albania-vm-ctf-challenge/) | ☐ | |
| 19. | [ Fortress](https://www.hackingarticles.in/hack-fortress-vm-ctf-challenge/) | ☐ | |
| 20. | [ USV](https://www.hackingarticles.in/hack-usv-vm-ctf-challenge/) | ☐ | |
| 21. | [ Pipe](https://www.hackingarticles.in/hack-pipe-vm-ctf-challenge/) | ☐ | |
| 22. | [ Fartknocker](https://www.hackingarticles.in/hack-fartknocker-vm-ctf-challenge/) | ☐ | |
| 23. | [ Bot Challenge: Dexter](https://www.hackingarticles.in/hack-bot-challenge-dexter-boot2root-challenge/) | ☐ | |
| 24. | [ Defence Space](https://www.hackingarticles.in/hack-the-defense-space-vm-ctf-challengehack-defense-vm-ctf-challenge/) | ☐ | |
| 25. | [ Super Mario](https://www.hackingarticles.in/hack-super-mario-ctf-challenge/) | ☐ | |
| 26. | [ Donkey Docker](https://www.hackingarticles.in/hack-donkeydocker-ctf-challenge/) | ☐ | |
| 27. | [ Analougepond](https://www.hackingarticles.in/hack-analougepond-vm-ctf-challenge/) | ☐ | |
| 28. | [ Zico 2](https://www.hackingarticles.in/hack-zico2-vm-ctf-challenge/) | ☐ | |
| 29. | [ Covfefe](https://www.hackingarticles.in/hack-covfefe-vm-ctf-challenge/) | ☐ | |
| 30. | [ Depth](https://www.hackingarticles.in/hack-depth-vm-ctf-challenge/) | ☐ | |
| 31. | [ The Ether: Evil Science](https://www.hackingarticles.in/hack-ether-evilscience-vm-ctf-challenge/) | ☐ | |
| 32. | [ DerpNStink](https://www.hackingarticles.in/hack-the-derpnstink-vm-ctf-challenge/) | ☐ | |
| 33. | [ W1R3S.inc](https://www.hackingarticles.in/hack-the-w1r3s-inc-vm-ctf-challenge/) | ☐ | |
| 34. | [ Bob:1.0.1](https://www.hackingarticles.in/hack-the-bob-1-0-1-vm-ctf-challenge/) | ☐ | |
| 35. | [ The blackmarket](https://www.hackingarticles.in/hack-the-blackmarket-vm-ctf-challenge/) | ☐ | |
| 36. | [ Blacklight:1](https://www.hackingarticles.in/hack-the-blacklight-1-ctf-challenge/) | ☐ | |
| 37. | [ Golden Eye:1](https://www.hackingarticles.in/hack-the-golden-eye1-ctf-challenge/) | ☐ | |
| 38. | [ Temple of Doom](https://www.hackingarticles.in/hack-the-temple-of-doom-ctf-challenge/) | ☐ | |
| 39. | [ Wakanda:1](https://www.hackingarticles.in/hack-the-wakanda-1-ctf-challenge/) | ☐ | |
| 40. | [ ch4inrulz:1.0.1](https://www.hackingarticles.in/hack-the-ch4inrulz-1-0-1-ctf-challenge/) | ☐ | |
| 41. | [ MinU:1](https://www.hackingarticles.in/hack-the-minu-1-ctf-challenge/) | ☐ | |
| 42. | [ Raven](https://www.hackingarticles.in/hack-the-raven-walkthrough-ctf-challenge/) | ☐ | |
| 43. | [ Matrix:1](https://www.hackingarticles.in/mercy-vulnhub-walkthrough/) | ☐ | |
| 44. | [ Raven:2](https://www.hackingarticles.in/raven-2-vulnhub-walkthrough/) | ☐ | |
| 45. | [ Escalate_Linux](https://www.hackingarticles.in/escalate_linux-vulnhub-walkthrough-part-1/) | ☐ | |
| 46. | [ Mercy](https://www.hackingarticles.in/mercy-vulnhub-walkthrough/) | ☐ | |
| 47. | [ KFIOFan:1](https://www.hackingarticles.in/kfiofan1-vulnhub-walkthrough/) | ☐ | |
| 48. | [ RootThis:1](https://www.hackingarticles.in/vulnhub-rootthis-1-walkthrough/) | ☐ | |
| 49. | [ Kuya:1](https://www.hackingarticles.in/vulnhub-kuya-1-walkthrough/) | ☐ | |
| 50. | [ Matrix:2](https://www.hackingarticles.in/matrix-2-vulnhub-lab-walkthrough/) | ☐ | |
| 51. | [ W34kn3ss 1](https://www.hackingarticles.in/w34kn3ss-1-vulnhub-lab-walkthrough/) | ☐ | |
| 52. | [ Casino Royale](https://www.hackingarticles.in/casino-royale-1-vulnhub-walkthrough/) | ☐ | |
| 53. | [ Unknowndevice64:1](https://www.hackingarticles.in/unknowndevice64-1-vulnhub-lab-walkthrough/) | ☐ | |
| 54. | [ HackinOS:1](https://www.hackingarticles.in/hackinos1-vulnhub-lab-walkthrough/) | ☐ | |
| 55. | [ Web Developer:1](https://www.hackingarticles.in/web-developer-1-vulnhub-lab-walkthrough/) | ☐ | |
| 56. | [ SP ike](https://www.hackingarticles.in/sp-ike-vulnhub-lab-walkthrough/) | ☐ | |
| 57. | [ DC6](https://www.hackingarticles.in/dc6-lab-walkthrough/) | ☐ | |
| 58. | [ DC-4](https://www.hackingarticles.in/dc-4-vulnhub-walkthrough/) | ☐ | |
| 59. | [ Development](https://www.hackingarticles.in/development-vulnhub-walkthrough/) | ☐ | |
| 60. | [ Silky-CTF: 0x01](https://www.hackingarticles.in/silky-ctf-0x01-vulnhub-walkthrough/) | ☐ | |
| 61. | [ Bravery](https://www.hackingarticles.in/digitalworld-local-bravery-vulnhub-walkthrough/) | ☐ | |
| 62. | [ DC-5](https://www.hackingarticles.in/dc-5-vulnhub-walkthrough/) | ☐ | |
| 63. | [ Happycorp:1](https://www.hackingarticles.in/happycorp1-vulnhub-walkthrough/) | ☐ | |
| 64. | [ Symfonos:1](https://www.hackingarticles.in/symfonos1-vulnhub-walkthrough/) | ☐ | |
| 65. | [ PumpkinRaising](https://www.hackingarticles.in/pumpkinraising-vulnhub-walkthrough/) | ☐ | |
| 66. | [ Matrix-3](https://www.hackingarticles.in/matrix-3-vulnhub-walkthrough/) | ☐ | |
| 67. | [ Symfonos:2](https://www.hackingarticles.in/symfonos2-vulnhub-walkthrough/) | ☐ | |
| 68. | [ Beast 2](https://www.hackingarticles.in/beast-2-vulnhub-walkthrough/) | ☐ | |
| 69. | [ Joy](https://www.hackingarticles.in/digitalworld-local-joy-vulnhub-walkthrough/) | ☐ | |
| 70. | [ MinU:v2](https://www.hackingarticles.in/minu-v2-vulnhub-walkthrough/) | ☐ | |
| 71. | [ Zeus:1](https://www.hackingarticles.in/zeus1-vulnhub-walkthrough/) | ☐ | |
| 72. | [ DomDom:1](https://www.hackingarticles.in/domdom-1-vulnhub-walkthrough/) | ☐ | |
| 73. | [ SP:Jerome](https://www.hackingarticles.in/spjerome-vulnhub-walkthrough/) | ☐ | |
| 74. | [ The Library 1](https://www.hackingarticles.in/the-library1-vulnhub-walkthrough/) | ☐ | |
| 75. | [ Symfonos:3](https://www.hackingarticles.in/symfonos3-vulnhub-walkthrough/) | ☐ | |
| 76. | [ Clamp 1.0.1](https://www.hackingarticles.in/clamp-1-0-1-vulnhub-walkthrough/) | ☐ | |
| 77. | [ Tr0ll:3](https://www.hackingarticles.in/tr0ll-3-vulnhub-walkthrough/) | ☐ | |
| 78. | [ CTF KFIOFAN:2](https://www.hackingarticles.in/ctf-kfiofan-2-vulnhub-walkthorugh/) | ☐ | |
| 79. | [ Nezuko:1](https://www.hackingarticles.in/nezuko-1-vulnhub-walkthrough/) | ☐ | |
| 80. | [ Serial: 1](https://www.hackingarticles.in/serial-1-vulnhub-walkthrough/) | ☐ | |
| 81. | [ Skydog Con](https://www.hackingarticles.in/hack-skydog-con-ctf-2016-catch-can-vm/) | ☐ | |
| 82. | [ Padding Oracle](https://www.hackingarticles.in/hack-padding-oracle-lab/) | ☐ | |
| 83. | [ Pentester Lab: SQL Injection to Shell 2](https://www.hackingarticles.in/hack-pentester-lab-sql-injection-shell-ii-blind-sql-injection/) | ☐ | |
| 84. | [ Gibson](https://www.hackingarticles.in/hack-gibson-vm-ctf-challenge/) | ☐ | |
| 85. | [ D0not5top](https://www.hackingarticles.in/hack-d0not5top-vm-ctf-challenge/) | ☐ | |
| 86. | [ EW Skuzzy](https://www.hackingarticles.in/hack-ew-skuzzy-vm-ctf-challenge/) | ☐ | |
| 87. | [ 64 Base](https://www.hackingarticles.in/hack-64base-vm-ctf-challenge/) | ☐ | |
| 88. | [ Vulnupload](https://www.hackingarticles.in/hack-the-vulnupload-vm-ctf-challenge/) | ☐ | |
| 89. | [ Lin.Security](https://www.hackingarticles.in/hack-the-lin-security-vm-boot-to-root/) | ☐ | |
| 90. | [ AI:Web:1](https://www.hackingarticles.in/ai-web-1-vulnhub-walkthrough/) | ☐ | |
| 91. | [ Symfonos:4](https://www.hackingarticles.in/symfonos4-vulnhub-walkthrough/) | ☐ | |
| 92. | [ Sunset: Nightfall](https://www.hackingarticles.in/sunset-nightfall-vulnhub-walkthrough/) | ☐ | |
| 93. | [ DC:7](https://www.hackingarticles.in/dc7-vulnhub-walkthrough/) | ☐ | |
| 94. | [ AI:Web:2](https://www.hackingarticles.in/ai-web-2-vulnhub-walkthrough/) | ☐ | |
| 95. | [ Silky-CTF:0x02](https://www.hackingarticles.in/silky-ctf-0x02-vulhub-walkthrough/) | ☐ | |
| 96. | [ HA: Infinity Stones](https://www.hackingarticles.in/ha-infinity-stones-vulnhub-walkthrough/) | ☐ | |
| 97. | [ DC8](https://www.hackingarticles.in/dc8-vulnhub-walkthrough/) | ☐ | |
| 98. | [ DC:9](https://www.hackingarticles.in/dc-9-vulnhub-walkthrough/) | ☐ | |
| 99. | [ CyNix:1](https://www.hackingarticles.in/cynix1-vulnhub-walkthrough/) | ☐ | |
| 100. | [ Symfonos:5](https://www.hackingarticles.in/symfonos5-vulnhub-walkthrough/) | ☐ | |
| 101. | [ Five86:1](https://www.hackingarticles.in/five861-vulnhub-walkthrough/) | ☐ | |
| 102. | [ Five86:2](https://www.hackingarticles.in/five86-2-vulnhub-walkthrough/) | ☐ | |
| 103. | [ EnuBox:Mattermost](https://www.hackingarticles.in/enubox-mattermost-vulnhub-walkthrough/) | ☐ | |
| 104. | [ Inclusiveness:1](https://www.hackingarticles.in/inclusiveness-1-vulnhub-walkthrough/) | ☐ | |
| 105. | [ 2much:1](https://www.hackingarticles.in/2much-1-vulnhub-walkthrough/) | ☐ | |
| 106. | [ MuzzyBox:1](https://www.hackingarticles.in/muzzybox-1-vulnhub-walkthrough/) | ☐ | |
| 107. | [ TBBT](https://www.hackingarticles.in/tbbt-funwithflags-vulnhub-walkthrough/) | ☐ | |
| 108. | [ VulnUni 1.0.1](https://www.hackingarticles.in/vulnuni-1-0-1-vulnhub-walkthrough/) | ☐ | |
| 109. | [ TBBT:2](https://www.hackingarticles.in/tbbt2-vulnhub-walkthrough/) | ☐ | |
| 110. | [ CengBox:1](https://www.hackingarticles.in/cengbox-1-vulnhub-walkthrough/) | ☐ | |
| 111. | [ DMV :1](https://www.hackingarticles.in/dmv-1-vulnhub-walkthrough/) | ☐ | |
| 112. | [ CryptoBank:1](https://www.hackingarticles.in/cryptobank-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ LAMPSecurity: CTF6](https://www.hackingarticles.in/lampsecurity-ctf6-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Wordy](https://www.hackingarticles.in/ha-wordy-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Armour](https://www.hackingarticles.in/ha-armour-walkthrough/) | ☐ | |
| 113. | [ HA: ISRO](https://www.hackingarticles.in/ha-isro-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Joker](https://www.hackingarticles.in/ha-joker-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Naruto](https://www.hackingarticles.in/ha-naruto-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Avengers Arsenal](https://www.hackingarticles.in/ha-avengers-arsenal-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Rudra](https://www.hackingarticles.in/ha-rudra-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Chakravyuh](https://www.hackingarticles.in/ha-chakravyuh-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Gears of War: EP#1](https://www.hackingarticles.in/gears-of-war-ep1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ djinn:1](https://www.hackingarticles.in/djinn1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Chanakya](https://www.hackingarticles.in/ha-chanakya-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Dhanush](https://www.hackingarticles.in/ha-dhanush-vulnhub-walkthrough/) | ☐ | |
| 113. | [ In Plain Sight:1](https://www.hackingarticles.in/in-plain-sight1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ UA: Literally Vulnerable](https://www.hackingarticles.in/ua-literally-vulnerable-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Sunset-Sunrise](https://www.hackingarticles.in/sunset-sunrise-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Sunset: dusk](https://www.hackingarticles.in/sunset-dusk-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Zion:1.1](https://www.hackingarticles.in/zion-1-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ LemonSqueezy:1](https://www.hackingarticles.in/lemonsqueezy1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Seppuku:1](https://www.hackingarticles.in/seppuku1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Natraj](https://www.hackingarticles.in/ha-natraj-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Pandavas](https://www.hackingarticles.in/ha-pandavas-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Glasgow Smile:1.1](https://www.hackingarticles.in/glasgow-smile-1-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ GitRoot:1](https://www.hackingarticles.in/gitroot-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Tre:1](https://www.hackingarticles.in/tre1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ BlackRose:1](https://www.hackingarticles.in/blackrose-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ GreenOptic:1](https://www.hackingarticles.in/greenoptic-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Presidential:1](https://www.hackingarticles.in/presidential-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Broken 2020:1](https://www.hackingarticles.in/broken-2020-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ So Simple:1](https://www.hackingarticles.in/so-simple1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Photographer 1](https://www.hackingarticles.in/photographer-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Star Wars:1](https://www.hackingarticles.in/star-wars-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ CengBox:2](https://www.hackingarticles.in/cengbox-2-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Pwned-1](https://www.hackingarticles.in/pwned-1-vulnhub-walkthorugh/) | ☐ | |
| 113. | [ Relevant: 1](https://www.hackingarticles.in/relevant-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Panabee: 1](https://www.hackingarticles.in/panabee-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Maskcrafter: 1.1](https://www.hackingarticles.in/maskcrafter-1-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Forensics](https://www.hackingarticles.in/ha-forensics-vulnhub-walkthrough/) | ☐ | |
| 113. | [ KB-Vuln: 3](https://www.hackingarticles.in/kb-vuln-3-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Vedas](https://www.hackingarticles.in/ha-vedas-vulnhub-walkthrough/) | ☐ | |
| 113. | [ HA: Sherlock](https://www.hackingarticles.in/ha-sherlock-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Cybox:1](https://www.hackingarticles.in/cybox-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Hogwarts: Bellatrix](https://www.hackingarticles.in/hogwarts-bellatrix-vulnhub-walkthrough/) | ☐ | |
| 113. | [ DevGuru:1](https://www.hackingarticles.in/devguru-1-vulnhub-walkthrough/) | ☐ | |
| 113. | [ Tomato:1](https://www.hackingarticles.in/tomato-1-vulnhub-walkthrough/) | ☐ | |
 
<a name="hard"></a>
## Hard [⤴](#table-of-contents)
| S. No. | Machine Name | Status | Writeups |
| --- | --- | --- | --- |
| 1. | [ DE-ICE:S1.130](https://www.hackingarticles.in/hack-the-de-ice-s1-130-boot2root-challenge/) | ☐ | |
| 2. | [ Breach 1.0](https://www.hackingarticles.in/hack-breach-1-0-vm-ctf-challenges/) | ☐ | |
| 3. | [ Breach 2.1](https://www.hackingarticles.in/hack-breach-2-1-vm-ctf-challenge/) | ☐ | |
| 4. | [ Billy Madison](https://www.hackingarticles.in/hack-billy-madison-vm-ctf-challenge/) | ☐ | |
| 5. | [ Necromancer](https://www.hackingarticles.in/hack-necromancer-vm-ctf-challenge/) | ☐ | |
| 6. | [ Cyberry:1](https://www.hackingarticles.in/hack-vm-cyberry-1boot2root-challenge/) | ☐ | |
| 7. | [ BSides London 2017](https://www.hackingarticles.in/hack-the-bsides-london-vm-2017boot2root/) | ☐ | |
| 8. | [ Game of Thrones](https://www.hackingarticles.in/hack-game-thrones-vm-ctf-challenge/) | ☐ | |
| 9. | [ Trollcave](https://www.hackingarticles.in/hack-the-trollcave-vm-boot-to-root/) | ☐ | |
| 10. | [ The Gemini inc](https://www.hackingarticles.in/hack-the-gemini-inc-ctf-challenge/) | ☐ | |
| 11. | [ PinkyPalace](https://www.hackingarticles.in/hack-the-pinkypalace-vm-ctf-challenge/) | ☐ | |
| 12. | [ Violator](https://www.hackingarticles.in/hack-the-violator-ctf-challenge/) | ☐ | |
| 13. | [ Bulldog 2](https://www.hackingarticles.in/hack-the-bulldog2-ctf-challenge/) | ☐ | |
| 14. | [ WinterMute:1](https://www.hackingarticles.in/hack-the-wintermute-1-ctf-challenge/) | ☐ | |
| 15. | [ /dev/random:K2](https://www.hackingarticles.in/hack-the-dev-random-k2-vm-boot2root-challenge/) | ☐ | |
| 16. | [ Gemini inc:2](https://www.hackingarticles.in/hack-the-gemini-inc2-ctf-challenge/) | ☐ | |
| 17. | [ Moonranker:1](https://www.hackingarticles.in/moonraker1-vulnhub-walkthrough/) | ☐ | |
| 18. | [ Replay:1](https://www.hackingarticles.in/replay-1-vulnhub-lab-walkthrough/) | ☐ | |
| 19. | [ Torment](https://www.hackingarticles.in/digitalworld-localtorment-vulnhub-walkthrough/) | ☐ | |
| 20. | [ 6 Days](https://www.hackingarticles.in/hack-6days-vm-ctf-challenge/) | ☐ | |
| 21. | [ IMF](https://www.hackingarticles.in/hack-imf-vm-ctf-challenge/) | ☐ | |
| 22. | [ thewall](https://www.hackingarticles.in/hack-thewall-vm-ctf-challenge/) | ☐ | |
| 23. | [ ROP Primer:1.0.1](https://www.hackingarticles.in/hack-the-rop-primer-1-0-1-ctf-challenge/) | ☐ | |
| 24. | [ USV:2017](https://www.hackingarticles.in/hack-usv-2017-ctf-challenge/) | ☐ | |
| 25. | [ C0m80](https://www.hackingarticles.in/hack-c0m80-vm-boot2root-challenge/) | ☐ | |
| 26. | [ Teuchter](https://www.hackingarticles.in/hack-the-teuchter-vm-ctf-challenge/) | ☐ | |
| 27. | [ Durian:1](https://www.hackingarticles.in/durian-1-vulnhub-walkthrough/) | ☐ | |
| 28. | [ Prime:1](https://www.hackingarticles.in/prime-1-vulnhub-walkthrough/) | ☐ | |
| 29. | [ View2aKill](https://www.hackingarticles.in/view2akill-vulnhub-walkthrough/) | ☐ | |
| 30. | [ Tempus Fugit:1](https://www.hackingarticles.in/tempus-fugit-1-vulnhub-walkthrough/) | ☐ | |
| 31. | [ Insanity:1](https://www.hackingarticles.in/insanity-1-vulnhub-walkthrough/) | ☐ | |
| 32. | [ Jigsaw:1](https://www.hackingarticles.in/jigsaw1-vulnhub-walkthrough/) | ☐ | |
| 33. | [ Mumbai:1](https://www.hackingarticles.in/mumbai1-vulnhub-walkthrough/) | ☐ | |
| 34. | [ PowerGrid:1.0.1](https://www.hackingarticles.in/powergrid-1-0-1-vulnhub-walkthrough/) | ☐ | |
| 35. | [ Tempus Fugit:1](https://www.hackingarticles.in/tempus-fugit-1-vulnhub-walkthrough/) | ☐ | |
| 36. | [ Primer](https://www.hackingarticles.in/hack-primer-vm-ctf-challenge/) | ☐ | |
