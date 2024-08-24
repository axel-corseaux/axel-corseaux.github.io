# Summary

[Click here to get to the interactive ICESat2 presentation.](https://visioterra.fr/telechargement/A003_VISIOTERRA_COMMUNICATION/HYP-087-VtWeb-E_Presentation_of_ICESat-2_ATLAS.pdf)

VtWeb is a web platform developed by VisioTerra. This platform allows to process and visualize Earth observation products, such as optical or radar data, Digital Elevation Models (DEMs), or altimetry data. To do so, VtWeb relies on "modules", which are independent services developed to process one particular dataset.

In this framework, modules have been developed to access and process data from the ICESat-1, ICESat-2 and GEDI spaceborne altimeters. Through VtWeb, users may request the preparation of data from these missions and display 3D elevation profiles from the altimeters acquisitions.

The acquisitions of these three altimeters are featured in two "hyperlook" documents given above. These "hyperlook" documents feature views of the acquisitions, and \"hyperlooks\", which are links heading to interactive views on the VtWeb platform.

# My contribution

Based on an existing architecture, I developed both ICESat-1 and GEDI modules. I also helped for the implementation of the ICESat-2 module. These modules are written in Java J2EE, using servlets for handling users requests.