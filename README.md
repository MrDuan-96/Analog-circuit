# Analog-circuit
Record the process of learning analog circuit
## 第一章
### 1.PN结
    人类电子行业的发展史是由电子管转向晶体管的过程，第一个晶体管的产生无疑是推动电子行业飞速发展的契机。
    本征半导体：没有参加杂质的如锗管和硅管
                由于其自身受到温度的影响会发生电子的移动
    杂质半导体：在本征半导体的基础之上掺加5价元素P 形成P型半导体
                在本征半导体的基础之上掺加3价元素B 形成N型半导体
    
    使用工艺将P型半导体和N型半导体进行拼接，即可在两端形成PN结
    
 ### 2.稳压二极管
 
     稳压二极管可分为 单向稳压二极管和双向稳压二极管
     
     主要参数为 稳压系数α ,Uz，表现为温度每变化一度，稳压的变化
     稳压范围在4V以下采用齐纳击穿较多，7V以上采用雪崩击穿较多
     
     小于4V，由于雪纳击穿较多，温度上升，齐纳击穿越容易，更易击穿，温度系数为负
     大于7V，由于雪崩击穿较多，温度上升，齐纳击穿越不容易，更易击穿，温度系数为正
    
 
 ### 3.三极管
 
 
    双极晶体管 BJT Bipolar Junction Transistor
    
    三个区域，三个电极，两个PN结
    
    箭头的方向指的是发射结导通的方向，由P->N PN结
    
    晶体管放大电路的三种接法分为共射接法，共基接法，共集接法
    
    共射：基极和发射极构成输入回路，集电极和发射极构成输出回路。
          既能放大电流又能放大电压，输入输出电阻居三种电路之中，输出电阻较大，频带较窄。
          常用作为低频电压放大电路的单元电路。
    共基：发射极和基极构成输入回路，集电极和基极构成输出回路。
          共集电路只能放大电流不能放大电压，是三种接法中输入电阻最大、输出电阻最小的电路，具有电压跟随的特点。
          常用于电压放大电路的输入和输出级。
    共集：基极和集电极构成输入回路，发射极和集电极构成输出回路。
          只能放大电压不能放大电流，输出电阻小，电压放大倍数、输出电阻与共射电路相当，是三种接法中高频特性最好的电路。
          常作为宽频带放大电路。

 ### 4.MOS管
    MOS管可分为结型场效应管和绝缘栅型场效应管
    MOS管几乎无电流，因此其功耗而言特别低，输入电阻非常高，受温度影响较小。
    仅多子参与导电，几乎无功耗
    
 #### 4.1 N沟道增强型MOS管
    
    
    一、结构
        1° g 栅极 控制极   -> b
        2° s 源极 载流子的源泉  -> e
        3° d 漏极 载流子的漏出  -> c
    
    二、工作原理
    ![avatar](https://dfsimg1.hqewimg.com/group1/M00/12/63/wKhk713mAyaAfEUWAAA_CTEWvaw730.jpg
)
https://dfsimg1.hqewimg.com/group1/M00/12/63/wKhk713mAyaAfEUWAAA_CTEWvaw730.jpg
        
 
 
