# Subjective Opinion Scores

There are two files containing subjective opinion scores. Each files is arranged with video names associated with their mean subjective opinion scores and their respective standard deviations. 
The video names are provided in *sourceContentName_spatialResolution_frameRate_quantizationParameter* format. (e.g. Beauty_1080p_120hz_q_27)

>**1. ETRI-LIVE_DMOS.csv** 
>		* contains Difference Mean Opinion Scores (DMOS) and their respective standard deviation. 
>		* can be used to evaluate prediction performances of reference (full/reduced) image/video quality models.


>**2. ETRI-LIVE_MOS.csv**
>		* contains Mean Opinion Scores (MOS) and their respective standard deviation. 
>		* can be used to evaluate prediction performances of no-reference image/video quality models.

We also provide video information matrix containing each distorted videos space-time resolution and bit rate informations.


>**3. ETRI-LIVE_videoInfo.csv** - contains video parameter information.
>		* **videoName**: sourceContentName_spatialResolution_frameRate_quantizationParameter
>		* **contentIndex**: videos generated from the same source content have the same number.
>		* **sourceSpatialResolution**: spatial resolution of the original source content.
>		* **sourceFrameRate**: frame rate of the original source content.
>		* **processedSpatialResolution**: spatial resolution of each distorted content.
>		* **processedFrameRateRatio**: frame rate ratio (distorted/source) of each distorted content.
>		* **bitrate**: bitrate of each distorted content in Mbps.
>		* **bitrateLevel**: bitrate level of each distorted content where higher number refers to heavier compression.

