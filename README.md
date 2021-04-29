# Biden_Trump_RNN_speech_bots
Using web scraping to gather data, and RNNs to generate speech similar to both Biden and Trump.

This project is meant to create statements, that are similar in subject and structure to real statements made by Joe Biden and Donald Trump before the 2020 election. It is in no way meant as a political statement. It is also not meant to serve as a deep analysis and comparison of their speech. It is simply meant to be a light-hearted and entertaining take on the political process in America.

I have trained two GRU-RNN models in the make_Biden_RNN and make_Trump_RNN notebook files. I have made a character and word encoded model for both candidates as .h5 files. To run this project without having to retrain the models, please run BidenOutput.ipynb and TrumpOutput.ipynb. There, you can change to character level encoding but you will output slightly less predictable "statements".

For this project, you will need to have installed a newer version of Tensorflow. I am personally using TF version 2.4.0rc0 which is a not flawless pre-production version meant for the Apple M1 chip. Therefore, if you have issues running the code, it may likely be caused by different syntax required for my TF version when I was building it. Slight modifications to this code may hence be necessary.
Other packages required are: tkinter, textwrap, bs4, numpy, etc.

To see examples of the output, check the Example.png files

Enjoy!