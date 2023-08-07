
# ShopiMart
This project is a simple e-commerce website built using the Django framework. It allows users to browse products, add them to their cart, and check out their orders. 
## Features

- User registration and login. (User Authentication System)
- Adding and removing products from the cart
- Increasing and decreasing product quantity.
- Checkout process with payment gateway integration



## Demo

#### Home Page :
![Home Page](https://raw.githubusercontent.com/rifatjamil54/ShopiMart--django-e-commerce-project/main/demo/Screenshot%20from%202023-04-27%2009-29-26.png)
#### Add to Cart :
![Add to Cart](https://github.com/rifatjamil54/ShopiMart--django-e-commerce-project/blob/main/demo/add_to_cart.gif)
#### Paypal Payment :
![Order Placed](https://github.com/rifatjamil54/ShopiMart--django-e-commerce-project/blob/main/demo/payment.gif)



## Installation

To install the project follow these steps:

1. Clone demo branch

 ```bash
git clone -b demo https://github.com/rifatjamil54/ShopiMart--django-e-commerce-project.git
```
```bash
cd ShopiMart--django-e-commerce-project
virtualenv venv
```
2.
Activate Virtualenv :

for Linux/Mac OS
```bash
 source venv/bin/activate
 ```  
 
for Windows

```bash
 venv\Scripts\activate

```

3.
```bash
pip install -r requirements.txt
cd ShopiMart/
python manage.py runserver

```


