# Reviving an Atari Mega ST 2

# Reference material

Formatting floppy using Debian 12

  sudo apt install ufiformat

  sudo ufiformat -f 720 -V -F /dev/sdc

Writing .ST files to floppy

  sudo dd if=diamond_edge_2_04_hisoft.ST of=/dev/sdc bs=512

## Documentation

[Atari Document Archive](https://docs.dev-docs.org/)

[Atari ST Interfaces & Connectors](https://info-coach.fr/atari/hardware/interfaces.php)

## DIY videos on YT

[Make your own Atari to VGA adaptor](https://youtu.be/N9xhNgCW2LQ) by the [The Back Office Show](https://backofficeshow.com/)
