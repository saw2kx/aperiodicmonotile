---
title: A 3D-Printable Tiling of Aperiodic Monotiles
---
<h1>Let’s make a group tessellation</h1>

<p>Everything you need is here and there are options from quick easy prints to STEP files for more advanced customisation.</p>

<h2>What is an aperiodic monotile?</h2>

<p>A monotile is a single tile shape that tiles the plane by repeated copies of itself, and an aperiodic tiling is one that has no translational symmetry.</p>

<p>This project uses the hat tile, discovered in 2023 by amateur mathematician David Smith and published with a proof by him and his collaborators.  Find more information in <i>further reading</i> below.</p>

<p>Here is a tiling using hat tiles:</p>
<img src="https://github.com/saw2kx/aperiodicmonotile/blob/main/images/hats.png?raw=true" alt="An aperiodic monotile tiling">
<i>Image from “An Aperiodic Monotile” by David Smith et al. (2023), licensed under CC BY 4.0.</i>

<h2>How can I participate?</h2>

<p>If you are newer to slicing models or just looking for a quick easy print, we have you covered (see <i>easy option</i>, below).  If you would like to play around in the slicer, we are curious to see what effects you will create and if you want to edit the inner hat tile or kite tile (using the STEP files in the repo), we are excited to see what you create.</p>

<p>We have prepared two different tiles: one with an open frame and one with a partitioned frame.  The spaces in the frame can be filled with either smaller tiles or with modifiers (more on that shortly).</p>

<p>Here is the open frame (white) with a inner hat tile (red):</p>
<img src="https://github.com/saw2kx/aperiodicmonotile/blob/main/images/openFrame.png?raw=true" alt="The open frame and inner tile" width="434" height="245">

<p>Here is the partitioned frame (yellow) with one kite tile (green):</p>
<img src="https://github.com/saw2kx/aperiodicmonotile/blob/main/images/partitionedFrame.png?raw=true" alt="The partitioned frame and one kite tile" width="434" height="245">

<p>Here are both frames showing the modifiers.  Whilst the inner hat tile and kite tiles are the same height as the frames and leave clearance for a good fit, the modifiers match the height of the straight part of the frame and have no clearance to the frame:
<img src="https://github.com/saw2kx/aperiodicmonotile/blob/main/images/modifiers.png?raw=true" alt="Both frames with modifiers" width="868" height="245">

<p>The modifiers can be deleted if you would like to leave a gap to insert a printed inner hat or kite tiles, left as they are to create a solid part, or modified for interesting effects (such as having no top layers to reveal infill)</p>

<h3>About the files</h3>
There are four files:
<ul>
  <li>Open frame and modifiers</li>
  <li>Partitioned frame and modifiers</li>
  <li>Inner hat tile</li>
  <li>Kite tile</li>
</ul>

<p>There are four sets of the above 3MF files.  The universal files work eveywhere, but there are also files for Orca Slicer, PrusaSlicer and Cura where I have labelled and grouped the objects for you.</p>
<a href = "https://raw.githubusercontent.com/saw2kx/aperiodicmonotile/main/3MF/AP_universal.zip">Universal</a> | 
<a href = "https://raw.githubusercontent.com/saw2kx/aperiodicmonotile/main/3MF/AP_PrusaSlicer.zip">PrusaSlicer</a> | 
<a href = "https://raw.githubusercontent.com/saw2kx/aperiodicmonotile/main/3MF/AP_OrcaSlicer.zip">Orca Slicer</a> | 
<a href = "https://raw.githubusercontent.com/saw2kx/aperiodicmonotile/main/3MF/AP_Cura.zip">Cura</a>

<h3>Easy option</h3>
<p>Use these STL files which exclude the modifiers.  Print the open frame and the inner hat tile or the partitioned frame and eight kite tiles.  This is also a good fallback option if you can’t use 3MF files or have issues with those provided here.</p>
<a href = "https://raw.githubusercontent.com/saw2kx/aperiodicmonotile/main/STL/Open%20frame.stl">Open frame</a> | 
<a href = "https://raw.githubusercontent.com/saw2kx/aperiodicmonotile/main/STL/Inner%20hat%20tile.stl">Inner hat tile</a><br>
<a href = "https://raw.githubusercontent.com/saw2kx/aperiodicmonotile/main/STL/Partitioned%20frame.stl">Partitioned frame</a> | 
<a href = "https://raw.githubusercontent.com/saw2kx/aperiodicmonotile/main/STL/Kite%20tile.stl">Kite tile</a>

<h3>Hard option</h3>
<p>Hit the repo link at the top, grab the STEP files and do some cool custom stuff, just be a good tile neighbour. ;)</p>

<h3>Did you notice that tiling has two types of tile?</h3>
<p>It still counts as one mathematically, but the darker blue tiles in the first image are reflected.  The ratio of normal to reflected tiles is φ<sup>4</sup> : 1 (≈ 6.854 : 1).  We have already made a good number of reflected tiles, so participants only need to print them as presented in the files.  If you get carried away and make a lot though, you could reflect (mirror) every seventh one and that’ll have us about right.  It doesn’t need to be exact because there is enough variance available to us in our non-infinite tiling.</p>

<h3>Measurements</h3>
<p>In testing on different printers with PLA and PETG, our caliper measurements were within 0.1mm of the dimensions indicated below.  Obviously this is somewhat unimportant for an aesthetic group project of this nature, but I provide it for calibration for the particular amongst us, or for peace of mind when using materials prone to difficulties with dimensional accuracy.</p><br>
<img src="https://github.com/saw2kx/aperiodicmonotile/blob/main/images/measurements.png?raw=true" alt="Frame measurements" width=500>
<br><br><br>

<h4>Attribution</h4>
<p>This project is inspired by and based on the work:</p>
<p><strong>"An Aperiodic Monotile"</strong> by David Smith, Joseph Samuel Myers, Craig S. Kaplan, and Chaim Goodman-Strauss, published in 2023.</p>
The original paper is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International (CC BY 4.0)</a>.  Proper attribution is provided here in accordance with the licence.</p>
<p>This repository, including any original designs or contributions made by the author of this project, is licensed under <a href="https://github.com/saw2kx/aperiodicmonotile/blob/main/LICENSE">CC BY-NC-SA 4.0</a>.</p>