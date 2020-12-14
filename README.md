# 2018, 2019 & 2020 examination results in Estonia
## C16 - Brandon Loorits & Tauno Tamm


## Introduction

In this project, we have analyzed 2018, 2019 and 2020 Estonian examination results to have a wide overview, where the government should take measures to improve Estonian education system. The data is taken from Estonian examination system (https://eis.ekk.edu.ee/eis/eksamistatistika), where shown data is reliable and controlled by the government.

## Running the Project

This project was made with Google Colab because of it's possibility to programme in pairs. It is recommended to run this code in Google Colab. If you want to run it in Jupyter Notebook, then you must have Geopanda preinstalled, because the project file uses geopanda.

## About the Project

def makeFloats(data) - takes string numbers and converts them into floats.

def average(dictonary) - from given dictonary where is located each school results, finds this schools overall average.

def StatesGraphUpsAndDowns(data1,data2) - puts together top 10 and top 10 counties whos results have changed the most over the given years data.

def GraphUpsAndDowns(data1,data2) - puts together top 10 and top 10 schools whos results have changed the most over the given years data.

def find(data,myset) - creates a new dataset where schools are appeared a single time. There is also added schools overall average as a new column.

def findState(data,myset) - creates a new dataset where counties are appeared a single time. There is also added counties overall average as a new column.

def BestState(data) - finds best counties from given data.

def BestSchool(data) - finds best schools from given data.

def Best(data) - finds top 10 schools whos score has grown over the year.

def Worst(data) - finds worst 10 schools whos score has decreased over the year.

def NegativesAndPositives(data, string) - finds how many results of schools have grown and decreased over the year of given data. Also shows the percentage.

def NegativesAndPositivesStates(data, string) - finds how many results of counties have grown and decreased over the year of given data. Also shows the percentage.

def UpsAndDowns(data1,data2) - computes result change of schools over the given year's data.

def UpsAndDownsStates(data1,data2) - computes result change of counties over the given year's data.

def map(data, text) - plot a heatmap of given data about counties. Gives a great overview of results by counties.
