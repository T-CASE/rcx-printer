# rcx-printer

This repository contains code for a dot matrix printer built using Lego Mindstorms RCX.

`printer` contains code for the RCX brick.
It requires `brickOS` (available as package for Debian/Ubuntu).

`img2rcx` is a software to transmit images to the RCX.
Since it has very little available memory, images are transmitted blockwise.
`img2rcx` acts as a server from which the RCX can request the image blocks via IR.


`rotation-paper` contains a template that can be printed, cut out, and, together with a light sensor, used to construct a DIY rotation sensor.