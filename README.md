<div align="center">
  <h1>Aux Cord - socialized music recommendation app </h1>
  Try it out with a friend here: https://aux-cord.onrender.com/
</div>
<div></div>
<img width="1362" alt="Screen Shot 2024-02-07 at 2 37 32 AM" src="https://github.com/ftrichardson/aux-cord/assets/141296571/5f2447ed-84a1-4eee-8b00-f36938a5caa2">

## Table of Contents
- [Demo](#demo)
- [Built With](#built-with)
- [Extended Description](#extended-description)
- [Usage](#usage)


## Demo
* pandas
* scikit-learn
* requests
* spotipy

## Built With

https://github.com/ftrichardson/aux-cord/assets/141296571/deda1565-3119-47c6-8b73-e72ab9633f1d

## Extended Description

## Usage

**1.** Clone the repository and navigate to aux-cord/ui directory
```python
git clone https://github.com/ftrichardson/aux-cord

cd aux-cord/ui
```

**2.** Create and activate a virtual environment
```python
virtualenv env

source env/bin/activate
```

**3.** Install dependencies
```python
pip install -r requirements.txt
```

**4.** Set up migrations
```python
python manage.py migrate
```

**5.** Start project's development server
```python
python manage.py runserver
```

**6.** Open your web browser and visit <a href="http://127.0.0.1:8000/" target="_blank">http://127.0.0.1:8000/</a> to access the application.
