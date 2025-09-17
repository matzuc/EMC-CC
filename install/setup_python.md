# Installazione ambiente Python da file `environment.yml`

Questa guida spiega come creare l’ambiente Python necessario per il laboratorio utilizzando **conda** (o Miniconda).


---

## 1. Installare Miniconda (se non già presente)
Scaricare e installare Miniconda dal sito ufficiale:   [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

---

## 2. Scaricare il repository
Clonare il repository del corso o scaricarlo come file `.zip` da GitHub.  
Se si usa `git`:
```bash
git clone https://github.com/matzuc/EMC-CC.git
cd EMC-CC


```
in alternativa, scaricare il file `.zip` da  [qui](https://github.com/matzuc/EMC-CC/archive/refs/heads/main.zip). o il file *.yaml* direttamente da  [qui](environment.yaml).

---

## 3. Creare l’ambiente

```bash
conda env create -f environment.yaml
```


3. Creare l’ambiente

Dalla cartella principale del repository (dove si trova il file environment.yml):

conda env create -f environment.yml


