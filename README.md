# Comparing Physics-based Hand Interaction in Virtual Reality: Custom Soft Body Simulation vs. Off-the-Shelf Integrated Solution

![teaser](https://github.com/louspawn/VR-physics-based-hand-interaction-comparison/assets/41284921/131415f4-42e9-4fce-a0e6-992448f137bf)

## Abstract
Physics-based hand interaction in VR has been extensively explored, but almost none of the solutions are usable. The only exception to that is CLAP, a custom softbody simulation offering realistic and smooth hand interaction in VR. Even CLAP, however, imposes constraints on virtual hand and object behavior. We introduce HPTK+, a software solution that utilizes the physics engine NVIDIA PhysX. Benefiting from the engine’s maturity and integration with game engines, we aim to enable more general and free hand interactions in virtual environments. We conducted a user study with 27 participants comparing the interactions supported by both libraries. Results indicate an overall preference for CLAP, but no significant differences in other measures or performance, except variance. These findings provide insights into the libraries' suitability for specific tasks. Additionally, we highlight HPTK+'s exclusive support for diverse interactions, positioning it as an ideal candidate for further research in physics-based VR interactions.

## Resources

📰 [Paper link](https://ieeexplore.ieee.org/document/10494127)

🎞️ [Comparative study overview video](https://youtu.be/CYSmvZRWVzk)

🎞️ [Showcase video](https://youtu.be/NAQ02zyXUaE)

🥽 Showcase APK (TBD)

## HPTK+

![Showcase](https://github.com/louspawn/VR-physics-based-hand-interaction-comparison/assets/41284921/055ef58c-0fcc-4d77-aea3-f738bb601d78)

HPTK+ is short for HPTK+ArticulationBodies, meaning the existing [HPTK library](https://github.com/jorgejgnz/HPTK) that has been created by Jorge, the second author of the paper, extended in functionality by the [Articulation Bodies](https://docs.unity3d.com/Manual/class-ArticulationBody.html) of NVIDIA PhysX that Christos, the first author of the paper, has been working on in parallel for his PhD project [Unity Physics Avatar](https://github.com/DI-UOA-RealityLab/Unity.Physics.Avatar). Christos and Jorge collaborated to combine the two projects and the end result has been integrated to the [HPTK Plus](https://github.com/louspawn/HPTK-Plus/tree/master) library.

## Authors

[​Christos Lougiakis](http://users.uoa.gr/~chrislou/) [1]

[Jorge Juan González](https://www.linkedin.com/in/jorgejgnz/) [2]

[Giorgos Ganias](https://www.linkedin.com/in/giorgos-ganias-801928164/) [1]

[Akrivi Katifori](https://www.linkedin.com/in/akrivi-katifori-34852818a/) [3]

[Ioannis-Panagiotis Ioannidis](https://www.linkedin.com/in/ioannis-ioannidis-a85a0a271/) [3]

[Maria Roussou](https://www.di.uoa.gr/en/staff/45) [1]


[1] [National and Kapodistrian University of Athens](https://en.uoa.gr/) [2] [PresenceXR](https://pxr.es/) [3] [ATHENA Research Center](https://www.athenarc.gr/en/home)

## Cite our work

```
@INPROCEEDINGS{10494127,
  author={Lougiakis, Christos and González, Jorge Juan and Ganias, Giorgos and Katifori, Akrivi and Ioannis-Panagiotis and Roussou, Maria},
  booktitle={2024 IEEE Conference Virtual Reality and 3D User Interfaces (VR)}, 
  title={Comparing Physics-based Hand Interaction in Virtual Reality: Custom Soft Body Simulation vs. Off-the-Shelf Integrated Solution}, 
  year={2024},
  volume={},
  number={},
  pages={743-753},
  keywords={Three-dimensional displays;Scalability;Virtual environments;User interfaces;Particle measurements;User experience;Software;Human-centered computing;Human computer interaction (HCI);Interaction techniques;Computing methodologies;Modeling and simulation;Simulation support systems;Simulation environments;Interaction paradigms;Virtual reality},
  doi={10.1109/VR58804.2024.00094}
}
```
