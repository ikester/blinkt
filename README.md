# A Golang library for the Pimoroni Blinkt #

The [Pimoroni Blinkt](https://shop.pimoroni.com/products/blinkt) is a low-profile strip of eight super-bright, color LED indicators that plugs directly onto the Raspberry Pi's GPIO header. Several available software libraries make it easy to control the color and brightness of each LED independently.

This is a re-implementation of [Pimoroni's Python library](https://github.com/pimoroni/blinkt), written in Go.

## How It Works ##

TBD

## Acknowledgements ##

This project draws inspiration and borrows heavily from the work done by @alexellis on [Docker on Raspberry Pis](http://blog.alexellis.io/visiting-pimoroni/) and his [Blinkt Go libraries](https://github.com/alexellis/blinkt_go), themselves based on work by @gamaral for using the `/sys/` fs interface [instead of special libraries or elevated privileges](https://guillermoamaral.com/read/rpi-gpio-c-sysfs/) to `/dev/mem` on the Raspberry Pi.

## Requirements ##

Physically install a [Pimoroni Blinkt](https://shop.pimoroni.com/products/blinkt) on the Raspberry Pi. **No additional sofware or setup is required for the Blinkt**.

## Usage ##

TBD

## License ##

This library is made available under an MIT-style License. See [LICENSE](./LICENSE).