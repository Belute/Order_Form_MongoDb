# Order_Form_MongoDb

This project is for **educational** porpuses only. 

## Project features

-   CSS
-   Html
-   Js
-   NodeJs
-   MongoDb


### Authors

Justinas: [Github](https://github.com/Belute)

#### How To Use


- Open integrated terminal for backend directory and rename it: backend

- Open integrated terminal for frontend directory and rename it: frontend

- In backend terminal type: npm install nodemon

- In backend terminal type: npm run start

- In frontend terminal type: npm install

- In frontend terminal type: npm run start

- Open MongoDb, create database OrderManagement

- Create orders and products inside OrderManagement



##### How To Use

```css
.container {
    font: bold 15px Poppins,
        sans-serif;
    position: fixed;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: rgb(238, 174, 202);
    background: radial-gradient(circle, rgba(238, 174, 202, 1) 0%, rgba(232, 236, 241, 1) 100%);

}
```
```js
       document.querySelectorAll('.delete').forEach(element => {
        let id = document.querySelector(".tr").getAttribute('data-id')

        element.addEventListener('click', () => {
            console.log(id)


            transferData(url + '/orders/delete-data/' + id, 'DELETE')
                .then(resp => {

                    location.reload();
                })
            getData()
        })


    })



```
```html
  <div class="form-group">
                            <label>Pavardė</label>
                            <input type="text" name="last_name" class="form-control">
                        </div>
                        <div class="form-group">
                            <label>Adresas</label>
                            <input type="text" name="address" class="form-control">
                        </div>
```
