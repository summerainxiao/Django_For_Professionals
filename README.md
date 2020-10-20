＃欢迎使用StackEdit！

嗨！我是** StackEdit **中的第一个Markdown文件。如果您想了解StackEdit，可以阅读我的文章。如果您想和Markdown一起玩，可以编辑我。与我完成后，您可以通过打开导航栏左上角的**文件浏览器**来创建新文件。


＃个文件

  StackEdit将文件存储在浏览器中，这意味着所有文件都会自动保存在本地，并且可以离线访问   **！**

##创建文件和文件夹

使用导航栏左上角的按钮可以访问文件浏览器。您可以通过在文件浏览器中插入**新建文件**按钮来创建新文件。您也可以通过替换**新建文件夹**按钮来创建文件夹。

##切换到另一个文件

您的所有文件和文件夹在文件浏览器中均以树形显示。您可以通过索引树中的文件从一个切换到另一个。

##重命名文件

您可以通过点击导航导航的文件名或通过更改更改当前文件**重命名**在文件浏览器按钮。

##删除文件

您可以通过在文件资源管理器中单击**删除**按钮来删除当前文件。该文件将被移动到**垃圾**文件夹，并在7天后闲置自动删除。

##导出文件

您可以通过将菜单中的**导入到磁盘**生成最新文件。您可以选择将文件导出为纯降价，使用把手模板导入为HTML或PDF。


＃同步

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication
Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

您可以使用[KaTeX]（https://khan.github.io/KaTeX/ ）渲染LaTeX数学表达式：

在*伽玛功能*满足$ \伽玛（ñ）=（N-1）！\ quad \ forall n \ in \ mathbb N $通过欧拉积分

$$        \伽玛（Z）= \ INT _0 ^ \ infty吨^ { Z-1 } ë1 { -t } dt的的的的的的的的\， 。$$



>您可以在[此处]（http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference ）上找到有关** LaTeX **数学表达式的更多信息。


## UML图

您可以使用[Mermaid]（https://mermaidjs.github.io/ ）呈现UML图。例如，这将产生一个序列图：
`                                                                            ` `人鱼时序图产品爱丽丝- >>鲍勃：您好鲍勃，你怎么样鲍勃- >>约翰：约翰你呢鲍勃-X爱丽丝：很好，谢谢鲍勃-X约翰：非常感谢！请注意约翰的权利：鲍勃认为很长很长的时间，太长了，以至于文本<br/>不能连续显示。鲍勃->爱丽丝：向约翰请教...爱丽丝- >约翰：对...约翰，你好吗？` ` `这将产生一个流程图：` ` `人鱼图表LR A [广场矩形] -链接文本- > B（（圆））A-> C（圆矩形）乙- > d {菱形}℃ - > d ` ` `                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       





      
水电费














