# 机器学习纳米学位

这是优达学城（Udacity）机器学习纳米学位中文项目描述。

查看英文项目描述，请访问：https://github.com/udacity/machine-learning

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. Please refer to [Udacity Terms of Service](https://www.udacity.com/legal) for further information.

## 所需软件

本项目采用以下软件和 Python 库：

Python 2.7
NumPy
pandas
matplotlib
你还需要安装和运行 Jupyter Notebook

对jupyter不熟悉的同学可以看一下这两个链接：

Jupyter使用视频教程
为什么使用jupyter？
如果您还未安装 Python，我们强烈推荐您安装 Python 发行版：Anaconda，其具备包括上述程序包在内的更多程序包。安装时，确保您选择的是 Python 2.7 安装程序，而不是 Python 3.x 安装程序。

如果您的计算机中已装有 Python 2.7，那么您可使用命令行上的 pip 安装 numpy， scikit-learn 和 Jupyter Notebook（之前叫'iPython'）。如果使用 pip 执行安装时出现问题，这个页面对 Windows 用户的某些程序包也是有用的。安装完 pip 之后，你可以执行下列命令安装所需要的包：

sudo pip install numpy pandas matplotlib jupyter scikit-learn


## 开始项目

要开始这个项目，你可以访问我们的 GitHub 页面，或者点击这里直接下载最新的项目所需文件。

projects/titanic_survival_exploration 文件夹包含三个文件：

Titanic_Survival_Exploration.ipynb: 这是最主要的文件，项目中的主要工作都将在这个文件上完成
titanic_data.csv: 项目数据表。您将需要把这个数据加载到 notebook 里。
titanic_visualizations.py: 这个 Python 脚本包含 helper 函数，可以让数据和存活结果可视化。
为了打开 jupyter notebook，需要完成以下几步。如果你使用 Windows 系统，你需要打开命令终端或 PowerShell；如果你使用 Mac 或者 Linux 系统，直接打开Terminal 终端即可。使用 cd 命令来打开项目文件夹。例如，在 Windows 上你可以使用 cd C:\Users\username\Documents\ （username 用自己的用户名替换）找到项目所在的文件夹；在 Mac 上，你可以使用 cd ~/Documents/。在 Windows 上你可以使用 dir 命令，在 Mac 或者 Linux 上用 ls 命令列出当前目录中的文件和文件夹。如果发现进错目录，可以使用 cd .. 返回上一级目录。

一旦你进入包含项目文件的文件夹，您可以输入命令

**jupyter notebook titanic_survival_exploration.ipynb**

打开一个浏览器窗口，或者新建标签页，来使用你的 notebook。依照 notebook 上的指导回答每一个问题完成这个项目。我们还提供了随项目的 READEME 文档，上面也有关于这个项目的信息和指导。

项目提交
评估
你的项目会由优达学城项目评审师按照 泰坦尼克号探索项目要求进行评审。请确定你仔细阅读了该要求，并在项目提交前自我对检查。要求当中的所有条目都必须合格项目才能通过。

提交文件
当你准备好提交项目时，你可以把下列文件压缩成一个 zip 文件上传。或者，你可以提交你在 GitHub 的 Repo 。可以把文件夹命名为 titanic_survival_exploration 便于查找：

带有完整问题答案和代码的 titanic_survival_exploration.ipynb notebook 文件。
notebook 项目导出的 HTML 文件，命名为 report.html。如何导出HTML的说明在 notebook 的最下方。. 你也许需要先在命令后通过 pip install mistune 命令安装 mistune 。
当你准备好所有这些文件，并且依照项目要求核对过之后，就可以在下面的项目提交页面提交你的项目了。