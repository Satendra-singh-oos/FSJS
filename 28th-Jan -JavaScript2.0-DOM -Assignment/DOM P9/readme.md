 # DOM ASSIGNMENT #

 ## 9<sup>th</sup> Assignment ##
**Intial Look of website**
 ![](./ass9.1-before.png)
 ![](./ass9.2-before.png)



- There Are Two Task that we need to perform
 
- Task - 1 -> Change the color of the Name of the product form grey to red
- Task - 2 -> on hover add the red color to the add to cart btn  

**Output**
![img](./ass9.1-after.png)

![](https://img.shields.io/badge/-Task--1-brightgreen)

**Code**

``` javascript
       const h1=document.querySelector("h1.title")
      h1.style.color="red";
    
 ```

**Output**
![img](./ass9.2-after.png)

![](https://img.shields.io/badge/-Task--2-brightgreen)

**Code**

``` javascript
        const btn =document.querySelector(".add-to-cart")
      btn.addEventListener('mouseover',()=>{
        btn.style.background='red'
      })
      
    
 ```
