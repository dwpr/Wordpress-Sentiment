This project is  my final assignment to take the degree of facilities at Ahmad Dahlan University <a href="http://digilib.uad.ac.id/penelitian/Penelitian/detail/105578/analisis-sentimen-komentar-tulisan-blog-menggunakan-metode-knearest-neighbour">[paper]</a>. 
This application is useful for providing sentiment info on comments and posts in blog posts (wordpress).
in this project the method what i use to classify comment to positive, neutral or negative is K-Nearest Neighbour (KNN), you can check step by step POC the method in <a href="https://informatikalogi.com/klasifikasi-teks-menggunakan-k-nn/">https://informatikalogi.com/</a>

### Required:
- python (2.7 or higher)
- <a href="https://wordpress.org/download/">wordpress</a>


### How to use this app
1. Restfull API
- extract RestAPI_python.zip
- run on pyhton with this script "python app.py" in your extract folder
- if error. There are no modules needed such as literature, flask etc., install first ex: pip install flask
- if other error such as python version maybe you can edit some code to your oython version, cause in this code i'm still use python 2.7

2. Wordpress
- install the plugin with wordpress (open TAnalyzer.zip)
- enable plugin (after restAPII running)
- if want to use my data comment, please import my database.db / my database.sql with phmyadmin
- the base plugin here is hercules sentiment analyzer, i just edit little bit for showing sentiment from my python restAPI. this Hercules Sentiment analyzer is cool plugin :D

Congratulation \ (^ o ^) /
<br>
if any question please mail me on <a href="mailto: dwipurwanto.210@gmail.com">dwipurwanto.210@gmail.com</a> | Telegram  <a href="https://t.me/dwipur21">Dwi Purwanto</a>
