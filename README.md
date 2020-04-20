# e_ink_pocast_player

The name is a placeholder right now. The project will(hopefully) be started in the near future but for now, this repo mostly serves to dump ideas and links for future references

## Features

- Screen size probably half of the one touch
- Optimized for episode discovering but not for podcast discovering
- Pairing with Bluetooth Headset(be super nice if can get LE audio working but that's a super stretch)
- Low power

## Hardware

Touch might not be possible since the capacitative touch layer can be a pain to integrate

The PSOC6 is a prime candidate right now due to CYW4343W being the only known chip with both Wifi and Bluetooth while having better power consumption compared to the ESP32. The CapSense technology also looks really promising for good UX

[PSOC6 dev kit with the CYW4343W](https://www.cypress.com/documentation/development-kitsboards/psoc-6-wi-fi-bt-prototyping-kit-cy8cproto-062-4343w#res1536)

[CapSense Guideline](https://www.cypress.com/file/41076/download)

Note that only CapSense chip can be bought, the CapSense sensor pad(the zig zag pattern) itself is made using copper traces. PCB Layout will require hatched ground plane. KiCad version 6 should have this feature so might have to use pre-release version

[Kindle Design](https://archive.nytimes.com/www.nytimes.com/interactive/2012/12/26/technology/light-reading.html?_r=0)

[waveshare e-ink](https://www.amazon.com/Waveshare-4-3inch-Resolution-Interface-Electronic/dp/B00VV5IMN0)

Already got approved for listen notes free API version, check email. Listen note seems to be the best API around

[ListenNotes Podcast API](https://www.listennotes.com/)
