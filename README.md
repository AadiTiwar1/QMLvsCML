# QMLvsCML

# Rough outline of project
Have 3 CML models: LSTM, GAN using LSTM, one more tbd. Then create Quantum equivalents for these models, that are identical in every metric except the type of computer it's ran on so that the only real difference is whether it's a Quantum or Classical ML model. You then give these models tasks like forecasting Stock Prices and see the differences in the time it takes for each to converge, RMSE accuracy, other metrics. After all of this, we will be able to determine what quantifiable advantage QML has over CML - does it run faster, converge faster, give more accurate RMSE's because of superpositions, etc.

# How I plan to make this project (Detailed)
 1. Research LSTM with GAN because I am not familiar with GAN, I'm only familiar with LSTM
 2. Go back to your QLSTM project and just steal the code for that and use it in this project
 3. Take your QLSTM model and use it as the generator for the GAN and use it in this project
 4. Research what your 3rd model will be - try to make it something that isn't related to LSTM, something modern and trendy and cool and trendy
 5. Make a Quantum Version for that
 6. Choose (~3) stocks that have different characteristics - Frequency of change, Average price, how much data/new it is, etc just very diverse options
 7. Do your analysis stuff
 
# Where I am right now
 2/13/23 - Writing this outline in hopes that it actually helps me in completing this project in time lmfao <br>
 2/14/23 - Decided on using Intel as our downwards trend, Apple as our consistent trend, Synopsis as our upwards trend. We are only considering last 2 years for all of these stocks, might play around with that number later. Also got LSTM and QLSTM to work, but QLSTM takes a ton of time to train, will need to look into that tomorrow<br>
 2/15/23 - Did nearly nothing today. Planning to implement CUDA so that code runs faster or something to fix QLSTM problem, will research tmrw. Still on track since the LSTM & QLSTM are working, just QLSTM takes a long time to run. Also need to rewrite data part. <br>
 2/16/23 - Did nothing <br>
 2/17/23 - Rewrote some of the LSTM and QLSTM parts so that it runs with the data we want it to run with. Couldn't get the QLSTM-GAN or LSTM-GAN working today, couldn't fix the QLSTM time-to-run problem either. Break just started, so I can make up for being behind soon. <br>
 2/18/23 - Started working on the LSTM-GAN and was able to fix alot of the misnamed files, code is running and is providing good results now. Still need to implement the Quantum counterpart, hopefully will be done by tomorrow. <br>
 
# Where I hope to be at certain times
 2/14/23 Finish choosing out the 3 different stocks we're gonna use <br>
 2/15/23 Have functioning LSTM and QLSTM models <br>
 2/16/23 Finalize title since deadline to change is 2/17/23 <br>
 2/18/23 Have functioning LSTM-GAN and QLSTM-GAN models <br>
 2/19/23 Begin uploading Abstract to judging folder (check website) <br>
 2/27/23 Finalize abstract as it is due 2/28/23 <br>
 3/6/23 Be done with your spectacular posterboard and ready to speech <br>
 3/7/23 Judges recieve projects online <br>
 3/8/23 Checking / Posterboard day <br>
 3/9/23 Synopsis Championship 2023 <br>
 
