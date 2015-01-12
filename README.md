RVE for 0.25+ / RSS 8.5
============

NEW TESTING VERSION - IMPORTANT READ
This is extremely experimental and highly unfinished!
This is simply so you guys can try out the new atmosphere shader and cloud detail.

>>SunFlare shared assets now updated to KSP 0.90

INTALL INFO!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

	Install RealSolarSystem 8.5 (including necessary textures!).
	Get the latest EVE-Overhaul .dll's from rbrays GitHub-OVERHAUL BRANCH (most recently updated).
	^^ Remove any prexisting textures and configs from bouldedCo folder (All required stuff is provided in RVE folder).
	Install DDS Loader.
	Install RVE < Placing RVE folder & EnvironmentalVisualEnhancements folder into gamedata folder.
	[Optional] For new lens flare put the included sharedassets10.assets into ksp_data & overwrite.

Below are is the list of obvious/known bugs in this testing version:

Clouds-

	Passing through layers can produce flashing effects
	Currently employing original cloud-cloud detail system; 8k mask, 2k detail

Atmosphere-

	Atmosphere shader serious visual bugs between 10-125km
	Sky is a little too dark at lower altitudes

Cities-

	Cities texture still WIP, higher res in some areas, not tiled yet
	City lights do not conform to city day texture and will appear very repetative at current scale value
	Heavily un-antialiased for some reason 'looks very bitty at distances'



The, unfinished, state of my RVE project for KSP 0.90 using the very latest overhaul version from rbray (includes SS normals, dedicated atmosphere shader, working shadows, and other features).


Requirements:

	-Sarbians DDS loader
 	-RSS 8.5+
 	-Latest EVE Overhaul (master zip) - Remove textures and config included in DL!

Priority bugs/to do list:

	-Reduce memory footprint
	-Fix "PuffBalls" glitch, (fixed with single 'apply' of EVE GUI).
	-Kitopia rings not loading on start



Licence: CC-BY-NC-SA
