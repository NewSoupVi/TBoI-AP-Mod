# ToDo 
## High Priority:
- [x] rewrite as class
- [x] test all goals
- [x] implement a goal only requiring to collect the required location count
  - [x] test
- [x] fix restock override
  - [x] breaks with binge eater.....
    - [x] steam sale doesn't work now prolly.......
      - [x] test multiple steam sales
- [x] look into RNG, we seem to get the same cards/pill when we spawn stuff quickly
- [x] prevent spawning items on top of ... (esp. when run start with many items)
  - [x] other items
  - [x] ~~player~~ `-> seems to not work as the player is moving during start (from center pos to actual start pos). wont fix`
- [x] fix collect behavoir
  - [x] collect seems to crash sometimes? maybe forfeit too? `fixed... I think?`
- [x] implement all collectables for start inv
- [x] boss rewards
  - [x] crashes on beast
  - [x] fix most boss shouldnt give reward on delirum stage
- [x] go thru the discord thread for potential other options/functions
- [x] traps
  - [ ] more traps!
    - [x] add trap: Paralysis 
    - [x] add trap: Wavy Mushroom
- [x] death link
- [x] datapackage version caching
  - [x] needs RoomInfo fix
    - [x] better caching ~~with seperate files~~
- [x] use RNG class from TBoI for hopefully better RNG
- [x] fix bug were we increase item step but not collect item!
- [x] figure out a better way to input AP host/port/slot name/password
  - [x] improve typing?
- [x] fix required locations max value
- [x] fix item drops by Bumbo not added to the check goal? `quick test worked fine`
- [x] fix teleport cucking you out of 2nd knife piece?
- [x] fix Tainted Isaac getting items permanently `-> spawn item on ground when 8 item in inv. not prefect but good enough imo`
- [ ] fix temporary characters sending death links `-> can't find a ~~good~~ way to differentiate via API`
- [ ] look into game crashing (and borking save) on beating goal? `can't reproduce`
- [ ] look into transformation seemingly not working or applying delayed `can't reproduce`
- [x] replace check items with a AP item on pickup
  - [x] fix Tainted Cain crafted item not giving checks? `no good way to fix, will use AP item as replacement on pickup of normal items instead`
  - [x] fix challenge room always triggering
  - [x] fix death certificate
  - [x] fix devil deal not accounting for revives
  - [x] fix double counting pickups
  - [x] fix flip
- [x] AP Webhost can't display custom wighting options `excluded on webhost for now`
- [x] new goal: full note aka all bosses with an extra option for how many chars
  - [x] broken? `fixed!`
- [ ] docs
  - [x] add guide to full save file  
- [x] fix AP cache init failure
- [x] fix Deathlink always set
- [x] fix price reset on morphing shop item (low price items)
- [ ] kick for wrong seed on reconnect?
- [x] release button in MCM
- [x] collect button in MCM
- [x] list hint button in MCM
  - [x] send random item hint button in MCM? => would require item group on AP side as alias??
- [x] limit drops per floor as new option
  - [x] account for skipping floors
  - [ ] reconnect spawns items again?
- [x] new goal: (certain amount of) note marks
- [ ] option to not connect on run start
- [ ] AP bum?!

## Maybe Later:
- [ ] wighting / balancing
  - [ ] more presets
- [ ] look into non blocking with socket.select
- [ ] whatever other great options AP has I don't know about
- [x] test MCM clash with ReHUD `seems to work on continued`
  - [x] test MCM Pure
- [ ] look into graphics glitch on transformations
- [ ] look into reruns
  - [ ] -> counts as old seed cause isContinued + new seed (?)
- [ ] test multiplayer
- [ ] test mod compatibilty
