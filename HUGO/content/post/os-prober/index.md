+++
author = "kazi sifat"
title = "OS prober"
date = "2019-03-11"
description = "config grub"
tags = [
    "grub"
]
categories = [
    "linux"
]
series = ["Themes Guide"]
aliases = ["migrate-from-jekyl"]
+++


sudo su

sudo echo "GRUB_DISABLE_OS_PROBER=false" >> /etc/default/grub

exit

sudo grub-mkconfig -o /boot/grub/grub.cfg