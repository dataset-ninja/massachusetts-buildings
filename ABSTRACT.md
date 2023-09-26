**The Massachusetts Buildings** Dataset consists of 151 aerial images of the Boston area, with each of the images being 1500 × 1500 pixels for an area of 2.25 square kilometers. Hence, the entire dataset covers roughly roughly 340 square kilometers.Authors randomly split the data into a *train* set of 137 images, a *test* set of 10 images and a *val* set of 4 images. The target maps were obtained by rasterizing building footprints obtained from the OpenStreetMap project. Unlike the GTA Buildings dataset we have used throughout the thesis, this data was restricted to regions with an average omission noise level of roughly 5% or less. It was possible to collect such a large a mount of high quality building footprint data because the City of Boston has contributed building footprints for the entire city to the OpenStreetMap project. The dataset covers mostly urban and suburban areas and buildings of all sizes, including individual houses and garages, are included in the labels. Figures(a) and (b) show two representative regions from the Massachusetts Buildings dataset.

![Fig](https://i.ibb.co/98g38QJ/Screenshot-2023-09-25-133450.png)
 
 <i>Figures (a) and (b) show two representative regions from the Massachusetts Buildings dataset. Figures (c) and (d) show predictions of a postprocessing network on these regions. Green pixels are true positives, red pixels are false positives, blue pixels are false negatives, and background pixels are true negatives.</i>
