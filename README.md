# dxfAssy

What this is:
DXF files are used by our nesting software to create g-Code readable by our CNC controllers.  This program is to automatically export .dxf files from an Autodesk Inventor Assembly file.  Assign the file to the correct table with parameters for each part and each different cutting process/controller.  Next, start the nesting software and autonest.

Why this is:
Previously, this process was done manually, opening each part, exporting the dxf and closing.  Then the file is imported and each object had to have parameters set in the nesting software.  This process could take up to 4 hours on large assemblies and has been automated into 2 minutes. No, seriously, 4 hours into 2 minutes.  

Notes:
This program is not interoperable with other systems.  It is specific to our production environment and nesting software.  An interface will be set up to change this.  This program has had the side effect of cutting out mistakes selecting the correct parameters in the nesting software versus pulling them from the part further improving production.

Future Update Plan:
Make the code compatible with future software upgrades.
Allow the user to select specific template files.
Standard error checking, flow control and exception checking. 
