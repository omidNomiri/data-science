# Plot exercise

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)

## About <a name = "about"></a>

in this part i code some plot like covid death in iran, order by month in digikala and solve problem of online retail.

### Output

#### Online retail

monthly growth
![Online retail](output/monthly_growth.png)

exist member and new member
![Exist Vs New](output/Exist_Vs_New.png)

#### Covid 19

daily death in iran
![daily death iran](output/daily_death_iran.png)

#### Digikala plot

digikala order by month
![order by month](output/order_by_month.png)

digikala customer by city
![customer by city](output/customer_by_city.png)

## Getting Started <a name = "getting_started"></a>

### Installing

First of all you need install requirements library copy this code and run in terminal.

``` terminal
pip install -r requirements.txt
```

## Usage <a name = "usage"></a>

After you install requirements library you can choice between the projects and run it.

### online retail

``` terminal
jupyter nbconvert --to script online_retail_plot.ipynb
```

### Covid19

``` terminal
jupyter nbconvert --to script covid_19_plot.ipynb
```

### digikala plot

``` terminal
jupyter nbconvert --to script digikala_plot.ipynb
```
