# OpenSCARA Hardware

This repository contains the 3D-printed parts, BOM and assembly guide to replicate my SCARA.

For a complete overview of the project, refer to the [main OpenSCARA repository](https://github.com/ggldnl/OpenSCARA). 

## 📋 Bill of Materials (BOM)

Below is a summary of the components required to build the robot:

| **Category**           | **Component**                           | **Quantity** | **Notes**                                                                                       | **Cost per part**                                 |
|------------------------|-----------------------------------------|--------------|-------------------------------------------------------------------------------------------------|---------------------------------------------------|
| Mechanical Components  | 3D-printed parts                        |              | All the meshes in the CAD directory | Being the total weight of the printed parts around 500g, referring to the current price of a PLA-CF spool from Bambulab (26.99€), the estimated cost is around 16€                                                    |
|                        | M2 Screw kit                            | 1            | You just need 4 M2x8 screws, two for each endstop, each with a nut. | Less than 8€ for an assorted 225pzs kit on Amazon |
|                        | M3 Screw kit                            | 1            | Refer to the instructions to know precisely how many screws and nuts you will need.             | About 12€ for an assorted 800pzs kit on Amazon    |

Approximate total cost: 290€

The prices listed in this BOM reflect the costs at the time of purchase and may no longer be accurate. This BOM is provided for reference only and should not be considered a precise cost estimate.

## 🔨 Assembly Instructions

Assembly instructions are available [here]().

## 3D Printing Profile

Print profiles and STL files for the robot parts are [hosted on MakerWorld](https://makerworld.com/en/models/).

Make sure to follow the recommended print settings for optimal strength and fitment.

## 📝 Notes

1. I printed everything in PLA-CF for more rigidity but you can use PLA if you want.

2. The `stepper.stl` and `stepper_pancake.stl` files are used in the URDF, we won't need them to build the actual robot. Check out the [simulation repository](https://github.com/ggldnl/OpenSCARA-Simulation).

3. I just found this [amazing web-based urdf visualizer](https://gkjohnson.github.io/urdf-loaders/javascript/example/bundle/). You can drag and drop a urdf file and the `CAD` folder and it will display it. This was quite handy during development.  

## TODO

- [ ] Update the BOM.
- [ ] Update the assembly instructions.
- [ ] Update the MakerWorld link with the correct URL.

## Contribution

Feel free to raise issues or contribute improvements to this repository. For further information about the project, check out the [main OpenSCARA repository](https://github.com/ggldnl/OpenSCARA). Give a ⭐️ to this project if you liked the content.
