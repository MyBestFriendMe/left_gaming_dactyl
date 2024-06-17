# Left-Hand Gaming Dactyl
One-handed Dactyl handwired keyboard

The idea of this project was to make a simple and easily mappable one-handed gaming keyboard based around a dactyl build.
It is techinally a Dactyl Manuform 4x6_2_3 which is not on the main branch of the QMK firmware but I was able to get mine working great as just a single keyboard and removing the right hand parts. If anyone shows any interest then I will probably create a right-hand version or at make a full keyboard setup. I am really just posting this to see if anyone even has any insterest in this kind of thing. I will make a whole build sheet if anyone is interested but otherwise this is just a fun thing I made for myself. I have had to almost entirely modify every keyboard I have ever made so I'd be burried neck deep in these descriptions if I made the full tutorial for each build.

* Prep
  - I configured this dactyl from the dactyl configurator:
  - https://ryanis.cool/dactyl/#manuform:Ch8IBhAEGgV0aHJlZSIDdHdvKgNib3gyBm5vcm1pZTgAEhAIxgoQowUYwgMgAii4CDBaGgkIARIDcmo5GAAiF1UAACBBGAAgAV0AAOBAZQAAQEBAAEgAKgYIABAAGAA=
  - I used a filament 3D printer to create the physical case. You are more than welcome to use the STLs I attached for your build. I used 3mm heat-set threads inserts.
  - I would advise using any other build guide on how to wire a keyboard from far more experienced makers than myself like this one: https://medium.com/swlh/complete-idiot-guide-for-building-a-dactyl-manuform-keyboard-53454845b065
  - The modifications that I made to mine that might be considered non-standard would be that since there is no right hand, I had to modify the QMK firmware to not use the whole right side. I personally took the Dactyl Manuform 4x6_4_3 profile and modified it to meet my need but since finishing the project I think it would have been far easier to just modify a standard non-split keyboard down to the configuration I used or even starting from scratch.
