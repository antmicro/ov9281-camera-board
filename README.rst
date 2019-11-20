========================
OV9281 Dual camera board
========================

.. Image:: images/ov9281-board-photo.jpg

Overview
========

This repository contains open hardware design files for a dual camera module, created by `Antmicro <https://antmicro.com/>`_.
This board is equipped with a pair 1-megapixel `OmniVision OV9281 <https://www.ovt.com/sensors/OV9281>`_ image sensors. 
It can be connected by MIPI CSI-2 interface exposed on an unified FFC interface. 


to a variety of host platforms including

The PCB design files were prepared in KiCad and are released as an Open Source Hardware (OSHW).

Key Features
============

   +------------------------------+-------------------------------------+
   | Image sensor(s):             | 2x monochrome global shutter OV9281 |
   +------------------------------+-------------------------------------+
   | Pixel size:                  | 3μm x 3 μm                          |
   +------------------------------+-------------------------------------+
   | Active array size:           | 1280 x800                           |
   +------------------------------+-------------------------------------+
   | Optical size:                | 1/4inch                             |
   +------------------------------+-------------------------------------+
   | Focusing range:              | 65mm ~ infinite                     |
   +------------------------------+-------------------------------------+
   | Output interface:            | 50-pin FFC connector                |
   +------------------------------+-------------------------------------+
   | Output formats:              | 8/10-bit BW RAW                     |
   +------------------------------+-------------------------------------+
   | Maximum image transfer rate: | 1280 x 800 @60 fps                  |
   +------------------------------+-------------------------------------+

Interface connector
===================

The board uses a 50-pin FFC connector which exposes two separate MIPI CSI interfaces for both cameras along with power supply rails and control signals.
The board is electrically compatible with Antmicro's products and open hardware designs including `Jetson Nano baseboard <https://github.com/antmicro/jetson-nano-baseboard>`_.
or Zynq Video Board

For more details regarding board connection please refer to schematic sheets.

Mechanics
=========

Board dimensions:

.. image:: images/ov9281-board-dimensions.png
