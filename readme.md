## TDS A35X FDE Patch

in this FDE Patch, I give you `"tdsa350-900"`, `"tdsa350-1000"`airfiles and `"aircraft_35K/359_patch.txt"` source patch config

# Download
`git -clone` or download source zip
# Installation :
1. backup your original aircraft.cfg (by copypasta it and name it something else like aircraft_orig.cfg)
2. in `"aircraft.cfg"`, the one which you didnt rename, you're gonna patch it with given `"aircraft_patch.txt"`
	2.1 replace all texts inside `aircraft.cfg` with texts in `aircraft_patch.txt.` now you've patched the config, great.
	2.2 then, you take `[fltsim]` section, aka liveries, from your backup, back to your `"patched"` config 
3. now replace your `airfile` with given one, back up on your discretion


# Change(s) Applicable to all variant
	- WBM enhancement : Changed fuel tanks position and payload positions to appropriate position.
	- Fuel consumption : as the name suggest, that's it.
	- Engine enhancement : reworked engine model to simulate Trent XWB's behaviour (that n1 would never exceeds 90% in normal ops)
	- Flight model enhancement : with a know-how from MSFS Headwind A330, this FDE now simulates proper flight controls feel, proper cruise drag, proper flaps pitch angle, proper flaps drag and proper flaps lift during its operations, landing? takeoff? I got you.
	- Miscelleneous config tweak : with the neat software named "Visualizer" (created by FSLabs, distributed on fsdevelopers.com) 
		It aids in "visualising" things like contact and scrape points, eyepoint, geometry, engines placement, and most importantly, "MAC placement" (or `wing_pos_apec_lon` in config), to its proper position. 

Specific change(s) Applicable to -941 variant
	- given fuel config is model -941/ULR 
	- given weight config is weight model "WV020"

Specific change(s) Applicable to -1041 variant
	- given weight config is weight model "WV006"

release version : 0.1.5.1 "engine rework part 2"
