# ETRI-LIVE STSVQ Database
ETRI-LIVE Space-Time Subsampled Video Quality (STSVQ) Database contains 437 videos generated by applying various levels of combined space-time subsampling and video compression on 15 diverse video contents. In this page, we provide a guide on how to obtain the videos and their respective subjective opinion scores. For detailed information, please visit the ETRI-LIVE database [website](https://live.ece.utexas.edu/research/ETRI-LIVE_STSVQ/index.html).

## Downloading the videos
To download the videos, please fill [this form](https://docs.google.com/forms/d/e/1FAIpQLScfk9y1XUWINq4EqsDuTXsfO7bJIPOYcfBUIAU19_QY92M-Qg/viewform) and a download link will be sent to you where you can access the download scripts and videos.
* The database consist of 15 original videos and 437 distorted videos. 
* All videos are provided in raw YUV file format at 3840x2160, 60/120Hz, and 10 bit. 
* For downloading the entire database, please ensure at least 4.6 TB space available.

### Windows users
	* Please configure curl here  
	* Create a directory  
	```
	download.bat
	```


## Subjective Scores
The subjective opinion scores for all 437 distorted videos are provided in [subjective_scores](/subjective_scores) directory.

## Target bit rate/QP Information
The five target bit rates associated with each source video, along with the corresponding QP and bit rate values of the space-time subsampled videos are provided in [target_bitrate_qp_info](/target_bitrate_qp_info) directory.

## Citation
If you use this database in your research, we kindly ask you to reference our paper

>D. Lee, S. Paul, C. G. Bampis, H. Ko, J. Kim, S. Jeong, B. Homan and A. C. Bovik, "A Subjective and Objective Study of Space-Time Subsampled Video Quality", submitted to IEEE Transactions on Image Processing. 


### Contact
Dae Yeol Lee, daelee711@utexas.edu
