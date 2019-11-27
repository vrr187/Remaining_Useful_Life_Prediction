# Remaining Useful Life Prediction <br>

<img style="display:inline; margin-left:100px" width=40% src="https://upload.wikimedia.org/wikipedia/de/c/c8/Logo_Uni_Paderborn.svg"/> &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp;&nbsp; &nbsp;
<img style="display:inline; margin-left:250px" width=20% src="https://groups.uni-paderborn.de/ldm/ausschreibungen/css/images/LDM%20Logo%20mit%20Text.png"/> &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;
<img style="display:inline; margin-left:250px" width=20% src="https://upload.wikimedia.org/wikipedia/commons/e/e5/NASA_logo.svg"/>
<br><br>

This work has been developed for the Chair of Dynamics and Mechatronics (LDM) of Universität Paderborn - Germany.

The objective is to conduct research and develop new methods and approaches to prognostic issues, especially in the field of predictive maintenance.

The data to be used is provided by The Prognostics Center of Excellence (PCoE) at NASA Ames. <br>
This dataset was used for the prognostics challenge competition at the International Conference on Prognostics and Health Management (PHM08). The challenge is still open for the researchers to develop and compare their efforts against the winners of the challenge in 2008. <br>

The official files provided by the competition as well as the source files and previous scores are located in the "original_data" folder and can also be found on the following link: <br> 
[PHM08 Challenge Data Set](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/)

### Brief Summary
The data sets consist of multiple multivariate time series which is further divided into training and test subsets. Each time series is from a different engine – i.e., the data can be considered to be from a fleet of engines of the same type.
Each engine starts with different degrees of initial wear and manufacturing variation which is unknown to the user. This wear and variation is considered normal, i.e., it is not considered a fault condition. <br>
The engine is operating normally at the start of each time series, and starts to degrade at some point during the series. <br>
In the training set, the degradation grows in magnitude until a predefined threshold is reached beyond which it is not preferable to operate the engine. <br>
In the test set, the time series ends some time prior to complete degradation. <br><br>
The goal is to train models able to predict as accurately as possible the RUL (remaining useful life) of each engine from the test set.
<br><br>
### Considerations

The work has been developed in Python 3.6 supported by Jupyter Notebook.<br>
All used libraries can be found in requirements.txt file.
All procedures performed in this work are arranged chronologically, along with the results and a more detailed description of the problem can be found in the notebook Main.ipynb.

This work is still under development. I leave it open to anyone who wants to share knowledge on the subject. Suggestions and constructive criticism are always welcome.
If you find any problems, improperly used algorithms, obsolete procedures and/or even badly written codes, please do not hesitate to leave a message or contact me in private. I reply quickly.
Whatever the criticism, I am 100% open to new knowledge and improving results.


Appropriate references and licenses are being provided.
