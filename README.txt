

Uriel Linux BETA:

Mini Linux Distro 64 bits

PACKAGE PROGRAMA:
  .. The Base ..
  sum (Summer Language 0.71.0),
  tte, edit, editor (Text Editor)

USAGE (using grub4dos from pen-drive):

Edit the file: "menu.lst"
# -------------------------------------
title Uriel Linux BETA
  kernel /vmlinuz
  initrd /uriel_rootfs.cpio.gz
# -------------------------------------

USAGE: Using the image ( .iso ) with qemu:

  qemu-system-x86_64 -cdrom Uriel_Linux_0.90.0_BETA_64_Bits.iso
  
