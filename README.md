Graublau Icon Theme for the GIMP
=================================
![Graublau Icon Theme](https://github.com/kstenschke/graublau-gimp-theme/blob/master/screenshot.png?raw=true)

Authors & License
-----------------
Created in 2013-2014 by Kay Stenschke

Licensed under the GNU GENERAL PUBLIC LICENSE, Version 2.

The icons used in this theme are based on icons from multiple different open source icon sets.
Most of the icons have been altered in some ways to create an overall harmonic theme.


| Icon Set                 |       Author          | Website                                    | License
| ------------------------ | --------------------- | ------------------------------------------ | -------------------------------------------------
| 48px web iconset         | Emey87                | http://emey87.deviantart.com/              | http://creativecommons.org/licenses/by-nd/3.0/
| Basic Set                | Pixel Mixer           | http://www.pixel-mixer.com/                | Free for commercial use
| Bijou                    | Visual Idiot          | http://visualidiot.com                     | WTFPL
| Centigrade MedicalSeries | Centrigade            | http://www.centigrade.de/                  | http://creativecommons.org/licenses/by/3.0/us/
| Crystal Project          | Everaldo Coelho       | http://www.everaldo.com/                   | http://www.gnu.org/copyleft/lesser.html
| Diagona Icons            | Yusuke Kamiyamane     | http://p.yusukekamiyamane.com/             | http://creativecommons.org/licenses/by/3.0/
| Discovery                | Hbons                 | http://hbons.deviantart.com                | http://creativecommons.org/licenses/by-sa/3.0/
| Essen, Bremen, Stuttgart | PC.de                 | http://www.pc.de                           | http://creativecommons.org/licenses/by/3.0/
| Farm-fresh               | FatCow Web Hosting    | http://www.fatcow.com/                     | http://creativecommons.org/licenses/by/3.0/us/
| Fugue Icons              | P. Yusukekamiyamane   | http://p.yusukekamiyamane.com/             | http://creativecommons.org/licenses/by/3.0/
| Humanity Icons           | Various               | https://launchpad.net/humanity             | http://www.gnu.org/licenses/gpl-2.0.html
| Iconic                   | P.J. Onori            | http://somerandomdude.com/work/iconic/     | http://creativecommons.org/licenses/by-sa/3.0/us/
| Momentum Glossy Icons    | Momentum Design Lab   | http://momentumdesignlab.com/              | http://creativecommons.org/licenses/by-sa/3.0/
| Nuvola                   | David Vignoni         | http://www.icon-king.com/                  | http://www.gnu.org/licenses/lgpl.html
| Silk                     | Marc James            | http://www.famfamfam.com/about/            | http://creativecommons.org/licenses/by/2.5/
| Tango Icons              | Tango Desktop Project | http://tango.freedesktop.org/              | http://www.gnu.org/copyleft/gpl.html
| Ultimate Gnome           | New Moon              | http://code.google.com/p/ultimate-gnome/   | http://www.gnu.org/licenses/old-licenses/gpl-2.0.html
| WooFunction Icon Set     | Liam McKay            | http://wefunction.com/                     | Free for commercial use 

Flavors
-------
There are two flavors: 

1. The "Graublau basic" flavor, which is mainly an icon theme, containing only little modifications of GTK styling.
2. The "Graublau OSX" flavor, which additionally to the icons also implements some GUI styles (buttons, scrollbars, etc.) adaptings the Gimp's look more to Mac OSX.


Installation
------------
1. Copy the Graublau (and/or Graublau-OSX) folder into the \Themes\ folder of your GIMP 2.8 installation.
2. Start the GIMP and activate the theme by selecting it via: Edit > Preferences > Theme 
3. Restart GIMP for the theme to be activated

Theme Path by OS:
-----------------
* Linux:   (Run GIMP at least once to have the preference directory created, and than) Copy the theme into the (hidden) directory: \Home\\.GIMP\\.theme
* Windows: Copy the theme into: C: > Users > YOUR_USER_NAME > .gimp-2.8 > themes.
* Mac OS X using Finder: Open contents of GIMP application package. Navigato to: Contents > Resources > share > gimp > 2.0 > themes. Paste Graublau theme folder here.


Icon Variants and Modifications
-------------------------------
For most icons in this theme, there's a colored "active", and an "inactive" version which has been 
reduced to grayscale and opacity between 70% and 80%.

To achieve optimal "crisp" icons with intact elements such as outlines, gradients, shadows, etc,
down-scaling is done manually and not calculational. None of the icons has been scaled up.

To achieve an overall harmonic look, several icons have been adapted in some ways:
* Size and colors (main non-grey color is blueish now in all icons) adjusted
* Removed or replaced sub elements (arrows, shadows, etc.)
* Corrected contrast and brightness
* Added shadows


Icons Source Reference
----------------------
Icons from the original GIMP iconset that are used unchanged or with little adaptions to fit the 
theme are not listed in the following reference.

###General Purpose Icons

| GIMP Filename                | Icon Set           | Name                    | Icon |
| ---------------------------- | ------------------ | ----------------------- | ---- |
| stock-anchor                 | Bijou              | anchor                  | ![anchor](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-anchor-16.png?raw=true) |
| stock-channels               | Farm Fresh         | layer_rgb               | ![channels](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-channels-c16.png?raw=true) |
| stock-color-pick-from-screen | Ultimate Gnome     | computer                | ![colorfromscreen](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-color-pick-from-screen-c16.png?raw=true) |
| stock-duplicate              | Silk               | page_white_copy         | ![duplicate](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-duplicate-16.png?raw=true) | 
| stock-dynamics               | Crystal Project    | move                    | ![channels](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-dynamics-c16.png?raw=true) |
| stock-edit                   | Humanity Icons     | stock_edit              | ![edit](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-edit-c16.png?raw=true) |
| stock-eye                    | Farm-fresh         | eye                     | ![eye](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-eye-16.png?raw=true) |
| stock-image                  | 48px web iconset   | picture                 | ![picture](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-image-48.png?raw=true) |
| stock-navigation             | Crystal Project    | move                    | ![navigation](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-navigation-c16.png?raw=true) |
| stock-reset                  | Humanity Icons     | reload                  | ![reset](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-reset-c16.png?raw=true) |


###Tool Icons

| GIMP Filename                   | Icon Set                      | Name                           | Icon |
| ------------------------------- | ----------------------------- | ------------------------------ | ---- |
| stock-tool-align                | Crystal Project               | stock_graphics-align-centered  | ![align](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-align-c16.png?raw=true) | 
| stock-tool-blend                | Crystal Project               | gradient                       | ![blend](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-blend-c16.png?raw=true) | 
| stock-tool-blur                 | Fugue Icons                   | water                          | ![blur](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-blur-c16.png?raw=true) | 
| stock-tool-bucket-fill          | Momentum Glossy               | paintbucket                    | ![bucketfill](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-bucket-fill-c16.png?raw=true) | 
| stock-tool-clone                | Fugue Icons                   | stamp                          | ![clone](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-clone-c16.png?raw=true) | 
| stock-tool-color-picker         | Momentum Glossy               | eyedropper                     | ![colorpicker](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-color-picker-c16.png?raw=true) | 
| stock-tool-crop                 | Momentum Glossy               | exact-o                        | ![crop](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-crop-c16.png?raw=true) | 
| stock-tool-dodge                | Fugue Icons                   | fire                           | ![dodge](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-dodge-c16.png?raw=true) |
| stock-tool-ellipse-select       | Farm Fresh                    | select                         | ![ellipseselect](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-ellipse-select-c16.png?raw=true) | 
| stock-tool-eraser               | Farm Fresh                    | draw_erasor                    | ![eraser](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-eraser-c16.png?raw=true) | 
| stock-tool-flip                 | Farm Fresh                    | shape_flip_horizontal          | ![flip](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-flip-c16.png?raw=true) | 
| stock-tool-foreground-select    | none (created for this theme) | none (created for this theme)  | ![fgselect](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-foreground-select-c16.png?raw=true) | 
| stock-tool-free-select          | Farm Fresh                    | select_lasso                   | ![freeselect](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-free-select-c16.png?raw=true) | 
| stock-tool-fuzzy-select         | Farm Fresh                    | magic_wand                     | ![fuzzyselect](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-fuzzy-select-c16.png?raw=true) | 
| stock-tool-heal                 | Centigrade MedicalSeries      | bandaid                        | ![heal](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-heal-c16.png?raw=true) | 
| stock-tool-ink                  | Crystal Project               | stock_insert-fields-author     | ![ink](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-ink-c16.png?raw=true) | 
| stock-tool-iscissors            | Momentum Glossy               | cut                            | ![scissors](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-iscissors-c16.png?raw=true) | 
| stock-tool-move                 | Farm Fresh                    | hand-tool                      | ![move](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-move-c16.png?raw=true) | 
| stock-tool-options              | Batch                         | mixer                          | ![options](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-options-c16.png?raw=true) | 
| stock-tool-paintbrush           | Momentum Glossy               | paintbrush                     | ![paintbrush](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-paintbrush-c16.png?raw=true) | 
| stock-tool-path                 | Farm Fresh                    | vector                         | ![path](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-path-c16.png?raw=true) | 
| stock-tool-pencil               | Momentum Glossy               | pencil                         | ![pencil](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-pencil-c16.png?raw=true) | 
| stock-tool-perspective          | Farm Fresh                    | transform_perspective          | ![perspective](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-perspective-c16.png?raw=true) | 
| stock-tool-rect-select          | Farm Fresh                    | select                         | ![rectselect](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-rect-select-c16.png?raw=true) | 
| stock-tool-reset                | Tango Icons                   | go-jump                        | ![reset](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/stock-reset-c16.png?raw=true) | 
| stock-tool-rotate               | Farm Fresh                    | transform_rotate               | ![rotate](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-rotate-c16.png?raw=true) | 
| stock-tool-scale                | Farm Fresh                    | transform_scale                | ![scale](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-scale-c16.png?raw=true) | 
| stock-tool-shear                | Farm Fresh                    | transform_shear                | ![shear](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-shear-c16.png?raw=true) | 
| stock-tool-smudge               | Farm Fresh                    | draw_smudge                    | ![smudge](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-smudge-c16.png?raw=true) | 
| stock-tool-text                 | Momentum Glossy               | text-font                      | ![text](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-text-c16.png?raw=true) | 
| stock-tool-zoom                 | Momentum Glossy               | search                         | ![zoom](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/tools/stock-tool-zoom-c16.png?raw=true) | 


###GTK Icons

| Gimp Filename          | Icon Set               | Name                        | Icon |
| ---------------------- | ---------------------- | --------------------------- | ---- |
| gtk-cancel             | Momenticons            | cancel                      | ![cancel](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-cancel.png?raw=true) |
| gtk-delete             | Momenticons            | delete                      | ![delete](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-delete.png?raw=true) |
| gtk-directory          | Essen                  | folder                      | ![directory](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-directory.png?raw=true) |
| gtk-edit               | Bremen                 | edit                        | ![directory](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-edit.png?raw=true) |
| gtk-go-down            | Basic Set2             | arrow_down                  | ![godown](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-go-down.png?raw=true) |
| gtk-go-up              | Basic Set2             | arrow_up                    | ![goup](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-go-up.png?raw=true) |
| gtk-new                | WooFunction            | add                         | ![new](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-new.png?raw=true) |
| gtk-open               | Nuvola                 | folder_open                 | ![new](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-open.png?raw=true) |
| gtk-redo               | Discovery              | edit-redo                   | ![redo](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-redo.png?raw=true) |
| gtk-refresh            | Momentics              | refresh1                    | ![refresh](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-refresh.png?raw=true) |
| gtk-save               | Farm Fresh             | save                        | ![save](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-save.png?raw=true) |
| gtk-save-as            | Farm Fresh             | save-as                     | ![save-as](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-save-as.png?raw=true) |
| gtk-undo               | Discovery              | edit-undo                   | ![undo](https://github.com/kstenschke/graublau-gimp-theme/blob/master/Graublau/images/gtk/stock-undo.png?raw=true) |

