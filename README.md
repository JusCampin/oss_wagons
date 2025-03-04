# bcc-wagons

## Description

Whether you're a hardworking farmer tending to your crops, a family embarking on a scenic countryside picnic, or a successful businessman looking to make an impression, these wagons will revolutionize the way you travel.

## Features

- Buy and sell wagons through the wagon shops
- Cash and/or gold may be used for payments in the menu
- Individual inventory for owned wagons
- Call your selected wagon using the `J` key
- Shop hours may be set individually for each shop or disabled to allow the shop to remain open
- Shop blips are colored and changeable per shop location
- Blips can change color reflecting if shop is open, closed or job locked
- Shop access can be limited by job and jobgrade
- Wagons can be returned at any shop location via prompt
- Return your wagon when afield by using the menu
- Give your wagon a special name at purchase time (rename wagon using the menu)
- Set a max number of wagons per player and wainwrights in the main config
- Distance-based NPC spawns
- Trade wagons with other players using the menu
- Limit individual wagon purchases to a specified job
- Wainwright job can sell wagons to players (more to come!)
- Shared inventory option. Allows wagon inventories to be looted when wagon is empty of players
- Wagon condition reduces while the wagon is spawned
  - Repair your wagon with the repair item (default: hammer / set in config)
  - Repair item can be used to repair both wagons and boats (if using bcc-boats)
  - Durability of repair item reduces with each use

## Commands
- Command `/wagonEnter` if you have trouble getting to your wagon
- Command `/wagonReturn` to return wagon when away from a shop (if enabled in config)

## Dependencies

- [vorp_core](https://github.com/VORPCORE/vorp-core-lua)
- [vorp_inventory](https://github.com/VORPCORE/vorp_inventory-lua)
- [bcc-utils](https://github.com/BryceCanyonCounty/bcc-utils)

## Installation

- Make sure dependencies are installed/updated and ensured before this script
- Add `bcc-wagons` folder to your resources folder
- Add `ensure bcc-wagons` to your `resources.cfg`
- Run the included database file `wagons.sql`
- Restart Server

## Credits
- lrp_stable
- [ByteSizd](https://github.com/AndrewR3K) - Vue Boilerplate for RedM
- [SavSin](https://github.com/DavFount) - UI conversion to VueJS

## GitHub
- https://github.com/BryceCanyonCounty/bcc-wagons
