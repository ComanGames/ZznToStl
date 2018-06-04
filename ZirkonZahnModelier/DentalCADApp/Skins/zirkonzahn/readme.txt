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

Brushes
--------------------------------------------------------------------------------
This folder contains all color and brushes used by the controls, e.g. SolidColor
Brushes, Gradient Breushes, Drawing Brushes, etc.

CustomControlStyles
--------------------------------------------------------------------------------
This folder contains all styles for CustomControls. These are subclasses controls
that have a Style/Template that defines the loook and feel. For example the 
ContentAndTextButton.

Named Styles
--------------------------------------------------------------------------------
This folder contains all named style (i.e. the ones with a x:Key). These styles
are used when we can't rely on the default style of the conrol, even when we
have created that default style. An example is the a help button which needs
round corners or specialy styled buttons for a toolbar.

