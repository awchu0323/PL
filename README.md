# 111 師大科技系程式語言

授課老師:蔡芸琤

姓名:陳亮竹

系級:科技系二年級

- [i.課程筆記區](https://github.com/awchu0323/PL#%E8%AA%B2%E7%A8%8B%E7%AD%86%E8%A8%98%E5%8D%80)

- [ii.作業連結區](https://github.com/awchu0323/PL#%E4%BD%9C%E6%A5%AD%E9%80%A3%E7%B5%90%E5%8D%80)

- [iii.專題連結區](https://github.com/awchu0323/PL#%E5%B0%88%E9%A1%8C%E9%80%A3%E7%B5%90%E5%8D%80)

# i.課程筆記區

## W1(0908):
 
  1.課程介紹
  2.程式下載
 
 ## W2(0915):
 
  ### 課程內容:
  
   1.基本訓練和練習
    
     int : 整數
     float : 浮點數
     str : 字串
  
  - [W2上課習題和課後習題](https://github.com/awchu0323/PL/tree/main/0915W1)
 
## W3(0922):
 
  ### 課程內容:
   1.取得資料列表
   - [W3資料列表](https://github.com/awchu0323/PL/blob/main/0922W2/0922%E4%B8%8A%E8%AA%B2%E6%B8%AC%E8%A9%A6.ipynb)
  
   2.字串
   
     list[] : 有順序，可放入不同類型的資料
     set{ } : 無序、元素不可重複，不可為串列
     
     新增 : .append()/.insert()/.extend()
     刪除 : del[]/.remove()/.pop()
     
     新增 : .add()/.update()
     刪除 : .remove()/.pop()/.clear()
     
     num[1:4]     #start:end-1
     num[:3]      #0:n項
     num[:-3]     #0:(end-n)項
     num[2:]      #n項:end
     num[-2:]     #結尾前n項
     num[:]       #all

   - [W3字串練習](https://github.com/awchu0323/PL/blob/main/0922W2/w3%20%E5%AD%97%E4%B8%B2.ipynb)
  
  ### 課堂習題:
   - [W3課後習題](https://github.com/awchu0323/PL/blob/main/0922W2/W3%20%E8%AA%B2%E5%A0%82%E7%B7%B4%E7%BF%921.ipynb)
 
## W4(0929)
  
  ### 課程內容:
   1.dictionary
  - [W4 dictionary&課堂練習](https://github.com/awchu0323/PL/blob/main/0929W4/0929w4%20%E4%B8%8A%E8%AA%B2.ipynb)
  
  ### 課堂習題:
  - [w4課後練習](https://github.com/awchu0323/PL/blob/main/0929W4/0929w4%20%E8%AA%B2%E5%A0%82%E7%B7%B4%E7%BF%92.ipynb)
  
## W5(1006) 

## W6(1013) 
 ### 課程內容:
  1.資料正則化
  
    (1)Character classes or groups:
       . any 
       | or
       [...] list    [^...]excluded
       (...) group
    (2)字元
      空白 - s
      非空白 - S
      包含底線的任何單詞字元 - w
      任何非單詞字元 - W
      數字 - d
      非數字 - D
      開始、非 - ^
      結尾 - $
      不限 - .
    (3)數量
      * 0次或更多
      + 1次或更多
      ? 0或1次
      {n}n次
      
   - [w6資料正則化](https://github.com/awchu0323/PL/blob/main/1013W6/W6%E8%B3%87%E6%96%99%E6%AD%A3%E8%B2%AC%E5%8C%96.ipynb) 
  
## W7(1020) 

 ### 課堂內容:
  1.爬蟲
  - [爬蟲ptt練習](https://github.com/awchu0323/PL/blob/main/%E4%BD%9C%E6%A5%AD3/%E7%88%AC%E8%9F%B2.ipynb)
 
## W8(1027)
  1.資料彙整
  
    (1)data.loc[行標籤,列標籤]
       ex:data.loc[1:5,["a","b","c","d"]]
    
    (2)data.iloc[行索引,列索引]
       ex:data.loc[1:5,[2:4]]
       ex2:data.loc[[1,3,5],[2,4]]
       
    (3)str.contains 尋找關鍵字，並傳回結果
          
  - [資料彙整和練習](https://github.com/awchu0323/PL/blob/main/1027W8/%E8%B3%87%E6%96%99%E5%BD%99%E6%95%B41027.ipynb)
## W9(1103)
   
# ii.作業連結區

   - [作業1-集合](https://github.com/awchu0323/PL/blob/main/%E4%BD%9C%E6%A5%AD1/%E4%BD%9C%E6%A5%AD1.ipynb)
   - [作業2-資料分析](https://github.com/awchu0323/PL/blob/main/%E4%BD%9C%E6%A5%AD2/%E4%BD%9C%E6%A5%AD2.ipynb)
   - [作業3-爬蟲](https://github.com/awchu0323/PL/blob/main/%E4%BD%9C%E6%A5%AD3/%E4%BD%9C%E6%A5%AD3.ipynb)
   - [作業4-資料彙整](https://medium.com/@andrew20030323/臺北市街頭隨機搶奪案件分析-2b2b228a47bc)
   - [作業4-資料彙整python](https://github.com/awchu0323/PL/blob/main/%E4%BD%9C%E6%A5%AD4/%E4%BD%9C%E6%A5%AD4.ipynb)
   - [作業5](https://medium.com/@andrew20030323/%E5%8F%B0%E7%81%A3%E6%9C%80%E9%AB%98%E6%B3%95%E9%99%A2-%E4%BA%A4%E9%80%9A%E6%A1%88%E4%BB%B6-b940f5f11e3a)
# iii.專題連結區
