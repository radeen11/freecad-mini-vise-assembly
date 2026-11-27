# FreeCAD Mini Vise Assembly

A parametric mini vise modeled in FreeCAD 1.1.4. The five-body assembly includes a base plate with four mounting holes, a fixed jaw, a guided sliding jaw, a rear screw support, and a lead screw with a handwheel.

## CAD files

- [Editable FreeCAD model](./Mini_Vise_Assembly.FCStd) — includes the feature history and adjustable jaw opening.
- [STEP export](./Mini_Vise_Assembly.step) — opens in FreeCAD and other STEP-compatible CAD applications at a fixed 40 mm jaw opening.

## Adjusting the jaw opening

Open the `.FCStd` file in FreeCAD. In the model tree, select **Vise settings**, then open the **Data** tab and change **Jaw Opening** to a value from 0 to 80 mm. The sliding jaw and lead screw move together.

## Geometry checks

All five bodies were checked as valid solids. No solid interference was found at 10 mm increments from 0 to 80 mm. The lead screw is represented by a smooth shaft.

## License

[MIT License](./LICENSE).
