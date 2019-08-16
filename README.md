# MRR SOLMini

Single-cell lithium-ion battery solar charger module for use with microcontrollers

## Features
- Input: 4.4V to 6V (solar panel) or 5V (USB); max. charging current 800mA
- Output: 3.3V @ max. 1A; 5V @ max. 800mA (Plus version only)

The MRR SOLMini is a single-cell lithium-ion battery solar charger module for use with microcontrollers based on a CN3063 constant-current/constant voltage linear charger for single cell Li-ion and Li Polymer rechargeable batteries. The Core version offers output directly from the battery. The Basic version offers only 3.3V output, while the Plus version offers both 3.3V and 5V output. Battery protection is offered by the DW01. For outputs, 3.3V is provided through a TPS73733 LDO regulator, while 5V is powered by the AP2007 DC-DC step-up converter.

Solar panel input is disabled by the FDN340P P-channel MOSFET when charging via USB.

Input and output pin headers are 2.54mm pitch, but wires can also be soldered directly to the through-hole pads.

Note 1: R4 can be removed if LED indicators are not required. This can help to reduce power consumption.

Note 2: Solar panels can be connected in parallel to increase charging current. However, note that max charging current is set at 800mA.

### Use cases

- Solar battery-powered outdoor data logger
- Solar battery-powered outdoor sensor
- Ultra-low current solar-powered devices

## Warning

- Do not exceed the input voltage limit of 6V.
- Do not exceed the stated current limits. While some components may be rated for higher currents, the connectors and traces are not, and exceeding the current limits may cause the module to overheat.
- Do not reverse polarity.

## Disclaimer

This product is provided as-is. While care has been taken to design a safe product, it is the user's responsibility to make sure precautions are taken to prevent damage or injury when using this product. This includes adhering to all warnings provided. By using this product, the user accepts responsibility to bear all liabilities from any damage or injury arising from the use of this product.
