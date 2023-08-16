# REACT_PLACE
REACT

- 修改state时，不要直接引用老的state变量
  错误的方式
  ```js
    let newList = oldList
    newList[0] = "xxx"
    setPopovers(newList)

  ```
