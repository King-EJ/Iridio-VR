IRIDIO VR  -  VR mod (Unity 6000.0.59, IL2CPP x64, HDRP, BepInEx 6)
====================================================================
Version 0.1.12 (test build)


<img width="1254" height="1254" alt="Iridio_ VR Jungle Expedition" src="https://github.com/user-attachments/assets/f4ebd0e5-8e3c-4690-a3af-2cef5880d30a" />


INSTALL
  unzip to game folder, only tested with virtual desktop XR

  **[Nefarius ViGEmBus](https://github.com/nefarius/ViGEmBus/releases) support - with the driver installed (ViGEmBusSetup_x64.msi in the zip) the VR
        controllers are a real virtual Xbox 360 controller ([Controls] InputMethod = Auto / ViGEm / InputSystem).**

VIEW
  * Play: first person at the player's eyes. The game's camera follows your head, so you walk and interact where
    you look. Right stick left / right turns you (snap turn; smooth turn in the VR settings menu).
  * Menus / pause / player menu: the game's picture on a screen in front of you. In play the HUD floats in front of
    you with its black parts see-through.
  * Cut-scenes: your view follows the game's camera.

WEAPONS (6DOF)
  * The gun in your hands follows your RIGHT controller and the shots go where the gun points (they come from the
    gun's own muzzle).
  * Each gun is placed so its barrel points where the controller points, with your hand about 22 cm behind the
    muzzle ([Weapons] GripBack). Measured about a second after you draw it.
  * **LIVE ADJUST: hold the left grip + press X**. The gun stays put in the air - move your right hand to where you want
    to hold it, then left grip + X again keeps it (saved per gun). VR settings menu: "Reset the gun's hold".
  * ZOOM SCREEN: while aiming (right grip) a small screen floats above the gun showing the game's aiming zoom along
    the barrel, with a red dot where the shot goes. [Zoom] in the config: size, position, ZoomStrength.
  * Laser: RIGHT STICK UP switches it on / off (from the gun's muzzle).
  * Flashlight follows your LEFT controller (off  by default).


CONTROLS (gameplay) - the VR controllers are a plain Xbox controller, so the controls you set in the game's own

settings are the ones that work ([Controls] PadLayout = Plain):

  HOLD left grip + B .... Start (pause menu)
  
  X + Y together ....... Back

  HOLD left grip + B ... Pause
  
  Right stick up ........ LASER on / off (the mod)
  
  HOLD left grip + right stick ........ LIVE LASER ADJUST: the laser turns up / down / left / right; right stick
                                        click resets it. Saved per gun ([Laser] in the config).
                                        
  HOLD left grip + Y (while zoomed) ... grab the ZOOM SCREEN with your left hand - move it, let go = it stays
                                        there (saved; VR settings: "zoom screen back above the gun")
                                        
  HOLD left grip + X .................. live weapon adjust - or, while carrying something (extinguisher, barrel,
                                        igniter can), live adjust of how you hold it (saved per kind, [Carry])
                                        
  **TWO-HANDED: bring the left controller to the gun's front (it buzzes), HOLD the left grip** - the gun points
              from your right hand to your left hand like a real rifle; let go = one hand ([Weapons] TwoHanded)
              
  HOLD left grip + X (gun) ............ live weapon adjust (the gun stays put, move your hand, again = keep)
  
  ([Controls] PadLayout = Mod: the 0.1.1 layout - right grip LT, left trigger RB, right stick down LB.)
  
  Both stick clicks: tap = re-centre the view, hold = VR settings menu.

ARMS
  Bare hands: both of the player's arms follow your controllers. Knife: the knife is in your right hand, the left
  arm follows your left controller. Guns: the gun is in your right hand ([Arms] LeftArmWithGuns = left arm too).
  [Arms] LeftHandOffset / RightHandOffset move the hands on the controllers.


Disable: to disable Mod rename winhttp.dll to winhttp.dll.bak

[VR Mod Manager](https://github.com/King-EJ/VR-Mod-Manager/releases/tag/VRModManager)

LICENSES
-
Uses Astien's OpenXR bridge. Free, non-commercial.
