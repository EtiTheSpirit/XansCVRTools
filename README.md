# Xan's CVR Tools
A collection of tools I designed for the ChilloutVR CCK. You can download them all in one on the [Releases page](https://github.com/EtiTheSpirit/XansCVRTools/releases).

# Tools

<details>
<summary><h2>VRChat Gesture Emulator</h2></summary>

This is the crown jewel of this toolkit. It provides a simple menu (check the toolbar at the top of Unity, look for "Xan's Tools") that automagically reconstructs your avatar's animator and data to convert CVR's Gesture parameters into mimics of the VRChat Gesture parameters, which fundamentally work differently and are not normally compatible.

This tool allows you to copy/paste node graphs in animators from a VRChat avatar into a ChilloutVR avatar, and then it just works:tm:.

![Example of the menu](https://github.com/EtiTheSpirit/XansCVRTools/blob/main/image/VRC%20to%20CVR%20Tool.png)

</details>
<details>
<summary><h2>Digitigrade Helper</h2></summary>

This system is for a specific setup for digitigrade legs on (usually) furry avatars. It comes with a new component that you add to a GameObject called `DigitigradeDescriptor` that can be used to assemble digitigrade legs (naturally, this is an editor-only component). The legs must be constructed in a very specific manner, as shown by the image below.

This system works on basically any Unity install, doesn't necessarily need to be CVR.

![Digitigrade construction](https://github.com/EtiTheSpirit/XansCVRTools/blob/main/image/Digitigrade%20Leg%20Mechanics.png)

</details>
