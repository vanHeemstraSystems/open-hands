# 文档

阅读文档：[vanheemstrasystems-Repository](https://vanHeemstraSystems-REPOSITORY-NAME.readthedocs.io/en/latest/)

## 100-安装读取thedocs

运行以下命令：

    $ pip install sphinx sphinx_rtd_theme recommonmark

旁边创建文档运行：

    $ cd docs
    $ make html

您的文档将在内部创建`docs/build`.

## 200-读取的自动化

1）确保有一个`.readthedocs.yml`在GitHub存储库的根部文件。

2）将您的github存储库连接到readthedocs<https://readthedocs.org/>

1.  去[读取thedocs](https://readthedocs.org/)并创建一个帐户
2.  单击“导入项目”
3.  如果尚未连接您的github帐户
4.  从列表中选择您的存储库
5.  配置您的项目设置

## 300-构建您的文档

1.  将您的更改推向GitHub
2.  ReadThedocs将自动构建您的文档
3.  请访问您的项目页面上的readThedocs以查看结果

## 400-设置Webhooks（可选）

ReadThedocs应自动设置Webhooks，但如果没有，则应自动设置：

1.  转到GitHub上的存储库设置
2.  转到Webhooks
3.  添加带有ReadThedocs项目设置的URL的Webhook

## 500-故障排除

-   **构建失败**：检查readthedocs上的构建日志
-   **缺少内容**：确保所有文件都包含在您的`toctree`
-   **格式化问题**：检查您的降价/重组文本是否有效
-   **图像未显示**：验证图像的路径正确

## 600-维护您的文档

-   根据需要更新您的文档文件
-   将更改推向github
-   readthedocs将自动重建
-   使用ReadThedocs的版本控制功能来维护不同版本的文档

## 700-触发读者上的构建

在[读取thedocs](https://readthedocs.org/)，登录到导航到您的GitHub存储库条目（例如，`https://app.readthedocs.org/projects/YOUR-GITHUB-REPOSITOY-NAME/`）和点点菜单（...）选择**重建版本**.

## 800-提示

-   **图像**：将图像移至`docs/source/_static/`并更新引用
-   **代码块**：确保指定正确的语法突出显示
-   **交叉引用**：更新以使用狮身人面像的参考系统
-   **元数据**：在每个页面上添加适当的元数据以获得更好的SEO

## 900-常见问题

-   **断开的链接**：转换后双检查所有链接
-   **缺少图像**：确保所有图像路径已更新
-   **建立失败**：检查readThedocs构建错误是否有错误
-   **格式化差异**：一些降价功能在狮身人面

## 1000-查看文档

访问<https://vanHeemstraSystems-REPOSITORY-NAME.readthedocs.io/en/latest/>
