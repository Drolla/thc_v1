_This is version v1.0 of THC. The development of this version has been stopped. Please consider moving to the new repository [thc](https://github.com/Drolla/thc)._

**THC**, **Tight Home Control**, provides a multi-protocol and manufacturer-independent automation framework that allows running control tasks, like for example for home automation.

THC has the following features :

* Flexible automation solution - High flexibility through the Tcl scripting language and powerful job definitions
* Target device independent - THC provides a standardized way to access and control various types of target devices: z-Way/Razberry (Z-Wave controller), OpenWeatherMap (access to weather data), MeteoSwiss (access to weather data).
* Rich features set - Responsive web interface, mail alert, random light control, device status and activity logging and plotting, action timer, ...
* Modularity - Support for other target devices, or more features can be added via new modules.
* Platform independent - THC can be installed on each platform that runs Tcl (version 8.5 or higher).
* Low resource needs - THC requires only about 2% CPU time on a on Raspberry PI version 1 (for a setup with 20 devices)

A web interface provides an optimal experience on desktop and mobile devices.

![THC web interface](https://github.com/Drolla/thc_v1/blob/master/developper/doc/thc_Web.gif)

While the users can perform control operations via the web interface the setup of THC is made via a configuration file that is based on Tcl syntax.  THC is in fact entirely programmed in Tcl.  Having some basic knowledge of this scripting language is an advantage for the creation of the configuration file.


### What's next

Start exploring the documentation resources for THC.

* [THC - Getting started](https://github.com/Drolla/thc_v1/wiki/THC-Getting-started) provides instructions for the installation and configuration of THC on your own computer.
* [THC - Basics](https://github.com/Drolla/thc_v1/wiki/THC-Basics) provides some basics about the way THC works and how to handle device states and events.
* [THC - Core functions](https://github.com/Drolla/thc_v1/wiki/THC-Core-functions) provides documentation for the THC core functions.
* [THC - Developers](https://github.com/Drolla/thc_v1/wiki/THC-Developers) provides information for developers that write THC modules or that contribute to the evolution of THC.
* [THC - Index](https://github.com/Drolla/thc_v1/wiki/THC-Index) provides an index to the different documentation pages and API procedures.
 
