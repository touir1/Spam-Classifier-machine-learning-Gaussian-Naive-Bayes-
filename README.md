# Spam Classifier (machine learning Gaussian Naive Bayes)
[![npm](https://img.shields.io/npm/l/date-2.svg?style=flat-square)]()

[website](https://touir1.github.io/Spam-Classifier-machine-learning-Gaussian-Naive-Bayes/)

Spam Classifier is a python script to detect if a mail is a spam or not

## Usage ##

to use Spam Classifier module with a console you need to:
```
Usage: spam_detector.py [options]

Options:
  -h, --help            show this help message and exit
  -c FILE, --classifier=FILE
                        import classifier from file
  -v FILE, --vectorizer=FILE
                        import vectorizer from file
  -m MESSAGE, --message=MESSAGE
                        required: classify the message given
  -s SUBJECT, --subject=SUBJECT
                        required: classify the subject given
```

to use Spam Classifier as a web service you need to:

**-Start the web server**
```
Usage: web_service.py [options]

Options:
  -h, --help            show this help message and exit
  -c FILE, --classifier=FILE
                        import classifier from file
  -v FILE, --vectorizer=FILE
                        import vectorizer from file
  -p PORT, --port=PORT  port of the server
  -a ADRESS, --adress=ADRESS
                        adress of the server
```

**-call the web service**

```
http://[adress]:[port]/[subject]/[message]

adress: adress of the server
port: port of the server
subject: subject of the mail encoded in url format
message: message of the mail encoded in url format
```
## Authors ##

* Mohamed Ali Touir
  * Github: [https://github.com/touir1](https://github.com/touir1)
  * Email: [touir.mat@gmail.com](mailto:touir.mat@gmail.com)
  * Twitter: [@TouirMohamedAli](https://twitter.com/TouirMohamedAli)

## License ##

Spam Classifier is published under the [MIT license](http://www.opensource.org/licenses/mit-license)

## Special thanks ##

csmining.org for providing the dataset used for training my model [csmining: Spam email datasets](http://csmining.org/index.php/spam-email-datasets-.html).
