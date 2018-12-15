# Bamazon

Bamazon is an Amazon-like storefront. The app will take in orders from customers and deplete stock from the store's inventory.

### Prerequisites

```
npm i  mysql

```
```
npm i inquirer
```

```
npm i console.table
```

```
npm i chalk
```

### Installing

Dependencies are listed in package JSON. To install, open the file and type the following in your terminal:

```
npm i
```

## Running the tests

Running this application will first display all of the items available for sale. The ID, name, and prices of products for sale are all included. Then, it will prompt the user with two questions:

<img width="564" alt="screen shot 2018-12-14 at 10 31 23 pm" src="https://user-images.githubusercontent.com/40437294/50040072-729ea180-fff1-11e8-857e-f88e31749d1b.png">

---

If the amount of the product selected is in stock, the user will receive back the total cost of their purchase.The product info will be shown 

<img width="520" alt="screen shot 2018-12-14 at 10 31 58 pm" src="https://user-images.githubusercontent.com/40437294/50040332-446f9080-fff6-11e8-9d3a-3272c5a2037f.png">

If the product is not in stock, the user will receive a 

---
If the user does not enter valid informaiton, an error message will be returned. 
<img width="520" alt="screen shot 2018-12-14 at 10 35 03 pm" src="https://user-images.githubusercontent.com/40437294/50046269-e8d4ef80-0055-11e9-8ddd-4a3bf564f02b.png">



---
---


## Built With
 Javascript, Node.js, SQL, Inquirer

## Authors

**Amanda Murillo** 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
