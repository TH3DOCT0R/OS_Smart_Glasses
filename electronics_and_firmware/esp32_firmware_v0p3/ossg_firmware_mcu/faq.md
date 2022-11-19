# Info // FaQ // QnA // Common questions // whatever

**WARNING: Pretty much everything here is subject to change**

## What is the current hardware setup?

* ESP32-PICO-D4 with 4mb spiram (I use a TinyPico for development)
* display module with CVBS driver board
* I2s microphone
* Android phone running the WearableIntelligenceSystem app

## What display is (currently) being used

We are using the SONY ECX336C + CVBS driver board + (what our supplier calls the) "freeform optics". 

Some suppliers refer to it as the "OL23C" display module.

#### How can I get one?

You can find them on Alibaba, however, ordering this way tends to be pretty expensive. You may have to message the seller for single unit pricing. We're getting them cheaper @ ~$170/singleUnit directly from a supplier, and will consider doing a bulk order (even cheaper) if enough people are interested. 

NOTE: The freeform optics are only compatible with the ECX336C/OL23C and NOT the older ECX336A/OL23A display module. If you intend on buying the display and freeform optics separately (if that's even possible), make sure you buy the correct display. As far as I know, the only other difference is that the ECX336C/OL23C outputs to a max brightness of 3000cd/m2, while the ECX336A/OL23A only outputs to a max brightness of 800cd/m2.

#### How is the display attached to the optics?

The display + freeform optics come glued together.

## I'd love to contribute to the OSSG firmware, but can't dump hundreds on display hardware! What alternatives exist?

* If you still want a display, I'd recommend the SON-FL08 module. These are ~$60 and come with a CVBS driver board and a magnifier. You will need to source your own prism (~$10). For an example of it in action (and links to buy), check out my [Telescope](https://github.com/alex1115alex/wearables-telescope) project.

* If you don't care about the display and just want to contribute while spending the least money, get a Composite-To-USB capture card from Amazon/etc for ~$10. More information about using this in the Telescope readme. 