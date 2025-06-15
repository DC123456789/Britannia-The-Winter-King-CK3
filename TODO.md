# To-Do list for the release of the Caledonia Update

## Step 1 : The Map

- Water
  - Draw major scottish lochs on rivers.png
  - Add those lochs to provinces.png
  - Add those loch provinces to definition.csv
  - Add those loch provinces to default.map
  - Add those loch provinces to climate.txt
  - Draw major scottish rivers on rivers.png
  - Add Lake items through in game map editor
  - Check loch/river system in game
  - Adjust river width accordingly
  - Add navigable river systems where possible (provinces.png, definition.csv, default.map, climate.txt)
    - Great Glen
    - Spey?
  - Draw additional sea-lochs where necessary (i.e. Moray)
  - Separate firths from sea zones
    - Forth
    - Clyde
    - Tay
    - Beauly
    - Dornoch
    - Lorne
    - Split Moray Firth
  - Add names to map_items_l_english.yml
- Provinces
  - Finish drawing province map
  - Add provinces to definition.csv
  - Add adjacencies in adjacencies.csv
  - Add provinces to climate.txt
  - Add provinces to 00_province_terrain.txt
- Impassable terrain
  - Draw mountains on provinces.png
  - Add those mountains to definition.csv
  - Add those mountains to default.map
  - Add those moutains to climate.txt
- Map
  - Draw better terrain all throughout Scotland
  - Adjust heightmap when necessary
- Titles
  - Establish landed title hierarchy in 00_landed_titles.txt
  - Add cultural names (from ck2 by default when possible)
  - Add correspond localization in BTWK_titles_l_english.yml & BTWK_cultural_names_l_english.yml
  - Add holdings when historical or necessary

## Step 2 : The Culture

- Revise Pictish Culture
  - Add Briton as parent culture
  - Figure out splitting date (current choice is 211, see Fraser, From Caledonia to Pictland)
  - Add custom history localization in BTWK_cultures_l_english.yml
  - Revise traditions
    - Adapt tradition_runestones (loads of work)
  - Check namelists
    - Namelists defined in name_lists/00_celtic.txt
    - Translingual equivalencies defined in name_equivalency/00_names.txt
    - Names defined in BTWK_dynasty_names_l_english.yml & BTWK_character_names_l_english.yml
  - Check ruler flavorization
    - BTWK_culture_titles_l_english.yml
- Revise Scottish Gaelic culture
  - Add Pictish as parent culture
  - Change start date (current choice is 685, battle of Dun Nechtain)
  - Revise traditions
  - Revise namelists
  - Revise ruler flavorization
- Revise Norse-Gael culture
- Add AS-Pictish culture?
- Add AS-Gaelic culture?
- No need for Romano-Pictish as that could be Romano-Brythonic

## Step 3 : The Religion

- Revise Pictish pagan religion
- Revise Pictish chrisitan flavorization

## Step 4 : The Government

- Check BTWK tribal government and whether it sufficiently corresponds to Pictish society
- Add "Farmer Republic" government
  - Lowborn rulers
  - New random old rich lowborn on succession
  - Dev debuff or smth else
  - No duchy tier
  - No war?
  - Chose between playable or not
    - If not playable, figure out a way to create a dynasty and family for ruler at game start and change gov to tribal
    - If playable, integrate lowborn gameplay from other mods
  - Add flavorization and UI elements for the governments
  - Add title flavorization? For now this is only meant for Western Scotland

## Step 5 : The History

- character history
- title history
- culture history
- province history
- war history

## Step 6 : The Story

- events, decisions, story cicles, etc.