# Task

## Introduction

Using [FastApi](https://pypi.org/project/fastapi/) with Python 3.10 as a backend, create a simple single-page application. Style the application to resemble a bank application that you would use to send money between bank accounts.

Requirements are:

## Backend

- Have an endpoint to return all exchange rates as a json
- Have an endpoint converting price from CZK to selected currency (should by enumeration)
- To succesfully serve FastApi backend use [Uvicorn](https://pypi.org/project/uvicorn/) - [documentation](https://www.uvicorn.org/)

## Frontend

- Navigation bar (can have dummy links)
- in upper right corner
  - current time and date
  - current name day.
- Input form for bank transfer needs to have:
  - Field for amount in CZK
  - Field bank account you want to transfer money to
  - Drop down menu with currency selection
  - Field that would calculate final amount based on selected currency
- CSS can be handled via any framework or pure CSS

## Links

- Name day API can be found [here](https://nameday.abalin.net/docs/)
- For current exchange rates use this [link](https://www.cnb.cz/cs/financni-trhy/devizovy-trh/kurzy-devizoveho-trhu/kurzy-devizoveho-trhu/denni_kurz.txt)
- For working with both endpoints use [Request library](https://docs.python-requests.org/en/latest/)

##  Nice to have
- use [Vue.js](https://vuejs.org/) for frontend
- create Dockerfile for the application (use _slim_ image)
- commit everything needed to install and run the application on any computer to the Git repository. Be sure not to commit unnecessary files.
- create backend endpoint to convert between any currencies (use CZK as "bridge" currency)


Application does not have to be complete!
