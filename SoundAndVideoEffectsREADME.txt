Find sounds listeners in hierarchy object bellow:
Audio sources are in Scene: Main Path:Camera/Pivot/Main Camera
								                  /AudioSourceSlot1
												  /AudioSourceSlot2
Audio listener is in Main Camera object.
Manager of the audio is in Main Camera object called "SoundManager.cs"

Particle systems:
In Hierarchy: 
---- Camera/Pivot/BackStaticElements/RainBasic
In Resources: 
---- Plugins/Water FX Particles/Materials/Rain.mat

Hack Effect:
In resources:
----Materials/HackEffect.mat
In hierarchy:
----MainScene/Stage/Level#1/Computer/HackEffect

Other:
Material for light sprites:
In resources:
----Materials/SpriteLighter.mat
use in every Sprite when we want illumination.

Flare for lamps:
In resources:
----Plugins/Standard Effects/LightCookies/Textures/LightSquareCookie.psd
In hierarchy:
----Foreground/StreetLamp/Light
