# Custom T-Deck fancy UI firmware compatible with Meshtastic network

## Overview

This repository contiains a fork of the Meshtastic 2.5.16 firmware with modifications targeted to the T-Deck fancy UI.  It is redistributed under the GPL v3 license.

## Building instructions:

    git clone https://github.com/kennytaylor661/t-deck-mesh-ui
    git switch tft-gui-work
    git submodule update --init
    pio run -e t-deck

This can be quickly built online for free with gitpod.io

