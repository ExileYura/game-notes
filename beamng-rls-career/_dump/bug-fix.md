[<< BACK <<](../!index.md)

| Bug                           | Solution                                                                                           |
| ----------------------------- | -------------------------------------------------------------------------------------------------- |
| Cannot pause game, map crash. | Press F5 to reload menus.                                                                          |
| Truck cannot release brakes.  | This issue impacts the front brakes specifically; remove these and keep brakes in the rear wheels. |

What I'd try, in this order:

Press/release the normal brake once, then press/release the parking-brake key once. There are reports of the vehicle getting stuck in a brake state where doing this clears it.
If it's a T-Series/semi: leave the engine running for 10–20 seconds before trying to move. Watch the air-pressure gauges. With realistic air-brake simulation, an empty/low air tank can keep the spring brakes applied despite the parking-brake control being released.
Press F5. This reloads the UI. It has fixed several Career/delivery soft-lock states where the game ends up behaving as though a mission is still controlling the vehicle.
Try repairing the truck. There are reports of Career vehicles becoming unable to drive in forward/reverse with the parking brake apparently off, with repairing the vehicle restoring functionality.
Test without mods, particularly drivetrain/engine/transmission mods. This is important if the problem occurs specifically when accepting a delivery. There are documented RLS Career cases where a modded engine caused the cargo-loading phase to leave the vehicle stuck with brake lights on; switching from the problematic version of the mod fixed it.
If you're using RLS Career Overhaul, update it and its dependencies. RLS has had numerous Career/delivery compatibility problems across BeamNG updates, and the current 0.39-compatible branch is still being maintained.

Put an air thing gauge on the HUD?
