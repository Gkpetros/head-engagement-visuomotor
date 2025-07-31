# head-engagement-visuomotor
Supplementary Material and Source data for the project: "Head engagement during visuomotor tracking is determined by postural challenges and aging"

# Head Engagement During Visuomotor Tracking

This repository contains the raw data for the project:


---

## Experiment 1 Data Description

- Each participant folder (`XX`) includes:
  - Three folders for **postural conditions**:
    - `1/` → Seated
    - `2/` → Firm
    - `3/` → Foam
  - Inside each postural folder:
    - Three folders for **eccentricity levels**:
      - `30/` → Small (±15°)
      - `60/` → Mid (±30°)
      - `90/` → Large (±45°)
    - Each of these contains **trial-wise raw data** files in `.csv` format.

### CSV File Contents

Each `.csv` file contains the following columns:

| Variable            | Description                                                        |
|---------------------|--------------------------------------------------------------------|
| `target`            | Target location in pixels on the computer screen (mirrored to beamer) |
| `CoP_x`             | Center of pressure (CoP) x-axis [cm]                               |
| `CoP_y`             | CoP y-axis [cm]                                                    |
| `CoP_z`             | CoP z-axis [cm]                                                    |
| `RightA_x/y/z`      | Right head marker coordinates [cm]                                 |
| `LeftA_x/y/z`       | Left head marker coordinates [cm]                                  |
| `RightS_x/y/z`      | Right shoulder (acromion) marker coordinates [cm]                  |
| `LeftS_x/y/z`       | Left shoulder marker coordinates [cm]                              |
| `RightGaze-Ray_X`   | Gaze vector from right eye to gaze point in space (x component)    |
| `RightGaze-Ray_Y`   | Gaze vector y component                                             |
| `RightGaze-Ray_Z`   | Gaze vector z component                                             |
| `GazePosition_x/y/z`| Gaze position in space [cm]                                        |

---

## Experiment 2

- Data is organized into two group folders:
  - `YoungAdults/`
  - `OlderAdults/`
- Each participant folder within these groups follows the same general structure as in Experiment 1 (only 1 target amplitude) containing trial-wise `.csv` data under different postural conditions.

---

## Notes

- All spatial measurements are in centimeters unless otherwise noted.
- Gaze vectors are in arbitrary 3D units (normalized directions).
- Data were collected using synchronized force plates, motion capture, and eye-tracking systems.

---

## License

Please see the `LICENSE` file for terms of use.

