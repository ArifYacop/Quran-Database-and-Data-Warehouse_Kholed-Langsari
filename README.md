# Quran-Database-and-Data-Warehouse_Kholed-Langsari.
Quran-Database-and-Data-Warehouse_Kholed-Langsari.
Overview
This project is a part of big data and data warehouse course (DS2303-314).  In this project, we work together in group to combine what we’ve learned throughout the program to build our own data engineering project. In This case, is Quran Database and Data Warehouse. This project train us in managing data in database by using Olap-cube and PostgreSQL database program.

Tools of use
A Computer
Python => 3
Jupyter, IPython
Visual Studio Code
PostgreSQL
Git, GitHub, GitHub Desktop

Al-Quran Dataset
Text and translation
alquran.csv = alquran
chinese_makin.csv = Chinese
english_hilali_khan.csv = English
indonesian_affairs.csv = Indonesian 
thai.csv = Thai

Tafseer
chinese_makin.csv = Chinese
english_hilali_khan.csv = English
indonesian_affairs.csv = Indonesian

Index
quran_surah.csv = quran_surah

Step to do star schema and analysis
Download PostgreSQL
Create the database and fill it with data
Insert the dataset
Create Fact Table
"alquran.index AS alquran_key,
alquran.surah AS alquran_surah,
alquran.ayah AS alquran_ayah,
chinese.id AS ch_key,
english.id AS en_key,
indonesian.id AS in_key,
thai.index AS th_key"
Connect Fact Table to all dimension Table including Surah Ayah Translate
For Analysis you can see how to do via this link https://github.com/ArifYacop/Quran-Database-and-Data-Warehouse_Kholed-Langsari

Questions & Answers
1. How many surah makkiyah and madaniyyah?
2. How many ayah sajadah in Al-Quran?
3. Where the ayah sajadah located in Al-Quran?
4. How many surah starts with Alif Lam Mim?
5. How many words "Allah" in Al-Quran?
6. Which ayah mentioned about the cow?
7. Which ayah that Allah mentioned to Malaikat?
8. Which ayah mentioned about Allah is the Most Merciful?
9. Which surah that contains the longest verse?
10. Which surah doesn't have basmalah?

Data source
https://github.com/hablullah/data-quran
https://quranenc.com/en/home

Authors
1. Arif Yacop
2. Abdulfatah Jehsoh
3. Hananee Bueraheng

Summary
In conclusion, this repository has discussed four key area is information about the Quran Al-Quran Dataset,Tools of use,Step to do star schema and analysis and saw that dealing with the Quran database can be a sentence for people who are very interested.






 