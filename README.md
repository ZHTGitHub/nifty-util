# nifty-util

nifty-util是一个实用而简单的JavaScript工具库。

## 安装

从GitHub上下载[最新的nifty-util](https://github.com/ZHTGitHub/nifty-util)，或使用[npm](https://github.com/ZHTGitHub/nifty-util)安装:

```bash
npm install nifty-util
```

## 如何使用

```bash
import util from 'nifty-util'
// or
import { isEqual } from 'nifty-util'
```

### isEqual(val1, val2)

判断两个值是否绝对相等，数组/对象只比较其属性值是否绝对相等

#### Arguments

val1: 任意值

val2: 任意值

#### Returns

(boolean): 若两个值绝对相等返回true，否则返回false.


#### Example

```bash
const result = isEqual(1, '1')
console.log(result)
// => false
```

### isYummy(value)

判断值是否合法

#### Arguments

value: 任意值

#### Returns

(boolean): 若值不为undefined、null、false、空字符串、空数组、空对象返回true，否则返回false.


#### Example

```bash
const result = isYummy({})
console.log(result)
// => false
```


