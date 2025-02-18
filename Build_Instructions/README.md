# Build notes

  

This folder includes the original version of the Voron 0.2 assembly manual. Start by using those instructions, and consulting this README file to account for all of the differences from the stock build.

  

As the project evolves, a separate, dedicated version of the manual will be created. These assembly instructions will also be updated to account for changes introduced in the future, and to streamline the printer build process. Please also report any mistakes, things you found confusing, or general suggestions, by submitting them as Issues here on Github.

  

Note that we have also copied over some comments from the build notes of some associated repositories, like for some of the parts that come from the [LDO kit](https://docs.ldomotors.com/en/voron/voron02/build-faqv02r1), the [DragonBurner extruder](https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner) assembly guide, etc.

  

# Comments relating to specific pages of the original assembly manual

  
### Core part of the assembly
* **Page 6** We have set up a dedicated channel on Discord, specifically for the Flex Printer. You can ask for help there. [Direct link to the channel](https://discord.gg/4RNmUT7A5G).
* **Page 7** Please make sure you log issues on the repo you are currently viewing, not the VoronDesign one. Otherwise, the repo mainteners won't be able to see them.
* **Page 12** Ignore if using our recommended BOM. It comes with pre-drilled extrusions.
* **Pages 13-15** Extrusions F & G are not included since the Kirigami bed will be used. The default-BOM extrusion ends should come pre-tapped.  As a result, Extrusions A & B are the same and Extrusions C & H are also the same.
* **Page 18** SKIP The kits include nut bars.
* **Page 19** Important: the linear rails need to be cleaned and lubed - you can refer to the [LDO Linear Rail Greasing Guide.](https://docs.ldomotors.com/en/guides/rail_grease_guide). **White lithium grease is the preferred choice of lubricant.** Be extra careful unwrapping with the rail that does not have the rubber stoppers, this is the HiWin rail for the x-axis.
* **Page 23** The no-drop nuts are incredibly useful. We have included a 50pc .3mf plate of these for the LDO extrusions. The Optional folder includes another version for extrusions that come with the FYSETC kit. The LDO ones are great, but in a few isolated locations they don't fit perfectly in a handfu(e.g. where the Z endstop is). You can just use regular nuts whenever this is the case.
* **Pages 36-46** 36-46 SKIP Use the [LDO Kirigami Bed Guide](https://www.ldomotion.com/p/guide/Kirigami-Bed-for-Voron-V02) for instructions.
	* Note we are not using the drag chain since there's no wires without the heated bed. Simplifies the wiring a fair bit as well. You're welcome.
	* So you also ignore all the other printed parts outside of the actual block for the Z nut.
* **Pages 47-48** The bed tramming is a notoriously unnerving experience, especially if the Kirigami bed comes delivered slightly out of shape. Try to get it as good as you can, but keep in mind it will never be perfect.
	* BTW if the Kirigami does come deformed, you can manually bend it to the required shape - the aluminium is quite pliable. Adjusting it ever so slightly can make tramming a whole lot easier.
	* Greg's Maker Corner on YouTube has a [good demo](https://youtu.be/r43oCBvVlFY?si=NVb_CkOZ1o9doB4y) of the tramming procedure.
* **Page 49** The manual still includes the old version of this parts (bolted from only one side), that's why it looks different. The updated one we have included will fit better.
* **Page 52** Comment on pre-loaded nuts in general: you won't need most of them because most of them are for clips for the enclosure, which we are not using.
	* We recommend still installing them according to the original guide, though, as they will make it easier to install any mods in the future.
	* An updated version of the guide coming soon will more clearly outline exactly which preloads you can definitely skip.
* **Page 58** Ignore both. We are not using the drag chain, and the deck panel will get installed elsewhere since we are going upside-down.
* **Page 62** See comment for Page 52 for notes about nut pre-loads.
* **Page 81** TIP: Insert your hex key into the holes thru the nut to pre-align the nuts into place.
* **Page 92** The Kirigami bed uses a different nut holder, this is the one we include with our printed files (see [LDO Kirigami Bed Guide](https://www.ldomotion.com/p/guide/Kirigami-Bed-for-Voron-V02) if in doubt). The spring and top part of the backlash nut does not attach until later.
* **Page 93** SKIP Not needed for Kirigami
* **Pages 94-95** You can safely ignore these since the open frame design allows to slide these in from the top at any point in the future.
* **Page 99** SKIP We won't be using the default spool holder; the position is not the best for the same reason as in the next comment.
* **Page 101** We won't be using the bowden fube or the filament runout sensor as it introduces extra friction on the TPU material and makes it harder to extrude.
* **Page 102** SKIP We will be att
* **Page 103** We are skipping the coloured accents so ignore these types of things throughout the whole manual.
* **Page 107** (If using the LDO kit or LDO leadscrew): Do NOT apply any lubricant on the leadscrew, it's Teflon coated.
* Page 110 Attach the top and spring on the backlash nut on this step, refer to the video on Page 108. This can be a little tricky to get the part to properly mesh and spring into place, so take your time.
* Page 112 This step is very critical, misalignment could cause permanent damage to the backlash nut or pre-mature excessive wear.
* **Page 122** Ignore, we are not using the cam locks.
* **Page 129** Leave a bit extra on top of this, so maybe like 1.1 m or so length in total. It will help with manually adjusting the belts to get the right tension.
* **Page 135** The Gates Carbon Drive app on iOS/Android is great for this. Make sure you are in a quiet environment and take the phone out of any case, hold microphone near belt.
	* If the belt is too loose you will find it hard to get any reading at all, that's what's going on. Tighten it a bit more until you start getting good readings, then you can reduce it if it's too high.
	* Usually go a bit higher than 110 Hz (even around 120Hz should be OK), since the belt will loosen a bit after it wears in, and over time later.
	* Refer to guide like [this one](https://docs.vorondesign.com/tuning/secondary_printer_tuning.html#belt-tension) if in doubt.
* **Page 136** Confusingly not stated in the original manual: if you alteady tightened the screws from Page 73, turning these knobs won't do anything. Generally you want to loosen these screws if we need to make major changes to the tension, and leave some room for finer adjustment later using the knobs.
* **Pages 139** SKIP We are using lock nuts instead to mitigate loosening over time.
* **Page 141-142** SKIP We are not using the heated bed.
* **Page 143** Use M3x30 instead (longer ones also work, but it will be annoying tightening the lock nut through the whole length).
	* You may also use extra lock nuts here (flat side up) instead of the nut and washer (i.e. in addition to the ones we use instead of the knobs).
* **Page 144** The bed from the BOM will already have this preapplied. Some might not have holes in the magnet sheet, though, so it's a bit harder to access later.
* **Page 146-148** SKIP You may now already be starting to see how removing the heated bed simplifies the assembly due to not having to deal with all the wiring.
* **Pages 150-177** SKIP We are using the DragonBurner extruder instead.
	* Use the [DragonBurner assembly manual](https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner) to build that extruder instead.
	* FYI we are using the V6 mount + Orbiter 2 + custom Umbilical PCB mount combo.
	* Skip all the bits for the LEDs, unless you really need them. If in doubt, keep in mind you can also always take off the extruder later and replace it with a modified version.
	* **Page 178** comment: note that we are using M3x50mm, due to the need to attach the ADXL front mount.
* **Page 181** We recommend to zip tie the Umbillical cord to the long strain relief part of the PCB mount. Due to the position of the printer, the cord will be contacting the bottom deck panel, and can cause the wires to pull out slightly; this can cause significant temperature sensor noise and even abrupt print failures.
* **Page 182** You can ziptie 'em around the strain relief spacers. By the way, make sure the bit beside the fans doesn't stick out too much; it will push down on the belt anyway, but if it's too tight it can actually restrict toolhead movement and cause issues like layer shifting.
	* BTW, note that we are using the [Umbillical PCB](https://github.com/VoronDesign/Voron-Hardware/tree/master/V0-Umbilical) by default. It simplifies the wiring quite a bit as you will see. As mention in the BOM, in the future we will likely replace this for the new [Orbitool SO2](https://www.orbiterprojects.com/orbitools/). As that will just use one USB cable instead of the Umbillical cord, reducing the strain relief issue.
* **Page 197** Before we attach the wiring, we will use the extrusions meant for the tophat to build the bottom third of the printer frame. **Jump to page 229.**
* **Page 230** We will need preloads for the deck panels; check the CAD assembly to make sure you have enough nuts for all of the clips.
	* Note you won't need most of the other preloads in this chapter, but you can put them in anyway (for the same reason as in the comment for Page 52).
	* Consult the CAD assembly to get an idea of how the whole thing is going to look like, so you know into which rails you might want to load a few nuts later (on those J extrusions, since they won't be accessible).
	* The tophat bit of the frame can be freely detached later, though, so it's also not that big of a deal.
* **Page 232** SKIP We are not using the cam lock.
* **Page 232-240** SKIP We are not using the panels.


### Bottom third of the frame (reusing tophat extrusions)
You can now use the elbow brackets to attach the tophat frame to the bottom bit of the printer (i.e. on top of the XY motion system). See the CAD assembly if in doubt.
* Then, mount the deck panel(s), using the clips (again, see CAD assembly for now, we will update the guide in the future to illustrate this).
* **Now** we can finally attach the feet, like on Page 102. Again, ignore the coloured accents from Page 103.
* After attaching the power supply to the bottom of the deck panel you are ready to go through Pages 208 through 212 to attach the bottom skirts (ignoring coloured accent from 211).
	* TIP: You can partially thread the screws into the nuts first since the skirt can slide afterwards.

### Sorting out the electronics
After assembling the bottom bit of the frame, go back to sort out the electronics.
* It can be worth referring to the [LDO Wiring Guide](****). Even though our setup differs due to not using their Picobilical, the illustrated guide is very useful. We will make a custom wiring guide in the next version of the guide.
* **Page 201** Toolhead wires will go to the Umbillical PCB on the Toolhead. Then you route from the PCB attached on the frame to the actual controller board.
* **Page 204** Ignore, we are using the SKR Pico.
* **Page 212-216** SKIP We are indeed using the headless (i.e. non-display) variant. IMHO the display is not worth it and the cheap ones tend to be buggy. You just control the printer via web browser on your local network, and you can also use an app like OctoApp on your phone to control the printer.
* **Page 218** SKIP We are not routing the filament through there.
* **Page 219** We are installing the Umbillical frame PCB here using the panel provided with the STL files.
* **Pages 220 to 226** SKIP, we are purposefully omitting the panels.
	* You can probably now see why.

### Initial setup
Almost there! You can now go through the [original startup guide](https://docs.vorondesign.com/build/startup/) for all the pre-flight checks, bed levelling, and software setup.
* Note we are of course using only the sections for the Voron0.
* For the printer.cfg and macros.cfg files, use our presets from the "Software" folder of this repository.
* Due to using the lock nuts for the bed levelling adjustment, once you set it up initially, you won't need to re-adjust it for a long, long time.
* Once done, consider sharing a picture of your finalised Flex Printer assembly on the [Discord channel](https://discord.gg/4RNmUT7A5G)!

### First print
You can run a first test print, using the slicer template included in the "Software" folder. The template is for [ORCA Slicer](https://github.com/SoftFever/OrcaSlicer) since that is currently shaping up to be the best open-source slicer if you're not using Prusa's printers. PrusaSlicer and SuperSlicer are also great, of course, but you should be fine with ORCA.
* BTW, download ORCA slicer from the official Github rather than the weird .net/.org domain names that appear online. IIRC some of these are fake or malicious.

# Post-setup tuning

### REQUIRED: Input shaping calibration
After completing the build you should also tune input shaping using [the official guide](https://www.klipper3d.org/Measuring_Resonances.html). Note we are using the ADXL345 for this, unless you have a different toolhead board which comes with an in-built one (like the LDO Picobilical, for instance).

### REQUIRED: Determining max accelerations and speeds
You should then also determine the maximum acceleration and speed using [Ellis' guide](https://ellis3dp.com/Print-Tuning-Guide/articles/determining_max_speeds_accels.html). Note we have already included his TEST_SPEED macro in our default template bundle.
* As he states, you'll probably want to run everyday prints at around 80-85% of the max acceleration and limit, to avoid issues.
* You will likely mainly notice issues with excessive max speed, at some point the toolhead will start crashing into the frame so be careful.

### OPTIONAL: General printer tuning
You should be good to go using the default print slicer template + the pressure advance values which we have included in the config.
* If you require further tuning of these parameters, or other aspects of the printer, [Ellis' guide](https://ellis3dp.com/Print-Tuning-Guide/articles/index_tuning.html) is a well-known resource with tutorials that help to better understand the basics, as well as some more advanced concepts.
* Your extruder flow rate might need calibration, but in our experience the default value of around 111% to 114% with this extruder/hotend combo.