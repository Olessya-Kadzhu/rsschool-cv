# Curriculum vitae (CV)
___


![Photo](Photo_Olessya.jpg)
* **Name:** Olesya Fedchenko 
* **Age:** 28  
* **Contacts for communication:**  
    * **Discord:** olessya_42 Olessya (@Olessya-Kadzhu)  
    * **GitHub**: Olessya-Kadzhu 

___

**About me:** I started to take an interest in FrontEnd development last year. I like to learn how a website works and see how you create the functionality of the website yourself. It's both mathematics and art. I took the JustCode course from 12.05.2023 to 06.25.2024. There I studied HTML, CSS, basic and advanced JavaScript, React. I am studying Veu3 on my own.

___

**Skills:** HTML, CSS, basic JavaScript, React and Veu3.

___

**Code example:** 

```javascript
const InetShopProducts = [ // ID и создание нового элемента массива
    {id: 1, name: "Graphics tablet",brand: "Drawing numbers", price: "1500$", quantity: "111150000"},
    {id: 2,name: "Speakers", brand: "Qut loud & co", price: "500$", quantity: "550000"},
    {id: 3,name: "Biomechanical hand", brand: "Nova Terminator", price: "1500$", quantity: "11150000"},
    {id: 4,name: "Android", brand: "Metal Face corporation", price: "25500$", quantity: "1500000"},
    ];
    let NextID = InetShopProducts.length + 1;
    const GenerateID = () => {
        return NextID++;
    };
    const NewProduct = {
        id: GenerateID(),
        name: prompt("Enter the new product name:"),
        brand: prompt("Enter the new product brand:"),
        price: prompt("Enter the new product price:"),
        quantity: prompt("Enter the new product quantity:"),
    };
    InetShopProducts.push(NewProduct);
    console.log(InetShopProducts); 
```
___

**Work experience:** <https://github.com/Olessya-Kadzhu/rsschool-cv.git>