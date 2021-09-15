# Earthquake-prediction
The datset contains the record of the earthquakes already happened across the  world since 1963 to 2003.
The important fetaures which play key role in predicting the results are consideared.
Since the data is random, so we need to scale it based on the model inputs. In this, we convert the given date and time to Unix time which is in seconds . This can be easily used as an entry for the model we have built:
Before creating the earthquake prediction model, we visualized the data on a world map that shows a clear representation of where the earthquake frequency will be more.
The data is split accordingly such that the inputs are TImestamp,Depth, Latitude and Longitude and the output is Magnitude . . The training set contains 70% and the test set contains 30%
Initially the model is performed using Randomforest regression and the model is boosted using XGBregressor.
