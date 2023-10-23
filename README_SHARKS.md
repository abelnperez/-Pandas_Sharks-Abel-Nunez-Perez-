![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Data Cleaning

## Introduction

Vamos a empezar limpiando y filtrando la informacion relevante del Data Set. Tenemos muchas columnas que no contienen informacion relevante para nuestro estudio, hay columnas nulas, duplicados, datos incompletos... vamos a ir ordenado, limpiando y clasificando la informacion que nos interesa 

## Getting Started

Primero definimos nuestro estudio, para ello definimos las columnas que contienen informacion relevante, desechando o ignorando el resto. Nos vamos a quedar con las siguientes:
- Case Number
- Date
- Year
- Type
- Country
- Area
- Location
- Activity
- Name
- Sex

Aun pudiendo reducirlo a menos columnas, son estas las que tienen informacion relevante para nuestro estudio.

## Goals

Tener nuestro Data Set limpio para poder llevar a cabo nuestro analisis

## Deliverables

- `main.ipynb` completed.
- `vehicles_messy-clean.csv` containing the clean dataset.

## Submission

Upon completion, add your deliverables to git. Then commit git, push to your forked repo, and create the pull request as in the previous labs. **REMEMBER

- Upon completion, commit your code and submit to github. **REMEMBER YOU HAVE ALREADY FORKED THE REPO BEFORE**!!

  ```
  git add .
  git commit -m "<lab or project name>"
  git push origin master
  ```

- Navigate to your repo and [create a Pull Request](https://help.github.com/articles/creating-a-pull-request/).
- Create a pull request with title following this format: **"[<your_campus>][<bootcamp_code>] [<lab/project_name>]<your_name>"**
  - For instance, if you are doing data bootcamp in Madrid, your name is Marc Pomar and the lab you are working on is `lab-numpy`, your pull request should be named like this: "[MAD][datamad10108] [lab-numpy] Marc Pomar"
- If you have successfully created the pull request you are done!  CONGRATS :)

## Resources

[Data Cleaning Tutorial](https://www.tutorialspoint.com/python/python_data_cleansing.html)

[Data Cleaning with Numpy and Pandas](https://realpython.com/python-data-cleaning-numpy-pandas/#python-data-cleaning-recap-and-resources)

[Data Cleaning Video](https://www.youtube.com/watch?v=ZOX18HfLHGQ)

[Data Preparation](https://www.kdnuggets.com/2017/06/7-steps-mastering-data-preparation-python.html)

[Google Search](https://www.google.es/search?q=how+to+clean+data+with+python)

## Additional Challenges for the Nerds

If you have completed the `Stats` challenge without much difficulty, you can try to tidy the data you will find in thie lab folder [weather](../weather-raw.csv). This dataset is a subset of a global historical climatology network dataset. The data represents the daily weather records for a weather station (MX17004) in Mexico for five months in 2010. The goal of this additional challenge is to get the most tidy dataset you are able to produce. **Hint:Variables are stored in both rows and columns.**

To accomplish this challenge, you will need to do some research on tidying and melt&pivot. Feel free to reference any resources you consider appropiate.

editado


