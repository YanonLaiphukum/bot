# Spam-Detection-Flask deploy

การทำ machine learning แยกข้อความ sms ที่เป็น spam

## model เทรนด้วยเทคนิค tf-idf และใช้ classification ด้วย SVM
> https://github.com/serversuck/spam/blob/main/spammodel.pkl



## การติดตั้ง
> git clone https://github.com/serversuck/spam.git
>
> pip install -r requirements.txt

## Run flask framework
> python app.py

## การทดสอบแบบ html form
http://localhost:5000

## การทดสอบแบบAPI
http://localhost:5000/api?msg=เงินกู้ของท่านได้รับการพิจารณาแล้ว

## Heroku deploy
> heroku login
> 
> heroku git:remote -a spammysms
> 
> git add .
> 
> git commit -am "make it better"
> 
> git push heroku main


## ทดสอบผลงานทำงานบน heroku

> https://spammysms.herokuapp.com

> https://spammysms.herokuapp.com/api?msg=เงินกู้ของท่านได้รับอนุมัติแล้ว

## นำ API ไปใช้กับ chatbot
<img src=http://techno.varee.ac.th/maxm5//Screen%20Shot%202565-05-30%20at%2012.45.42.png>

##อ้างอิง
https://github.com/divyansh1195
