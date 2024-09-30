# Left-Hand Gaming Dactyl
One-handed Dactyl handwired keyboard

The idea of this project was to make a simple and easily mappable one-handed gaming keyboard based around a dactyl build.
It is techinally a Dactyl Manuform 4x6_2_3 which is not on the main branch of the QMK firmware but I was able to get mine working great as just a single keyboard and removing the right hand parts. If anyone shows any interest then I will probably create a right-hand version or at make a full keyboard setup. I am really just posting this to see if anyone even has any insterest in this kind of thing. I will make a whole build sheet if anyone is interested but otherwise this is just a fun thing I made for myself. I have had to almost entirely modify every keyboard I have ever made so I'd be burried neck deep in these descriptions if I made the full tutorial for each build.

***If you are trying to use my dumb QMK code just be warned that I haven't figured out the OLED display yet. It may or may not work for you. I melted the existing screen before I could test my code so include at your own risk!***

* Prep
  - I configured this dactyl from the dactyl configurator:
  - https://ryanis.cool/cosmos/beta#cm:Cr0BChYSEBBAIAlAoJKcAkj5h4zdgAkwEjhPCg0SBRCQQSATEgASADg7Cg0SBRCQTSATEgASADgnChoSBRCQWSATEgASAxCwLxIDELBfOBNAhICcAQodEgUQkGUgExIAEgMQsDsSAxCwazgAQIQqSICAkAEKGhIFEJBxIBMSABIAEgA4FEC84oawGEiEgJABCh4SBBAQIBMSAxCgThICEDASADgoQMrehoAYSIiAkAEYAECOiditsFVI7IW4rqAGCmUKTxISEEAgAECxg7iO8AFIl4mwockOEhAgAECh+JOQAkjHiYSVgL8bEhEgAECrhZyPsAZI84uUjYDaHRISCJAgIABA24v4l0BI34WIyfkDOAAYAjCAMED3jZSukAVI0pHwvfD7BxiCICIJCMkBEL4BGJwEggEBAkgDUAFYQ2ADcgogClAAaLQBcI4CePSHvP6AOQ==
  - I used a FDM 3D printer to create the physical case. You are more than welcome to use the STLs I attached for your build. I used 3mm heat-set threads inserts.
  - I would advise using any other build guide on how to wire a keyboard from far more experienced makers than myself like this one: https://medium.com/swlh/complete-idiot-guide-for-building-a-dactyl-manuform-keyboard-53454845b065
  - The modifications that I made to mine that might be considered non-standard would be that since there is no right hand, I had to modify the QMK firmware to not use the whole right side. I personally took the Dactyl Manuform 4x6_2_3 profile and modified it to meet my needs but since finishing the project I think it would have been far easier to just modify a standard non-split keyboard down to the configuration I used or even starting from scratch.

![image](https://i.imgur.com/dYDgjU1.jpeg)
