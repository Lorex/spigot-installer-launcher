# Minecraft spigot 伺服器安裝程式及啟動器

## 介紹
這是一支可以自動設定 Minecraft 伺服器所需環境，並且自動安裝 spigot 伺服器的工具。
目前只有一些簡陋的功能，未來會繼續擴充。

## 參數列表
參數名稱      | 作用
--------------|-----------
```--start``` | 啟動伺服器
```--help```  | 顯示參數列表
```--install-java``` | 安裝 Java Server JRE 1.8
```--ram=<min>-<max>``` | 設定記憶體使用量

## 範例
- 開啟伺服器 : ```./server --start```
- 開啟伺服器並設定記憶體使用量為 1G 至 2G : ```2./server --ram=1G-2G --start
