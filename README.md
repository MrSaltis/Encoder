# Encoder

Kuriama su Python 3.6 jupyter notebook

Laboratorinio pavyzdys pavyko ir užkrovus veikia.
Bet bandant įkelti savo paveiksliukus meta klaida, kad netinkamas formatas.

Paleidimas:

1. Atsisiųsti "Anaconda 3.7" - https://www.anaconda.com/distribution/
2. Įdiegti "Anaconda".
3. Paleisti "Anacondda Prompt" failą.
4. Sukuriama python 3.6 aplinka įrašant kodą:
     conda create --name tensorflow python=3.6
5. Atidarome sukurtą aplinką:
     activate tensorflow
6. Įdiegiame Jupyter notebook:
     conda install jupyter
7. Įdiegiame Tensorflow:
     pip install --upgrade tensorflow==1.12.0
8. Įdiegiame Keras:
     pip install --upgrade keras==2.2.4
9. Linkinam naują Tensorflow aplinką su Jupyter:
     python -m ipykernel install --user --name tensorflow --display-name "Python 3.6 (tensorflow)"
9. Galiausiai nurodome kelią iki norimo folderio kur norime paleisti jupyter notebook ir rašome:
     jupyter notebook
10.Atsidarius jupyter notebook ir atidarant failą išmes lentutę, joje pasirinkti "Python 3.6 (Tensorflow)" ir spaudžiame "Set Kernel"
