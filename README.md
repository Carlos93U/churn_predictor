# SKLEARN_DIGITS_PREDICTOR | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/800px-Python-logo-notext.svg.png" height=20> | <img src="https://i.postimg.cc/cHqB5VtL/scikit-learn-logo.png" height=20>| <img src="https://pandas.pydata.org/static/img/pandas_white.svg" height=20>  | <img src="https://i.postimg.cc/m2dwfTdm/numpy-logo.png" height=20> |  <img src="https://matplotlib.org/_static/logo_dark.svg" height=20> | <img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" height=20> | <img src="https://assets.ydata.ai/oss/ydata-profiling_red.png" height=20> |[<img src="https://static-00.iconduck.com/assets.00/github-icon-2048x1988-jzvzcf2t.png" height=20> ](https://github.com/Carlos93U) | [<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/640px-LinkedIn_logo_initials.png" height=20>](https://www.linkedin.com/in/juan-carlos-huillcas/) |

## 1. Resume

The project focuses on a dataset from a telecommunications company to predict if customers will churn. It utilizes the scikit-learn library, specifically the binomial logistic regression model. The analysis involves exploring relevant variables and implementing the model to predict churn. The aim is to understand the factors influencing customer churn and provide a strategy to retain them using supervised learning techniques.

[![ocr-intro-1.webp](https://i.postimg.cc/3RC8JJ00/ocr-intro-1.webp)](https://postimg.cc/tZJQBb59)

## 2. Data Set Characteristics

The load_digits dataset from sklearn contains images of handwritten digits from 0 to 9 in an 8x8 pixel grayscale format. With 1797 samples, each image has a label indicating the corresponding digit. Widely used in machine learning for classification and pattern recognition, each image is represented as a matrix of pixels with grayscale intensities ranging from 0 to 16.

| Characteristic | Value |
|--------------|--------------|
| `Number of Instances`    | 1797    |
| `Number of Attributes`    | 64    |
| `Attribute Information`    | 8x8 image of integer pixels in the range 0 to 16    |
| `Missing Attribute Values`    | None    |

The multiclass logistic regression model from sklearn is employed using the load_digits data. The notebook includes all the necessary code to load, analyze, and subsequently train and test the model.

## 3. Setting up

*Create a virtual enviroment with:*

```
python3 -m venv env

```
*Activate virtual enviroment:*

```
source env/bin/activate
```

*Install requirements*

```
pip install -r requirements.txt
```

## 4. Running

* *Open a Jupiter Notebook:*
* *Run All*
* *See outputs*

[![output.png](https://i.postimg.cc/gJ7ny6Tf/output.png)](https://postimg.cc/9RGmCzVp)


## 5. Conclutions:

EDA
* aproximadamente la misma cantidad de hombres que de mujeres hacen churn
* los contratos mes a mes incluyen en la decision del usuario a realizar churn
* el no tener seguridad en linea y soporte tecnico contribuyen en gran medida a a realizar churn
* el tener altos cargos mensuales y poco tiempo en la empresa influyen a que los usuarios hagan churn
* tener contrado a dos anios es un buen indicador para que el usuario no salgue de la compania
* se pueden ir seleccionando las variables que aportan mas oresicion al modelo.




## 5. Libraries and documentation

* [Python](https://www.python.org/doc/)
* [sklearn](https://scikit-learn.org/stable/)
* [pandas](https://pandas.pydata.org/)
* [numpy](https://numpy.org/)
* [matplotlib](https://matplotlib.org/)
* [seaborn](https://seaborn.pydata.org/index.html#)
* [ydata_profiling](https://docs.profiling.ydata.ai/latest/)

## 6. Sources
* [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)