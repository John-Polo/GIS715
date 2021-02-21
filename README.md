# GIS715
#GeoViz


<body>
  <div class='tableauPlaceholder' id='viz1613165632478' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;El&#47;ElectionResults2016WinnerbyCounty&#47;Story1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ElectionResults2016WinnerbyCounty&#47;Story1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;El&#47;ElectionResults2016WinnerbyCounty&#47;Story1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                
</body>
</html>

<hr>
<hr>
This is the Tableau homework.

<div class='tableauPlaceholder' id='viz1613339901088' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ho&#47;Homework2_16133390334720&#47;Lateblight2018&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Homework2_16133390334720&#47;Lateblight2018' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ho&#47;Homework2_16133390334720&#47;Lateblight2018&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                

<hr>
<hr>
<img src='https://user-images.githubusercontent.com/68556651/108634995-b059a900-744a-11eb-848c-959f78bb342c.jpg'>
Styling Maps with QGIS (part 1): Neon.
The data were raster and vector layers for airports. To get this effect, start by clicking on the brush icon on the left side of the QGIS above the Layer table of contents (T.O.C.). That will open a Layer Styling (L.S.) window, which appears on the right in the image above. In the top of L.S., make sure that Airports is the active layer and 
In the L.S. window, scroll to bottom and expand the Layer Rendering (L.R.) section. Check the draw effect attribute and click on the star icon that becomes active. Then follow these steps:
Airports layer
  Change Fill color of Airports to 255/0/254
   Change Stroke width to 0.2
  Change Size of Airports to 10
  Apply Drop Shadow
Flight paths layer
  Change Color to 255/0/254
  Change Stroke width to 1.26
  Apply Outer Glow
  Spread 5
  Blur 3
  Color ramp  Create New Color Ramp
  Gradient
  Color 1 – 255 | 0 | 254
  Color 2 – 0| 0| 0
  Continuous
  Play with Opacity
  Add another symbol layer
  Add a second Simple line to the symbol    
  Make sure it is above the previous symbol
  Give it a lighter pink Color (255 | 185 | 255)
  Give it a Stroke width of 0.46



<img src='https://user-images.githubusercontent.com/68556651/108635112-74731380-744b-11eb-878e-131210e32bbd.jpg'>
Styling Maps with QGIS (part 1): Neon.
The data were raster and vector layers for airports. To get this effect, start by clicking on the brush icon on the left side of the QGIS above the Layer table of contents (T.O.C.). That will open a Layer Styling (L.S.) window, which appears on the right in the image above. In the top of L.S., make sure that Airports is the active layer and in the L.S. window, scroll to bottom and expand the Layer Rendering (L.R.) section. Check the draw effect attribute and click on the star icon that becomes active. Then follow these steps:
Airports layer
  Change Fill color of Airports to 255/0/254
   Change Stroke width to 0.2
  Change Size of Airports to 10
  Apply Drop Shadow
Flight paths layer
  Change Color to 255/0/254
  Change Stroke width to 1.26
  Apply Outer Glow
  Spread 5
  Blur 3
  Color ramp  Create New Color Ramp
  Gradient
  Color 1 – 255 | 0 | 254
  Color 2 – 0| 0| 0
  Continuous
  Play with Opacity
  Add another symbol layer
  Add a second Simple line to the symbol    
  Make sure it is above the previous symbol
  Give it a lighter pink Color (255 | 185 | 255)
  Give it a Stroke width of 0.46


<img src='https://user-images.githubusercontent.com/68556651/108635177-f8c59680-744b-11eb-9002-8b1dad77ac87.jpg'>
Styling Maps with QGIS (part 1): blending.
The data were raster and vector layers for world-wide bathymetry. To get this effect, start by clicking on the brush icon on the left side of the QGIS above the Layer table of contents (T.O.C.). That will open a Layer Styling (L.S.) window, which appears on the right in the image above. In the top of L.S., make sure that the appropriate layer is the active layer and in the L.S. window, scroll to bottom and expand the Layer Rendering (L.R.) section. Check the draw effect attribute and click on the star icon that becomes active. Repeat on each ne_10m_bathymetry_* layers: set the layer blending mode of the land layer to “Multiply”.


<img src='https://user-images.githubusercontent.com/68556651/108635223-5823a680-744c-11eb-8380-fd4eae9857d1.jpg'>
Styling Maps with QGIS (part 2): Jemez_1.
The data were raster and vector layers for world-wide bathymetry. To get this effect, start by clicking on the brush icon on the left side of the QGIS above the Layer table of contents (T.O.C.). That will open a Layer Styling (L.S.) window, which appears on the right in the image above. In the top of L.S., make sure the appropriate layer is active and in the L.S. window, scroll to bottom and expand the Layer Rendering (L.R.) section:
Change the rendering of the DEM:
  Change Singleband gray to Hillshade.
  Change the layer blending mode of a polygon layer to “Multiply”:
    Turn on the Land ownership layer. 
    Make sure that the Land Ownership layer is the focus layer in the Layer Styling panel.
    Expand the Layer Rendering section of the Layer Styling panel.
    Locate the Blending mode.
    Select “Multiply” under “Layer” (Ignore Menke.  He says Feature but means Layer).
Add boundaries to the scene in a harmonious way:
    Turn on the PLSS Townships layer
    Make sure that the PLSS Township layer is the focus layer in the Layer Styling panel.
    Select “Simple Fill”, just under Fill.
    Increase the stroke width to 0.66.
    Expand the Layer Rendering section of the Layer Styling panel.
    For the Blending mode, select “Overlay” under “Layer”.
Explore the use of blending modes in Layout view
    Click Project > Layouts > Blending Modes (a preconfigured layout for this project)    
    Select the “made with QGIS” symbol
    Select Item Properties 
    Expand the Rendering section
    Change the Blending mode to Multiply.




<img src='https://user-images.githubusercontent.com/68556651/108635253-80aba080-744c-11eb-8c50-1b4b271e75d0.jpg'>

<img src='https://user-images.githubusercontent.com/68556651/108635283-ac2e8b00-744c-11eb-8521-d0f597b54533.jpg'>

