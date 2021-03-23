create env

conda create -n wineq python=3.7 -y
activate env

conda activate wineq
created a req file

install the req

pip install -r requirements.txt
download the data from

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

#python src/get_data.py
#run dvc repro
# git add . and commit -m "stage one a"
#run dvc repro
# git add . and commit -m "stage two"
# run dvc metrics show
# run dvc metrics diff
#run dvc repro
# git add . and commit -m "tracker added"

# run  pytest -v
# run tox
# run tox
pip insall -e .
tox  command :
bash
for rebuilding .
tox -r
pytest command:
pytest -v
setup command:
pip install -e .
(pep8
flacke8)


build your own packages commands:
python setup.py install

tox command -

tox
for rebuilding -

tox -r
pytest command

pytest -v
setup commands -

dEPLOY:
1. mkdir .github\workflows\cli

pip install -e .
build your own package commands-

python setup.py sdist

git init
git add . && git commit -m "webapp created && tested" git push origin main

############ Deploy on heroku ################
1 mkdir .github\workflows\
2 touch .github\workflows\ci-cd.yaml
3 git add . && git commit -m "github work flow added" && git push origin main
4. Procfile created