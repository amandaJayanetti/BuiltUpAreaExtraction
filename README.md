# Built-up Area Extraction

<img src="https://github.com/amandaJayanetti/BuiltUpAreaExtraction/blob/master/Example1.png" height="300" />


A number of different methods and techniques are available for the classification of land cover using remotely sensed data. Satellite image classification basically involves grouping individual pixels into a set of spectral classes based on the spectral characteristics of pixels in various bands. These spectral classes are then matched to a set of pre-defined land cover categories. A single land cover class may be represented with one or more spectral classes. 

Identification of built-up areas with a single round of supervised classification often produces unsatisfactory outcomes due to high spectral confusion between roads and building classes. However there are distinct differences in spectral properties of water and vegetation pixels from those of building and road pixels. The built-up area extraction pipeline described in the ipython notebook in this repository was designed based on this observation and it includes two rounds of supervised classification. In the first round, road and building pixels are extracted from the rest of the image using supervised per-pixel classification. Then object based image classification is used to identify the built up areas in the image.

