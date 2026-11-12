# PCB fabrication checklist

The updated project archive includes Gerber files for copper, solder mask, silkscreen and board outline, plus plated-through-hole (`PTH.drl`) and non-plated-through-hole (`NPTH.drl`) drill files in `TeensyTeleopsGerber/`.

Before manufacturing:

1. Confirm schematic, PCB layout and fabrication exports are the same revision.
2. Run KiCad ERC and DRC, review footprints and custom symbols.
3. Verify power/ground paths, motor current capacity, thermal constraints and protection.
4. Check board outline, stack-up, tracks, clearances, connector orientations and drills.
5. Regenerate and visually inspect fabrication outputs if the design changes.
6. Prepare BOM and assembly outputs if needed.

**The presence of Gerbers does not establish fabrication readiness.** The board has not been manufactured or tested.
