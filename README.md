# notes

:point_right: more papers in this area:

- :link: [Awesome-Privacy-Computing](https://github.com/primihub/Awesome-Privacy-Computing)：1-SMPC，7-PPML
- :link: [PPML-Resource](https://github.com/Ye-D/PPML-Resource)

:point_right: content of this repository:

- [notes](#notes)
  - [1. basic theory](#1-basic-theory)
    - [1.1 paper](#11-paper)
    - [1.2 other resources](#12-other-resources)
  - [2. application: math library (for machine learning/general computation)](#2-application-math-library-for-machine-learninggeneral-computation)
    - [2.1 paper](#21-paper)
    - [2.2 other resources](#22-other-resources)
  - [3. application: PPML](#3-application-ppml)
    - [3.1 paper](#31-paper)
    - [3.2 other resources](#32-other-resources)
  - [4. application: specific scenario](#4-application-specific-scenario)
    - [4.1 paper](#41-paper)
    - [4.2 other resources](#42-other-resources)

## 1. basic theory

### 1.1 paper

- basic

| Theme | Title                                                      | Team/Main Author | Venue and Year | Key Description |
| :---- | :--------------------------------------------------------- | :--------------- | :------------- | --------------- |
| SPDZ  | :star: MP-SPDZ: A Versatile Framework for Multi-Party Computation |                  |                |                 |
| ABY   | :star: ABY                                                 |                  |                |                 |
| ABY   | :star: ABY2.0                                              |                  |                |                 |
| ABY   | :star: ABY3                                                |                  |                |                 |

- optimizing technique

| Theme | Title                                                                              | Team/Main Author | Venue and Year | Key Description |
| :---- | :--------------------------------------------------------------------------------- | :--------------- | :------------- | --------------- |
|       | :star: Pushing the Communication Barrier in Secure Computation using Lookup Tables | Ghada Dessouky   | NDSS 2017      |                 |

### 1.2 other resources 

| Theme       | Title                                                                                                                                                | Year | Key Description                                                                                                                          | Author                                                            |
| :---------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- | :--- | ---------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| 概述        | [安全多方计算学习路线](https://zhuanlan.zhihu.com/p/351492646)                                                                                       | 2021 | “SMPC的构造大体分为以下流派：①GC（混淆电路）②SPDZ（算数电路）（基于SS和SHE）③GMW（布尔电路）④ABY（算数、布尔、混淆电路的share转换）⑤FHE” | [六三 @知乎](https://www.zhihu.com/people/an-quan-xiao-qi)        |
| OT          | [混淆电路介绍（一）不经意传输](https://zhuanlan.zhihu.com/p/126396795)                                                                               | 2020 |                                                                                                                                          | [Yang Yang @知乎](https://www.zhihu.com/people/tonyyang-svail-41) |
| OT          | [Lecture 19 - Oblivious Transfer (OT) and Private Information Retrieval (PIR)](https://www.cs.princeton.edu/courses/archive/fall07/cos433/lec19.pdf) | 2007 | ①OT的定义；②OT的possible application（PIR、SFE）；②2选1-OT的构造（trapdoor permutations）；③n选1-OT的构造（复杂度O($\sqrt{n}$)           | Boaz Barak @Princeton                                             |
| GC          | [混淆电路介绍（二）逻辑电路](https://zhuanlan.zhihu.com/p/138188677)                                                                                 | 2020 | 函数->逻辑电路（e.g. 比较大小的函数）                                                                                                    | [Yang Yang @知乎](https://www.zhihu.com/people/tonyyang-svail-41) |
| GC          | [调试电路编译器CBMC-GC以及ABY时遇到的问题及解决办法](https://zhuanlan.zhihu.com/p/150512905)                                                         | 2022 | CBMC-GC：一个能把C程序转换成布尔电路的电路编译器                                                                                         | [向往的生活 @知乎](https://www.zhihu.com/people/qin-hong-75-76)   |
| GC          | [混淆电路介绍（三）混淆电路原理](https://zhuanlan.zhihu.com/p/138371497)                                                                             | 2020 |                                                                                                                                          | [Yang Yang @知乎](https://www.zhihu.com/people/tonyyang-svail-41) |
| GMW         | [GMW Protocol](https://zhuanlan.zhihu.com/p/237061306)                                                                                               | 2020 | ①由2选1-OT构造n选1-OT（复杂度O(n)）；②用n选1-OT安全计算任意constant size函数；③GMW Protocol                                              | [Yang Yang @知乎](https://www.zhihu.com/people/tonyyang-svail-41) |
| :star: SPDZ |                                                                                                                                                      |      |                                                                                                                                          |                                                                   |                                                                   
| :star: ABY  |                                                                                                                                                      |      |                                                                                                                                          |                                                                   |                                                                   

## 2. application: math library (for machine learning/general computation)

### 2.1 paper

| Title                                               | Team/Main Author  | Venue and Year | Security Setting | Key Description |
| :-------------------------------------------------- | :---------------- | :------------- | :--------------- | --------------- |
| :star: SIRNN                                        | Deevashwer Rathee | S&P 2021 |                  |                 |
| :star: SecFloat                                     | Deevashwer Rathee | S&P 2022        |                  |                 |
| :star: Secure Computation on Floating Point Numbers | Mehrdad Aliasgari | NDSS 2013      |                  |                 |

### 2.2 other resources

| Theme | Title | Author | Year | Key Description |
| :---- | :---- | :----- | :--- | --------------- |
|       |       |        |      |                 |

## 3. application: PPML

### 3.1 paper

- Semi-honest

| Title                                                                                    | Team/Main Author  | Venue and Year | Security Setting | Support Secure Training? | Key Description | Key Reference / Idea |
| :--------------------------------------------------------------------------------------- | :---------------- | :------------- | :--------------- | ------------------------ | --------------- | -------------------- |
| CryptoNets                                                                               |                   |                |                  |                          |                 |                      |
| MiniONN                                                                                  |                   |                |                  |                          |                 |                      |
| Chamelon                                                                                 |                   |                |                  |                          |                 |                      |
| SecureML                                                                                 |                   |                |                  |                          |                 |                      |
| Delphi                                                                                   |                   |                |                  |                          |                 |                      |
| :star: Optimizing Privacy-Preserving Outsourced Convolutional Neural Network Predictions | Minghui Li        | TDSC 2022      |                  |                          |                 |                      |
| CrypTFlow                                                                                |                   |                |                  |                          |                 |                      |
| CrypTFlow2                                                                               |                   |                |                  |                          |                 |                      |
| Cheetah                                                                                  |                   |                |                  |                          |                 |                      |
| :star: Secure Floating-Point Training                                                    | Deevashwer Rathee | USENIX 2023 |                  |                          |                 |                      |

- Malicious

| Title       | Team/Main Author | Venue and Year | Structure / Num of Parties | Support Secure Training? | Key Description | Key Reference / Idea |
| :---------- | :--------------- | :------------- | :------------------------- | ------------------------ | --------------- | -------------------- |
| SecureNN    |                  |                |                            |                          |                 |                      |
| Falcon      |                  |                |                            |                          |                 |                      |
| Muse        |                  |                |                            |                          |                 |                      |
| :star: SIMC |                  |                |                            |                          |                 |                      |

### 3.2 other resources

| Theme | Title                 | Author                                | Year | Key Description                            |
| :---- | :-------------------- | :------------------------------------ | :--- | ------------------------------------------ |
|       | :star: [2022 Summer School on PPML](https://www.conferencemanager.dk/ppmlschool2022) | 很多                                     | 2022 | 很多关于PPML的slide |
|       | EzPC系列论文总结&介绍[【part1】](https://medialib.cmcdn.dk/medialibrary/7B031F9C-64B5-43B7-B5AC-D0DF772C7975/00E11E10-8E32-ED11-84B6-00155D0B0940.pdf)[【part2】](https://medialib.cmcdn.dk/medialibrary/7B031F9C-64B5-43B7-B5AC-D0DF772C7975/516EB609-8E32-ED11-84B6-00155D0B0940.pdf) | Divya Gupta @Microsoft Research India | /    | 介绍CrypTFlow2、SIRNN、Llama、SecFloat |

## 4. application: specific scenario

### 4.1 paper

| Title                                                                                                          | Team/Main Author | Venue and Year | Key Description |
| :------------------------------------------------------------------------------------------------------------- | :--------------- | :------------- | :-------------- |
| End-to-end Privacy Preserving Training and Inference for Air Pollution Forecasting with Data from Rival Fleets |                  |                |                 |

### 4.2 other resources

| Theme | Title | Author | Year | Key Description |
| :---- | :---- | :----- | :--- | --------------- |
|       |       |        |      |                 |

