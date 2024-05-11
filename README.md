# NN-A82582C
Main code for article NN-A82582C
The main script includes two parts: 

**1 Analysis code for image data**; 

**2 Analysis code for sequencing data**.

If you have any feedback or issue, you are welcome to either post issue in Issues section or send email to jingmiao@cibr.ac.cn.

## ATP1.0 Two-photon In Vivo Imaging Data Analysis

### Exampluar data

You can download the exampluar data [here](\ABCD.tif) 

You can download the project files post signal extraction via [AQuA](https://github.com/yu-lab-vt/AQuA) (*Yizhi Wang et.al nat. neurosci 2019*)  from [here](\ABCD.mat).

Opts for signal extraction can be downloaded [here](opts.csv).

### Code 

1. **Res2DensityMap** This function accepts an AQUA project file 'res' and outputs a normalized Inflares density map as shown in Fig. 3a.
2. **Res2DensityCurve** This function accepts an AQUA project file 'res' and outputs a Inflares density curve as shown in Fig. 3c.
3. **Res2RoiRegion** This function takes an AQUA project file 'res' as input and outputs a two-dimensional ROI of Inflares as shown in Fig. 2c, with the ROI color mapping corresponding to the maximum response for the signal.
4. **Res2FreqPlt** This function accepts an AQUA project file 'res' and plot frequency figure as shown in Fig. 2d.

## Sequencing data
### Raw dara
The sequencing data has been uploaded to NCBI and can be downloaded here. 

[Seq Data in Figure9](ww.1234)

[Seq Data in Extend data Figure9](ww.1234)

