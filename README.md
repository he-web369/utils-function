<!--
 * @Author: hsl
 * @Descripttion: js工具函数库
 * @Date: 2021-11-19 15:28:04
 * @LastEditTime: 2021-11-19 16:15:37
-->
# Javascript 函数库(test edition)
## 导出方式：commonJS
## 使用方式(usage)：
    const utils = require('he-utils')
    utils.deepClone(args)
## 方法列表
### 1.deepClone(对象深拷贝)：
    params: obj:object
### 2.fillSudoku(填充残缺数独)：
    params: board:Array<Array<string>>
### 3.solveNQueens(解决n皇后问题)：
    params: n:number
    