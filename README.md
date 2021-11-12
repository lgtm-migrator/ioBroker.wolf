![Logo](admin/wolf.png)
# ioBroker.wolf

![Number of Installations](http://iobroker.live/badges/wolf-installed.svg) ![Number of Installations](http://iobroker.live/badges/wolf-stable.svg) [![NPM version](http://img.shields.io/npm/v/iobroker.wolf.svg)](https://www.npmjs.com/package/iobroker.wolf)
[![Downloads](https://img.shields.io/npm/dm/iobroker.wolf.svg)](https://www.npmjs.com/package/iobroker.wolf)

[![NPM](https://nodei.co/npm/iobroker.wolf.png?downloads=true)](https://nodei.co/npm/iobroker.wolf/)

Connect to WOLF devices.
Read in [english](docs/en/README.md).

Lese auf [deutsch](docs/de/README.md).

<!--
	Placeholder for the next version (at the beginning of the line):
	### __WORK IN PROGRESS__
-->

## Changelog
### 1.3.3 (2021-11-12)
* (eifel-tech) Min value of outside temperature corrected

### 1.3.2 (2021-08-31)
* (eifel-tech/tobias) Corrected error: DP 149 with correct Type (Issue #30)
* (eifel-tech/tobias) Changes for js-controller 3.3

### 1.2.1 [2020.06.20]
* (schweigel) Corrected error: DPT_Switch in boolean mode didn't work correct

### 1.2.0 [2020.03.20]
* (LHBL2003) Added for all variables "write" as Bool value
* (bluefox) Admin3 compatibility

### 1.1.1 [2019.12.02]
* (schweigel) Fixed: DPT_Date is wrong
* (schweigel) Fixed: CWL - DPT_TimeOfDay - error
 
### 1.1.0 [2019.09.13]
* (RustyThePropellerHead) ISM8i Firmware v1.50 Update to be able to use the new DataPoints (FW Released in 2016)
                          * As a side note the GLT °C boiler setpoint is defined and read as a 1°C resolution, but you can send the boiler setpoint commands with 0.1°C resolution
* (RustyThePropellerHead) DHW minimum value reduced from 20°C to 0°C to allow for deactivation                          
* (RustyThePropellerHead) Reorganisation of the hg0 to have its own area on the adapter configuration webpage.
* (RustyThePropellerHead) Scalling DPT_FlowRate_m3/h corrected
* (RustyThePropellerHead) Lookup "Programmwahl CWL" corrected

### 1.0.0 [2017.11.21]
* (bluefox) resize logo

### 0.9.1 [2016.12.19]
* (smiling_Jack) Add Bool option
* (smiling_Jack) Add Bar option
* (smiling_Jack) Bugfix Type 5.001 Scaling 

### 0.1.0 [2015.12.01]
* (smiling_Jack) Add writing to ism8

### 0.0.9 [2015.11.06]
* (smiling_Jack) Bugfix
* (smiling_Jack) Add test output

### 0.0.8 [2015.11.02]
* (smiling_Jack) Bugfix io-package

### 0.0.7 [2015.11.02]
* (smiling_Jack) new object management
* (smiling_Jack) Bugfixes

### 0.0.6 [2015.10.20]
* (smiling_Jack) Bugfix parsing

### 0.0.5 [2015.10.16]
* (smiling_Jack) Add support for multiple data
* (smiling_Jack) Add debug output 
* (smiling_Jack) Bugfixes

### 0.0.4 [2015.10.15]
* (smiling_Jack) Bugfix on parse error
* (smiling_Jack) Add DPT_HVACContrMode
* (smiling_Jack) Add DPT_HVACMode

### 0.0.3 [2015.10.14]
* (smiling_Jack) add CWL
* (smiling_Jack) remove ISM8 ip

### 0.0.2 [2015.10.12]
* (smiling_Jack) add BWL-1-S
* (smiling_Jack) update readme

### 0.0.1 [2015.10.08]
* (smiling_Jack) first release

## License

The MIT License (MIT)

Copyright (c) 2015-2021 smiling_Jack

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
