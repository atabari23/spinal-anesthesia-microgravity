# Spinal canal geometry

| File | What it is | Units in the file |
|---|---|---|
| `spinal_canal_C3-L5.stl` | The canal as printed and cast (C3 to L5), 42,192 triangles. About 435 mm long, internal volume about 40.7 mL. | Decimetres (multiply by 100 for mm) |
| `spinal_canal_C3-L5_with_end_connectors.stl` | The same canal with two cylindrical pegs (8.7 mm diameter, 32 and 34 mm long) at the ends, used to form the tubing connections in the cast. About 493 mm overall. | Metres |

GitHub shows STL files in a 3D viewer; click either file to rotate it.

**How it was made.** A sagittal CT from the VerSe dataset (27-year-old individual) was opened in 3D Slicer 5.6.2 and the canal was traced by hand from C3 to L5. The surface was cleaned and smoothed in Blender 4.1, with pegs added at each end to anchor the core during casting. Dr. Alex Suen printed it in water-soluble PVA on a Prusa XL (0.2 mm layers, 15% grid infill). The print was cast in clear epoxy, cured for 48 h, and the PVA dissolved out in warm water, leaving a hollow canal. A 25-gauge Quincke spinal needle was then fixed through a drilled access tunnel at about L3–4 (full method in [docs/1_canal_model.md](../docs/1_canal_model.md)).

**What the model leaves out.** It is rigid and has no spinal cord, nerve roots, cauda equina, dural compliance or CSF pulsation. It was built to show differences between solutions under different gravity, not to reproduce absolute spread in a patient.

**Licence.** Derived from VerSe (Sekuboyina A et al., *Med Image Anal* 2021;73:102166; Löffler MT et al., *Radiol Artif Intell* 2020;2:e190138), CC BY-SA 4.0. These files are shared under CC BY-SA 4.0.

SHA-256
```
85a6a5edfeeea2343a9de885a8d168201dc5167393a3b86da9521910796717f5  spinal_canal_C3-L5.stl
774962077a112f6320bd3e32bfa1864a0592b5d9b021cc4b1815f423b917e91f  spinal_canal_C3-L5_with_end_connectors.stl
```
