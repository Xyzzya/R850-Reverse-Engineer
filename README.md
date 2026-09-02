# R850-Reverse-Engineer
Reverse engineering Rafael Micro's R850 TV Tuner found on some revisions of the now-defunct ABS-CBN TV Plus TV Set Box, with the ultimate goal of using the IC for a Software-Defined Radio.

Surprise... it is still empty. I cross-checked its pinout with the R836 TV Tuner (R836's datasheet is publicly available online with a quick Google search), and so far it matches. For the drivers, I recommend checking out nns779/px4_drv/driver/r850.c and r850.h, that's all.
