## SimH
The [SimH project](https://github.com/simh/simh) by former DEC employee Robert Supnik is capable of simulating (in addition to systems from other companies) the following:

### Alpha Simulators
- Alpha
### PDP Simulators
- PDP-1
- PDP-4
- PDP-6
- PDP-7
- PDP-8
- PDP-9
- PDP-10
- PDP10-KA
- PDP10-KI
- PDP10-KL
- PDP10-KS
- PDP-11
- PDP-15
### VAX Simulators
- VAX 11/780
- VAX-11/730
- VAX-11/750
- VAX 8200/8250
- VAX 8600/8650
- MicroVAX I & VAXstation I
- MicroVAX II & VAXstation II & VAXstation II/GPX
- rtVAX 1000 (or Industrial VAX 620)
- MicroVAX 2000 & VAXstation 2000
- MicroVAX 3100 M10/M20
- MicroVAX 3100 M10e/M20e
- InfoServer 100
- InfoServer 150 VXT
- VAXstation 3100 M30
- VAXstation 3100 M38
- VAXstation 3100 M76
- VAXstation 4000 VLC
- VAXstation 4000 M60
- MicroVAX 3100 M80
- InfoServer 1000

### Network Hardware
- Phase V DECnet connections on VAX Unibus and Qbus system
- DPV11 for Qbus VAX system

### Living Computers Museum + Labs
The [Living Computers Museum + Labs](https://www.livingcomputers.org/) in Seattle WA, USA provides access to several systems in their collection via SSH, several of which are SimH emulators. SSH connection is available through a [web brower](https://ssh.livingcomputers.org:4443/) or through a terminal:

```bash
ssh menu@tty.livingcomputers.org
```

Available DEC systems include:
- lc, a PDP-10 KS10 running the Incompatable Timesharing System (ITS) v. 1648
- ka175, a SimH PDP-10 KA10 1050 running TOPS-10 v. 6.03a
- kl2065, a SimH PDP-10 KL10 2065 running TOPS-10 v. 7.04
- rosenkrantz, a VAX 7000-640 running OpenVMS v. 7.3
- misspiggy, a PDP-11/70 running  Research UNIX v7
- zippy, a VAX-11/780-5 running Researvh  UNIX v8
- guildenstern, a simh MicroVAX 3900 running BSD 4.3
- snake, a  PDP-11/84 running BSD 2.11
- alphy, an  Alphastation running  OSF/1
