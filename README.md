# rust-armv7-builder-image
A builder image for our Rust and Vue based platforms meant for ARMv7 processors

## Defaults
By default we package [OpenSSL](https://www.openssl.org/) and [Postgresql](https://www.postgresql.org/) built using arm-linux-gnueabihf utilities found at [raspberrypi/tools](https://github.com/raspberrypi/tools)

## Locations
- OpenSSL can be found in `/openssl/out`
- Postgresql can be found in `/postgres/out`