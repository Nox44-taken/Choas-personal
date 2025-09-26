Just like the other choas scripts, this is also a working bubblegum project with a twist of my own. 
Massive thanks to the makers of hhe following scripts
-True Auto Stats
https://github.com/Yi1i1i/True-Auto-Stats-for-AIDungeon-RPG-Scenarios

-autocards and localized languages
https://github.com/LewdLeah/

-simlpfied actions based input but reputeX removed
https://github.com/MillennialJesus/ReputeX-Engine

-Simplified time input & Text formatter from dynamic worlds, with Story Arc Engine incorprorated as combined execution
nolonger publicly available?? atleast it was at some point

-narrative guidance overhaul, Random events,
https://help.aidungeon.com/what-are-scripts-and-how-do-you-install-them

-added paragraph fix
https://github.com/Eliterose19/Paragraph-Fix/

-added system requests script
search under script library thread in ai dungeon discord 

the basic functioning of all those scripts hasn't changed only made tweaks to help them work together



Personal changes added


-adjusted AC to always display its messages since usually it only displays when the last popup messasge is unchanged, but TAS outputs messages per turn


- added a story status card to allow user to see and affect the following parameters

                    story status
        [World Clock: [🕒 Year 100, 02-15 06:11] (Action took 1 minute)- for display only to show action based input script effect


          Current turn: 430 - also for display only to know how close you are to triggering SAE


            Year: 100 - can be adjusted and will affect global time

            Month-Day: 02-15 - can be adjusted and will affect global time

              Hour-Minute: 06:11 - can be adjusted and will affect global time

          Turns Per Removal: 50 - can be adjusted and will affect SAE element removal from current story arc

          Current Heat: -150 - can be adjusted and will affect guidance overhaul script


        Current Temperature: 1 - can be adjusted and will affect guidance over haul script

      AI: 0 - ignore this, rather dont touch it. it has fail safes after element removal but still testing if it affects the script


      Authors Note: created by guidance overhual script can be adjusted only in input script



        TD: 5 can be adjusted and will affect how many minutes pass when you select do

        TS: 1 can be adjusted and will affect how many minutes pass when you select say

        TST: 5 can be adjusted and will affect how many minutes pass when you select story

        TC: 5 can be adjusted and will affect how many minutes pass when you select continue

        turn: 430 ignore this for display only
      ]

  - added am card called New Auth Note that allows works like the generic authors note since the multiple scripts affect the generic plot component. After changing it, just make any input (do/say/story) to trigger its addition to AN

- added a prompt debug card well its original purpose was fixed so it just shows current time. change its triggers if you want so that it can appear in your story
- made TAS compatible with 3rd person perspective, check under (youwords) feel free to add your character name i have mine as Nox
- also added healing of ep and mana to basic healing mechanisms
- tweaked SAE by adding element removal to cater for long arcs. before it moved between plot elements based on text similarity score i simply added ((removal and reset to focus on first point ))


