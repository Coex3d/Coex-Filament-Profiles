# PETG

[Coex 3D PETG](https://coex3d.com/collections/petg-filament) is a perfect material for prototypes, aesthetic parts, and sturdy, slightly-flexible functional parts. Our PETG is made from only 100% virgin resin and colorant, with no fillers! All 1.75mm diameter Coex 3D are specified to ±0.03mm. 

# PETG Printing Recommendations

| Setting |Recommendation|
| --- | --- |
| Extruder Temperature | 225-245C |
| Bed Temperature | 60-80C (Heated Bed Required) |
| Build Surface | Any (Glass, PEI, BuildTak, garolite, etc.) |
| Bed Adhesion | [Magigoo](https://coex3d.com/products/magigoo-original-50ml), painters tape, glue stick |
| Part Cooling | 50-75% cooling fan. Some cooling is recommended. |
| Drying | 65C for 3+ hours |

# PETG Printing Tips
- **Important!** PETG is capable of fusing to glass and PEI print surfaces, causing damage when prints are removed. Using an additional adhesion agent such as Magigoo or glue stick will help prevent parts from fusing to the bed.
- ETG is slightly more hygroscopic than PLA, so drying your filament can be necessary if it is exposed to humidity. Coex 3D recommends drying our PETG at 65C for at least 3 hours. You can tell when your filament needs drying if you experience under-extrusion/inconsistent extrusion, and/or excess stringing. Hearing a "popping" sound during a print is another sign of filament that needs to be dried.
- PETG can often result in more stringing than would be expected with PLA or similar filaments. There are a few steps you can take to reduce stringing:
    - **Reduce print temperature.** Keep in mind that reducing print temperature will slightly decrease layer adhesion and part strength, but can help reduce stringing.
    - **Increase retraction.** Increasing retraction length can help reduce stringing, especially on Bowden-style extrusion configurations.
    - **Enable "Wipe while Retracting" in your slicer.** Most slicers allow for this option, which will start a travel move just before/during the filament retraction. This helps "wipe off" the nozzle as a travel move starts, reducing stringing.
    - **Enable "Combing Mode" (Cura) or "Avoid Crossing Perimeters" (PrusaSlicer/SuperSlicer/etc.).** Rather than travel moves always going in a straight line, this will cause them to choose a path that avoids crossing over perimeters, effectively keeping the nozzle "inside" the print area wherever possible. This eliminates stringing right at the source but still cannot eliminate it all (such as between multiple parts).
    - Unfortunately in many cases stringing is impossible to fully eliminate, so some post-processing of prints is often necessary.
