# CSE151BCompetition Initial Setup

## 1. Create a virtual environment (Command might be different depending on OS and CLI)

```console
$ python -m venv env
```

## 2. Activate the virtual environment (Command might be different depending on OS and CLI)

This first command is for Windows using a UNIX CLI (bash, wsl)

```console
$ source env/Scripts/activate
```

This second command should work for Mac and Linux

```console
$ source env/bin/activate
```

This third command is for Powershell

```console
$ env\Scripts\activate
```

## 3. Install Dependencies (This could take a while)

```console
$ pip3 install -r requirements.txt
```

## 4. Download training and testing data

Download the data from the competition page [here](https://www.kaggle.com/competitions/cse151b-spring2022/data). Then move the test and train folders to the root of this directory.

## 5. Try running the Jupyter Notebook, you should get no errors. If you've followed all the steps and you still get error, try restarting VSCode.
