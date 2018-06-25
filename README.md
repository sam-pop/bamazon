# bamazon

bamazon is a command line node/mySQL Amazon-like storefront app.

The app will take in orders from customers and deplete stock from the store's inventory, track product sales across the store's departments and provide a summary of the sales, over head expanses and profits of the store's departments.

## How to use

Prerequisites:

* mySQL server
* Node.js
* NPM (package manager)

Before running the app you will have to use the `npm install` command from the command-line in order to install the required packages (using the _package.json_ file).

Make sure your mySQL server is up and running in the background -> in the mysql console (`mysql -u root`) run the command `source schema.sql` to build our sql schema.

Run the following commands:
`node bamazonCustomer.js` - Customer view.
`node bamazonManager.js` - Manager view.
`node bamazonSupervisor.js` - Supervisor view.

**Below are examples of the different store views:** _(click on the image for the full video)_

### Customer View

[![bamazon_Customer.gif](https://s8.postimg.cc/c38ci1rlx/bamazon_Customer.gif)](https://youtu.be/cKullh4pPqQ)

### Manager View

[![bamazon_Manager.gif](https://s8.postimg.cc/gcd2kb2lx/bamazon_Manager.gif)](https://youtu.be/o5I7rBO1v5k)

### Supervisor View

[![bamazon_Supervisor.gif](https://s8.postimg.cc/cfzqocchh/bamazon_Supervisor.gif)](https://youtu.be/Q20lfLzt8ig)