# Julia Zakharova

## Contacts

* Address: Russia, Nizhny Novgorod
* Phone: +7(960)1977278
* Email: sorulaijuli@gmail.com
* GitHub: [JuliaSoru](https://github.com/JuliaSoru)

***

## About me

I started programming at the institute. I had experience in backend product development on python for about a year. I solved many tasks on integration of various servers with the backend. Developed an API for an online school server.

***

## Skills

* Git
* HTML
* CSS
* Python
* Django
* Django rest framework
* Celery
* PostgreSQL
* WebSocket

***

## Code Examples

```
const products = {
    rootProducts: document.getElementById('catalog'),
    render: function () {
        let htmlCatalog = ''
        for (let i of CATALOG) {
            htmlCatalog += `
            <li class="product-element" data-id="${i.id}">
            <span class="product-element__name">${i.name}</span>
            <img class="product-element__img" src="${i.img}" alt="Sneakers">
            <span class="product-element__price">${i.price.toLocaleString()} USD</span>
            <button class="product-element__btn">Add to cart</button> 
           
            </li>
            `
        }
        this.rootProducts.innerHTML = `
        <ul class="product-container">
        ${htmlCatalog}
        </ul>
        `
    }
} 
```
