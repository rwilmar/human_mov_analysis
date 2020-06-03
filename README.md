# Human Motion analysis

This is a tool for Visual Human Motion analysis from video files using DeepLearning models and bokeh visualizations.

Inferenced studios have been included for you to play with and improve according to your special needs; however new videos can be analyzed using the jupiter notebook included or trough the use of a python script.

Enjoy and share the voice.

Wil.

## Setting Up
Packages needed to run the samples are:
- Python 3.5+
- OpenVino 2020.0 (works on OpenVino 2019)
- OpenCV 4.0+
- Bokeh Server


## Running
To run the examples jypiter notebooks can be used,

for the Bokeh app directly from a Bokeh server, navigate to the parent directory
[`Human 3dPose app`](https://github.com/rwilmar/human3dPose.git),
and execute the command

    bokeh serve --show dashboard

## Preview
Dashboard head,with the signal browser and videoframe preview
![Head and Main Speed signal browser](/images/screenshot1.png)
Detailed speed graphs per joint timeseries and freq analysis
![Detail Speed per joint](/images/screenshot2.png)
Advanced frequency analysis heatmap and datatable
![Advanced Frequency analysis](/images/screenshot3.png)
also includes working video preview

## Licences

This example uses code from the following projects:

* https://fontawesome.com/license
* https://getbootstrap.com/docs/3.3/getting-started/
* https://github.com/puikinsh/gentelella/blob/master/LICENSE.txt

Other packages and licences related might be used please let me know the case to include them here... 
