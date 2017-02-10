# dxfAssy

What this is:
DXF files are used by our nesting software to create g-Code readable by our CNC controllers.  This program is to automatically export .dxf files from an Autodesk Inventor Assembly file.  Assign the file to the correct table for each different cutting process/controller.  Start the nesting software and autonest.

Why this is:
Previously, this process was done manually, opening each part, exporting the dxf and closing.  This process could take up to 2 hours on large assemblies and has been automated into 2 minutes.

Notes:
This program is not interoperable with other systems.  It is specific to our production environment and nesting software.  An interface will be set up to change this.

Future Update Plan:
Make the code compatible with future software upgrades.
Allow the user to select specific template files.
Standard error checking, flow control and exception checking. 
