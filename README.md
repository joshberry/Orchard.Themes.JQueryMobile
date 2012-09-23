jQuery Mobile theme for Orchard CMS
===================================

Overview
--------
The theme provides [jQuery mobile](http://jquerymobile.com) support for Orchard CMS, implementing the required css, scripts and page structure.

Setup
-----
1. Download and install the theme from the [Orchard theme gallery](http://gallery.orchardproject.net).
2. Optional - Change the jQuery mobile theme swatch. 
     To do this, open the Layout.cshtml file in the theme's views directory and update the following line to one of the 5 default theme swatches (a, b, c, d, e).
     
     ```csharp
     // set jqm swatch (a, b, c, d or e)
     Model.Attributes.Add("data-theme", "d");
     ```


