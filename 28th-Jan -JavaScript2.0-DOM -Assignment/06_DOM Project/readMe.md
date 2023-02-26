 # DOM ASSIGNMENT #

 ## 6<sup>th</sup> Assignment ##
**Intial Look of website**
 ![](./Solution/inital.png)


- The Task is to performa the following given task
 
- 1-> change the equalizer to iNeouron Logo 
- 2-> Changing the pricing of th tag from $4 to $10 
- 3-> Add linkdin icon in the footer


**Output**
![img](./Solution/out.png)

![](https://img.shields.io/badge/-Task--1-brightgreen)

**Code**

``` javascript
    const head=document.querySelector("header")
    //console.log(head);
    const logo=head.querySelector("img")
    logo.src="./assets/ineuron-logo.png"
     
 ```


 ![](https://img.shields.io/badge/-Task--2-brightgreen)

**Code**

``` javascript
    const price=document.querySelector(".app_price")
    // console.log(price);
    const span=price.querySelector("span")
    span.textContent="$10"
     
 ```


![](https://img.shields.io/badge/-Task--3-brightgreen)

**Code**

``` javascript
    const footer=document.querySelector(".footer_social")
  
    const div = document.createElement("div")
    div.className="footer_social_ico"
    
    const linkdin=document.createElement("i")
    linkdin.className="fa-brands fa-linkedin"

    div.appendChild(linkdin)
   footer.appendChild(div)
     
 ```
