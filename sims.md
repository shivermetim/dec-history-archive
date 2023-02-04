## SimH
The [SimH project](https://github.com/simh/simh) by former DEC employee Robert Supnik is capable of simulating (in addition to systems from other companies) the following:

### Alpha Simulators
- Alpha
### PDP Simulators
- PDP-1
- PDP-4
- PDP6
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

a] multics             Multics MR12.7          Honeywell 6180
[b] toad-2              TOPS-20 7(110131)-1     XKL TOAD-2
[d] cdc6500             NOS 1.3                 DTCyber CDC-6500
[e] lc                  ITS ver 1648            PDP-10 KS10
[f] ka175               TOPS-10 6.03a           sim KA10 1050
[g] kl2065              TOPS-10 7.04            sim KL10 2065
[h] rosenkrantz         OpenVMS 7.3             VAX 7000-640
[j] ibm4361             VM/SP5                  Hercules FlexCUB
[z] bitzone             NetBSD BBS              AMD64

[a] misspiggy           UNIX v7                 PDP-11/70
[b] zippy               UNIX v8                 VAX-11/780-5
[c] lcm3b2              UNIX SVR3.2.3           AT&T 3B2/1000-70
[d] guildenstern        BSD 4.3                 simh MicroVAX 3900
[e] snake               BSD 2.11                PDP-11/84
[f] hkypux              HP/UX 10.20             HP9000/715
[g] alphy               OSF/1                   Alphastation
[h] three               SunOS 4.1.1             Sun-3/160
[i] indy                IRIX 6.5                SGI Indy R5000