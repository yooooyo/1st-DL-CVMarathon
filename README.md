# 資料科學學習地圖

[![hackmd-github-sync-badge](https://hackmd.io/MJUqlpCzTe2lABohydZQZQ/badge)](https://hackmd.io/MJUqlpCzTe2lABohydZQZQ)


---

<img src="https://github.com/chenkenanalytic/img/blob/master/spe-ke/%E5%AD%B8%E7%BF%92%E8%97%8D%E5%9C%96.jpg?raw=true" style="zoom: 25%;" />

# 機器學習 百日馬拉松

---

<img src="https://camo.githubusercontent.com/097fbf775d6614c786514b800ce9f475ed01d3f3/68747470733a2f2f692e696d6775722e636f6d2f7a4931307a6a352e706e67" alt="Map" style="zoom:80%;" />

---

### 先備知識

##### 關於機器學習的大概念 ：[Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/ml-intro)

##### Numpy套件                         ：[從零開始學資料科學：Numpy 基礎入門](https://blog.techbridge.cc/2017/07/28/data-science-101-numpy-tutorial/)

##### Pandas套件                         ：[從pandas開始Python與資料科學之旅 ](https://medium.com/datainpoint/%E5%BE%9E-pandas-%E9%96%8B%E5%A7%8B-python-%E8%88%87%E8%B3%87%E6%96%99%E7%A7%91%E5%AD%B8%E4%B9%8B%E6%97%85-8dee36796d4a)

---


| Day | Topic                                                                                | Source | Progress |
|:---:|:------------------------------------------------------------------------------------ | ------ | --- |
|  1  | [資料介紹與評估資料](#Day-1-資料介紹與評估資料)                                      |        |     |
|  2  | [機器學習概論](#機器學習概論)                                                        |        |     |
|  3  | [機器學習-流程與步驟](#機器學習-流程與步驟)                                          |        |     |
|  4  | [EDA/讀取資料與分析流程](#EDA/讀取資料與分析流程)                                    |        |     |
|  5  | [如何新建一個 dataframe?如何讀取其他資料?](#如何新建一個dataframe?如何讀取其他資料?) |        |     |
|  6  | [EDA：欄位的資料類型介紹及處理](#EDA：欄位的資料類型介紹及處理)                      |        |     |
|  7  | [特徵類型](#特徵類型)                                                                |        |     |
|  8  | [EDA資料分佈](#EDA資料分佈)                                                          |        |     |
|  9  | [EDA：Outlier及處理](#EDA：Outlier及處理)                                      |        |     |
| 10  | [數值型特徵-去除離群值](#數值型特徵-去除離群值)                                      |        |     |
| 11  | Text                                                                                 |        |     |
| 12  | Text                                                                                 |        |     |
| 13  | [常用的DataFrame操作](#常用的DataFrame操作)                                          |        |     |
| 14 |  | | |
| 15 |  | | |
| 16 | [EDA: 不同數值範圍間的特徵如何檢視/繪圖與樣式Kernel Density Estimation (KDE)](#EDA:不同數值範圍間的特徵如何檢視/繪圖與樣式Kernel-Density-Estimation-\(KDE\)) | | |
| 17 | [EDA: 把連續型變數離散化](#EDA: 把連續型變數離散化) | | |

# 資料介紹與評估資料
# 機器學習概論
# 機器學習-流程與步驟
# EDA/讀取資料與分析流程
# 如何新建一個dataframe?如何讀取其他資料?
# EDA：欄位的資料類型介紹及處理
# 特徵類型
# EDA資料分佈
# EDA ：Outlier及處理
# 數值型特徵-去除離群值
# 
# 

# 常用的DataFrame操作
## HOMEWORK

# <font color=#1B7CEB>EDA:不同數值範圍間的特徵如何檢視/繪圖與樣式Kernel Density Estimation (KDE)</font>

## 目的

**- 知道 matplotlib 的其他 theme**

**- 學會什麼是 Kernel Density Estimation (KDE) 與如何繪製**

## 繪圖風格

- plt.style.use(‘default’) # 不需設定就會使用預設
- plt.style.use('ggplot')
- plt.style.use(‘seaborn’) # 或採用 seaborn 套件繪圖

![ default ggplot seaborn 風格](https://ai100-fileentity.cupoy.com/ml100/dailytask/1586225294169/1594093518238)



> **<font color=#1B7CEB> 轉變繪圖風格的目的 </font>**

用已經被設計過的風格, 讓觀看者更清楚明瞭，包含色彩選擇、線條、樣式等。

## Kernel Density Estimation (KDE)

> 不同 kernel function 的結果

![](https://ai100-fileentity.cupoy.com/ml100/dailytask/1586225294169/1594009345517)

- 採用無母數方法畫出一個觀察變數的機率密度函數
  - 某個 X 出現的機率為何
  
- Density plot 的特性
  - 歸一：線下面積和為 1
  - 對稱：K(-u) = K(u)
  
- 常用的 Kernel function
  - Gaussian (Normal dist)
  - Cosine
  

## 繪圖資源

[Python Graph Gallery](https://python-graph-gallery.com/)
> ![link text](https://ai100-fileentity.cupoy.com/ml100/dailytask/1586225294169/1594010130470)

[R Graph Gallery](https://www.r-graph-gallery.com/)
> ![link text](https://ai100-fileentity.cupoy.com/ml100/dailytask/1586225294169/1594010232046)

## HOMEWORK

# EDA: 把連續型變數離散化

## 目的

- **了解離散化連續數值的意義以及方法**

## 總結

- 離散化的目的是讓事情變簡單、減少 outlier 對分析以及訓練模型的影響

- 主要的方法是等寬劃分 (對應 pandas 中的 cut) 以及等頻劃分 (對應 pandas 中的 qcut)

- 可以依實際需求來自己定義離散化的方式

## HOMEWORK

  



