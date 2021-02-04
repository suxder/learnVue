# learnVue

## 一、基本命令

- v-if &v-else
- v-show
- v-for

## 二、常用函数

### 1.数字数组排序函数

```javascript
function sortNumber(a,b) {
    return a - b
}
```

### 2.对象数组排序函数

```javascript
function sortArray(array,key) {
    return array.sort(function (a,b) {
      var x = a[key]
      var y = b[key]
      return ((x < y) ? -1 : ((x > y) ? 1 : 0))
    })
  }
```





