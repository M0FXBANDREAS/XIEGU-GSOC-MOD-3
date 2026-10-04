M0FXB HamTech GSOC MOD — V1.4beta TX06 — BLACK DASHBOARD

WHAT CHANGED
- Targeted the frame_vfoBack style behind the large frequency display and S/Power/SWR meter area shown in your photo.
- Changed that dashboard background from RGB(120,120,110) grey to jet black RGB(0,0,0).
- The separate RIT/button grey style is deliberately retained.
- TX04 bold-waterfall renderer and TX03 waterfall palette are retained.
- PTT, ATU, tuning, G90 V1.81 compatibility, FFT data and span logic are unchanged.
- 200 kHz span is NOT added in TX06.

WINDOWS INSTALLATION
1. Keep your working TX05/TX04/TX03 card as backup.
2. Extract this ZIP.
3. In Rufus select a SPARE microSD and the included TX06 .img file.
4. Write in DD mode if Rufus asks. Writing erases the selected card.
5. Ignore/cancel Windows requests to format Linux partitions.
6. Safely eject, power GSOC OFF, insert TX06 card and boot.

FIRST TEST
- Check the large area behind the frequency digits and signal/power/SWR meters is now black.
- Check text, meter scales, RX indicator and VFO/mode buttons remain readable.
- Check waterfall, tuning and RX normally.
- Test PTT/ATU only after RX is verified, using a dummy load/safe antenna setup.

STATUS
The exact frame style was located next to the frame_vfoBack identifier and patched without globally replacing grey UI colours. Binary and raw-image patch checks passed. TX06 has not been tested on physical GSOC hardware here.
