# CIGRLogger
An android app to collect camrea images, IMU data, and GPS measurements in Rinex.
Now we only submit an app which is tested with the Xiaomi Mi 8. The code will be submited later.
Our aim is to develop an app that can collect measurements with an Android smartphone. We want to make sure the collection can be solved with some standard project with as little extra processing as possible. Now the images and the IMU data have to be trasfered to bag in PC before solved with VINS-mono. The Rinex file can be solved with RTKLIB without extra pre-processing.    
our work is based on other excellent projects as follows:

1 MarsLogger by J. Z. Huai. 

https://github.com/OSUPCVLab/mobile-ar-sensor-logger/wiki 

We fully recommand you watch his work.

2 Geo++ Rinex Logger by GEO++ Ltd. 

https://play.google.com/store/apps/details?id=de.geopp.rinexlogger&hl=zh 

Although there are many apps outputing GNSS measurements, we find only GEO++ Rinex Logger can give files which can be solved with RTKLIB directly. We appreciate their job and we treat the output of GEO++ rinex logger as benchmark to modify our code. 

3 gnssdatalogger by butterflying 10

https://github.com/butterflying10/gnssdatalogger

This work provide means of outputing rinex file though the output cannot be solved with RTKLIB directly. There is also some error in the code but we still benefit much from his work.

The code will be submited later. We hope this job can be helpful for you. 

The output directory is : Android/data/pku.edu.cigrlogger/files/data/yyyy_mm_dd_hh_mm_ss
