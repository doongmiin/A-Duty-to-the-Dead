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
        ~.obsidian/snippets/

NOTE: When following this tutorial video on JAN-31-2023, ^this CSS file is no longer in the repository.

18. FROM
        ObsidianTTRPGProject/ObsidianTTRPGShare/Pathfinder/Second_Edition/TTRPG_Statblocks/Bestiary_Layouts/_attachments/
    copy
        Path2eBlock.json
    to
        ~/zz_Downloads/

19. Settings > Community plugins > TTRPG Statblocks > Layouts > "Import From JSON" > ~/zz_Downloads/Path2eBlock.json
20. Open Command Palette, "Reload app without saving"

21. Settings > Community plugins > TTRPG Statblocks > Layouts > Default Layout > "Path2eBlock"
22. Open Command Palette, "Reload app without saving"

23. Settings > Community plugins > Dice Roller > Display Formula With Results = FALSE
24. Settings > Community plugins > Dice Roller > Always Render Dice = TRUE
25. Open Command Palette, "Reload app without saving"

26. Navigate to the README of TTRPG Statblock (we can get there through the Community plugin browser) and see the codeblock in the USAGE section. At the time of writing this, it looks like this:
    ```statblock
    monster: <SRD/Homebrew Monster Name>
    ```

27. Paste codeblock from previous step to
    ~/zz_Templates/zz_Markdown_Templates/Combat Templates/Insert Monster (TTRPG Statblocks).md/
