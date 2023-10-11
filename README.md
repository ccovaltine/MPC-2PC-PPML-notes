# MPC-2PC-PPML-notes

- [MPC-2PC-PPML-notes](#mpc-2pc-ppml-notes)
  - [1. basic theory](#1-basic-theory)
    - [1.1 paper](#11-paper)
    - [1.2 other resources](#12-other-resources)
  - [2. general computation framework](#2-general-computation-framework)
    - [2.1 paper](#21-paper)
    - [2.2 other resources](#22-other-resources)
  - [3. ML framework](#3-ml-framework)
    - [3.1 paper](#31-paper)
    - [3.2 other resources](#32-other-resources)
  - [4. specific application](#4-specific-application)
    - [4.1 paper](#41-paper)
    - [4.2 other resources](#42-other-resources)

## 1. basic theory

### 1.1 paper

- basic

| Title      | Team/Main Author | Venue and Year | Key Description |
| :--------- | :--------------- | :------------- | :-------------- |

- optimizing technique

| Title                                                                       | Team/Main Author | Venue and Year | Key Description |
| :-------------------------------------------------------------------------- | :--------------- | :------------- | :-------------- |
| :star: Pushing the Communication Barrier in Secure Computation using Lookup Tables | Ghada Dessouky   | NDSS 2017      |  |

### 1.2 other resources 

| Theme | Title                                                                                                                                                | Author                                                            | Year | Key Description                                                                                                                |
| :---- | :--------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------- | ---- | ------------------------------------------------------------------------------------------------------------------------------ |
| OT    | [混淆电路介绍（一）不经意传输](https://zhuanlan.zhihu.com/p/126396795)                                                                               | [Yang Yang @知乎](https://www.zhihu.com/people/tonyyang-svail-41) | 2020 |                                                                                                                                |
| OT    | [Lecture 19 - Oblivious Transfer (OT) and Private Information Retrieval (PIR)](https://www.cs.princeton.edu/courses/archive/fall07/cos433/lec19.pdf) | Boaz Barak @Princeton                                             | 2007 | ①OT的定义；②OT的possible application（PIR、SFE）；②2选1-OT的构造（trapdoor permutations）；③n选1-OT的构造（复杂度O($\sqrt{n}$) |
| GC    | [混淆电路介绍（二）逻辑电路](https://zhuanlan.zhihu.com/p/138188677)                                                                                 | [Yang Yang @知乎](https://www.zhihu.com/people/tonyyang-svail-41) | 2020 | 函数->逻辑电路（e.g. 比较大小的函数）                                                                                          |
| GC    | [混淆电路介绍（三）混淆电路原理](https://zhuanlan.zhihu.com/p/138371497)                                                                             | [Yang Yang @知乎](https://www.zhihu.com/people/tonyyang-svail-41) | 2020 |                                                                                                                                |
| GMW   | [GMW Protocol](https://zhuanlan.zhihu.com/p/237061306)                                                                                               | [Yang Yang @知乎](https://www.zhihu.com/people/tonyyang-svail-41) | 2020 | ①由2选1-OT构造n选1-OT（复杂度O(n)）；②用n选1-OT安全计算任意constant size函数；③GMW Protocol                                    |

## 2. general computation framework

### 2.1 paper

| Title                                               | Team/Main Author  | Venue and Year | Security Setting | Key Description |
| :-------------------------------------------------- | :---------------- | :------------- | :------------- | --------------- |
| ABY                                                 |                   |                |                |                 |
| ABY2.0                                              |                   |                |                |                 |
| ABY3                                                |                   |                |                |                 |
| :star: SIRNN                                        | Deevashwer Rathee |                |                |                 |
| :star: SecFloat                                     | Deevashwer Rathee | SP 2022        |                |                 |
| :star: Secure Computation on Floating Point Numbers |                   |                |                |                 |

### 2.2 other resources

| Description | Author | Year | URL |
| :---------- | :----- | :--- | :-- |
|             |        |      |     |

## 3. ML framework

### 3.1 paper

- Semi-honest

| Title                                                                             | Team/Main Author | Venue and Year | Security Setting | Support Secure Training? | Key Description | Key Reference / Idea |
| :-------------------------------------------------------------------------------- | :--------------- | :------------- | :----------------------- | ------------------------ | --------------- | -------------------- |
| CryptoNets                                                                        |                  |                |                          |                          |                 |                      |
| MiniONN                                                                           |                  |                |                          |                          |                 |                      |
| Chamelon                                                                          |                  |                |                          |                          |                 |                      |
| SecureML                                                                          |                  |                |                          |                          |                 |                      |
| Delphi                                                                            |                  |                |                          |                          |                 |                      |
| :star: Optimizing Privacy-Preserving Outsourced Convolutional Neural Network Predictions | Minghui Li       | TDSC 2022      |                          |                          |                 |                      |
| CrypTFlow                                                                         |                  |                |                          |                          |                 |                      |
| CrypTFlow2                                                                        |                  |                |                          |                          |                 |                      |
| Cheetah                                                                           |                  |                |                          |                          |                 |                      |
| :star: Secure Floating-Point Training                                             |                  |                |                          |                          |                 |                      |

- Malicious

| Title    | Team/Main Author | Venue and Year | Structure / Num of Parties | Support Secure Training? | Key Description | Key Reference / Idea |
| :------- | :--------------- | :------------- | :------------------------- | ------------------------ | --------------- | -------------------- |
| SecureNN |                  |                |                            |                          |                 |                      |
| Falcon   |                  |                |                            |                          |                 |                      |
| Muse     |                  |                |                            |                          |                 |                      |
| SIMC     |                  |                |                            |                          |                 |                      |

### 3.2 other resources

| Description       | Author | Year | URL |
| :---------------- | :----- | :--- | :-- |
| EzPC系列总结&介绍 |        |      |     |

## 4. specific application

### 4.1 paper

| Title                                                                                                          | Team/Main Author | Venue and Year | Key Description |
| :------------------------------------------------------------------------------------------------------------- | :--------------- | :------------- | :-------------- |
| End-to-end Privacy Preserving Training and Inference for Air Pollution Forecasting with Data from Rival Fleets |                  |                |                 |

### 4.2 other resources

| Description | Year | Author | URL |
| :---------- | :--- | :----- | :-- |
|             |      |        |     |
