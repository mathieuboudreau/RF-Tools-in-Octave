---
interact_link: content/intro.ipynb
kernel_name: sos
title: 'Introduction'
prev_page:
  url: 
  title: ''
next_page:
  url: /01/RF_Pulse_Simulator
  title: 'RF Pulse Simulator'
comment: "***PROGRAMMATICALLY GENERATED, DO NOT EDIT. SEE ORIGINAL FILES IN /content***"
---

<h1>RF Tools Demo </h1>
    
Demo for the rf_tools octave package

ISMRM 2019, Montreal Canada

Run this with

    jupyter notebook rf_tools_demo.ipynb
    
This requires that octave be installed, the signal toolbox, and the octave kernel for jupyter.

<h2> Outline </h2>

There are four parts to this tutorial
- RF Pulse simulator -- abr.m
- Shinnar-Le Roux pulse design routines -- b2rf.m, and friends
- Minimum and maximum phase pulses -- dzmp.m
- 2D spiral pulse design -- dz2d.m

The first three sections cover the Shinnar-Le Roux (SLR) pulse design method described in

"Parameter relations for the Shinnar-Le Roux selective excitation pulse design algorithm," J Pauly, P Le Roux, D Nishimura, A Macovski IEEE transactions on medical imaging 10 (1), 53-65
