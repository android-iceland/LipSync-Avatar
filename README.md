


<img src="https://raw.githubusercontent.com/android-iceland/LipSync-Avatar/main/LipSync-Avatar.png" width="800">
<br>

## Click on this button to run on Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/android-iceland/LipSync-Avatar/blob/main/LipSync_Avatar.ipynb)


## Demo <br>
### Input form 
![](https://github.com/android-iceland/LipSync-Avatar/blob/main/form.png)
### Result (click on the video)

<!-- <video src="https://github.com/android-iceland/LipSync-Avatar/blob/main/video/sample.mp4" controls></video> -->



 [![Watch the video](https://github.com/android-iceland/LipSync-Avatar/blob/main/video/sample.gif)](https://www.youtube.com/watch?v=w8Qwrh8t0n4)

#### Use green screen effect to use  the AI Avatar in your videos. 
### Input form 
![](https://github.com/android-iceland/LipSync-Avatar/blob/main/form2.png)

### Result (click on the video)
[![Watch the video](https://github.com/android-iceland/LipSync-Avatar/blob/main/video/sample1.gif)](https://www.youtube.com/watch?v=nlYIeaM8Cug)

#### Use green screen effect to use  the AI Avatar in your videos. 


### How to use your own video to generate ai avatar video
1. add your video in the folder called `videos` 
  for example you uploaded a video called `own.mp4` 
  
2. below this cell 'Fill the upscale checkbox to upscale your video'
 on line no  2
 ```
 select_avatar = "alisa" #@param ["alisa", "jenny", "anna"] {allow-input: true}
 ```
 update the select_avatar with your file name without the file extension
 ```
 select_avatar = "own" #@param ["own","alisa", "jenny", "anna"] {allow-input: true}
 ```
3. now you are good to go with your own video





```bibtex
@credit{Thanks to,
  Wav2Lip = {https://github.com/Rudrabha/Wav2Lip},
  GFPGAN  = {https://github.com/TencentARC/GFPGAN},
}
```

```bibtex
@author{android-iceland,
  Wav2Lip = {for lip synchronization},
  GFPGAN  = {for face upscaling},
}
```


