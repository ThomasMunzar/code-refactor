# code-refactor

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |  


## Description
For this project I fixed up a sites html and css. The website itself functioned normally and looked great from the outside, but once you got a look at the code that made up the website, where was a lot that needed to be fixed. The html document was made up of mostly ```` <div> ```` elements.
On top of all the ````<div>```` elements, the css was full of redundant code.
the code did what it was supposed to do but it was over complicated and needed to be simplified.

For instance;

some of the initial CSS code looked like this:

```CSS
 .benfit-lead {
    margin-bottom: 32px;
    color: #fffff;
}

.benefit-brand {
     margin-bottom: 32px;
    color: #ffffff;
}
.benefit-cost{
     margin-bottom: 32px;
    color: #ffffff;
}
 ```

While this works, it can be cleaned up by consolodating CSS selectors into one line since they all have the same values being added to them. 
When i did that it looked like this.


```CSS
.benefit-lead, .benefit-brand, .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```

Also in the HTML there were ```<div>``` values with the class=header. While that worked, it isnt the best practice as far as accesibility stardards go. So in this case i removed the ```<div>``` and its class and made it ```<header>```. Then I changed all the CSS selectors that were orgionally looking for class=header to look for just header.

## Learning Points

This was a hard assignment for me but I feel a bit more confident after finishing it.  Reading code is so new for me and it can get overwhelming. But now that I am starting to understand semantic html I realize why it is so important to use it.  Reading code that is made up of all div is not fun, or easy on the eyes and brain. Also, realizing that the CSS can be consolodated is a really cool practice and habbit to start as i beging my coding career.

## Author Info

Thomas Munzar is a student of the UC Berkeley Extension Coding Bootcamp. He is from Oakland, CA and is enjoying his new educaiton.

### Thomas Munzar

[Github] https://github.com/ThomasMunzar
[LinkedIn] https://www.linkedin.com/in/thomas-munzar-659b51250/


##

Special shout out to Google, WM3 school, my ASKBCS, my fellow collegues and my family.