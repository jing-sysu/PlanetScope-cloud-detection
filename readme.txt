;---------------------------------------------------------------------------------------------------------------------------------
;           STI-ACSS algorithm for cloud and cloud shadow detection in PlanetScope time-series images
;           Developed by Jing Wang, email: w1012j@163.com
;           Division for Ecology and Biodiversity, School of Biological Sciences, University of Hong Kong                 
;           update date:  2021-07-20
;           Copyright belong to Jing Wang
;
; Please cite the reference:
;           Jing Wang, Dedi Yang, Shuli Chen, Xiaolin Zhu, Shengbiao Wu, Marc Bogonovich, Zhengfei Guo, Zhe Zhu, Jin Wu*,
;           "Automatic cloud and cloud shadow detection in tropical areas for PlanetScope satellite images", 
;           Remote sensing of Enviroment, Volume 264, 2021, 112604, ISSN 0034-4257, https://doi.org/10.1016/j.rse.2021.112604. Accepted in 11/07/2021
;
; If you have any problem in running this code, please feel free to contact w1012j@163.com
; We also welcome any suggestions/comments about this algorithom/code.
;---------------------------------------------------------------------------------------------------------------------------------
This code is written by Matlab

The main function is 'autoSTIACSS.m'

The exampledata includes a time-series images (21 images, 10km*10km (3334*3334*4 pixels) per image) in a Mulga woodland in Alice Springs, Australia in 2019. 

Example data in Dropbox:https://www.dropbox.com/sh/veszf5lukz6x61k/AACMEZ1LWdjNopL7rvp3iovha?dl=0

More details are shown in the 'autoSTIACSS.m'
