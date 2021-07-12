==========================================================
Smart method Speech to text task (4) -continute
==========================================================

=========================================
in this task we will convert the humman voice to reading text 
using : 
1-Python
2-IBM watson speech to text servies 
=========================================

Prerequisite : 
============
1-install python in your machine 
2-Pycham editor 
3-IBM watson account 

Configuration:
==============
1-go to your ibm account 
2- select catlog && choose speech to text servies 
3- select free plan
4-copy the api key 

Installation
============
1-clone the ibm watson https://github.com/IBM/watson-streaming-stt
2- open the project folder and install pip install pipwin
3- python -m pipwin install pyaudio
4-in speech.cfg file paste the api key and change the region to selected region in ibm watson servies , prefer dallays 
5-write creating text file code in on_message method 

Getting Started
===============
to test write this code 
python transcribe.py -t [recording secend ]




