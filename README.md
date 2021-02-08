# Magneds VueJS Test
For this application, we want to display the contents of the JS file you find [here](src/fixtures/pxtqu8tf3c69m4wus0t9s8wzt.json)

__The project has been left in its state that matches that of the vue-cli create command. Cleanup and remove any parts that you feel 
are not needed__

The expectations are as follows:
* Create the design as you see [here](./vue-magneds-test.png)
* Introduce navigation using 'VueRouter' between the Homepage and this page
* On the rendering of the blocks. Enable it so I can click on it, and it will fill the block to 100 value.
* Color the blocks based off their value.
    * 0 = Grey
    * 100 = Purple
* When the last block is clicked, have a modal open displaying the following message:
    * "Good job on completing your collection!"
    * The modal will close when clicking outside the modal or on the 'Close' button

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```
