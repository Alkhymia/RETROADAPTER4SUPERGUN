# RETROADAPTER4SUPERGUN

Uses the concept of Paul Quereshi's RetroAdapter, but with CommonGround-Output instead of USB.
Lets you connect a wide range of controllers to a supergun or JAMMA incl SNES, MD, SAT, PSX, N64 etc.


## Work in progress

Right now, only the pcb is provided. The Code for the RetroAdapterMod needs to be rewritten because the pins changed!
If you would like to help finish this project, any help is appreciated.


## PCB Specification

You can order the printed circuit board e.g. from itead.cc using the GERBER files that I provided.

```
50 x 50 mm
1.2 to 1.6 (recommended) mm Thickness
HASL
```

### Installing

* solder all components to the pcb
* Atmega µController needs to be flashed via ISP-PORT.
* connect your favourite joypad to either the DB9 or DB15 connector as shown in the original connection diagram. Bare in mind that the pins may have changed! A detailed new connection diagram will follow in the future.
* connect the output to your JAMMA or SUPERGUN setup.
* Play your arcade games with your favourite controller, such as the Sega Saturn or SNES joypad.


## Links

* Original source for "USB Retropad Adapter" from Bruno Freitas acquired via http://www.brunofreitas.com/node/41 (included for reference in folder original_Files)

* Original source for "Retro Adapter v2.1a" from Paul Qureshi acquired via http://denki.world3.net/retro_v2.html (incuded for reference in folder original_Files)

* https://github.com/rsn8887/RetroAdapterMod



## Built With

* [EAGLE](https://www.autodesk.de/products/eagle/overview)


## Contributing

Please read [CONTRIBUTING.md] for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

* **Alex Schütz** - *Concept & PCB Design*
* **rsn8887** - *RetroAdapterMod*
* **Paul Qureshi** - *RetroAdapter*

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


## Acknowledgments

* This is a work in progress.
* Don't mess with electronics if you don't know what you're doing!
