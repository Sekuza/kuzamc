#                       ADDED                                                                            #
- Added job descriptions in the menu
- Added new icons
- Added new custom items:
    > Guides
    > Workstation Lumberjack
    > Firewood
    > Saw
    > Delivery Wood chips
    > Delivery Chipboard
    > Delivery Warped wood chips
    > Delivery crimson wood chips
    > Delivery reinforced chipboard
    > Workstation Digger
    > Brush
    > Unknown fragment
    > Delivery fossil fragment
    > Delivery unknown fossil
    > Delivery ancient skeleton
    > Workstation fisherman
    > Knife
    > Delivery fish oil
    > Delivery fish remains
    > Delivery tuna
    > Delivery salve
    > Workstation Hunter
    > Tanning knife
    > Fur
    > Delivery animal skin
    > Delivery Tanned leather
    > Workstation blacksmith
    > Coil
    > Delivery Weapons
    > Delivery Armors
    > Delivery Projectiles
    > Delivery Coil
    > Workstation Chef
    > Delivery Meat
    > Delivery Vegetables
    > Delivery Mixed food
    > Workstation Farmer
    > Delivery Wheat flour
    > Delivery Jam
    > Delivery Butter
    > Delivery Cheese
    > Delivery Milk
- Added custom items to the shop
- Added VR compability
    
#                       CHANGES                                                                            #

- Replaced the shops from the marketplace with better ones
- The wandering trader got better trades now
- Tablist has been changed:
   > Moved the balance from the tablist into the HUD
- Changed the currency from **$** to *(**C**)oins
- Changed the texture of the **menu** item
- Increased the costs for the iron rank certification
    > From 1600C to 1800C
- Changed the menu icons
- Disabled temporary the entry into the end
- Piston dublication has been deactivated
- Changed the costs for heads:
    > Player Heads: 100 Coins -> 300 Coins
    > Other Heads:  100 Coins -> 150 Coins
- The Chat emotes have been revised
- Changed some things for the backpacks:
    - **Pouch:**
    > _Can only store food_
    - **Leathered Backpack:**
    > Changed the size from 2 to 3
    > Auto-pickup has been activated

#                       FIXES                                                                            #

- Fixed a bug where you can't sleep at night
- Fixed a bug where you can't interact with NPC's
- Fixed a bug where the nameplates were permanently visible
- Fixed a bug where you don't have the permissions to the head shop
- Fixed a bug where the **leathered backpack** didn't worked
- Fixed a bug where you can't buy the recipe for **leathered backpack**

#                       REMOVED                                                                            #

- Removed **How-to books** from kit starter
- Removed the job **Explorer**
- Removed **Time set day** button from the menu

#                       JOB CHANGES                                                                            #

### Lumberjack (Woodcutter)
- Renamed the job from **Woodcutter** to **Lumberjack**
- The lumberjack earns money by processing wood into deliveries, these deliveries can be sold to a trader. You have to craft a workstation        to process your wood.
- These are the traits:
   >1x Stripped Log **||** 1x Saw                                                 => 4x Firewood
   >32x Stripped Log **||** 1x Saw                                               => 1x Delivery: Wood Chips
   >16x Delivery;Wood chips **||** 1x Saw                                   => 1x Delivery: Chipboard
   >36x Warped Stripped Log **||** 1x Saw                                  => 1x Delivery: Warped Wood Chips
   >36x Crimson Stripped Log **||** 1x Saw                                  => 1x Delivery: Crimson Wood Chips
   >6x Delivery: Crimson Wood chips **||** 6x Delivery: Warped Wood chips   => 1x Delivery: Reinforced Chipboard
- These are the following shop prices
   >Delivery: Wood chips:  20 Coins
   >Delivery: Chipboard: 300 Coins
   >Delivery: Warped Wood chips: 15 Coins
   >Delivery: Crimson Wood chips: 15 Coins
   >Delivery: Reinforced Chipboard: 450 Coins
- Changed the following EXP values:
   > BREAKING Logs & Stripped Logs from 3.5XP to 5.0XP
   > BREAKING Planks: 1.25XP
   > BREAKING Warped Logs & Warped Stripped Logs: 6.0XP
   > BREAKING Crimson & Warped Planks: 1.5XP
- Doesn't get money for breaking and stripping blocks
- Resetted the job progression for everyone
- Job re-join cooldown: 12 hours
        
### Digger

- The digger earns money by digging and processing fossiles in the workstation. The processed fossiles can be sold to a trader.
- These are the traits
   >10x Unknown fragment  **||** 1x Brush                        => 1x Delivery: Fossil fragment
   >5x Delivery: Fossil fragment **||** 1x Brush                 => 1x Delivery: Unknwon fossil
   >3x Delivery: Unknown fossil **||** 1x Brush                   => 1x Delivery: Ancient Skeleton
- These are the following shop prices:
   >Delivery;Fossil fragment:  20 Coins
   >Delivery;Unknown fossil:   120 Coins
   >Delivery;Ancient skeleton: 400 Coins
- The job digger can craft a new item:
   >Brush
- You have a small chance to get unknown fragments through digging dirt, sand, gravel, clay
- You can also find unknown fragments through soul sand & soul soil
- Changed the following incomes:
   > BREAKING Dirt/Sand from 0.1 Coins to 0.4 Coins
   > BREAKING Soul sand from 0.5 Coins to 0.6 Coins
   > BREAKING Soul soil: 0.6 Coins
   > BREAKING Clay from 0.5 Coins to 0.6 Coins
- Increased experience gain by 100%
- Resetted the job progression for everyone
- Job re-join cooldown: 12 hours
      
### Miner

- The miner earns money by mining ores and selling copper ingots to a trader.
- These are the following shop prices:
   >Copper Ingot:  1 Coin
- Changed the following EXP values:
   > Removed the experience gain for stones
   > Increased the experience gain for all ores by 100%
- Resetted the job progression for everyone
- Job re-join cooldown: 12 hours

### Farmer

- The farmer earns money by doing typical farm life activities. This job can also get money by processing items into deliveries.
- These are the traits:
   > 64x Wheat                               => 1x Delivery: Wheat flour
    > 64x Sweet Berries                         => 1x Delivery: Jam
    > 1x Milk Bucket || 1x Milk Bucket          => 1x Delivery: Milk
    > 10x Delivery: Milk                         => 1x Delivery: Butter
    > 10x Delivery: Milk || 1x Delivery: Butter   => 1x Delivery: Cheese
- These are the following shop prices:
   >Delivery: Wheat flour:  20 Coins
   >Delivery: Jam:          20 Coins
   >Delivery: Butter:       30 Coins
   >Delivery: Cheese:       80 Coins
- Changed the following EXP values:
   > Increased experience gain for taming by 100%
   > Increased experience gain for breeding by 100%
   > Increased experience gain for shearing by 100%
   > Increased experience gain for milking by 100%
   > Increased experience gain for breaking by 100%
   > Increased experience gain for collecting by 100%
   > PLACING crops: 1XP
   > Removed experience gain for saplings & flowers
- Changed the following income values:
   > No income for taming
   > No income for breeding
   > Increased the income for placing crops by 500%
   > Removed income for saplings & flowers
- Resetted the job progression for everyone
- Job re-join cooldown: 12 hours

### Farmer

- The fisherman earns money by processing fishes in the workstation. Processed items can be sold to a trader.
- These are the traits:
   >10x Cod       ||     1x Knife                    => 1x Delivery: Fish oil
   >10x Cod       ||     1x Knife                    => 2x Delivery: Fish remains
   >10x Salmon    ||     1x Knife                    => 1x Delivery: Fish oil
   >10x Salmon    ||     1x Knife                    => 2x Delivery: Fish remains
   >4x Tropical fish  ||  1x Knife                   => 2x Delivery: Fish oil
   >10x Delivery: Fish remains  ||  10x Irong Ingot   => 1x Delivery: Tuna
   >10x Delivery: Fish oil                            => 1x Delivery: Salve
- These are the following shop prices:
   >Tuna: 50 Coins
   >Salve: 150 Coins
- This job can craft a new item:
   > Knife
- No income through fishing
- Changed the following experience values:
   > FISHING salmon from 14XP to 20XP
   > FISHING cod from 14XP to 20XP
   > FISHING tropical fish from 15XP -> 22.5XP
   > FISHING pufferfish from 16XP -> 30XP
   > FISHING nautilus shell from 150XP to 500XP
   > FISHING trash loot from 1XP to 4XP
   > FISHING rare loot to 10XP
- Resetted the job progression for everyone
- Job re-join cooldown: 12 hours

### Hunter

- The hunter earns money by killing monsters and processing fur's in the workstation. Processed items can be sold to a trader.
- These are the traits:
   >32x Rotten flesh                                => 1x Leather
   >15x  Fur || 1x Tanning knife                    => 1x Delivery: Animal skin
   >5x Delivery: Animal skin || 1x Tanning knife     => 1x Delivery: Tanned Leather
- These are the following shop prices:
   >Delivery: Animal Skin:       10 Coins
   >Delivery: Tanned Leather:   110 Coins
- This job can craft a new item:
   >Tanning knife
- You have a chance to drop the following items by killing it:
   - Wolf
      > 1x Fur [50%]
   - Rabbit
     > 1x Fur [50%]
   - Ocelot
     > 1x Fur [50%]
   - Ravager
      > 8-10 x Fur [50%]
- Changed the following experience values:
   > No more income & XP for taming
   > No more income & XP for common animals
   > Increased the experience gain for uncommon animals by 100%
   > Increased the experience gain for monsters by 50%
- Resetted the job progression for everyone
- Job re-join cooldown: 12 hours

### Blacksmith

- The blacksmith earns money by smelting metals and processing items in the workstation. Processed items can be sold to a trader.
- These are the traits:
   >20x Copper Ingot                       => 1x Coil
   >32x  Iron Ingot || 12x Gold Ingot      => 1x Delivery: Weapons 
   >64x  Iron Ingot || 32x Gold Ingot      => 1x Delivery: Armor
   >64x Arrow      || 20x Flint            => 1x Delivery: Projectiles 
   >5x Coil       || 20x Coal              => 1x Delivery: Coils
- These are the following shop prices:
   >Delivery: Weapon: 50 Coins
   >Delivery: Armor: 105 Coins
   >Delivery: Projectiles: 50 Coins
   >Delivery: Coils: 22 Coins
- Changed the following values for income:
  > SMELTING Raw Iron from 0.20 Coins to 0.75 Coins
  > SMELTING Raw Gold from 0.20 Coins to 0.75 Coins
  > SMELTING Raw Copper from 0.05 Coins to 0.20 Coins
  > No income through crafting
- Changed the following experience values:
  > SMELTING Raw Iron from 0.5XP to 3XP
  > SMELTING Raw Gold from 0.5XP to 3XP
  > SMELTING Raw Iron from 0.05XP to 1.5XP
  > Increased the experience gain by crafting armors, weapons & projectiles by 50%
  > Increased the experience gain by repairing armors, weapons & projectiles by 25%
- Resetted the job progression for everyone
- Job re-join cooldown: 12 hours

### Explorer

- Job has been removed

### Chef

- The chef earns money by cooking food and processing items. Processed items can be sold to a trader.
- These are the traits:
   >32x Cooked Porkshop || 32x Cooked Beef                     => 1x Delivery: Meat
   >32x Cooked Chicken || 32x Cooked Beef                      => 1x Delivery: Meat
   >32x Carrot || 32x Beetroot                                 => 1x Delivery: Vegetables
   >2x Delivery: Meat || 2x Delivery: Vegetables                 => 1x Delivery: Mixed food
- These are the following shop prices:
   >Delivery: Meat:              30 Coins
   >Delivery: Vegetables:        25 Coins
   >Delivery: Mixed food:       150 Coins
- Changed the following values for income:
  > increased the income for cooking through the campfire by 100%
  > increased the income for cooking through the furnace by 100%
  > No income through crafting
- Changed the following experience values:
   > increased the experience gain for cooking through campfire by 200%
   > increased the experience gain for cooking through furnace by 100%
   > increased the experience gain for eating by 50%
   > increased the experience gain for crafting by 100%
- Resetted the job progression for everyone
- Job re-join cooldown: 12 hours

#                       DISCORD SERVER CHANGES                                                                            #

- Moved server changelogs to github
- Added the channel "guides"
- Changed the name from the bot **KUZA** to **Minecraft Server**