# MPMB XUA24A "The Artificer"
This script adds the Artificer & its subclasses from the 2024 *Unearthed Arcana: The Artificer* article.

**This script is to be used in conjunction with the 5.24E scripts by ThePokésimmer. It will not work properly without those installed first. You can find those scripts here: https://github.com/thepokesimmer/2024-PHB/tree/main**

**Script Credit Note:**
This file has been compiled by MasterJedi2014, though the bones of the script are based on the code from MPMB and those who have contributed to the sheet's existing material in the "all_WotC_pub+UA" script. I am also using code within the script written by the users Shroo, ThePokésimmer, & TrackAtNite. The only things in this script that I can currently take credit for are:
- Alterations made to address changes made by the UA;
- Converting the Homunculus Servant infusion into a spell, along with the needed `CompanionList` & `CreatureList` entries.

This script will allow users to more easily playtest the revised Artificer. It also includes options to re-enable some aspects of the 2019/2020 Artificer that might be needed for an existing character to function.

**Script Patch Notes:**
- **2024-12-25:**
  - Initial upload of script (V11).
- **2024-12-26:**
  - V11 superseded by V12. I missed some code from TrackAtNite, which is why there wasn't a "Replicate Magic Item" set of options in the "Choose Feature" menu. That missing code has been successfully integrated into my script, which now properly shows a set of "Replicate Magic Item" options.
- **2024-12-28:**
  - V12 superseded by V13. Updated the `regExpSearch` strings of the base class & the subclasses to match the strings of the base class & the subclasses in the `all_WotC_pub+UA.js` file. This seems to have fixed some bugs that were causing old pre-*ERLW* Armorer features to appear in the place of the XUA24A Armorer's features.
- **2025-01-01:**
  - V13 superseded by V16. The script now allows the user to select all allowed Common, Uncommon, & Rare magic items at the appropriate levels. Much thanks to user TrackAtNite, as without their code, this wouldn't be functioning as it now is.
- **2025-01-04:**
  - V16 superseded by V17. The script now adds the Elementalism, True Strike, Arcane Vigor, Dragon's Breath, & Circle of Power spells to the UA Artificer's spell list.
- **2025-01-21:**
  - V17 has been updated with the following changes: The code that alters the Elementalism, True Strike, Arcane Vigor, Dragon's Breath, & Circle of Power spells has been changed so as to prevent possible sheet errors; The script has been updated with code to fix an issue preventing 1st level Artificers from being able to generate a spell sheet.

**Known Bugs:**
- V17: The "Replicate Magic Item" feature only adds the blanket statement magic item plan listings (ex: non-potion, scroll, or cursed Common magic items at lvl 2); It isn't adding the items that the rest of the tables at each level say are available. This is causing some items to appear in "Replicate Magic Item" menus of a later level than they should.

**Script Content Source:**
- https://media.dndbeyond.com/compendium-images/ua/the-artificer/AzQEA72K8EMf9HmU/UA2024-Artificer.pdf

For instructions on how to add this script to the sheet, please see this page: https://www.flapkan.com/how-to/add-more-content
