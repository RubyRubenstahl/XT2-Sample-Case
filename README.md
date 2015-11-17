#Butler XT2 Sample Case Show

This show file is specificily designed to show off the interactive features of the Butler XT2, Glass Touch T12, Glass Touch T6R, and DMX2PWM from [e:cue](http://ecue.com).

###Features
 - Two zone control (16pxl board and DMX2PWM backlight operate as separate zones) using two mutex groups. 
 - The Glass touch T12 controls the 16pxl baord, the T6R controls the backlight. 
 - The momentary switches in the case are programmed to add a flash & sparkle overlays on the 16pixel board.
 - Branded action pad featuring a color picker for the 16pxl baord.
 - Secondary action pad interface using an image of the case interior to simulate the physical case.

###Usage
In order for the Glass Touch programming to be applied to your case, you must discover the Glass Touches via the Device Manager and then copy the programming from the show file's Glass Touch devices to the discovered devices. You can then delete original glass touches (once you verify that the programming has been copied over of course). 

###Note
On all Action Pad and Glass Touch buttons triggering cues in Mutex Group 1 (the 16pxl board), the **release button** trigger is configured to run **Trigger Label 2**, which stops the color picker cuelists. This ensures that the color picker does not accidentally override cues. 
 
