# TED-Talks

This is for Applied Statistical Modeling midterm project. Used varying intercept mixed effect model to explore what makes some TED Talks are more popular than others. Why and how this multilevel model works is written in _report.pdf_ file.

## 1. Data Resource

[Kaggle] https://www.kaggle.com/rounakbanik/ted-talks

Scraped from TED official Website (TED.com) and contains information for all videos until September 21st, 2017.

## 2. Data Manipulation

Rmd file: report.Rmd

## 3. Videos

TED started to offer free online videos since June 2006.

* __How many videos are published in each year?__

<img width="711" alt="fig_1" src="https://user-images.githubusercontent.com/42655633/50543946-8e3ea600-0bb4-11e9-9f57-42a3afc0809c.png">

Each video has couple related tags.

* __Which tag contains most videos?__

<img width="817" alt="fig_5" src="https://user-images.githubusercontent.com/42655633/50543952-ac0c0b00-0bb4-11e9-8490-90029d1eb30d.png">

__Technology__! Definitely.

## 4. Speakers

* __What do they do?__

<img width="813" alt="fig_4" src="https://user-images.githubusercontent.com/42655633/50543950-a4e4fd00-0bb4-11e9-9a04-12c8be65f8f4.png">

## 5. Views and Comments

Every video has a _Rate_ button, and audiences could choose three words to describe the video.

* __What if we pick out the most rated word for each video, and see how often these words appeared overall.__

<img width="718" alt="fig_3" src="https://user-images.githubusercontent.com/42655633/50543948-9c8cc200-0bb4-11e9-9f6b-bbf0bb797a07.png">

_Inspiring_ and _Informative_ appeared A LOT. __Awesome!__

* __Next take a look at comments.__

<img width="725" alt="fig_2" src="https://user-images.githubusercontent.com/42655633/50543947-9565b400-0bb4-11e9-9d48-04fa33533bc5.png">

Seems like videos published earlier tend to have more comments. Fair.

## 6. Text Mining

* __What did people talk about?__

Bigram wordcloud for transcripts. Below just shows videos which tagged _Technology_.

<img width="488" alt="fig_6" src="https://user-images.githubusercontent.com/42655633/50543954-b3cbaf80-0bb4-11e9-8060-11d6555d814d.png">
