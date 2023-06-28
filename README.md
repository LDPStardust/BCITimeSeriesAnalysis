# BCITimeSeriesAnalysis
Myself and three peers - Michael Piccolo, Marlene Gonzalez, and Zachary Peskin - worked in tandem with a group of graduate level engineering students at California State University, Fullerton to develop strong predictive models pertaining to Brain Computer Interface data. 

Brain Wave Data Analysis Through Time Series Simulations.pdf, is our formal paper, BCI ARIMA Modeling Code.Rmd is an R markdown file containing our code and explanations of the work and code. The csv files are the raw data used - time series of four segments where subjects put on a g.Nautilus headset which recorded electroencephalography (EEG) and functional near-infrared spectroscopy (fNIRS) data. Segment 1 files were control segments where subjects sat still and weren't given any active mental stimuli, and the latter segments consisted of three separate games.

This data pertains to one specific client who was observing and determining whether or not subjects were experience stress, and we were tasked with improving the whole group's predictive modeling. Built around and concerned with the nature of EEG and fNIRS behavior, the end result is applicable to other tasks and interests pertaining to EEG and fNIRS data, though this project had a heavy focus on the stress-related experiments and heavily used EEG data. After running exploratory data analysis, we decided to use Auto-Regressive Integrated Moving Average (ARIMA) resampling to flesh out the limited data on hand for effective and sound time series modeling.
