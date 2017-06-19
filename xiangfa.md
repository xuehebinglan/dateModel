

## 我的想法

`curIdx`, `preIdx`, `winIdx`,
- 如果 `curIdx`对应的date `arrToDate(showArr[curIdx])`,跟全局存好的startDate相差小于等于2天，
    - 则`startLeft == 0`
- 如果 等于3天，`startLeft = -1`
- 如果 大于等于4天，`startLeft = -2`
- 如果 等于dLen-3， `startLeft = -3`
- 如果 等于dLen-2,dLen-1和 dLen， `startLeft = -4`

[0,1,2,3,4,5,6,7,8]

startDate，如果curIdx在前三个:
- eleLeft = [0,100,200,300,400,500,600,700,800]
- containerLeft = 
    
    
    
开始判断各种情况

首先根据长度

一、 结尾

[11,12,13,14,15,16,17,18,19]

最后9个数

- 如果框中最后5个，[15,16,17,18,19]
    - 点 19 ，18 ，17 都没事
