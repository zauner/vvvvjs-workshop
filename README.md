# Node15 VVVV.js Workshop

Hello!

## Lesson 1 - Setup and handling

Getting VVVV.js to run on a page. Starting with a template page, participants should

* add the required script include tags etc. to start VVVV.js
* create a new patch file
* launch the editor

Then, the patch editor user interface and differences to vvvv.exe can be explored. Also *saving* is explained.

Notable differences:

* Modulating Value IOBoxes
* no bangs and toggles
* ...
*

## Lesson 2 - Canvas Graphics

Based on an empty page with VVVV.js and an empty patch loaded, participants should

* create a Canvas Renderer
* draw some Canvas Shapes
* try and understand Canvas Render State nodes

## Lesson 3 - WebGL Graphics and shaders

Based on an empty page with VVVV.js and an empty patch loaded, participants should

* create a WebGL Renderer
* create a Sphere -> PhongDirectional chain
* create a Grid -> Constant chain
* load a texture from a file (should be prepared in the lesson folder)
* (maybe) define a custom shader via DefineNode
* (maybe) make some color adjustments in the custom shader
* (maybe) use Canvas Renderer output as WebGl texture input

## Lesson 4 - Embedding

Typical header graphics example: given a simple website with some lorem ipsum and a div for a header animation at the top, VVVV.js loaded and empty patch present

* give the header graphics div a suitable id
* create a Renderer
* embed the Renderer via Descriptive Name

## Lesson 5 - HTML/CSS/Event Nodes

A prepared Canvas graphics patch should be extended by the participants by adding HTML elements to control the graphics.

* use GetElement (HTML) to get the #controls div
* add a headline to the #controls div using the Element (HTML) node, and style it somehow
* add a spreaded Element (HTML) node for the labels
* add a RangeSlider (HTML) node and append it below the spreaded node
* add a GetValue (HTML) node to get the range slider values

## Lesson 6 - Loading Remote Data

David, HTTP (Network Get) + XPath + schnelle Bildergallerie? XML und Bilder sollten vorbereitet sein

## Lesson 7 - Visualising Data

Based on a website with data in an HTML table, participants should

* Get the data into the patch via HTML nodes
* draw a pie chart
* (maybe) create some interaction

## Lesson 8 - VVVV.js - to VVVV connection
*
