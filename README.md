This is tested and working on my SV04 running the stock build of Marlin FW that shipped with the mainboard. It should also work with klipper depending on how you have your macros set up.



Make sure to disable filament ramming under: Printer settings > Multimaterial.


Copy and paste start and end gCodes into the respective sections in Orcaslicer:

Printer settings > machine start G-code.

Printer settings > machine end G-code.

Printer settings > before layer change G-code.


-------------------------------------------------------------


There is a file for each toolhead containing the respective start and end gcodes for each.


------------------------------------------------------------

I have also included the Orcaslicer profiles themselves which you should be able to simply import via the file dropdown menu at the top left corner of Orcaslicer.