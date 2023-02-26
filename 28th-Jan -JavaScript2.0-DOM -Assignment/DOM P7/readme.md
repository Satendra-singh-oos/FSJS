 # DOM ASSIGNMENT #

 ## 7<sup>th</sup> Assignment ##
**Intial Look of website**
 ![](./ass7.1-before.png)
 ![](./ass7.2-after.png)
 


- There Are Two Task that we need to perform
 
- Task - 1 -> Remove the languages that have 2.0 in their
            name(Every alternative language) 
- Task - 2 -> Use JavaScript to write something in the input box
            and submit the form. This should refresh the page and the languages
            in the left card should come back. 


**Output**
![img](./ass7.1-after.png)

![](https://img.shields.io/badge/-Task--1-brightgreen)

**Code**

``` javascript
   const main =document.querySelector(".main__languages");
      const link = main.querySelectorAll("a")
      
      for(let i=0; i<link.length;i++){
        if(link[i].textContent.includes('2.0')){
          link[i].remove(); 
        }
      }
 ```


**Output**
![img](./ass7.2-after.png)


 ![](https://img.shields.io/badge/-Task--2-brightgreen)

**Code**

``` javascript
const input =document.querySelector(".main__form-input")
      const btn =document.querySelector(".main__form-btn")
      
      input.disabled =false
      btn.disabled=false;
      
      btn.addEventListener('click',(event)=>{
        window.location.reload()
        
      })     
    
 ```





