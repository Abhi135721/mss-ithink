# mss-ithink
Given any dataset containing customer dataset, this application analyzes the data in the dataset and produces graphs


The dataset id data.csv which here is of 200MB size(approximately)

## Steps:
    1. Run graph_app.py using python
      python graph_app.py
    2. Step-1 will start a localhost server on port number 5000
    3. Upload data.csv on webpage after entering http://localhost:5000 on your browser.
    4. After uploading click on analize
    5. Select options from the given list i.e , on which data you want to analyze
    6. You can continue further analysis or can view the graph of analyzed data or can save the analyzed data in csv format
    
## Pre Requisites:
  ### Python (version 2):
        #importing required modules
        import os
        import pickle
        import csv
        import json
        import pygal
        import pandas as pd
        from flask import Flask,redirect, url_for,request,render_template
        import numpy as np
        from pyspark.sql import *
        from pyspark import SparkContext,SparkConf
        from pyspark.sql.types import *
        import pickle
        import sys
        import json
        from pprint import pprint
        import csv
    
