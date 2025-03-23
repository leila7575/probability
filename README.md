

#  Probability
Statistical distributions



## Description

The project implements statistical distributions:
- **Poisson**
- **Exponential**
- **Normal**
- **Binomial**

  
![3-s2 0-B9780123736956000119-f11-09-9780123736956](https://github.com/user-attachments/assets/13fe8de6-8a74-430a-a751-28f544130b96)

source: https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/probability-distribution






## Classes description

### Poisson Distribution

| Method | Description 
--- | --- 
|pmf(k) | CCalculates the PMF for a given number of successes (k)
|cdf(k)| Calculates the CDF for a given number of successes (k)

### Exponential Distribution

| Method | Description 
--- | --- 
|pdf(x) | Calculates the PDF for a given time period (x)
|cdf(x)| Calculates the CDF for a given time period (x)

### Normal Distribution

| Method | Description 
--- | --- 
|z_score(x) | Calculates the z-score for a given x-value (x)
|x_value(z)| Calculates the x-value for a given z-score (z)
|pdf(x) | Calculates the PDF for a given x-value (x).
|cdf(x)| Calculates the CDF for a given x-value (x).


### Binomial Distribution

| Method | Description 
--- | --- 
|pmf(k) | Calculates the PMF for a given number of successes (k)
|cdf(k)| Calculates the CDF for a given number of successes (k)



## Usage

PMF calculation for binomial class:

     Binomial = __import__('binomial').Binomial

    binomial = Binomial(n=10, p=0.5)
    print('binomial.pmf(30))
    print('binomial.cdf(30))


## Authors

Leila Louajri

Studying Machine Learning & AI at Holberton School Toulouse. I'm a PharmD candidate with a passion for biotechnology, machine learning, and data science. My goal is to merge machine learning techniques with biotechnology applications.

[LinkedIn](https://www.linkedin.com/in/leila-louajri-4750aa211/)
