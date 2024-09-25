# ECED4406 Lab 1

In progress details for ECED4406 lab #1.

This includes some high-resolution photso of the PCB you can use for answering parts of the lab.

## Flashrom (SPI Programmer)

[Flashrom](https://www.flashrom.org/) is a good open-source SPI flash read/write tool. In the repository there is the file `flashrom-1.4.zip` which is a build for Windows. You will need to unzip the files onto a folder. See lab for more information.

### Pico as a SPI Programmer

Included in the repo is a fork of StackSmashing's original Raspberry Pi Pico flashrom adapter, the file `pico_serprog.uf2`, which is from 
https://github.com/opensensor/pico-serprog?tab=readme-ov-file .

See the lab description to use this.

## Pico as a USB-Serial adapter (Lab 2)

While we don't use it here, you may decide you want to try decoding the serial messages. You can use the [following link](https://github.com/Noltari/pico-uart-bridge) by downloading the UF2 file from "releases" to convert the board from the SPI programmer into a USB-serial adapter.

We will do this in lab #2 so there is no need to do so right now, I just leave the reference if you want.