# Diyabet Tahmini: 

## İçerikler
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Bug / Feature Request](#bug---feature-request)


## Demo
Link: [https://diyabet-tahmin.herokuapp.com/](https://diyabet-tahmin.herokuapp.com/)


## Genel Bakış
Bu, bir hastanın şeker hastası olup olmadığını tahmin eden basit bir Flask web uygulamasıdır.


## Kurulum
Kod Python 3.6.10'da yazılmıştır. Python kurulu değilse [burada] (https://www.python.org/downloads/) bulabilirsiniz. Python'un daha düşük bir sürümünü kullanıyorsanız pip paketini kullanarak yükseltebilir, pip'in en son sürümüne sahip olduğunuzdan emin olabilirsiniz. Gerekli paketleri ve kitaplıkları kurmak için, depodan [klonlama] (https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) sonra proje dizininde bu komutu çalıştırın:
```bash
pip install -r requirements.txt
```

## Heroku'da Paylaşım
Sanal uygulama oluşturmak için giriş yapın veya kayıt olun. Bu projeyi manuel olarak dağıtmak için github profilinizi bağlayabilir veya ctl'yi indirebilirsiniz.
[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── diabetes_model.pkl
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 


## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/Mandal-21/diabetes-prediction/issues) here by including your search query and the expected result

