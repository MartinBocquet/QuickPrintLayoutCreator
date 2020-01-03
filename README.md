# QuickPrintLayoutCreator


It is the official page for the QGIS plugin "Quick Print Layout Creator and Exporter".

This plugin transform several layers into several print layouts. These new layouts could be exported on the same time.The particularity of the plugin is to create the print layouts from several layers.

When you wish to create multiple maps, you need, for each maps, format your layer, create your print layout, and then export it. 
This plugin helps you to do it in one step : define your layers, your template, and the plugin will generate one print layout by layers, and alows to export them.

step 1 : create, analyse and change colors of your layers
![layers](https://github.com/MartinBocquet/QuickPrintLayoutCreator/blob/master/doc/step%201%20-%203%20layers.png)

step 2 : create you template
![Template](https://github.com/MartinBocquet/QuickPrintLayoutCreator/blob/master/doc/step%202%20-%20create%20the%20template.png)

step 3 : use the plugin
![Plugin](https://github.com/MartinBocquet/QuickPrintLayoutCreator/blob/master/doc/step%203%20-%20use%20the%20plugin.png)

step 4 : you have the result : new layouts and files
![Result](https://github.com/MartinBocquet/QuickPrintLayoutCreator/blob/master/doc/step%204%20-result%20-%203%20layouts%20and%203%20files.png)

Comparaison with the existants plugins

On Qgis 3, some plugins help to export, but none of the are creating the layouts :

QuickPrint or EZPrinter https://plugins.qgis.org/plugins/ezprinter/ are exporting the map into a PDF. But they don’t create the layouts, and you can only export one layer at the time.
Maps Printer https://plugins.qgis.org/plugins/MapsPrinter/ export several existing layouts, but don’t create these layouts.
Layout Loader (https://plugins.qgis.org/plugins/layout_loader/) helps to create layout, but can only be used with some templates, not the ready-to-export layouts.
Template Loader (experimental) helps you to create a template, but don’t create the other layouts.
