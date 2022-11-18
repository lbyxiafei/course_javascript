[toc]

# JavaScript

## Variable

### var, let, const
> var 和 let 的区别：var会检测并征用当前更高一层scope的variable的内存地址，有点类似python中的global（function scope v.s global scope例外）

> 为了避免confusion，以及与其他大多数语言一致，推荐使用`let`

> const在对象是primitive时，类似c++中的const int x: 既无法更改内容，也无法re-assign

> const在对象是非primitive时较特殊，可以更改内容，但无法re-assign

## [Projects Reference](https://github.com/bradtraversy/modern_js_udemy_projects)

## Function

### IIFE

> Immediate Invokable Function Expression

```javascript
(function sayhi(p){
    console.log(`${p} says hi`);
})('llama');
```