# REACT_PLACE
REACT

- 修改state时，不要直接引用老的state变量
  错误的方式
  ```js
    let newList = oldList
    newList[0] = "xxx"
    setPopovers(newList)

  ```

- 使用useEffect第二个参数来控制依赖，当依赖发生变更，才执行useEffect里的代码
  ```js
    useEffect(()=>{},[attr1])

  ```

- 不要将jsx存放在state里！！！
