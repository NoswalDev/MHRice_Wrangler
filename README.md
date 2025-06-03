# MHRice_Wrangler
Wrangles data from the MHRice database: https://github.com/wwylele/mhrice

Currently outputs:
- Monster Names & IDs
- Item Names, IDs, & Properties
  - Anomaly Items
- Item Drop Tables
- Anomaly Drop Lots
- Anomaly Item Drop Table Average Worth
- Anomaly Investigation Average Material Drop

### entry notes:
- slash: slash damage
- strike: blunt damage
- shell: shot damage
- elect: thunder damage
- piyo: stun buildup
- hyakuryu: rampage
- mystery: afflicted
- hagibui: carve & part break
- multiple_target_reward_table_index: multi anom essence drops
- multiple_fix_reward_table_index: multi anom coin drops
- "Skill": 44 :armor skill id
- "Deco": 44 :deco id
- "MrDeco": 78: mr deco id
- Alchemy: charm melding
  - Alchemy4: Wisp of Mystery
  - Alchemy5: Rebirth
  - AlchemyShinki: Anima
  - AlchemyKyokkou: Reincarnation
  - AlchemyTensei: Aurora
  - AlchemyHaki: Vigor
  - AlchemyEnkan: Cyclus
- evaluation_value: melding value of monster parts for base game charm melding
- category_worth: crafting worth for weapons, armor, augments, and anomaly charm melding
- monster_rank: in the context of anomaly (mystery), references A#
- meat_data.meat_container: hitzone data in monster database
- decorations_product: crafting material list for decos w/ key items and key enemies
- clear_quest_no_list: prerequisite quest list
- armor_buildup: max defense upgrade available per player level
- spy: meowcenaries

### section notes:
- monsters: monster specific info
- monster_lot: monster drops
- pop: drops from collection or carve
- lots: list of tables that define item drops
  - Drop Lots
    - Drop Tables
      - Pop Drops

### Current:
- deco unlock conditions
- armor unlock conditions

### Future:
- event quest min level requirements
- item min level requirements
  1. key quest level
    1. monster level
      1. monster material level
    2. quest reward item level
  2. event quest level
    1. monster level
      1. monster material level
  3. meowcenary level
    1. meowcenary item level
  4. progress flag event
    1. event rewards level
    2. progress flag level
  
  
