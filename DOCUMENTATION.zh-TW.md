# 文件

閱讀文檔：[vanheemstrasystems-Repository](https://vanHeemstraSystems-REPOSITORY-NAME.readthedocs.io/en/latest/)

## 100-安裝讀取thedocs

運行以下命令：

    $ pip install sphinx sphinx_rtd_theme recommonmark

旁邊創建文檔運行：

    $ cd docs
    $ make html

您的文檔將在內部創建`docs/build`.

## 200-讀取的自動化

1）確保有一個`.readthedocs.yml`在GitHub存儲庫的根部文件。

2）將您的github存儲庫連接到readthedocs<https://readthedocs.org/>

1.  去[讀取thedocs](https://readthedocs.org/)並創建一個帳戶
2.  單擊“導入項目”
3.  如果尚未連接您的github帳戶
4.  從列表中選擇您的存儲庫
5.  配置您的項目設置

## 300-構建您的文檔

1.  將您的更改推向GitHub
2.  ReadThedocs將自動構建您的文檔
3.  請訪問您的項目頁面上的readThedocs以查看結果

## 400-設置Webhooks（可選）

ReadThedocs應自動設置Webhooks，但如果沒有，則應自動設置：

1.  轉到GitHub上的存儲庫設置
2.  轉到Webhooks
3.  添加帶有ReadThedocs項目設置的URL的Webhook

## 500-故障排除

-   **構建失敗**：檢查readthedocs上的構建日誌
-   **缺少內容**：確保所有文件都包含在您的`toctree`
-   **格式化問題**：檢查您的降價/重組文本是否有效
-   **圖像未顯示**：驗證圖像的路徑正確

## 600-維護您的文檔

-   根據需要更新您的文檔文件
-   將更改推向github
-   readthedocs將自動重建
-   使用ReadThedocs的版本控制功能來維護不同版本的文檔

## 700-觸發讀者上的構建

在[讀取thedocs](https://readthedocs.org/)，登錄到導航到您的GitHub存儲庫條目（例如，`https://app.readthedocs.org/projects/YOUR-GITHUB-REPOSITOY-NAME/`）和點點菜單（...）選擇**重建版本**.

## 800-提示

-   **圖像**：將圖像移至`docs/source/_static/`並更新引用
-   **代碼塊**：確保指定正確的語法突出顯示
-   **交叉引用**：更新以使用獅身人面像的參考系統
-   **元數據**：在每個頁面上添加適當的元數據以獲得更好的SEO

## 900-常見問題

-   **斷開的鏈接**：轉換後雙檢查所有鏈接
-   **缺少圖像**：確保所有圖像路徑已更新
-   **建立失敗**：檢查readThedocs構建錯誤是否有錯誤
-   **格式化差異**：一些降價功能在獅身人面

## 1000-查看文檔

訪問<https://vanHeemstraSystems-REPOSITORY-NAME.readthedocs.io/en/latest/>
