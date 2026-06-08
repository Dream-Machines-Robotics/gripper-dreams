# Dream Gripper

The **Dream Gripper** is a hardware project at [Dream Machines](https://dream-machines.eu/). It's a 3D-printable robot gripper designed to handle objects ranging from an O-ring to a coffee mug, using only standard materials and a 3D printer.

## Design Goals

We set out to build a gripper that:

- has tips nimble enough to pick up an O-ring,
- is strong enough to lift heavy objects without breaking under pressure, and
- provides visual feedback on grip force.

The target working range spans anything from the size of an O-ring to a coffee mug. Beyond performance, the gripper was built to be easily reproducible — it relies only on standard materials and a 3D printer — and is designed for use with a linear rail as its platform.

## Components

The gripper is made up of three major components:

| Component | Material | Price |
|---|---|---|
| [Rigid backbone](https://eu.store.bambulab.com/products/pla-cf) | PLA-CF | €26.99 |
| [Soft insert](https://www.amazon.de/dp/B09KKZLZVR?ref=ppx_yo2ov_dt_b_fed_asin_title) | TPU95A | ~€30.00 |
| [Grip tape](https://www.amazon.de/dp/B0FB8LQ29P?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1) | - | €16.99 |

<img width="400" alt="Robot setup" src="https://github.com/user-attachments/assets/0dc6d53d-df09-465b-8564-8f528a3da1f3" />

## Design

### Gripper Tip

The tip is rigid PLA-CF covered with a thin layer of grip tape. This **"fingernail" design** lets the gripper exert more force on small pieces while keeping a slim profile.

### TPU Insert

The middle section uses a soft TPU insert that grips larger objects more firmly by increasing the contact surface. Objects with sharp corners benefit too: the TPU wraps the grip tape layer around the edges of the object.

<img width="400" alt="Wrapping around round object" src="https://github.com/user-attachments/assets/6781c858-d0b3-4085-b052-146b5208bd67" />

<!-- TODO (Sixtus): add a photo here showing the gripper picking up one of the cubes -->

## Assembly Instructions

1. Print the backbone in **PLA-CF** and the insert in **TPU95A**. The slots in the backbone should have enough tolerance to accept the TPU inserts; a tight fit is intended.
2. Completely remove all supports from both parts.
3. Press the TPU insert into the backbone slots.
4. Lay the assembly gripping-side down on a strip of grip tape. Trace the outline onto the back of the tape and cut out the shape. Leave extra material toward the inside of the gripper so you can extend the grip tape over the TPU by a few centimetres on each side, otherwise the tape may loosen over time.

## Credits

Built by **Sixtus Klein** at **[Dream Machines](https://dream-machines.eu/)**.
[LinkedIn](https://www.linkedin.com/in/sixtus-klein-a41421265/?skipRedirect=true) · [X](https://x.com/sixtusklein)
