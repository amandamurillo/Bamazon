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

<img width="519" alt="screen shot 2018-12-15 at 4 39 04 pm" src="https://user-images.githubusercontent.com/40437294/50048708-3e29f480-0088-11e9-9a00-9d82e0415a7d.png">

---

If the amount of the product selected is in stock, the user will receive back the total cost of their purchase. Additionally, the product information: ID, name, department, price and stock quantity will be upadated to in our database, and shown.

<img width="520" alt="screen shot 2018-12-15 at 5 40 36 pm" src="https://user-images.githubusercontent.com/40437294/50049082-dc21bd00-0090-11e9-8d59-46e19d711663.png">

If the product is not in stock, the user will receive a 

<img width="521" alt="screen shot 2018-12-14 at 10 36 32 pm" src="https://user-images.githubusercontent.com/40437294/50048839-9bbf4080-008a-11e9-92ed-b66c660b8be9.png">

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
