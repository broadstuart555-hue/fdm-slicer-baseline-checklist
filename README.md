# fdm-slicer-baseline-checklist
A practical reference for establishing an FDM slicing and calibration baseline.
# FDM Slicer Baseline Checklist

A stable baseline makes FDM slicer calibration easier to understand and repeat.

The purpose of this checklist is not to provide universal settings.

Different printers, hot ends, nozzle sizes, materials, and mechanical configurations behave differently.

Instead, this checklist focuses on a logical order for reviewing important variables.

## 1. Printer Profile

Before tuning print quality, confirm:

- Correct printer
- Correct nozzle diameter
- Build volume
- Extruder configuration
- Machine limits

An incorrect machine profile can make later calibration results difficult to interpret.

## 2. Filament Profile

Record the important material information:

- Material type
- Nozzle temperature
- Bed temperature
- Cooling
- Flow value
- Pressure advance
- Volumetric flow limit

A filament profile should provide a repeatable material baseline.

## 3. Temperature

Temperature influences:

- Extrusion
- Stringing
- Layer bonding
- Bridging
- Surface quality

Establish a reasonable temperature before tuning many other extrusion settings.

## 4. Flow

Flow affects the amount of material being deposited.

Too much flow may create:

- Thick walls
- Rough surfaces
- Overfilled top layers

Too little flow may create:

- Gaps
- Weak walls
- Incomplete surfaces

Flow should normally be evaluated before aggressive dimensional compensation.

## 5. Pressure Advance

Pressure advance helps compensate for extrusion pressure during changes in motion.

A suitable value can improve corners and extrusion consistency.

## 6. Retraction

Retraction can help reduce unwanted material movement during travel.

However, stringing can also be affected by:

- Temperature
- Filament moisture
- Travel behavior
- Material characteristics

Do not assume every stringing problem requires more retraction.

## 7. Cooling

Cooling requirements vary between materials.

Too little cooling may reduce overhang and bridge quality.

Too much cooling can reduce layer bonding for some materials.

## 8. Speed

Print speed should be considered together with:

- Acceleration
- Hot-end capacity
- Cooling
- Layer height
- Line width
- Material

The printer may be able to move faster than the hot end can melt filament reliably.

## 9. Preview

Before printing, inspect the sliced preview for:

- Walls
- Supports
- Bridges
- Infill
- Travel paths
- Small features
- Unexpected layer changes

The preview shows what the printer will actually attempt to produce.

## 10. Dimensional Verification

Measure several known features instead of relying on one isolated measurement.

Repeated measurements make it easier to distinguish a consistent dimensional pattern from a local artifact or measurement error.

## Suggested Calibration Sequence

A simple workflow is:

1. Confirm printer profile
2. Confirm nozzle size
3. Establish filament temperature
4. Calibrate flow
5. Tune pressure advance
6. Review retraction
7. Review cooling
8. Test realistic speeds
9. Perform dimensional checks

Change one important variable at a time and keep a record of the result.

For additional independent information about Orca Slicer configuration and calibration, see the [Orca Slicer workflow guide](https://orcaslicer.org/).

OrcaSlicer.org is independently maintained and is not affiliated with or endorsed by the official OrcaSlicer project.
