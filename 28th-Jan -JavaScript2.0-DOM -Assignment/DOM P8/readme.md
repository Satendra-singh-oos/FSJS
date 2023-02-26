 # DOM ASSIGNMENT #

 ## 8<sup>th</sup> Assignment ##
**Intial Look of website**
 ![](./ass8.1-before.png)
 ![](./ass8.2-before.png)
 ![](./ass8.3-before.png)
 


- There Are Two Task that we need to perform
 
- Task - 1 -> Add the border in the side-box text
- Task - 2 ->  Remove the background and make it into white 
- Task - 3 ->  To make the navbar expand by onClick toggle in the small size screen 

**Output**
![img](./ass8.1-after.png)

![](https://img.shields.io/badge/-Task--1-brightgreen)

**Code**

``` javascript
      const side =document.querySelector(".new")
      side.style.border = "5px solid red";
    
 ```

 **Output**
![img](./ass8.2-after.png)

![](https://img.shields.io/badge/-Task--2-brightgreen)

**Code**

``` javascript
      const body=document.querySelector("body")
      body.style.background ="#FFFF"

    
 ```


 **Output**
![img](./ass8.3-after.png)

![](https://img.shields.io/badge/-Task--3-brightgreen)

**Code**

``` javascript
   const navBtn =document.querySelector(".navbar-toggler")
      const show=document.querySelector(".navbar-collapse")
      //console.log(show);
      navBtn.addEventListener('click',()=>{
        show.classList.toggle('show')
      })
    
 ```
