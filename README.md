# Kudos Rack Panel Designer

Browser tool for laying out 19" and 10" rack panels and sending them to panel makers.

**Live:** https://nealkudos.github.io/rack-panel-designer/

- 75 connector cutouts: Neutrik D-size family, speakON, powerCON, IEC, CEE, Socapex, Harting, D-sub, VEAM Powerlock and CIR, switches, LEDs, fans and vents
- Custom parts and uploaded logos (SVG, PNG or JPG — engraved as vectors)
- Device shelf builder: add device boxes (W × H × D), cut front windows, tray shelf with strap and vent slots, shelf DXF + PDF sheet
- Exports: DXF (OUTLINE / CUT / ENGRAVE layers), dimensioned A3 PDF drawing with cutout schedule, SVG, and a zipped fabrication pack
- Projects save in the browser and can be saved/opened as `.rackpanel.json`

All positions are hole centres in mm from the panel's bottom-left corner, viewed from the front.
Parts marked **Verify** use cutouts from secondary sources — check them against the maker's drawing before cutting.

Single file, no build step: `index.html`.
