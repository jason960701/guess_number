# 猜數字遊戲

這個程式是一個簡單的猜數字遊戲，玩家需要猜出系統生成的隨機數字。

## 如何使用

1. 安裝Python（如果尚未安裝）。
2. 下載程式碼或使用git clone。

```bash
git clone https://github.com/your_username/guess-the-number.git
```
## 配置
遊戲的設定可以透過config.xml檔案進行調整。這個檔案包含了範圍和最大猜測次數的設定
```
<config>
    <range>
        <min>1</min><!-- 最小值-->
        <max>100</max><!--最大值-->
    </range>
    <max_attempts>10</max_attempts><!--猜的次數-->
</config>
```
你可以根據需要修改這些值。
