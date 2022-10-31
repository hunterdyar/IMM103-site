---
title: Deploy To The Quest
---
Deploy a Project to the quest.

This is the project that "should" be trivial. Basically, we set up an empty project for VR, and then move an existing environment (the Impossible Space project) into it. We will discover that this is not trivial, and there will be many hiccups and technical roadblocks.

This project, really, is an entire week with no creative or artistic decision making. Just solve the technical challenges of deploying to a quest. After this assignment, being able to do this on your own will be assumed, so consider "research/internalize the process" as part of the assignment.

To do this project, you will need to do a few things:

1. Set up your meta account for development, and enable developer mode on your quest.
1. Set up your computer for building for android devices.
1. Get a project configured and succesfully building, and deployed to the device.
2. Get an VR Framework (ultimateXR, in this case) configured, and use it's setup (as described in the ultimateXR documentation) to easily add things like hands or locomotion to your project. *While this may not be strictly neccesary for your impossible space, it is required because we will be using this framework for your final projects*.
3. Re-create your impossible space in your new unity project. Some files can be copied over trivially, other things absolutely cannot. You should consider this an act of "reconstruction" and not "copying".
   > Notably, we probably used the default render pipeline, and are now using the new render pipeline, so learning how to "upgrade materials" to use with URP may be required. Lighting/materials will appear differently and may require tweaking.

4. Getting the environment to work with teleportation. This involved arranging your colliders, if you need to.

### Submission
Come to class with a charged quest that has your experience running on it. If you used any new assets that were not part of your original 'impossible space', you will need to note the attribution somewhere for me to see.

### Evaluation
I am looking for the following criteria:

- Does it run on your device.
- Did you transfer another project into this one.
- Does the new environment "work" now that it's in VR.
  - i.e.: Do we need to adjust the scale, make colliders for the ground, or add a ceiling we forgot about the first time, and so on.

### Links

- [UltimateXR Unity Framework](https://www.ultimatexr.io/)
The following three links, in order, cover most of the VR setup. After which, it's time to recreate (not from scratch) the impossible space.
- [Zero To Quest (Part 1: Developer Mode Setup)](https://impr.hdyar.com/guides/zeroToQuest.html)
- [Zero to VR With Ultimate XR](https://guidebook.hdyar.com/docs/unity/virtual-reality/zero-to-quest-ultimate-xr/)
- [How To Use UltimateXR](https://guidebook.hdyar.com/docs/unity/virtual-reality/how-to-use-ultimate-xr/)
