# Flex Printer

The Flex Printer is an open-source project aimed to solve printing challenges with ultra-flexible elastomers.
It is based on the [Voron 0.2](https://github.com/VoronDesign/Voron-0) frame and motion system, but has been heavily stripped down to remove unnecessary parts, and significantly simplify the assembly procedure.

The project is aimed at providing a democratised platform for carrying out research in soft robotics involving the printing of soft elastomers (e.g. for fluidic soft robots).
The printer can be built for less than $500, with the total assembly time estimated at 1-3 days for first-time users (and under 1 day for those with prior experience).

<p align="center">
<img src=https://imgur.com/1nZLRVS.png, width="30%">
</img>

## Table of Contents
* [Overarching philosophy](#Overarching-philosphy)
* [Key features](#Key-features)
* [Printing impossible geometries](#Demos)
* [Getting started](#Getting-started)
* [Join the official Discord channel](#Discord)
* [How to contribute](#How-to-contribute)


## Overarching philosophy
The original Voron printers are very fun to build, but can be an arduous process for first-time builders; it is a platform designed primarily with hobbyists in mind. The Flex Printer has been optimised to simplify the assembly and usage of the printer as much as possible. The guidance provided in this repo also suggests several pieces of advice based on prior experience. The project follows a Keep It Simple, Stupid (KISS) philosophy.

## Key features

- Upside-down print orientation
    - Enables better bridging and minimises the risk of fluidic channel blockage
    - Reduces the need for support of tall thin membranes 
- The printer can print parts in virtually any orientation
    - Enables new types of soft robots or metamaterials 
- 2.85 mm Filament
    - Wider filament allows the extruder to push on extremely flexible material more effectively
- Copper-plated nozzle and titanium alloy heatbreak
    - TPU does not stick to Copper-plated nozzles
    - Titanium alloy heatbreak prevents premature heating of the filament
- Removed Heat bed
    - TPU adheres well to PEI, removing the heat bed reduces build complexity
- Open design
    - The lack of enclosure allows for better cooling and reduces part count 
- Compact and portable
    - The printer fits on any desktop
- 120x120x120 mm build volume
- CoreXY
    - Printing at high accelerations and travel speeds minimises the need for retraction
- Klipper firmware
    - Resonance compensation 
- Filament runout sensor
- Low cost <$500

## Printing impossible geometries
[![Demonstration of printer capabilities]()](https://vimeo.com/1057922438/d0713f3f35)

## Getting started
- Follow the part sourcing guide in the [BOM_Sourcing_Guide](https://github.com/maksgepner/flex-printer/tree/main/BOM_Sourcing_Guide) folder to procure the parts needed to build the printer.
- If your BOM doesn't include all of the required parts, print the remaining ones using the resources available in the [Print_These_Parts](https://github.com/maksgepner/flex-printer/tree/main/Print_These_Parts) folder.
- Follow the build instructions in the [Build_Instructions](https://github.com/maksgepner/flex-printer/tree/main/Build_Instructions) folder to build the printer and get it ready for printing your first parts.
- Visit the [Fluidic Machine Bestiary](https://github.com/The-Soft-Robotics-Forum/fluidic-machine-bestiary) for a repository of ready-to-print monolithic robots. The Bestiary also contains an ever-growing library of fluidic control, actuator, and sensor components that use can use to build your own, entirely new, soft robots.

## Join the official Discord channel
We have set up a dedicated [Discord channel](https://discord.gg/4RNmUT7A5G) on the Soft Robotics Forum server on Discord. It's a great way to ask for help and advice when assembling and using the printer, as well as to connect with other, and start contributing your own ideas to the project.

## How to contribute
This is a beginner guide for forking github repositories and contributing to project. If you have prior experience, skip to [Step 6](#Step-6:-Pull-Request)
If you plan to contribute please see the license and not the requirements of such. 
### Step 1: Fork the Repo 
1. Click the "Fork" button in the top-right corner of the page - [1](https://www.freecodecamp.org/news/how-to-fork-a-github-repository/)
2. Chose where to fork the repository 
### Step 2: Clone your forked repo
1. Go to your forked repo and copy the URL that appears when the green code button is clicked. 
2.  open a terminal on your computer and run `git clone [URL]` [2](https://www.gitkraken.com/learn/git/problems/github-how-to-fork)
### Step 3: Create a branch 
1. navigate to your recently cloned repo on your pc via terminal
2. `git checkout -b [NEW_BRANCH_NAME]` where new_branch_name is the name you wish to give your branch
### Step 4: Make changes 
1. make your desired changes to the part files keep note of the voron naming scheme and be consistent 
2.  run `git add .` 
3. run `git commit -m "a detailed message of the changes you have made"`
### Step 5: Push Changes and Create a pull request
1. `git push origin [NEW_BRANCH_NAME]`
2. go to your fork on the github website and select compare and pull request
3. fill in the pull request details 
### Step 6: Pull Request
- Provide a clear and concise title for the pull request
- include a detailed description of the part changes you have made and why
	- if you have introduced new parts make sure the naming is consistent with the in place naming scheme
	- if you have introduced new hardware please provide a BOM for this
