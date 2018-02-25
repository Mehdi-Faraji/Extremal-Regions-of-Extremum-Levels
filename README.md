# Extremal Regions of Extremum Levels (EREL) Detector
**Authors:** [Mehdi Faraji]( www.ualberta.ca/~faraji ), [Jamshid Shanbehzadeh]( https://scholar.google.ca/citations?user=NIgpCKkAAAAJ&hl=en ), [Kamal Nasrollahi]( https://scholar.google.dk/citations?user=EqjkO6sAAAAJ&hl=en ), [Thomas B. Moeslund]( https://scholar.google.com/citations?user=XmkDts4AAAAJ&hl=en )

![Detected Regions](/Images/ubc13.jpg)

The following repository contains the original implementation of the EREL detector.

## Contribution.
The main contributions of EREL are:
- A new interest point called **Maxima of Gradient Magnitudes (MGMs)** is introduced. MGMs are mostly concentrated around the edges (region boundaries) 

![MGMs](/Images/mgms_all.jpg)

- Using global information of the image to select the extremal regions. The extracted regions have:

    * *High repeatability*
    
    * *High Coverage*: 
      * Extracted regions cover most part of the image
    
    * *High Adaptability*: 
      * EREL can be used in wide range of applications
      
    * Quasi-linear Time Complexity 
      * EREL can detect repeatable regions in a quasi-linear time which is very fast.
    
- *Available Implementation*: 
    * EREL has been implemented by C++, however it can be easily run in Matlab using the provided interface written in a MEX (Matlab Executable) file.
    
    

### If you use this code please cite the following publications:
**[1]** Faraji, Mehdi, et al. "Extremal regions detection guided by maxima of gradient magnitude." IEEE Transactions on Image Processing 24.12 (2015): 5401-5415. [pdf]( http://vbn.aau.dk/ws/files/219488957/tip_preprint.pdf)

**[2]** Faraji, Mehdi, et al. "Erel: extremal regions of extremum levels." Image Processing (ICIP), 2015 IEEE International Conference on. IEEE, 2015. [pdf]( https://www.researchgate.net/profile/Jamshid_Shanbezadeh/publication/281681367_Extremal_Regions_Detection_Guided_by_Maxima_of_Gradient_Magnitude/links/5795759808aed51475dc7020/Extremal-Regions-Detection-Guided-by-Maxima-of-Gradient-Magnitude.pdf )

 
