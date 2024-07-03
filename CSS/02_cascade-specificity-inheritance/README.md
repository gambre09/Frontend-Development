# What I Learned?

## 1. Cascade in Css.
Importance given to styling in css
eg. if two tag have different colors...
```
ul{
    font-weight: 700;
    color: purple;
}

ul{
    font-weight: 700;
    color: red;
}
```
then the last styling will be applied, this is called cascade rule of Css.<br>
![image](https://github.com/gambre09/Frontend-Development/assets/115577142/6b079f06-9871-4870-b0d0-11fbe0a0e486)

## 2. Specificity in Css.
Every selector(#id, .class, [attribute], <p>tags) has its specificity.
Css style is applied of those who specificity value is higher
### HTML
```
<h1 id="Hello" class="Hello">Hello World!</h1>
```
### CSS
![image](https://github.com/gambre09/Frontend-Development/assets/115577142/2e65b314-56c0-4176-ad82-1f21b9c02899)

### Output
![image](https://github.com/gambre09/Frontend-Development/assets/115577142/fb62ad45-f0ab-4c97-ab7b-ad38d4330ae1)

## 3. Inheritance
Styles which are not applied to some tags until we inherit
like...
eg. <Button>

html
```
<body>
    <h1 id="Hello" class="Hello">Hello World!</h1>
    <p>Hi, This is Abhishek Gambre</p>
    <button>Submit</button>
  </body>
```
Css
```
body{
    font-family: cursive;
    font-style: italic;
} 
```
here button will not change the font style unless its inherited.<br>
![image](https://github.com/gambre09/Frontend-Development/assets/115577142/5f72193e-1aa3-4de0-82bd-b77b0bcd7bd1)

Inherit
Css
```
body{
    font-family: cursive;
    font-style: italic;
} 

button{
    font-family: inherit;
    font-style: inherit;
}
```
![image](https://github.com/gambre09/Frontend-Development/assets/115577142/b9be8639-9be0-42bb-a98b-2326b266ca5f)