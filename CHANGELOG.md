# Changelog

## 2026-10-29

- Worked example page (examples/group1.html): the Group 1 example report next to the live twin. Pointing at a value flashes its settings field and its Readouts line in the twin. The page lists every design setting with the reason for its value, shows the frame trials, and runs a pick-and-place demonstration with fruits at random places.
- The twin can now take values and commands from a page that embeds it. Long readout values now wrap.
- Tractor start now has a round crop (Ball, 8 in, 8 lb) and a 25 lb gripper, not a bale. "Add object" therefore places a round fruit.
- Run the arm: Camera auto no longer places a hidden object; place one by coordinates or push Random object. The placement box is open and easier to see. An empty harness does not push objects (its straps are slack).
- Group 9 options: End effector = Harness on hook (a hook, straps and a cradle; an operator attaches and releases it, 10 s each; no jaw opening or slip check), and Bin type = Pallet trailer (a flat deck at the rim height, at least the object diameter + 6 in wide; the object is lowered onto it).
- Collision checks: the cylinder length sliders now stop before the gripper hits an object, the bin wall, the floor or the bar. The object in the gripper can no longer pass through another object. The pick-and-place demonstration stops with a message if a step would collide.
- Default view: the camera arm and the cylinders now face you, and the frame legs stand behind the bar. You no longer need to turn the view around.
- Automatic run: the arm aims slightly below the grasp height (so the fingers close below the widest point), closes the empty gripper after the release (so the open fingers clear the bin rim), and starts each pick from a higher home position.
- Automatic run: after the release, the arm now goes back over the bin rim before it goes down to home. Before, it could stop at the bin wall.
- Readouts: clearer names. "Cylinder 1 force at this tip position" (empty gripper and with the object), "Load on the tip now" (what is on the tip) and "Heaviest object at this tip position" (cylinders at the relief pressure, no safety factor). The color key explains why the shaded band stops above the ground.
- New View button: Front view (as Figure 1), a flat view from behind the tractor. The frame legs now stand outside the pick width.
- The workspace map now shows the full reachable region after you change the geometry. Before, it could show only a part of it, so the tip seemed to be outside the shaded zone.
- The readouts no longer stop when the drop point is out of reach. Rim clearance now says that the drop point is not reachable.
- The extend and retract speeds are hidden until Show answers is selected.
- Weight, Height and Gripper length accept larger values (up to 1,000 lb, 36 in and 48 in).

## 2026-10-25

- Numbered panel with Required and Optional steps.
- Counterbalance valves folder: setting as a ratio or in psi, pilot ratio, leakage.
- Bin and pick width folder: a drawn bin, the drop point, and a rim clearance check of the front of the fruit.
- Show worst point searches the full work path: pick, lift, carry and drop.
- Readouts for the pressure in each cylinder, the forces and pressures at the worst point, and a counterbalance guide.
- Help pages in Simplified Technical English, with equations that contain no unit constants.
