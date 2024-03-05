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

## units
-Responsive
```80vw``` This represents 80% of the viewport's width
```80vh``` This denotes 80% of the viewport's height

The choice between using `em` and `rem` in CSS depends on the specific use case and desired outcome. Here are some general guidelines:

1. **Use `em`** when you want to scale the font size based on the parent element's font size. This is useful for creating a consistent design where certain elements should scale proportionally with their parent elements.

2. **Use `rem`** when you want to maintain a fixed font size regardless of the parent element's font size. This is ideal for elements that should always have the same font size, regardless of the parent's font size.

For example, if you have a navigation bar that should always have the same font size, regardless of the parent element's font size, you would use `rem`. On the other hand, if you have a heading that should scale proportionally with its parent element's font size, you would use `em`.

In summary, use `em` when you want to scale font sizes based on the parent element's font size, and use `rem` when you want to maintain a fixed font size regardless of the parent element's font size.
