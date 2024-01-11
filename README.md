# sony-md-remote
Attempt to create a functional remote for use with Sony Minidiscs

## Goals of this project
1. Create an aftermarket Male TRS + 4pin edge connector with 2mm pitch for use with the Minidisc portable players
2. Create a simple passive remote for use with players like the MZ-R70
3. Create an LCD based remote to replace the RM-MC40ELK remote used on devices like the MZ-NH1
4. Create a BLE5.0 remote that can be used with a bluetooth headset. Should be able to support playback controls, as well

## Custom Male TRS + 4pin edge connector with 2mm pitch
Every goal of this project hinges on this aspect. I cannot find anyone suggesting that they've found a source for this specific connector. However, I believe one can be hobbled together with a custom PCB and a board mounted male TRS 3.5mm connector like [this one](https://www.digikey.com/en/products/detail/cui-devices/SP-3533-02/9486641).

Soldering the male TRS connector to the side of a PCB may require a jig in order to assure alignment. My current plans will most likely not provide quite as low profile connector as the original, and may protrude from the device about 11mm. There are straight male TRS connectors, like [this one](https://www.digikey.com/en/products/detail/cui-devices/SP-3533-WT/9486639), might provide the low profile connection like the original but will prove to be slightly more difficult to hand solder. According to the datasheet, it could yeild an overall connection height around 5mm.

