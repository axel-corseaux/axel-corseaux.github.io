# Summary

[Click here to read the full technical note.](https://earth.esa.int/eogateway/documents/20142/37627/Technical+Note+on+Planimetric+Misregistration+Assessment.pdf/a2cbd7dd-61ad-6586-792f-f17d0b85eedd)

Digital Elevation Models (DEMs) are 3D representations of the terrain or surface of the Earth. These models consist of elevations on a discrete grid, usually stored in standard or custom image formats. DEMs may represent a city, a region, a country or even the whole world. Nowadays, a wide variety of DEMs are free to download and use.

Due to the increasing number of available open DEMs, researchers may want to find the best DEM to perform their own studies. One crucial step before carrying such studies is to make sure DEMs are comparable. One of the requirements is to have two superimposable DEMs in order to perform comparisons. Depending on the study areas, local shifts may be observed from one DEM to another. This study presents a novel method to quantify these shifts, applied to the comparison between EU-DEM and Copernicus DEM EEA-10, two DEMs covering Europe. The study has shown multiple types of shifts, including homogeneous displacements, or links with the land cover and the source data of the DEMs.

# My contribution

I carried-out this study, developed the tools required to process DEMs and retrieve the planimetric shifts. I also edited the entire technical note giving the methods and results of this study. All the processes have been developed in Java, using a multithreaded approach.