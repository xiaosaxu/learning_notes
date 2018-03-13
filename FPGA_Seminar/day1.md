

 - 回路
 - 布尔函数
 - Verilog

 FPGA

 - running on AWS
 - 電子工作Verilog
 - 

## 补码

- 3位比特可以表示无符号整数: 0到7 
- 3位比特可以表示带符号的整数: -4到3
- 4位比特可以表示无符号整数: 0到15 
- 4位比特可以表示带符号的整数: -8到7

## 实现一个3位比特加法器

 - 两个输入, 3比特下的0到7(无符号整数)
 - 输出为4位比特, 取值从0到14

具体步骤:
 - 实现一个半加法器
    - 输入两个1比特数, 输出1比特的结果位和进位位
 - 实现一个全加法器
    - 输入两个1比特的加数 和 进位位, 输出 结果位和进位位

## 实现一个3位比特的减法器

 - 被减数的取值范围是0到7
 - 减数的取值范围是0到4
 - 输出的取值范围是 -4到7, 是4比特位的带符号整数


具体步骤:
 - 实现一个补码器, 对于给定的3比特输入, 输出其补码

## 实现一个计数器

 - 对于给定的输入, 输出其中比特位是1的个数

 