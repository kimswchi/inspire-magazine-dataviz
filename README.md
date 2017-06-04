# Inspire Illuminated: An Interactive Visualization of a Terrorist Magazine

This project visualizes various aspects of *Inspire*, an online English-language magazine produced by al-Qaeda affiliate al-Qaeda in the Arabian Peninsula.

The current version of the visualization is hosted [here](https://kimswchi.github.io/inspire-magazine-dataviz/).

The packages used for the project are listed in `package_versions.md`.

### Note on reproducibility
Using R v3.4.0 the graphs may not render correctly in HTML format. Specifically, the spacing around plotly figures may be larger than specified in the R code. If this is the case, check the source code for the rendered HTML and make sure the image size is specified correctly for the figures. If not, edit manually and save over the old HTML file.

For example, change this

`<div id="3a44e9b7042" style="width:1000px;height:900px;" class="plotly html-widget"></div>`

to

`<div id="3a44e9b7042" style="width:700px;height:432px;" class="plotly html-widget"></div>`
