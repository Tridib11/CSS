# CSS - learning path

## To remove default css

```
*{
    margin: 0;
    padding: 0;
}
```

## CSS Box Model - Margin, Padding & Borders

## box-sizing: border-box;
 ```
 {
  height:200px,
  box-sizing: border-box
 }
  ```
  - When this is used it means that the 200px includes the content
    ,padding and border but not margin
    if you dont use this then it means that 200px is only for a 
    certain thing not the included thing


## Margin Collapse

```
{
  .box2{
    color: white;
    background-color: blue;
    padding: 10px;
    margin: 25px;
    border: 2px solid black;
    height: 200px;
    box-sizing: border-box;
}
.box1{
    color: yellow;
    background-color: blue;
    padding: 10px;
    margin: 25px;
    border: 2px solid black;
    height: 200px;
    box-sizing: border-box;
}

}
```
- Suppose you have done something like this then it will fall under a category called as Margin collapse where if you have 2 boxes then the one having the greatest margin will be used suppose u have ``` magin:35px ``` in box1 and ``` margin:25px ``` in box2 then the 35px will be used in the between and 25px will be ignored

## To center text

```
{
  text-align:center;
}
```