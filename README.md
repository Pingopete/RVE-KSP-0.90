RVE for 0.25 / RSS 8.2.1+
============

NEW TESTING VERSION - IMPORTANT READ
This is extremely experimental and highly unfinished!
This is simply so you guys can try out the new atmosphere shader and cloud detail.

Below are is the list of obvious/known bugs in this testing version:

Clouds-

	Cloud detail not tiled yet (edges obvious and abrupt)
	Volumetric textures do not conform to either detail 'cloudlets', not to overall cloud mask (i.e. they appear everywhere)
	Cloud are for some reason extremely bright at mid day, may burn your eyes a bit
	Passing through layers can produce flashing and obvious lines and more
	Detail wrapping isn't finished yet and produces strange mirrored effects at seems
	-low level cloud (1k mask, 8k detail)
	-cirrus layer (1k mask, 1k detail)

Atmosphere-

	Awaiting individual controls for 'sky haze' and 'ground haze' - sky haze is too obvious proportionatly to ground haze
	Sky is a little too dark at lower altitudes
	Atmosphere is strongest at centre of view on horizon and not so at edges
	Soft upwards-fall off only appears in PQS and not in Space
	-white layer 25km
	-blue layer 45km

Cities-

	Cities texture still WIP, higher res in some areas, not tiles yet
	Heavily un-antialiased for some reason 'looks very bitty at distances'



The, unfinished, state of my RVE project for KSP 0.25 using the very latest overhaul version from rbray (includes SS normals, dedicated atmosphere shader, "working" shadows, and other features).


Requirements:

	-Sarbians DDS loader
 	-RSS 8.2.1
 	-Latest EVE Overhaul (master zip) - Do not need textures included in DL!

Priority bugs/to do list:

	-Reduce memory footprint
	-Extend PQS terrain shader distance, too short on RSS
	-Fix "PuffBalls" glitch (VolumeHexRadius/VolumeSegmentDiv?
	-KSC Flickering issue when Cam01Range < 1, need comprimise

Includes WIP:

	-New cloud details with Transparency
	-Atmosphere shader in RSS, needs separated ground haze effect from other layers
	-Other planets unfinished/unchecked as with RVE 0.2.2 Dev.


Licence: CC-BY-NC-SA
