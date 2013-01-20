Cura Profiles
====

These are profiles for Cura.  They are known to work with Cura 12.12+.

The profiles with filenames in the form of "Cura [[PRINT TYPE]] [MATERIAL]] Profile.ini" are the equivalents of the Quickprint mode with the corresponding options set.

Depending on your requirements, you need to make the following changes after loading them:

* Set "Filament Diameter'" to match your actual filament diameter.  These profile files use the Cura default of "2.89".
* Set "Support Structure" to your preference.  When you specify "Print support structure" in Quickprint, it uses the equivalent value of "Exterior only".
* Set "Nozzle size" to your actual nozzle size.  These profile files use the Cura default of 0.4.  If you change the nozzle size, you should also change the "Wall thickness" as follows to match the Quickprint settings:
   -  For print type of "Normal Quality", set "Wall thickness" to 2 times your nozzles size
   - For print type of "Fast-Low Quality", set "Wall thickness" to 1.4 times your nozzles size
   - For print type of "High Quality", set "Wall thickness" to 2 times your nozzles size
   - For print type of "Thin Walled", set "Wall thickness" to 1.5 times your nozzles size

Also note that the "Full settings" mode of Cura now has "Enable retraction" set by default.  You may want to consider setting retraction in these profile files as well.


