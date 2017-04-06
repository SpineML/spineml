# SpineML Schemas and example models

This repository contains the main SpineML schemas which govern the SpineML modelling syntax.

A number of example models are provided. Some of these have [SpineCreator](https://github.com/SpineML/SpineCreator) project files, meaning that they can be loaded and viewed in SpineCreator.

You can validate a (LowLevel) model like this:

xmllint --schema schemas/SpineMLLowLevelNetworkLayer.xsd --valid /path/to/your/model.xml

Or an experiment like this:

xmllint --schema schemas/SpineMLExperimentLayer.xsd --valid /path/to/your/experiment0.xml

Finally validate a component like this:

xmllint --schema schemas/SpineMLComponentLayer.xsd --valid /path/to/your/component.xml
