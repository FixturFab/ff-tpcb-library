# FixturFab TPCB Library 

This repository contains the FixturFab TPCB KiCad Library. This includes the footprints and symbols for receptacles that are used within both the Development and Production Test Fixtures that are designed and manufactured by FixturFab. 

**NOTE: This repository is a work in progress, please create issues to help us improve it.**

## Development Test Fixture Receptacles 

Generic receptacles are used for all Development Test Fixtures. Select any receptacle starting with a "R". 

## Production Test Fixture Receptacles

FixturFab highly recommends using only wireless receptacles in production test systems. This makes it very easy to replace a damaged TPCB. This footprint is labeled "KS-WL". 

All Ingun receptacles start with a "KS". 

## Footprint Libraries

- FF_GuidePins.pretty
  - Guide pin footprints
  - Used for cutouts in TPCB to ensure the TPCB won't interfere with Spring Guide Pins
- FF_Receptacles.pretty
  - Standard receptacle footprints
  - KS-* symbols correspond to an Ingun receptacle 
  - R* footprints correspond to a Generic or Centalic receptacle
  
## Symbol Libraries

- FF_GuidePins.kicad_sym
  - Guide Pin Symbols
- FF_Receptacles.kicad_sym
  - Receptacle Symbols