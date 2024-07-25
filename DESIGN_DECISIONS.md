# Dev Test Fixture Design Decisions

This page aims to illustrate the design decisions behind the Dev Test Fixture. The design process started in early 2019 and has seen several iterations and improvements. This page gives background about why things are done the way they are, to help communicate with folks new to the project what has been tried, and why it was not chosen. 

## Overview

The Dev Test Fixture is a mostly laser-cut bed-of-nails test fixture. It features a hinged closing motion and a maximum working area of 196mm x 180mm. FixturFab rates the fixture to be capable of testing 1k+ units, and we have several customers have used it in production for >2k units successfully. 

## Changes

### Side Plates

Holes were added to the front/back plates to allow for optional side plates to be attached. This allows for the fixture to be completely enclosed, which is preferable when deploying to a fixture to the factory floor. 

### Pressure Plate Supports

The acrylic pressure plate would "bow" significantly in high probe count (>50) test fixtures. To counteract this bow, 3D printed Pressure Plate Supports can be added. The default pressure plate has the mounting holes for these supports, which can be added at any time to the fixture if needed. 

### Pressure Plate (Lid) Locks

The pressure plate would consistently close due to no mechanism in place to keep it open. 3D printed lid locks are added to the hinge mounting screws which can be used to keep the pressure plate open when the fixture is not in use. 

### 2 and 3 Collar Height Support 

The generic Rxxx-2x and Rxxx-3x receptacles have differing heights. To support both of these receptacles, different back plate heights are provided. Use the corresponding back plate height for the receptacle size that is used within the fixture. 

### Tall Fixture Plates

A "Tall" variant was designed to provide additional space within the test fixture base for instrumentation, wiring, etc. To use this version, replace the Front and Back Plates with the "Tall" versions