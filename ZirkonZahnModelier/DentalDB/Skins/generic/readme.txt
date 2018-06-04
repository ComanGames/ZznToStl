BinarySkin.sln / BinarySkin.csproj
-------------------------------------------------------------------------------
To improve start-up time of the application the skin files (*.xaml) can be 
pre-compiled using the BinarySkin Solution. The BinarySkin Solution automatically
compiles all .xaml files inside its root and child directories. There is no need
to add files to the solution by hand.



Folder Structure:
================================================================================

BaseControlStyles
--------------------------------------------------------------------------------
This folder contains the unnamed styles that are picked up by default for the
controls contained within the WPF libraries (Button, ComboBox, RadioButton, etc...)
ATTENTION: this is a shared part of DentalCAD and DentalDB. If you change here 
something, the changes will be applied for both of them.

Brushes
--------------------------------------------------------------------------------
This folder contains all color and brushes used by the controls, e.g. SolidColor
Brushes, Gradient Breushes, Drawing Brushes, etc.
ATTENTION: this is a shared part of DentalCAD and DentalDB. If you change here 
something, the changes will be applied for both of them.

DentalDBStyles
--------------------------------------------------------------------------------
This folder contains all styles used in DentalDB only. If you want to change the
style of DentalDB, do it here.

DentalDBBrushes
--------------------------------------------------------------------------------
This folder contains all color and brushes used by the controls, e.g. SolidColor
Brushes, Gradient Breushes, Drawing Brushes, etc used in DentalDB only. If you 
want to change a brush, font etc. of DentalDB, do it here.

