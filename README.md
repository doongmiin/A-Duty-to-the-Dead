# a-duty-to-the-dead
Notes from Kylee's "A Duty to the Dead" pf2e campaign. For best results, open the "A Duty to the Dead" directory as a vault in Obisian.md

# Initial Creation
Initial creation of this repository followed the directions in Josh Plunkett's Youtube video, [Obsidian - Setting up a Pathfinder 2e Vault](https://youtu.be/-gJZe9BN9pU).

## Step-by-Step
NOTE: Steps 1-5 are just Josh Plunkett's preferences.
1. Settings > Options > Appearance > Base color scheme = Light
2. Settings > Options > Appearance > Themes > "Manage" = "ITS Theme"
3. Create a new directory = ~/.obsidian/snippets/
4. FROM GitHub SIRvb/Obsidian--ITS-Theme/ download "Theme - All Alternate Themes.css"
5. Save that css file to ~/./obsidian/snippets/
6. Settings > Options > Appearance > CSS snippets > "Theme - All Alternate Themes.css" = TRUE

NOTE: There are these two preferences that are actually helpful.
    1. Settings > Options > Editor > Default editing mode = "Source mode"
    2. Settings > Options > Editor > Readable line length = FALSE

7. Settings > Options > Community plugins > "Turn on community plugins"
8. Settings > Options > Community plugins > Community plugins > "Browse"
    - Install-and-Enable:
        - "Advanced Tables" by Tony Grosinger
        - "Dataview" by Michael Brenan
        - "Kanban" by mgmeyers
        - "Various Complements" by tadashi-aikawa
        -  "Style Settings" by mgmeyers

        - "Dice Roller" by Jeremy Valentine
        - "Fantasy Calendar" by Jeremy Valentine
        - "Initiative Tracker" by Jeremy Valentine
        - "Markdown Attributes" by Jeremy Valentine
        - "Obsidian Leaflet" by Jeremy Valentine
        - "Second Window" by Jeremy Valentine
        - "TTRPG Statblocks" by Jeremy Valentine

NOTE: Settings > Options > Core plugins > Page Preview > Options > "Require Cntrl/Cmd to trigger page preview on hover", "Kanban"=FALSE

NOTE: Ensure Settings > Options > Core Plugins > Templates = TRUE
TIP: Designate Settings > Options > Hotkeys > "Templates: Insert template" = [Alt + T] or [option + T]

NOTE: Settings > Options > Core plugins > Templates > Templates folder location = "zz_Templates"

9. FROM
    GitHub
        ObsidianTTRPGProject/ObsidianTTRPGShare/
    download
        ObsidianTTRPGProject/ObsidianTTRPGShare/TTRPGShare_Community_Vaults/Pathfinder_2E/
10. Copy /Pathfinder_2E/ to the Obsidian Vault.

NOTE: In a roundabout way, Josh Plunkett copies the contents of /Pathfinder_2E/ into ~/mechanics. but I copied the folder itself; In other words, his ~/mechanics folder is my ~/Pathfinder_2E folder.

11. Open Command Palette, "Reload app without saving"

12. Move ~/Pathfinder_2E/GM Screen/ to ~/GM Screen/

13. Create directories
    - ~/Party/
    - ~/World/
    - ~/zz_Attachments/
    - ~/zz_Downloads/
    - ~/zz_Templates/
    - ~/zz_Templates/Handlebar Templates/
    - ~/zz_Templates/Markdown Templates/

NOTE: I plan to move ~/zz_Attachments/ and ~/zz_Templates/ inside ~/zzzzz/

NOTE: In Obsidian, right-click on /zz_Attachments/ and make it the designated attachments directory

14. FROM
    GitHub
        ObsidianTTRPGProject/ObsidianTTRPGShare/
    download
        ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/

NOTE: We're going to begin exploring the directories and files in the ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/TTRPG_Statblocks/ 

15. Copy files from
        ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/TTRPG_Statblocks/Bestiary/
    to
        ~/Pathfinder_2E/Bestiary

16. FROM
        ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/TTRPG_Statblocks/Bestiary_Layouts/
    copy
        Template-2ETools-Monster-Handlebar.md
    to
        zz_Templates/Handlebar Templates/

17. FROM
        ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/TTRPG_Statblocks/Bestiary_Layouts/_attachments/
    copy
        Pathfinder2E-TTRPG-Statblocks.css
    to
        ~/.obsidian/snippets/

18. Settings > Options > Appearance > CSS snippets > Pathfinder2E-TTRPG-Statblock = TRUE

19. FROM
        ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/TTRPG_Statblocks/Bestiary_Layouts/_attachments/
    copy
        Path2eBlock.json
    to
        ~/zz_Downloads/

20. Settings > Community plugins > TTRPG Statblocks > Layouts > "Import From JSON" > ~/zz_Downloads/Path2eBlock.json
21. Open Command Palette, "Reload app without saving"

22. Settings > Community plugins > TTRPG Statblocks > Layouts > Default Layout > "Path2eBlock"
23. Open Command Palette, "Reload app without saving"

24. Settings > Community plugins > Dice Roller > Display Formula With Results = FALSE
25. Settings > Community plugins > Dice Roller > Always Render Dice = TRUE
26. Open Command Palette, "Reload app without saving"

27. Navigate to the README of TTRPG Statblock (we can get there through the Community plugin browser) and see the codeblock in the USAGE section. At the time of writing this, it looks like this:
    ```statblock
    monster: <SRD/Homebrew Monster Name>
    ```

28. Paste codeblock from previous step to
    ~/zz_Templates/zz_Markdown_Templates/Combat Templates/Insert Monster (TTRPG Statblocks).md/

29. Navigate to the README of Initiative Tracker (we can get there through the Community plugin browser) and find the codeblock example. At the time of writing this, it looks like this:
    ```encounter
    name: Example
    creatures:
    - 3: Goblin
    ```

30. Paste codeblock from previous step to
    ~/zz_Templates/zz_Markdown_Templates/Combat Templates/Insert Encounter (Initiative Tracker).md/

31. FROM
        ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/Initiative_Tracker/_attachments/
    copy
        data.json
    to
        ~/.obsidian/plugins/initiative-tracker/
32. Open Command Palette, "Reload app without saving"

33. Navigate to
        Settings > Community plugins > Initiative Tracker > Statuses
    The ones that don't have the `PF-` prefix are ones from the d&d 5e SRE. In other words, those can be deleted.
34. Open Command Palette, "Reload app without saving"

35. FROM
        ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/Action_Icons/
    copy
        PF2e-Actions-Font.css
    to
        ~/.obsidian/snippets
36. Open Command Palette, "Reload app without saving"

37. Settings > Options > Appearance > CSS snippets > PF2-eActions-Font = TRUE

38. FROM
        ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/Action_Icons/Templates/
    copy
        .md files
    to
        zz_Templates/Markdown Templates/PF2e Action Icons/
39. Open Command Palette, "Reload app without saving"

40. FROM
        ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/Action_Icons/Notes/
    copy
        .md files
    to
        ~/GM Screen/

41. FROM
        ObsidianTTRPGProject/ObsidianTTRPGShare/System_Agnostic/Templates/Call Out Boxes/
    copy
        .md files
    to
        zz_Templates/Markdown Templates/Call Out Boxes/

# Updated Content from ObsidianTTRPGProject
While following Josh Plunkett's Youtube video, there were a handful of GitHub folders that he downloaded and copied to various directories in the Obsidian vault.

Instead of following those steps, I simply forked the GitHub/ObsidianTTRPGProject/ObsidianTTRPGShare/ repository and copied files using a file explorer like Doulble Commander (on Windows) or Commander One (on Mac)

When ObsidianTTRPGShare has new updates:
- I sync the changes to my fork,
- From fork, create a branch with only the Pathfinder_2E directory
- I sync the fork to my computer using GitHub Desktop

- Check whether there's updates in ~/Pathfinder_2E/Bestiary/
- If yes, follow Step #15

- Step #16
- Step #17, #18
- Step #19, #20
- Step #22
- Step #31
- Step #35
- Step #38
- Step #40
- Step #41