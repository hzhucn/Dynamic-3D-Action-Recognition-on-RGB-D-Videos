# [Dynamic 3D Hand Gesture and Action Recognition with Learning spatio-temporal aggregation on Different Representation](https://rezazad.000webhostapp.com)


Dynamic 3D Human Action and Hand Gesture Recogntin on RGB-D videos with State of the Art results on public datasets. This Method Learns Human Actions with Aggregating of Spatio-Temporal Description from different representation. If this code helps with your research please consider citing following paper:
</br>
> R. Azad and S. Kasaei, "Dynamic 3D Hand Gesture and Action Recognition with Learning spatio-temporal aggregation on Different Representation", To be submit, 2017.
## Updates
- Aug 28, 2017: First release, Complete Implementation for MSR Action 3D dataset
## Prerequisties and Run
This code has been implemented in Matlab 2016a and tested in both Linux(ubuntu) and Windows 10, though should be compatible with any OS running Matlab. following Environement and Library needed to run the code:
* Matlab 2016
* [VL feat 0.9.20](http://www.vlfeat.org/)
</br>
**Run Demo**
Run the 'Main_MSRAction3D' for both feature extraction and classification of dynamic 3D action. The 'Main_MSRAction3D' uses 'Step1_Extract_Featues' for extracting spatio-temporal features from different represantion of 3D video and 'Step2_Description_Classification' for aggregating of descriptions and classification phase. These two functions can be use seperetely too. Function that related to 'Video Summarization', 'Forward Bakward Motion', 'Difference Forward Energy', 'Temporal Sequence Generating', 'Binary Weighted Mapping', and extracting 'Regional LBP and HOG' features has been implemented in 'Video_Analyser' class.     
## Short Overview
![Action and Hand Gesture Recognition](https://user-images.githubusercontent.com/20574689/29744825-1f43af08-8ac2-11e7-894e-2cb1b316185a.png)
=========
## Heading 2
Heading 2
---------
### Heading 3
#### Heading 4
**Bold**
*Italik*
<br />

* One
* Two
* Three

<br />

1. One
1. One
1. One

The word ~~We~~ must be omitted :+1:

First Header | Second Header| XYZ
------------ | -------------|----
Content from cell 1 | Content from cell 2| X
Content in the first column | Content in the second column|YZ
1|2|3
4|5|6

The function `goHome()` is a main function!

```matlab
function goHome()
  if true
    disp('Go Home!')
  end
end
```

Pleas click on this [google](https://www.google.com)!


Ziserman told me:

> You are amazing Reza!!!

```javascript
if (isAwesome){
  return true
}
```
