# WIP - to be completed
## Redox-Nano (Wireless)

The Redox-Nano is the wireless ZMK version of the Redox keyboard using Nice!Nano mcu

## Summary

  - [Bill of materials](#bill-of-materials)
  - [Assembly](#assembly)
  - [Firmware](#firmware)
  - [Battery usage](#battery-usage)
  - [Case compatibility](#case-compatibility)

## Bill of materials

#### Transmitters

| Qty | Item                                          | Notes                                               |
|----:|-----------------------------------------------|-----------------------------------------------------|
|   2 | Redox Nano PCB               |  |
|  70 | Cherry MX compatible switches                 |                                                     |
|  70 | Kailh PCB sockets CPG151101S11                |                                 |
|  70 | SOD-123 1N4148/1N4148W diodes                 | 1N4148 THT diodes can also be used                  |
|   2 | LiPo             | |
|   2 | JS102011SAQN SMT slide switch                 | [digikey](https://www.digikey.com/product-detail/en/c-k/JS102011SAQN/401-1999-1-ND/1640114)|
|   2 | LiPo header              |                                                     |

## Assembly

##### MCUs detail

<p align="center">
<img src="" alt="MCUs detail 1" width="300"/>
</p>
##### Slider switch detail

<p align="center">
<img src="." alt="Slider switch detail" width="600"/>
</p>

##### Diodes and hot-swap socket detail

<p align="center">
<img src="" alt="Diode and hot-swap socket detail 1" width="300"/>
</p>

##### Battery termincal installation detail

<p align="center">
<img src="" alt="Battery holder installation detail. Ground pad." width="300"/>
</p>

##### Left and right hand completed assembly

<p align="center">
<img src="" alt="Left and right hand completed assembly" width="600"/>
</p>

##### Switches assembly

<p align="center">
<img src="" alt="PCB attached to top case via switches" width="600"/>
</p>

##### Battery install detail

<p align="center">
<img src="" alt="Battery taped to case" width="600"/>
</p>

##### Final case assembly

<p align="center">
<img src="" alt="Case fully assembled" width="600"/>
</p>

##### Rev 2.0WHS 3D printed case

The STLs are for the left hand keyboard only, you'll need to mirror them along the X axis in your slicer for the right hand keyboard.

Hardware required for assembly:
- 10x M3 8 mm screws

## Firmware

### Step-by-step firmware upload guide

Follow the standard ZMK guide: [ZMK](https://zmk.dev/docs/user-setup)


## Battery usage

Needs to be investigated still

## Case compatibility

The nano version is not compatible with previous cases
