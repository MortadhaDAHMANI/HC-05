# HC-05 :radio: :computer: :phone:

## Summary
#### What is HC-05?
HC-05s are Bluetooth 2.0/2.1 EDR devices that have a serial UART layer on top of the Bluetooth. The UART layer makes them easy to use but hides the Bluetooth functions from the user. This is good if all you want is to make 2 things talk to each other. The HC-05 has two modes of operation; AT command mode and transmission mode. When in AT command mode all data received over the serial UART connection is treated as a command, and when in transmission mode, all data received over the serial UART connection is treated as data. 

> "Bluetooth RF Transceiver Master Slave Integrated Bluetooth Module Serial Port Communication"
--------------------

## Pinout
![alt iviny](https://github.com/MortadhaDAHMANI/HC-05/raw/master/HC-05-WITH-CONFIRM-CONNECTION-CIRCUIT-584x467.jpg)

```diff
- NOTICE: Connect the HC-05 RX Pin to Arduino TX through a voltage divider (1K /2K2 Ohm).
```

### Useful links
* [AT Commands](http://www.martyncurrey.com/hc-05-with-firmware-2-0-20100601/ "AT Commands")
* [AT Commands](http://www.martyncurrey.com/hc-05-fs-040-state-pin/ "State")
* [Hardware Design](https://www.electronicshub.org/hc-05-bluetooth-module/ "Hardware Design")
* [Specification](http://www.martyncurrey.com/hc-05-zg-b23090w-bluetooth-2-0-edr-modules/ "Specification")
* [Courses](https://openclassrooms.com/fr/courses/5224916-developpez-un-robot-mobile-connecte-par-bluetooth "OpenClassrooms")

### Donation
If this project help you, you can give me a tip ;)

<!---
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg?style=for-the-badge&logo=paypal&link=https://www.paypal.com/paypalme2/billzgithub)](https://paypal.me/mamdpay)
-->

<a href="https://paypal.me/mamdpay" rel="In"> <img src="https://www.pngarts.com/files/4/Paypal-Donate-PNG-High-Quality-Image.png" alt="Donation" height="70"></a>

<!--a href="https://www.linkedin.com/in/mortadhadahmani" rel="In"> <img src="https://ps.w.org/button-paypal-donation/assets/icon-256x256.jpg" alt="Donation" height="150"></a-->

<!--a href="https://paypal.me/mamdpay" rel="In"> <img src="https://www.paypalobjects.com/webstatic/mktg/logo/AM_mc_vs_dc_ae.jpg" alt="Donation" height="100"></a-->

<!--a href="https://paypal.me/mamdpay" rel="In"> <img src="https://wildflowercottage.org/wp-content/uploads/2019/03/paypal_donate_button_png_996391.png" alt="Donation" height="150"></a-->

### Author
* This version has been created by: [**Mortadha DAHMANI**](mailto:mortadha.dahmani@gmail.com)

<a href="https://www.linkedin.com/in/mortadhadahmani" rel="In"> <img src="https://github.com/MortadhaDAHMANI/Py-SIM800L/raw/master/in2.jpg" alt="In" height="40"></a>

### Revision History
* Initial Release : 25 Mars 2012

### License
* _HC-05_ is distributed under the **LGPL** version 3 license.
