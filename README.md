# ETRI-LIVE STSVQ Database
ETRI-LIVE Space-Time Subsampled Video Quality (STSVQ) Database contains 437 videos generated by applying various levels of combined space-time subsampling and video compression on 15 diverse video contents. In this page, we provide a guide on how to obtain the videos and their respective subjective opinion scores. For detailed information, please visit the ETRI-LIVE database [website](https://live.ece.utexas.edu/research/ETRI-LIVE_STSVQ/index.html).

## Downloading the videos
To download the videos, please visit [this link](https://utexas.box.com/s/9rku1m3pwi96m7pls3q0j82sacvji9lx) where you can access the download scripts and videos.
* The database consist of 15 original videos and 437 distorted videos. 
* All videos are provided in raw YUV file format at 3840x2160, 60/120Hz, and 10 bit. 
* For downloading the entire database, please ensure at least 4.5 TB space available.

### Windows users
* You need to have cURL set up to use the download script. If you have Windows 10 version of 1803 or later, cURL is installed by default. If using an older Windows version, download cURL for Windows [here.](https://curl.haxx.se/download.html)  
* Set a directory where you will store the 15 original videos (~151 GB). Place the following script and the inside the folder and run. 
	```
	download_original.bat
	```
* Set a directory where you will store the 437 distorted videos (~4.31 TB). Place the following script inside the folder and run. 
	```
	download_distorted.bat
	```

### Linux/Mac Users
* Set a directory where you will store the 15 original videos (~151 GB). Place the following script and the inside the folder and run. 
	```
	bash download_original.sh
	```
* Set a directory where you will store the 437 distorted videos (~4.31 TB). Place the following script inside the folder and run. 
	```
	bash download_distorted.sh
	```

You can also manually download selected videos by using direct download links for each videos provided in the *ETRI-LIVE_directLink.xlsx*. (Note: This file is in [this link](https://utexas.box.com/s/9rku1m3pwi96m7pls3q0j82sacvji9lx)).  


## Subjective Scores
The subjective opinion scores for all 437 distorted videos are provided in [subjective_scores](/subjective_scores) directory.

## Target bit rate/QP Information
The five target bit rates associated with each source video, along with the corresponding QP and bit rate values of the space-time subsampled videos are provided in [target_bitrate_qp_info](/target_bitrate_qp_info) directory.

## Citation
If you use this database in your research, we kindly ask you to reference our paper

>D. Lee, S. Paul, C. G. Bampis, H. Ko, J. Kim, S. Jeong, B. Homan and A. C. Bovik, "A Subjective and Objective Study of Space-Time Subsampled Video Quality", IEEE Transactions on Image Processing, vol. 31, pp. 934-948, 2022. 


### Contact
Dae Yeol Lee, daelee711@utexas.edu
