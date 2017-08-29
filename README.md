# ugs-platform-plugin-camera

A simple webcam plugin for the UGS Platform.

## Installation

1. Download the nbm file from the Releases tab
2. In UGS Platform, go to Tools->Plugins
3. In the Downloaded tab, click Add Plugin...
4. Select the downloaded nbm file
5. Click Install
6. Restart UGS Platform

## Usage

Open the webcam pane from Window->Plugins->Camera
Choose desired webcam from the dropdown menu (if multiple present)
Choose crosshair style and colour beneath the webcam image.

## Registration

Can be done using a macro. "G10 L20 P0 X<offset_x> Y<offset_y> Z<offset_Z>" will set the current work offset zero to the tool
position. Replace offset_x/offset_y/offset_z with the fixed offset of the crosshair centre from the tool position.

