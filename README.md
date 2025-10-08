# Nice Cup of Uni-tea

An open-air wood"work" shop that was supposed to be a nice little Unity VR hello-world and turned into a trial in putting fallen-apart laws of physics back together.

## Setup

1. Install Unity Editor 6000.0.58f2
2. `git clone git@github.com:dorukayhan/nice-cup-of-unitea.git`
3. Open project
4. File > Build Profiles > Build for Windows
5. Get some ~~Uni~~tea and a VR headset running in desktop link whatever mode while Unity compiles over 9000 versions of a single lighting shader. I used a Quest 2, but anything that works with Unity OpenXR Plugin 1.15.1 should work, and anything with Oculus or Meta branding will definitely work
6. Run nice-cup-of-unity.exe in the build folder

## Known issues

- The toolbox is low enough that you can climb on it if you left-stick walk into it.
- The flashlight shines through solid objects (e.g. the workbench).
- Convex hulls are too complicated, and as a result grabbable tools clip into the workbench when dropped.