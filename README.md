# Door-And-Window-Detection-Dataset

The dataset includes 1000 labelled Google Street View images for building façade elements detection. 

Doors and windows are labelled in each image based on the YOLO format.

The dataset are splitted as train, validatioan, and test.

The dataset can be downloaded from following link:



If you use the dataset, please cite these publications:

@Article{isprs-archives-XLIII-B4-2022-315-2022,
AUTHOR = {Sezen, G. and Cakir, M. and Atik, M. E. and Duran, Z.},
TITLE = {DEEP LEARNING-BASED DOOR AND WINDOW DETECTION FROM BUILDING FAÇADE},
JOURNAL = {The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences},
VOLUME = {XLIII-B4-2022},
YEAR = {2022},
PAGES = {315--320},
URL = {https://isprs-archives.copernicus.org/articles/XLIII-B4-2022/315/2022/},
DOI = {10.5194/isprs-archives-XLIII-B4-2022-315-2022}
}

@Article{su15118979,
AUTHOR = {Isiler, Mehmet and Yanalak, Mustafa and Atik, Muhammed Enes and Atik, Saziye Ozge and Duran, Zaide},
TITLE = {A Semi-Automated Two-Step Building Stock Monitoring Methodology for Supporting Immediate Solutions in Urban Issues},
JOURNAL = {Sustainability},
VOLUME = {15},
YEAR = {2023},
NUMBER = {11},
ARTICLE-NUMBER = {8979},
URL = {https://www.mdpi.com/2071-1050/15/11/8979},
ISSN = {2071-1050},
ABSTRACT = {The Sustainable Development Goals (SDGs) have addressed environmental and social issues in cities, such as insecure land tenure, climate change, and vulnerability to natural disasters. SDGs have motivated authorities to adopt urban land policies that support the quality and safety of urban life. Reliable, accurate, and up-to-date building information should be provided to develop effective land policies to solve the challenges of urbanization. Creating comprehensive and effective systems for land management in urban areas requires a significant long-term effort. However, some procedures should be undertaken immediately to mitigate the potential negative impacts of urban problems on human life. In developing countries, public records may not reflect the current status of buildings. Thus, implementing an automated and rapid building monitoring system using the potential of high-spatial-resolution satellite images and street views may be ideal for urban areas. This study proposed a two-step automated building stock monitoring mechanism. Our proposed method can identify critical building features, such as the building footprint and the number of floors. In the first step, buildings were automatically detected by using the object-based image analysis (OBIA) method on high-resolution spatial satellite images. In the second step, vertical images of the buildings were collected. Then, the number of the building floors was determined automatically using Google Street View Images (GSVI) via the YOLOv5 algorithm and the kernel density estimation method. The first step of the experiment was applied to the high-resolution images of the Pleiades satellite, which covers three different urban areas in Istanbul. The average accuracy metrics of the OBIA experiment for Area 1, Area 2, and Area 3 were 92.74%, 92.23%, and 92.92%, respectively. The second step of the experiment was applied to the image dataset containing the GSVIs of several buildings in different Istanbul streets. The perspective effect, the presence of more than one building in the photograph, some obstacles around the buildings, and different window sizes caused errors in the floor estimations. For this reason, the operator&rsquo;s manual interpretation when obtaining SVIs increases the floor estimation accuracy. The proposed algorithm estimates the number of floors at a rate of 79.2% accuracy for the SVIs collected by operator interpretation. Consequently, our methodology can easily be used to monitor and document the critical features of the existing buildings. This approach can support an immediate emergency action plan to reduce the possible losses caused by urban problems. In addition, this method can be utilized to analyze the previous conditions after damage or losses occur.},
DOI = {10.3390/su15118979}
}
