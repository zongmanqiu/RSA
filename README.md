# RSA: 用于响应面分析的SPSS宏    
# RSA: SPSS macro for response surface analysis    
*Copyright (C) 2021-2023 by Qiu Zongman    
*License: Apache 2.0    
*E-mail: qiuzongman@foxmail.com    
*Research Gate: Zongman Qiu    
*Bilibili: 邱宗满 (ID: 423767625)    
*微信公众号: 邱宗满 (ID: qiuzongman2020)    
*项目托管在Github: https://github.com/zongmanqiu/RSA    
    
# 功能    
## 二阶RSA    
*20个二阶RSA核心参数    
*Z-hat检验    
*Wald检验    
*受约束的二阶RSA模型，包括上升岭和严格模型    
## 有调节的二阶RSA    
*可设定调节变量水平    
## 三阶RSA    
*三阶RSA参数    
*Wald检验    
*受约束的三阶RSA模型，包括非对称和水平依赖模型，及其对应的上升岭和严格模型    
*范围检查    
## 其它功能    
*数据转换    
*稳健标准误    
*Bootstrap估计    
*边际均值估计，及其配对比较    
*数据保存：变量、Bootstrap估计，以及三阶RSA的范围检查    

# 更新日志    
## [4.0.1] - 2023-1-6    
### 修复    
*Delta方法中的一个错误，这个错误会导致二阶RSA模型参数标准误在特定条件下错位，例如p11和p21的标准误位置互换    
