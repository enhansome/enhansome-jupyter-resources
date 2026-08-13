# Awesome jupyter resources with stars

<!-- markdownlint-disable -->

<h1 align="center">
    Jupyter资源与工具库大全
    <br>
</h1>

<p align="center">
    <strong>Jupyter开源工具库资源大全，划分子版块并梳理排行，每周自动更新</strong>
</p>

<p align="center">
    <a href="#Contents" title="项目数量"><img src="https://img.shields.io/badge/projects-270-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="欢迎完善"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/HanXinzi-AI/awesome-jupyter-resources/releases" title="最近更新"><img src="https://img.shields.io/github/release-date/HanXinzi-AI/awesome-jupyter-resources?color=green&label=updated"></a>
</p>

本资源清单包含270个jupyter相关的开源工具资源，这些热门工具总共分成13个不同的子板块，这些项目目前在github上已经收到260K个点赞。所有的工具资源每周会自动从GitHub和工具维护平台采集信息，并更新排行展示。本清单参考[best-of模板](https://github.com/best-of-lists/best-of) ⭐ 1,883 | 🐛 20 | 📅 2026-08-07完成，内容参考了[awesome-jupyter](https://github.com/markusschanta/awesome-jupyter) ⭐ 4,659 | 🐛 16 | 📅 2026-08-13，欢迎大家提PR丰富本清单。

## 目录

* [Notebook环境](#Notebook环境) *13 个项目*
* [交互式小部件和可视化](#交互式小部件和可视化) *49 个项目*
* [Jupyter拓展](#Jupyter拓展) *23 个项目*
* [Jupyter-magic拓展](#Jupyter-magic拓展) *10 个项目*
* [Jupyter内核](#Jupyter内核) *36 个项目*
* [Jupyter-Notebook分享与格式转换](#Jupyter-Notebook分享与格式转换) *23 个项目*
* [Jupyter-Notebook工具](#Jupyter-Notebook工具) *24 个项目*
* [JupyterLab渲染器](#JupyterLab渲染器) *7 个项目*
* [JupyterLab主题](#JupyterLab主题) *8 个项目*
* [JupyterLab扩展](#JupyterLab扩展) *50 个项目*
* [JupyterHub认证](#JupyterHub认证) *15 个项目*
* [JupyterHub容器等](#JupyterHub容器等) *8 个项目*
* [Jupyter组件](#Jupyter组件) *3 个项目*
* [Others](#Others) *4 个项目*

## 图标解释

* 🥇🥈🥉  综合项目质量分
* ⭐️  github上star的数量
* 🐣  小于6个月的新项目
* 💤  非活跃项目(6个月未更新)
* 💀  沉寂项目(12个月未更新)
* 📈📉  项目趋势(向上or向下)
* ➕  最近添加的项目
* ❗️  警告(例如 项目没有license)
* 👨‍💻  项目的开发贡献者数量
* 🔀  项目被fork的数量
* 📋  项目issue的数量
* ⏱️  项目包上次更新时间
* 📥  工具库被下载次数
* 📦  项目依赖的工具库数量

<br>

## Notebook环境

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*支持Jupyter笔记本的开发环境。*

<details><summary><b><a href="https://github.com/jupyter/notebook">Jupyter</a></b> (🥇27 ·  ⭐ 10K · 📉) - Jupyter Interactive Notebook. <code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter/notebook) ⭐ 13,298 | 🐛 1,907 | 🌐 Jupyter Notebook | 📅 2026-08-11 (👨‍💻 610 · 🔀 3.8K · 📥 8.8K · 📦 10 · 📋 4.5K - 44% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/jupyter/notebook
  ```
* [PyPi](https://pypi.org/project/notebook) (📥 11M / month):
  ```
  pip install notebook
  ```
* [Conda](https://anaconda.org/conda-forge/jupyter) (📥 2.3M · ⏱️ 18.11.2021):
  ```
  conda install -c conda-forge jupyter
  ```
* [Docker Hub](https://hub.docker.com/r/jupyter/datascience-notebook) (📥 27M · ⭐ 940 · ⏱️ 23.08.2022):
  ```
  docker pull jupyter/datascience-notebook
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyterhub">JupyterHub</a></b> (🥇25 ·  ⭐ 7.1K) - Jupyter笔记本电脑的多用户服务器。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyterhub/jupyterhub) ⭐ 8,328 | 🐛 197 | 🌐 Python | 📅 2026-08-13 (👨‍💻 280 · 🔀 1.7K · 📦 1.9K · 📋 2.1K - 5% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/jupyterhub/jupyterhub
  ```
* [PyPi](https://pypi.org/project/jupyterhub) (📥 130K / month):
  ```
  pip install jupyterhub
  ```
* [Conda](https://anaconda.org/conda-forge/jupyterhub) (📥 650K · ⏱️ 06.06.2022):
  ```
  conda install -c conda-forge jupyterhub
  ```
* [Docker Hub](https://hub.docker.com/r/jupyterhub/jupyterhub) (📥 2.7M · ⭐ 310 · ⏱️ 19.08.2022):
  ```
  docker pull jupyterhub/jupyterhub
  ```

</details>
<details><summary><b><a href="https://github.com/nteract/nteract">nteract</a></b> (🥇25 ·  ⭐ 5.9K) - 交互式计算套件<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/nteract/nteract) ⭐ 159 | 🐛 41 | 🌐 TypeScript | 📅 2026-08-13 (👨‍💻 180 · 🔀 530 · 📥 1.4M · 📋 1.7K - 9% open · ⏱️ 23.07.2022):

  ```
  git clone https://github.com/nteract/nteract
  ```
* [PyPi](https://pypi.org/project/nteract_on_jupyter) (📥 2.4K / month):
  ```
  pip install nteract_on_jupyter
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter/docker-stacks">Docker Stacks</a></b> (🥈22 ·  ⭐ 7.2K) - 包含Jupyter应用程序的即可运行的Docker映像。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter/docker-stacks) ⭐ 8,452 | 🐛 8 | 🌐 Python | 📅 2026-08-09 (👨‍💻 220 · 🔀 2.6K · 📋 770 - 5% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/jupyter/docker-stacks
  ```
* [Docker Hub](https://hub.docker.com/r/jupyter/scipy-notebook) (📥 86M · ⭐ 360 · ⏱️ 23.08.2022):
  ```
  docker pull jupyter/scipy-notebook
  ```

</details>
<details><summary><b><a href="https://github.com/vatlab/sos">sos</a></b> (🥈22 ·  ⭐ 230) - 用于日常数据分析的SoS工作流系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/vatlab/sos) ⭐ 287 | 🐛 67 | 🌐 Python | 📅 2025-11-06 (👨‍💻 36 · 🔀 30 · 📦 2.7K · 📋 1.4K - 4% open · ⏱️ 21.06.2022):

  ```
  git clone https://github.com/vatlab/SOS
  ```

</details>
<details><summary><b><a href="https://github.com/googledatalab/datalab">DataLab</a></b> (🥈21 ·  ⭐ 980 · 💤) - 面向大数据的交互式工具和开发人员经验。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/googledatalab/datalab) ⚠️ Archived (👨‍💻 52 · 🔀 250 · 📋 890 - 25% open · ⏱️ 16.08.2021):

  ```
  git clone https://github.com/googledatalab/datalab
  ```
* [PyPi](https://pypi.org/project/datalab) (📥 56K / month):
  ```
  pip install datalab
  ```

</details>
<details><summary><b><a href="https://github.com/nteract/hydrogen">Hydrogen</a></b> (🥉19 ·  ⭐ 3.8K) - 交互运行代码，检查数据并作图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/nteract/hydrogen) ⭐ 4,019 | 🐛 180 | 🌐 TypeScript | 📅 2026-07-19 (👨‍💻 89 · 🔀 320 · 📋 1.3K - 13% open · ⏱️ 25.03.2022):

  ```
  git clone https://github.com/nteract/hydrogen
  ```

</details>
<details><summary><b><a href="https://github.com/Kaggle/docker-python">docker-python</a></b> (🥉19 ·  ⭐ 2.2K) - Kaggle Python Docker映像。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Kaggle/docker-python) ⭐ 2,729 | 🐛 32 | 🌐 Python | 📅 2026-08-12 (👨‍💻 150 · 🔀 810 · 📋 300 - 4% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/kaggle/docker-python
  ```
* [Docker Hub](https://hub.docker.com/r/kaggle/python) (📥 190K · ⭐ 160 · ⏱️ 23.08.2022):
  ```
  docker pull kaggle/python
  ```

</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-workspace">ML Workspace</a></b> (🥉18 ·  ⭐ 2.7K · 💤) - 基于Web的多合一IDE，专门用于机器学习和数据任务。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/ml-tooling/ml-workspace) ⭐ 3,542 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-07-26 (👨‍💻 11 · 🔀 330 · 📋 87 - 9% open · ⏱️ 22.11.2021):

  ```
  git clone https://github.com/ml-tooling/ml-workspace
  ```
* [Docker Hub](https://hub.docker.com/r/mltooling/ml-workspace) (📥 510K · ⭐ 24 · ⏱️ 13.07.2021):
  ```
  docker pull mltooling/ml-workspace
  ```

</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-hub">ML Hub</a></b> (🥉17 ·  ⭐ 250 · 💤) - 机器学习团队的多用户开发平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/ml-tooling/ml-hub) ⭐ 321 | 🐛 17 | 🌐 Python | 📅 2021-12-23 (👨‍💻 7 · 🔀 54 · 📥 1.9K · 📋 26 - 57% open · ⏱️ 23.12.2021):

  ```
  git clone https://github.com/ml-tooling/ml-hub
  ```
* [Docker Hub](https://hub.docker.com/r/mltooling/ml-hub) (📥 44K · ⭐ 5 · ⏱️ 18.02.2020):
  ```
  docker pull mltooling/ml-hub
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/retrolab">jupyterlab-classic</a></b> (🥉17 ·  ⭐ 240) - 下一代老式笔记本用户UI界面。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/retrolab) ⚠️ Archived (👨‍💻 17 · 🔀 43 · 📥 790 · 📦 80 · 📋 110 - 3% open · ⏱️ 04.05.2022):

  ```
  git clone https://github.com/jtpio/jupyterlab-classic
  ```
* [PyPi](https://pypi.org/project/jupyterlab-classic) (📥 70 / month):
  ```
  pip install jupyterlab-classic
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/vscode-jupyter">VSCode Jupyter</a></b> (🥉16 ·  ⭐ 710) - VS Code Jupyter extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/microsoft/vscode-jupyter) ⭐ 1,523 | 🐛 253 | 🌐 TypeScript | 📅 2026-08-10 (👨‍💻 250 · 🔀 150 · 📋 7.7K - 8% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/microsoft/vscode-jupyter
  ```

</details>
<details><summary><b><a href="https://github.com/iot-salzburg/gpu-jupyter">gpu-jupyter</a></b> (🥉14 ·  ⭐ 390) - 充分利用Jupyterlab的灵活性。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/iot-salzburg/gpu-jupyter) ⭐ 766 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2026-08-11 (👨‍💻 10 · 🔀 140 · 📋 56 - 21% open · ⏱️ 21.07.2022):

  ```
  git clone https://github.com/iot-salzburg/gpu-jupyter
  ```

</details>
<br>

## 交互式小部件和可视化

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*提供交互式UI小部件和可视化工具的扩展。*

🔗 <b><a href="https://github.com/ml-tooling/best-of-ml-python#data-visualization">best-of-ml-python - Data Visualization</a></b>  - Python-based data visualization libraries.

<details><summary><b><a href="https://github.com/jupyter-widgets/ipywidgets">ipywidgets</a></b> (🥇34 ·  ⭐ 2.6K) - Interactive Widgets for the Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter-widgets/ipywidgets) ⭐ 3,326 | 🐛 795 | 🌐 TypeScript | 📅 2026-08-09 (👨‍💻 200 · 🔀 830 · 📦 4.7K · 📋 1.8K - 31% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/jupyter-widgets/ipywidgets
  ```
* [PyPi](https://pypi.org/project/ipywidgets) (📥 7.8M / month):
  ```
  pip install ipywidgets
  ```
* [Conda](https://anaconda.org/conda-forge/ipywidgets) (📥 5.8M · ⏱️ 19.08.2022):
  ```
  conda install -c conda-forge ipywidgets
  ```
* [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 79K / month):
  ```
  npm install @jupyter-widgets/jupyterlab-manager
  ```

</details>
<details><summary><b><a href="https://github.com/ydataai/pandas-profiling">pandas-profiling</a></b> (🥇33 ·  ⭐ 9.4K) - 从pandas DataFrame创建HTML分析报告。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/ydataai/pandas-profiling) ⭐ 13,669 | 🐛 323 | 🌐 Python | 📅 2026-04-22 (👨‍💻 92 · 🔀 1.3K · 📦 8.8K · 📋 580 - 19% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/pandas-profiling/pandas-profiling
  ```
* [PyPi](https://pypi.org/project/pandas-profiling) (📥 1.2M / month):
  ```
  pip install pandas-profiling
  ```
* [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 270K · ⏱️ 02.05.2022):
  ```
  conda install -c conda-forge pandas-profiling
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥇30 ·  ⭐ 1.3K) - Jupyter-Leaflet.js桥接。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jupyter-widgets/ipyleaflet) ⭐ 1,537 | 🐛 300 | 🌐 TypeScript | 📅 2026-05-07 (👨‍💻 80 · 🔀 320 · 📦 2.6K · 📋 500 - 36% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/jupyter-widgets/ipyleaflet
  ```
* [PyPi](https://pypi.org/project/ipyleaflet) (📥 110K / month):
  ```
  pip install ipyleaflet
  ```
* [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 870K · ⏱️ 23.08.2022):
  ```
  conda install -c conda-forge ipyleaflet
  ```
* [NPM](https://www.npmjs.com/package/jupyter-leaflet) (📥 50K / month):
  ```
  npm install jupyter-leaflet
  ```

</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">bokeh</a></b> (🥇28 ·  ⭐ 17K) - 浏览器中的Python交互式数据可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/bokeh/bokeh) ⭐ 20,429 | 🐛 861 | 🌐 TypeScript | 📅 2026-08-12 (👨‍💻 610 · 🔀 3.9K · 📦 150 · 📋 7K - 9% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/bokeh/bokeh
  ```
* [PyPi](https://pypi.org/project/bokeh) (📥 3.6M / month):
  ```
  pip install bokeh
  ```
* [Conda](https://anaconda.org/conda-forge/bokeh) (📥 8.2M · ⏱️ 15.08.2022):
  ```
  conda install -c conda-forge bokeh
  ```

</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥇27 ·  ⭐ 3.6K) - Visualizer for Pandas Data Structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

* [GitHub](https://github.com/man-group/dtale) ⭐ 5,213 | 🐛 70 | 🌐 TypeScript | 📅 2026-07-24 (👨‍💻 27 · 🔀 290 · 📦 460 · 📋 470 - 8% open · ⏱️ 07.08.2022):

  ```
  git clone https://github.com/man-group/dtale
  ```
* [PyPi](https://pypi.org/project/dtale) (📥 100K / month):
  ```
  pip install dtale
  ```
* [Conda](https://anaconda.org/conda-forge/dtale) (📥 150K · ⏱️ 07.08.2022):
  ```
  conda install -c conda-forge dtale
  ```

</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥇27 ·  ⭐ 3.3K) - 用于IPython / Jupyter笔记本的绘图库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/bqplot/bqplot) ⭐ 3,694 | 🐛 278 | 🌐 TypeScript | 📅 2026-05-07 (👨‍💻 59 · 🔀 440 · 📦 34 · 📋 570 - 36% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/bqplot/bqplot
  ```
* [PyPi](https://pypi.org/project/bqplot) (📥 82K / month):
  ```
  pip install bqplot
  ```
* [Conda](https://anaconda.org/conda-forge/bqplot) (📥 1M · ⏱️ 22.08.2022):
  ```
  conda install -c conda-forge bqplot
  ```
* [NPM](https://www.npmjs.com/package/bqplot) (📥 9.3K / month):
  ```
  npm install bqplot
  ```

</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvolume">ipyvolume</a></b> (🥇27 ·  ⭐ 1.8K) - 基于IPython的Jupyter笔记本中用于Python的3d绘图<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/widgetti/ipyvolume) ⭐ 1,962 | 🐛 213 | 🌐 TypeScript | 📅 2023-11-29 (👨‍💻 41 · 🔀 220 · 📦 840 · 📋 300 - 56% open · ⏱️ 26.07.2022):

  ```
  git clone https://github.com/maartenbreddels/ipyvolume
  ```
* [PyPi](https://pypi.org/project/ipyvolume) (📥 56K / month):
  ```
  pip install ipyvolume
  ```
* [Conda](https://anaconda.org/conda-forge/ipyvolume) (📥 380K · ⏱️ 20.04.2021):
  ```
  conda install -c conda-forge ipyvolume
  ```
* [NPM](https://www.npmjs.com/package/ipyvolume) (📥 2.1K / month):
  ```
  npm install ipyvolume
  ```

</details>
<details><summary><b><a href="https://github.com/matplotlib/ipympl">jupyter-matplotlib</a></b> (🥇27 ·  ⭐ 1.3K) - Matplotlib Jupyter集成。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/matplotlib/ipympl) ⭐ 1,656 | 🐛 169 | 🌐 Jupyter Notebook | 📅 2026-07-31 (👨‍💻 28 · 🔀 190 · 📦 3.7K · 📋 260 - 44% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/matplotlib/ipympl
  ```
* [PyPi](https://pypi.org/project/ipympl) (📥 150K / month):
  ```
  pip install ipympl
  ```
* [NPM](https://www.npmjs.com/package/jupyter-matplotlib) (📥 27K / month):
  ```
  npm install jupyter-matplotlib
  ```

</details>
<details><summary><b><a href="https://github.com/plotly/jupyter-dash">jupyter-dash</a></b> (🥇27 ·  ⭐ 800) - 在Jupyter Notebook和JupyterLab中开发Dash应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/plotly/jupyter-dash) ⚠️ Archived (👨‍💻 10 · 🔀 210 · 📥 77 · 📦 1.8K · 📋 62 - 62% open · ⏱️ 28.06.2022):

  ```
  git clone https://github.com/plotly/jupyter-dash
  ```
* [PyPi](https://pypi.org/project/jupyter-dash) (📥 370K / month):
  ```
  pip install jupyter-dash
  ```

</details>
<details><summary><b><a href="https://github.com/nteract/papermill">papermill</a></b> (🥈26 ·  ⭐ 4.8K) - 参数化，执行和分析笔记本。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/nteract/papermill) ⭐ 6,467 | 🐛 194 | 🌐 Python | 📅 2026-07-06 (👨‍💻 100 · 🔀 360 · 📦 2.4K · 📋 340 - 30% open · ⏱️ 15.08.2022):

  ```
  git clone https://github.com/nteract/papermill
  ```
* [PyPi](https://pypi.org/project/papermill) (📥 870K / month):
  ```
  pip install papermill
  ```
* [Conda](https://anaconda.org/conda-forge/papermill) (📥 300K · ⏱️ 23.01.2022):
  ```
  conda install -c conda-forge papermill
  ```

</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">facets-overview</a></b> (🥈25 ·  ⭐ 7K · 💀) - 机器学习数据集的可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/PAIR-code/facets) ⚠️ Archived (👨‍💻 28 · 🔀 850 · 📦 130 · 📋 150 - 50% open · ⏱️ 06.05.2021):

  ```
  git clone https://github.com/pair-code/facets
  ```
* [PyPi](https://pypi.org/project/facets-overview) (📥 290K / month):
  ```
  pip install facets-overview
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥈24 ·  ⭐ 830) - Jupyter-Three.js桥接。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter-widgets/pythreejs) ⭐ 988 | 🐛 77 | 🌐 JavaScript | 📅 2024-10-10 (👨‍💻 30 · 🔀 170 · 📦 21 · 📋 220 - 23% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/jupyter-widgets/pythreejs
  ```
* [PyPi](https://pypi.org/project/pythreejs) (📥 65K / month):
  ```
  pip install pythreejs
  ```
* [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 410K · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge pythreejs
  ```
* [NPM](https://www.npmjs.com/package/jupyter-threejs) (📥 4.6K / month):
  ```
  npm install jupyter-threejs
  ```

</details>
<details><summary><b><a href="https://github.com/martinRenou/ipycanvas">ipycanvas</a></b> (🥈24 ·  ⭐ 630) - Jupyter中的交互式画布。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/martinRenou/ipycanvas) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-01 (👨‍💻 20 · 🔀 51 · 📦 780 · 📋 110 - 36% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/martinRenou/ipycanvas
  ```
* [PyPi](https://pypi.org/project/ipycanvas) (📥 26K / month):
  ```
  pip install ipycanvas
  ```
* [Conda](https://anaconda.org/conda-forge/ipycanvas) (📥 80K · ⏱️ 19.08.2022):
  ```
  conda install -c conda-forge ipycanvas
  ```

</details>
<details><summary><b><a href="https://github.com/quantopian/qgrid">qgrid</a></b> (🥈23 ·  ⭐ 2.9K · 💀) - 用于排序，过滤和编辑DataFrame的交互式工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/quantopian/qgrid) ⭐ 3,087 | 🐛 181 | 🌐 Python | 📅 2024-01-12 (👨‍💻 30 · 🔀 390 · 📋 270 - 54% open · ⏱️ 07.04.2020):

  ```
  git clone https://github.com/quantopian/qgrid
  ```
* [PyPi](https://pypi.org/project/qgrid) (📥 69K / month):
  ```
  pip install qgrid
  ```
* [Conda](https://anaconda.org/conda-forge/qgrid) (📥 360K · ⏱️ 04.03.2021):
  ```
  conda install -c conda-forge qgrid
  ```
* [NPM](https://www.npmjs.com/package/qgrid) (📥 930 / month):
  ```
  npm install qgrid
  ```

</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipywebrtc">ipywebrtc</a></b> (🥈23 ·  ⭐ 210 · 💀) - 适用于Jupyter笔记本/实验室的WebRTC。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/maartenbreddels/ipywebrtc) ⭐ 253 | 🐛 44 | 🌐 JavaScript | 📅 2024-02-20 (👨‍💻 9 · 🔀 33 · 📦 570 · 📋 51 - 60% open · ⏱️ 29.03.2021):

  ```
  git clone https://github.com/maartenbreddels/ipywebrtc
  ```
* [PyPi](https://pypi.org/project/ipywebrtc) (📥 56K / month):
  ```
  pip install ipywebrtc
  ```
* [Conda](https://anaconda.org/conda-forge/ipywebrtc) (📥 260K · ⏱️ 29.03.2021):
  ```
  conda install -c conda-forge ipywebrtc
  ```
* [NPM](https://www.npmjs.com/package/jupyter-webrtc) (📥 340 / month):
  ```
  npm install jupyter-webrtc
  ```

</details>
<details><summary><b><a href="https://github.com/cytoscape/ipycytoscape">ipycytoscape</a></b> (🥈23 ·  ⭐ 200) - Cytoscape Jupyter小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/cytoscape/ipycytoscape) ⭐ 290 | 🐛 74 | 🌐 Python | 📅 2026-07-06 (👨‍💻 32 · 🔀 55 · 📥 3 · 📦 78 · 📋 160 - 37% open · ⏱️ 20.05.2022):

  ```
  git clone https://github.com/QuantStack/ipycytoscape
  ```
* [Conda](https://anaconda.org/conda-forge/ipycytoscape) (📥 56K · ⏱️ 05.04.2022):
  ```
  conda install -c conda-forge ipycytoscape
  ```

</details>
<details><summary><b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥈22 ·  ⭐ 620 · 💀) - 使用Mapbox GL JS可视化Python Jupyter笔记本中的数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/mapbox/mapboxgl-jupyter) ⭐ 679 | 🐛 43 | 🌐 Python | 📅 2025-02-06 (👨‍💻 21 · 🔀 130 · 📦 140 · 📋 99 - 32% open · ⏱️ 19.04.2021):

  ```
  git clone https://github.com/mapbox/mapboxgl-jupyter
  ```
* [PyPi](https://pypi.org/project/mapboxgl) (📥 11K / month):
  ```
  pip install mapboxgl
  ```

</details>
<details><summary><b><a href="https://github.com/mwouts/itables">itables</a></b> (🥈21 ·  ⭐ 320) - Jupyter中的交互式表格。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/mwouts/itables) ⭐ 969 | 🐛 40 | 🌐 Python | 📅 2026-08-07 (👨‍💻 4 · 🔀 29 · 📦 140 · 📋 49 - 10% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/mwouts/itables
  ```
* [PyPi](https://pypi.org/project/itables) (📥 13K / month):
  ```
  pip install itables
  ```

</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvuetify">ipyvuetify</a></b> (🥈21 ·  ⭐ 260) - 基于vuetify UI组件的Jupyter小部件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/widgetti/ipyvuetify) ⭐ 356 | 🐛 85 | 🌐 Python | 📅 2026-08-12 (👨‍💻 10 · 🔀 44 · 📦 4 · 📋 170 - 26% open · ⏱️ 07.02.2022):

  ```
  git clone https://github.com/mariobuikhuizen/ipyvuetify
  ```
* [PyPi](https://pypi.org/project/ipyvuetify) (📥 66K / month):
  ```
  pip install ipyvuetify
  ```
* [Conda](https://anaconda.org/conda-forge/ipyvuetify) (📥 85K · ⏱️ 07.02.2022):
  ```
  conda install -c conda-forge ipyvuetify
  ```

</details>
<details><summary><b><a href="https://github.com/vidartf/ipydatawidgets">ipydatawidgets</a></b> (🥈21 ·  ⭐ 31) - 一组小部件，以帮助促进大型数据集的重用。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/vidartf/ipydatawidgets) ⭐ 44 | 🐛 12 | 🌐 TypeScript | 📅 2023-06-14 (👨‍💻 5 · 🔀 8 · 📦 570 · 📋 10 - 20% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/vidartf/ipydatawidgets
  ```
* [PyPi](https://pypi.org/project/ipydatawidgets) (📥 71K / month):
  ```
  pip install ipydatawidgets
  ```
* [Conda](https://anaconda.org/conda-forge/ipydatawidgets) (📥 170K · ⏱️ 24.08.2022):
  ```
  conda install -c conda-forge ipydatawidgets
  ```

</details>
<details><summary><b><a href="https://github.com/InsightSoftwareConsortium/itkwidgets">itkwidgets</a></b> (🥉20 ·  ⭐ 460) - 交互式Jupyter小部件，以可视化图像，点集等。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/InsightSoftwareConsortium/itkwidgets) ⭐ 622 | 🐛 128 | 🌐 Python | 📅 2026-03-10 (👨‍💻 4 · 🔀 61 · 📥 66 · 📋 200 - 43% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/InsightSoftwareConsortium/itkwidgets
  ```
* [PyPi](https://pypi.org/project/itkwidgets) (📥 14K / month):
  ```
  pip install itkwidgets
  ```
* [NPM](https://www.npmjs.com/package/itkwidgets) (📥 1.4K / month):
  ```
  npm install itkwidgets
  ```

</details>
<details><summary><b><a href="https://github.com/evidentlyai/evidently">evidently</a></b> (🥉19 ·  ⭐ 2.6K) - 交互式报告，可在分析过程中分析机器学习模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/evidentlyai/evidently) ⭐ 7,800 | 🐛 297 | 🌐 Jupyter Notebook | 📅 2026-08-05 (👨‍💻 24 · 🔀 270 · 📦 550 · 📋 110 - 20% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/evidentlyai/evidently
  ```

</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉19 ·  ⭐ 740 · 💤) - What-If工具的源代码/网页/演示。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/PAIR-code/what-if-tool) ⭐ 1,006 | 🐛 97 | 🌐 HTML | 📅 2026-06-21 (👨‍💻 20 · 🔀 140 · 📋 110 - 52% open · ⏱️ 05.01.2022):

  ```
  git clone https://github.com/PAIR-code/what-if-tool
  ```
* [PyPi](https://pypi.org/project/witwidget) (📥 11K / month):
  ```
  pip install witwidget
  ```
* [NPM](https://www.npmjs.com/package/wit-widget) (📥 5.9K / month):
  ```
  npm install wit-widget
  ```

</details>
<details><summary><b><a href="https://github.com/QuantStack/ipysheet">ipysheet</a></b> (🥉19 ·  ⭐ 500 · 💤) - Jupyter Handsontable集成。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/QuantStack/ipysheet) ⭐ 552 | 🐛 76 | 🌐 Python | 📅 2024-01-04 (👨‍💻 10 · 🔀 62 · 📦 3 · 📋 120 - 51% open · ⏱️ 14.12.2021):

  ```
  git clone https://github.com/QuantStack/ipysheet
  ```
* [PyPi](https://pypi.org/project/ipysheet) (📥 54K / month):
  ```
  pip install ipysheet
  ```
* [Conda](https://anaconda.org/conda-forge/ipysheet) (📥 55K · ⏱️ 11.08.2021):
  ```
  conda install -c conda-forge ipysheet
  ```
* [NPM](https://www.npmjs.com/package/ipysheet) (📥 3.4K / month):
  ```
  npm install ipysheet
  ```

</details>
<details><summary><b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉19 ·  ⭐ 470 · 💀) - Jupyter / IPython Notebook的Dragndrop数据透视表和图表。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/nicolaskruchten/jupyter_pivottablejs) ⭐ 708 | 🐛 26 | 🌐 Python | 📅 2024-03-15 (👨‍💻 3 · 🔀 62 · 📦 260 · 📋 58 - 29% open · ⏱️ 04.12.2018):

  ```
  git clone https://github.com/nicolaskruchten/jupyter_pivottablejs
  ```
* [PyPi](https://pypi.org/project/pivottablejs) (📥 14K / month):
  ```
  pip install pivottablejs
  ```

</details>
<details><summary><b><a href="https://github.com/timkpaine/ipydagred3">ipydagred3</a></b> (🥉19 ·  ⭐ 38) - ipywidgets库，用于在其中绘制有向无环图。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/timkpaine/ipydagred3) ⭐ 85 | 🐛 5 | 🌐 Python | 📅 2026-08-01 (👨‍💻 3 · 🔀 5 · 📦 11 · 📋 19 - 15% open · ⏱️ 21.07.2022):

  ```
  git clone https://github.com/timkpaine/ipydagred3
  ```
* [PyPi](https://pypi.org/project/ipydagred3) (📥 910 / month):
  ```
  pip install ipydagred3
  ```
* [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 79K / month):
  ```
  npm install @jupyter-widgets/jupyterlab-manager
  ```

</details>
<details><summary><b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉18 ·  ⭐ 740 · 💀) - Jupyter中的Google地图。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/pbugnion/gmaps) ⭐ 766 | 🐛 80 | 🌐 Python | 📅 2026-04-13 (👨‍💻 16 · 🔀 140 · 📦 1 · 📋 200 - 32% open · ⏱️ 22.07.2019):

  ```
  git clone https://github.com/pbugnion/gmaps
  ```
* [PyPi](https://pypi.org/project/gmaps) (📥 8.7K / month):
  ```
  pip install gmaps
  ```
* [Conda](https://anaconda.org/conda-forge/gmaps) (📥 270K · ⏱️ 02.08.2019):
  ```
  conda install -c conda-forge gmaps
  ```
* [NPM](https://www.npmjs.com/package/jupyter-gmaps) (📥 1.8K / month):
  ```
  npm install jupyter-gmaps
  ```

</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉18 ·  ⭐ 330) - 适用于Vega和Vega-Lite的IPython / Jupyter笔记本模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/vega/ipyvega) ⭐ 389 | 🐛 21 | 🌐 Jupyter Notebook | 📅 2025-04-01 (👨‍💻 11 · 🔀 55 · 📋 95 - 13% open · ⏱️ 01.08.2022):

  ```
  git clone https://github.com/vega/ipyvega
  ```
* [PyPi](https://pypi.org/project/vega) (📥 7.3K / month):
  ```
  pip install vega
  ```
* [Conda](https://anaconda.org/conda-forge/vega) (📥 500K · ⏱️ 10.02.2022):
  ```
  conda install -c conda-forge vega
  ```

</details>
<details><summary><b><a href="https://github.com/QuantStack/ipytree">ipytree</a></b> (🥉18 ·  ⭐ 93) - 使用Jupyter-widgets协议和jsTree的Tree Widget。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/QuantStack/ipytree) ⭐ 133 | 🐛 32 | 🌐 CSS | 📅 2026-03-16 (👨‍💻 8 · 🔀 25 · 📋 31 - 48% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/QuantStack/ipytree
  ```
* [PyPi](https://pypi.org/project/ipytree) (📥 34K / month):
  ```
  pip install ipytree
  ```
* [Conda](https://anaconda.org/conda-forge/ipytree) (📥 45K · ⏱️ 23.08.2022):
  ```
  conda install -c conda-forge ipytree
  ```

</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvue">ipyvue</a></b> (🥉18 ·  ⭐ 40 · 💤) - Vue库的Jupyter小部件基础。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/widgetti/ipyvue) ⭐ 72 | 🐛 17 | 🌐 Python | 📅 2026-08-11 (👨‍💻 3 · 🔀 11 · 📦 20 · 📋 7 - 28% open · ⏱️ 10.12.2021):

  ```
  git clone https://github.com/mariobuikhuizen/ipyvue
  ```
* [PyPi](https://pypi.org/project/ipyvue) (📥 66K / month):
  ```
  pip install ipyvue
  ```
* [Conda](https://anaconda.org/conda-forge/ipyvue) (📥 55K · ⏱️ 28.10.2021):
  ```
  conda install -c conda-forge ipyvue
  ```

</details>
<details><summary><b><a href="https://github.com/g2nb/igv-jupyter">igv.js widget</a></b> (🥉17 ·  ⭐ 150) - 集成了igv.js的Jupyter Notebook扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/g2nb/igv-jupyter) ⚠️ Archived (👨‍💻 5 · 🔀 15 · 📦 12 · ⏱️ 14.06.2022):

  ```
  git clone https://github.com/igvteam/igv-jupyter
  ```
* [PyPi](https://pypi.org/project/igv-jupyter) (📥 270 / month):
  ```
  pip install igv-jupyter
  ```

</details>
<details><summary><b><a href="https://github.com/spacetelescope/jdaviz">jdaviz</a></b> (🥉17 ·  ⭐ 73) - Jupyter平台中的JWST天文数据分析工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/spacetelescope/jdaviz) ⭐ 177 | 🐛 348 | 🌐 Python | 📅 2026-08-10 (👨‍💻 29 · 🔀 35 · 📋 690 - 38% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/spacetelescope/jdaviz
  ```
* [PyPi](https://pypi.org/project/jdaviz) (📥 1.7K / month):
  ```
  pip install jdaviz
  ```

</details>
<details><summary><b><a href="https://github.com/altair-viz/altair_viewer">Altair Viewer</a></b> (🥉17 ·  ⭐ 52 · 💤) - 用于Altair和Vega-Lite可视化的查看器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/altair-viz/altair_viewer) ⚠️ Archived (👨‍💻 3 · 🔀 8 · 📋 7 - 42% open · ⏱️ 14.01.2022):

  ```
  git clone https://github.com/altair-viz/altair_viewer
  ```
* [PyPi](https://pypi.org/project/altair_viewer) (📥 570K / month):
  ```
  pip install altair_viewer
  ```

</details>
<details><summary><b><a href="https://github.com/jpmorganchase/ipyregulartable">ipyregulartable</a></b> (🥉16 ·  ⭐ 66) - Jupyter中的高性能，可编辑，可样式化的数据表。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/jpmorganchase/ipyregulartable) ⭐ 113 | 🐛 9 | 🌐 JavaScript | 📅 2026-08-09 (👨‍💻 5 · 🔀 13 · 📦 9 · 📋 25 - 40% open · ⏱️ 20.07.2022):

  ```
  git clone https://github.com/jpmorganchase/ipyregulartable
  ```
* [PyPi](https://pypi.org/project/ipyregulartable) (📥 230 / month):
  ```
  pip install ipyregulartable
  ```
* [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 79K / month):
  ```
  npm install @jupyter-widgets/jupyterlab-manager
  ```

</details>
<details><summary><b><a href="https://github.com/vidartf/ipyscales">ipyscales</a></b> (🥉16 ·  ⭐ 13 · 💀) - 用于度量的小部件库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/vidartf/ipyscales) ⭐ 14 | 🐛 3 | 🌐 TypeScript | 📅 2023-01-08 (👨‍💻 4 · 🔀 3 · 📦 53 · 📋 6 - 33% open · ⏱️ 05.01.2021):

  ```
  git clone https://github.com/vidartf/ipyscales
  ```
* [PyPi](https://pypi.org/project/ipyscales) (📥 60 / month):
  ```
  pip install ipyscales
  ```
* [Conda](https://anaconda.org/conda-forge/ipyscales) (📥 54K · ⏱️ 06.01.2021):
  ```
  conda install -c conda-forge ipyscales
  ```

</details>
<details><summary><b><a href="https://github.com/OpenGeoscience/geonotebook">geonotebook</a></b> (🥉15 ·  ⭐ 1.1K · 💀) - Jupyter笔记本扩展，用于地理空间可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/OpenGeoscience/geonotebook) ⭐ 1,086 | 🐛 39 | 🌐 Python | 📅 2019-01-21 (👨‍💻 9 · 🔀 140 · 📋 83 - 44% open · ⏱️ 21.01.2019):

  ```
  git clone https://github.com/OpenGeoscience/geonotebook
  ```
* [Docker Hub](https://hub.docker.com/r/geonotebook/geonotebook) (📥 130K · ⭐ 7 · ⏱️ 21.01.2019):
  ```
  docker pull geonotebook/geonotebook
  ```

</details>
<details><summary><b><a href="https://github.com/nipy/niwidgets">niwidgets</a></b> (🥉15 ·  ⭐ 76 · 💀) - 适用于Jupyter笔记本的Neuroimaging小部件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/nipy/niwidgets) ⭐ 86 | 🐛 32 | 🌐 Jupyter Notebook | 📅 2022-12-08 (👨‍💻 16 · 🔀 33 · 📦 28 · 📋 34 - 50% open · ⏱️ 24.03.2020):

  ```
  git clone https://github.com/nipy/niwidgets
  ```
* [PyPi](https://pypi.org/project/niwidgets) (📥 72 / month):
  ```
  pip install niwidgets
  ```

</details>
<details><summary><b><a href="https://github.com/lgpage/nbtutor">nbtutor</a></b> (🥉14 ·  ⭐ 400) - 可视化Jupyter Notebook单元中的Python代码执行（逐行）。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/lgpage/nbtutor) ⭐ 472 | 🐛 27 | 🌐 TypeScript | 📅 2026-08-12 (👨‍💻 3 · 🔀 38 · 📦 28 · 📋 34 - 29% open · ⏱️ 04.04.2022):

  ```
  git clone https://github.com/lgpage/nbtutor
  ```
* [Conda](https://anaconda.org/conda-forge/nbtutor) (📥 110K · ⏱️ 19.04.2022):
  ```
  conda install -c conda-forge nbtutor
  ```

</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipymaterialui">ipymaterialui</a></b> (🥉13 ·  ⭐ 83 · 💀) - 基于React Material UI组件的Jupyter小部件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/maartenbreddels/ipymaterialui) ⭐ 86 | 🐛 31 | 🌐 Jupyter Notebook | 📅 2022-12-30 (👨‍💻 3 · 🔀 14 · 📦 5 · 📋 10 - 70% open · ⏱️ 29.10.2019):

  ```
  git clone https://github.com/maartenbreddels/ipymaterialui
  ```
* [PyPi](https://pypi.org/project/ipymaterialui) (📥 47 / month):
  ```
  pip install ipymaterialui
  ```
* [NPM](https://www.npmjs.com/package/jupyter-materialui) (📥 86 / month):
  ```
  npm install jupyter-materialui
  ```

</details>
<details><summary><b><a href="https://github.com/medialab/ipysigma">ipysigma</a></b> (🥉13 ·  ⭐ 38) - 一个自定义的Jupyter小部件库，用于使用sigma.js显示图形。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/medialab/ipysigma) ⭐ 308 | 🐛 75 | 🌐 Jupyter Notebook | 📅 2025-11-25 (👨‍💻 3 · 🔀 6 · 📋 100 - 43% open · ⏱️ 10.06.2022):

  ```
  git clone https://github.com/Yomguithereal/ipysigma
  ```
* [PyPi](https://pypi.org/project/ipysigma) (📥 110 / month):
  ```
  pip install ipysigma
  ```
* [NPM](https://www.npmjs.com/package/ipysigma) (📥 280 / month):
  ```
  npm install ipysigma
  ```

</details>
<details><summary><b><a href="https://github.com/CermakM/jupyter-datatables">Jupyter DataTables</a></b> (🥉11 ·  ⭐ 140 · 💀) - 利用pandas DataFrames的Jupyter Notebook扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/CermakM/jupyter-datatables) ⚠️ Archived (👨‍💻 4 · 🔀 15 · 📋 28 - 46% open · ⏱️ 11.12.2019):

  ```
  git clone https://github.com/CermakM/jupyter-datatables
  ```
* [PyPi](https://pypi.org/project/jupyter-datatables) (📥 550 / month):
  ```
  pip install jupyter-datatables
  ```

</details>
<details><summary><b><a href="https://github.com/leifwalsh/perfume">perfume</a></b> (🥉11 ·  ⭐ 33 · 💀) - Jupyter中的交互式性能基准测试。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/leifwalsh/perfume) ⭐ 33 | 🐛 4 | 🌐 Python | 📅 2024-12-02 (👨‍💻 3 · 🔀 4 · 📋 6 - 33% open · ⏱️ 31.10.2020):

  ```
  git clone https://github.com/leifwalsh/perfume
  ```
* [PyPi](https://pypi.org/project/perfume-bench) (📥 33 / month):
  ```
  pip install perfume-bench
  ```

</details>
<details><summary><b><a href="https://github.com/jtpio/ipyp5">ipyp5</a></b> (🥉10 ·  ⭐ 33 · 💀) - p5.j​​s Jupyter小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jtpio/ipyp5) ⭐ 42 | 🐛 17 | 🌐 Python | 📅 2023-01-04 (👨‍💻 2 · 🔀 5 · ⏱️ 16.10.2020):

  ```
  git clone https://github.com/jtpio/ipyp5
  ```
* [PyPi](https://pypi.org/project/ipyp5) (📥 22 / month):
  ```
  pip install ipyp5
  ```

</details>
<details><summary><b><a href="https://github.com/timkpaine/tributary">tributary</a></b> (🥉10 ·  ⭐ 3) - 在Python中流式反应图和数据流图。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/timkpaine/tributary) ⭐ 466 | 🐛 9 | 🌐 Python | 📅 2026-06-23 (👨‍💻 7 · ⏱️ 05.07.2022):

  ```
  git clone https://github.com/timkpaine/tributary
  ```
* [PyPi](https://pypi.org/project/tributary) (📥 61 / month):
  ```
  pip install tributary
  ```
* [Conda](https://anaconda.org/conda-forge/tributary) (📥 21K · ⏱️ 17.05.2022):
  ```
  conda install -c conda-forge tributary
  ```

</details>
<details><summary><b><a href="https://github.com/GianniBalistreri/easyexplore">easyexplore</a></b> (🥉10 ·  ⭐ 3) - 用于在Python中轻松有效地进行数据探索的工具箱。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/GianniBalistreri/easyexplore) ⭐ 5 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2023-07-06 (👨‍💻 4 · 🔀 2 · 📦 1 · 📋 24 - 33% open · ⏱️ 08.06.2022):

  ```
  git clone https://github.com/GianniBalistreri/easyexplore
  ```
* [PyPi](https://pypi.org/project/easyexplore) (📥 300 / month):
  ```
  pip install easyexplore
  ```

</details>
<details><summary><b><a href="https://github.com/asvcode/Vision_UI">Vision UI</a></b> (🥉9 ·  ⭐ 250 · 💀) - Fastai的UI视觉界面-现在与Google兼容。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/asvcode/Vision_UI) ⭐ 248 | 🐛 2 | 🌐 Python | 📅 2025-07-18 (👨‍💻 3 · 🔀 32 · 📋 3 - 33% open · ⏱️ 05.07.2020):

  ```
  git clone https://github.com/asvcode/Vision_UI
  ```

</details>
<details><summary><b><a href="https://github.com/ipyannotate/ipyannotate">ipyannotate</a></b> (🥉9 ·  ⭐ 120 · 💀) - Jupyter Widget，用于数据标注。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/ipyannotate/ipyannotate) ⭐ 140 | 🐛 19 | 🌐 Python | 📅 2023-01-06 (👨‍💻 3 · 🔀 10 · ⏱️ 20.09.2020):

  ```
  git clone https://github.com/ipyannotate/ipyannotate
  ```
* [PyPi](https://pypi.org/project/ipyannotate) (📥 24 / month):
  ```
  pip install ipyannotate
  ```
* [NPM](https://www.npmjs.com/package/ipyannotate) (📥 51 / month):
  ```
  npm install ipyannotate
  ```

</details>
<details><summary><b><a href="https://github.com/DGothrek/ipyaggrid">ipyaggrid</a></b> (🥉9 ·  ⭐ 10 · 💀) - Jupyter小部件-Notebook中的Ag-grid。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/DGothrek/ipyaggrid) ⭐ 11 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2019-05-06 (👨‍💻 2 · ⏱️ 06.05.2019):

  ```
  git clone https://github.com/DGothrek/ipyaggrid
  ```
* [PyPi](https://pypi.org/project/ipyaggrid) (📥 2.7K / month):
  ```
  pip install ipyaggrid
  ```
* [NPM](https://www.npmjs.com/package/ipyaggrid) (📥 3.1K / month):
  ```
  npm install ipyaggrid
  ```

</details>
<br>

## Jupyter拓展

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*扩展Jupyter自身功能的应用程序插件。*

<details><summary><b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥇21 ·  ⭐ 4.9K · 📈) - Jupyter的各种笔记本扩展的集合。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) ⭐ 5,278 | 🐛 387 | 🌐 JavaScript | 📅 2024-07-04 (👨‍💻 130 · 🔀 770 · 📋 770 - 41% open · ⏱️ 17.07.2022):

  ```
  git clone https://github.com/ipython-contrib/jupyter_contrib_nbextensions
  ```
* [PyPi](https://pypi.org/project/jupyter_contrib_nbextensions) (📥 300K / month):
  ```
  pip install jupyter_contrib_nbextensions
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥇21 ·  ⭐ 330) - Jupyter Notebook Extension，用于监视您自己的资源。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) ⭐ 536 | 🐛 55 | 🌐 TypeScript | 📅 2026-08-11 (👨‍💻 24 · 🔀 73 · 📥 73 · 📋 58 - 53% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/jupyter-server/jupyter-resource-usage
  ```
* [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 27K / month):
  ```
  pip install jupyter-resource-usage
  ```
* [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 500K · ⏱️ 23.11.2020):
  ```
  conda install -c conda-forge nbresuse
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥇21 ·  ⭐ 170) - Jupyter服务器扩展，可将git存储库单向同步。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/nbgitpuller) ⭐ 238 | 🐛 90 | 🌐 Python | 📅 2026-08-01 (👨‍💻 25 · 🔀 61 · 📦 500 · 📋 130 - 39% open · ⏱️ 22.06.2022):

  ```
  git clone https://github.com/jupyterhub/nbgitpuller
  ```
* [PyPi](https://pypi.org/project/nbgitpuller) (📥 7.7K / month):
  ```
  pip install nbgitpuller
  ```
* [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 40K · ⏱️ 20.03.2022):
  ```
  conda install -c conda-forge nbgitpuller
  ```

</details>
<details><summary><b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥈20 ·  ⭐ 9.2K) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/dunovank/jupyter-themes) ⭐ 9,820 | 🐛 205 | 🌐 CSS | 📅 2025-06-22 (👨‍💻 43 · 🔀 1K · 📋 390 - 48% open · ⏱️ 03.02.2022):

  ```
  git clone https://github.com/dunovank/jupyter-themes
  ```
* [PyPi](https://pypi.org/project/jupyterthemes) (📥 35K / month):
  ```
  pip install jupyterthemes
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥈20 ·  ⭐ 1.1K) - 用于在Notebook分配(任务/作业)和评分的系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter/nbgrader) ⭐ 1,369 | 🐛 295 | 🌐 Python | 📅 2026-08-11 (👨‍💻 97 · 🔀 290 · 📥 34 · 📋 810 - 24% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/jupyter/nbgrader
  ```
* [PyPi](https://pypi.org/project/nbgrader) (📥 3.4K / month):
  ```
  pip install nbgrader
  ```
* [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 120K · ⏱️ 23.06.2022):
  ```
  conda install -c conda-forge nbgrader
  ```

</details>
<details><summary><b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥈20 ·  ⭐ 400 · 💀) - Jupyter扩展，可将笔记本变成Web应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/oschuett/appmode) ⭐ 465 | 🐛 3 | 🌐 Python | 📅 2026-07-27 (👨‍💻 8 · 🔀 63 · 📦 320 · 📋 53 - 7% open · ⏱️ 26.04.2021):

  ```
  git clone https://github.com/oschuett/appmode
  ```
* [PyPi](https://pypi.org/project/appmode) (📥 2.1K / month):
  ```
  pip install appmode
  ```
* [Conda](https://anaconda.org/conda-forge/appmode) (📥 170K · ⏱️ 16.11.2021):
  ```
  conda install -c conda-forge appmode
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈20 ·  ⭐ 250) - Jupyter笔记本服务器扩展到代理Web服务。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) ⭐ 400 | 🐛 110 | 🌐 Python | 📅 2026-08-11 (👨‍💻 64 · 🔀 110 · 📦 4 · 📋 160 - 39% open · ⏱️ 08.07.2022):

  ```
  git clone https://github.com/jupyterhub/jupyter-server-proxy
  ```
* [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 110K / month):
  ```
  pip install jupyter-server-proxy
  ```
* [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 810K · ⏱️ 25.01.2022):
  ```
  conda install -c conda-forge jupyter-server-proxy
  ```

</details>
<details><summary><b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥈19 ·  ⭐ 910 · 📈) - A jupyter notebook serverextension providing config.. <code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) ⭐ 981 | 🐛 72 | 🌐 JavaScript | 📅 2024-06-05 (👨‍💻 20 · 🔀 110 · 📋 82 - 60% open · ⏱️ 09.07.2022):

  ```
  git clone https://github.com/jupyter-contrib/jupyter_nbextensions_configurator
  ```
* [PyPi](https://pypi.org/project/jupyter_nbextensions_configurator) (📥 320K / month):
  ```
  pip install jupyter_nbextensions_configurator
  ```

</details>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥈18 ·  ⭐ 220) - Jupyter内部的Conda环境和包管理扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/mamba-org/gator) ⭐ 272 | 🐛 71 | 🌐 TypeScript | 📅 2026-07-31 (👨‍💻 25 · 🔀 23 · 📥 2 · 📦 1 · 📋 53 - 26% open · ⏱️ 25.07.2022):

  ```
  git clone https://github.com/mamba-org/gator
  ```
* [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 18K · ⏱️ 26.07.2022):
  ```
  conda install -c conda-forge mamba_gator
  ```
* [NPM](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 140 / month):
  ```
  npm install @mamba-org/gator-lab
  ```

</details>
<details><summary><b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥉17 ·  ⭐ 980 · 💀) - pyforest-自动化导入工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/8080labs/pyforest) ⭐ 1,119 | 🐛 11 | 🌐 Python | 📅 2024-07-16 (👨‍💻 13 · 🔀 180 · 📋 23 - 39% open · ⏱️ 14.06.2021):

  ```
  git clone https://github.com/8080labs/pyforest
  ```
* [PyPi](https://pypi.org/project/pyforest) (📥 6.9K / month):
  ```
  pip install pyforest
  ```

</details>
<details><summary><b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉17 ·  ⭐ 170) - 从Jupyter Notebook监控Apache Spark。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/krishnan-r/sparkmonitor) ⚠️ Archived (👨‍💻 3 · 🔀 50 · 📥 2.4K · 📋 22 - 68% open · ⏱️ 16.05.2022):

  ```
  git clone https://github.com/krishnan-r/sparkmonitor
  ```
* [PyPi](https://pypi.org/project/sparkmonitor) (📥 1.4K / month):
  ```
  pip install sparkmonitor
  ```
* [Docker Hub](https://hub.docker.com/r/krishnanr/sparkmonitor) (📥 920 · ⏱️ 04.10.2019):
  ```
  docker pull krishnanr/sparkmonitor
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥉17 ·  ⭐ 94) - 用于运行RStudio rsession代理的Jupyter扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) ⭐ 128 | 🐛 40 | 🌐 Python | 📅 2026-08-01 (👨‍💻 20 · 🔀 68 · 📦 41 · 📋 71 - 36% open · ⏱️ 16.06.2022):

  ```
  git clone https://github.com/jupyterhub/jupyter-rsession-proxy
  ```
* [PyPi](https://pypi.org/project/jupyter-rsession-proxy) (📥 2.6K / month):
  ```
  pip install jupyter-rsession-proxy
  ```

</details>
<details><summary><b><a href="https://github.com/Anaconda-Platform/nb_conda">nb_conda</a></b> (🥉16 ·  ⭐ 130 · 💀) - Jupyter内部的Conda环境和包管理扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/Anaconda-Platform/nb_conda) ⚠️ Archived (👨‍💻 14 · 🔀 29 · 📋 63 - 55% open · ⏱️ 11.09.2020):

  ```
  git clone https://github.com/Anaconda-Platform/nb_conda
  ```
* [Conda](https://anaconda.org/conda-forge/nb_conda) (📥 390K · ⏱️ 05.06.2022):
  ```
  conda install -c conda-forge nb_conda
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥉16 ·  ⭐ 56) - Jupyter / Jupyterlab扩展，用于制作，下载和提取。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) ⭐ 90 | 🐛 11 | 🌐 Python | 📅 2026-08-11 (👨‍💻 9 · 🔀 10 · 📥 3.3K · 📋 33 - 3% open · ⏱️ 20.07.2022):

  ```
  git clone https://github.com/jupyterlab-contrib/jupyter-archive
  ```
* [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 27K · ⏱️ 08.04.2022):
  ```
  conda install -c conda-forge jupyter-archive
  ```

</details>
<details><summary><b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉15 ·  ⭐ 460 · 💀) - 在Jupyter Notebook中启动Tensorboard。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/lspvic/jupyter_tensorboard) ⭐ 461 | 🐛 44 | 🌐 Python | 📅 2022-06-14 (👨‍💻 4 · 🔀 70 · 📋 69 - 57% open · ⏱️ 16.02.2020):

  ```
  git clone https://github.com/lspvic/jupyter_tensorboard
  ```
* [PyPi](https://pypi.org/project/jupyter-tensorboard) (📥 2.5K / month):
  ```
  pip install jupyter-tensorboard
  ```

</details>
<details><summary><b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉15 ·  ⭐ 230 · 💤) - Jupyter对ws-over-ws的支持。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/googlecolab/jupyter_http_over_ws) ⚠️ Archived (👨‍💻 3 · 🔀 38 · 📋 29 - 72% open · ⏱️ 30.08.2021):

  ```
  git clone https://github.com/googlecolab/jupyter_http_over_ws
  ```
* [PyPi](https://pypi.org/project/jupyter_http_over_ws) (📥 52K / month):
  ```
  pip install jupyter_http_over_ws
  ```

</details>
<details><summary><b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥉15 ·  ⭐ 190 · 💀) - 利用pandas DataFrames的Jupyter Notebook扩展。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

* [GitHub](https://github.com/mozilla/jupyter-spark) ⚠️ Archived (👨‍💻 12 · 🔀 29 · 📦 16 · 📋 27 - 48% open · ⏱️ 01.12.2020):

  ```
  git clone https://github.com/mozilla/jupyter-spark
  ```
* [PyPi](https://pypi.org/project/jupyter-spark) (📥 560 / month):
  ```
  pip install jupyter-spark
  ```

</details>
<details><summary><b><a href="https://github.com/data-8/nbzip">nbzip</a></b> (🥉15 ·  ⭐ 80 · 💀) - 压缩并下载jupyter笔记本的所有内容。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/data-8/nbzip) ⚠️ Archived (👨‍💻 6 · 🔀 15 · 📦 290 · 📋 14 - 64% open · ⏱️ 22.11.2019):

  ```
  git clone https://github.com/data-8/nbzip
  ```
* [PyPi](https://pypi.org/project/nbzip) (📥 720 / month):
  ```
  pip install nbzip
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉14 ·  ⭐ 76 · 💀) - Jupyter内容管理扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter-incubator/contentmanagement) ⚠️ Archived (👨‍💻 8 · 🔀 25 · 📋 27 - 25% open · ⏱️ 11.06.2018):

  ```
  git clone https://github.com/jupyter-incubator/contentmanagement
  ```
* [PyPi](https://pypi.org/project/jupyter_cms) (📥 150 / month):
  ```
  pip install jupyter_cms
  ```
* [Conda](https://anaconda.org/conda-forge/jupyter_cms) (📥 77K · ⏱️ 17.11.2021):
  ```
  conda install -c conda-forge jupyter_cms
  ```

</details>
<details><summary><b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉12 ·  ⭐ 14 · 💤) - Jupyter中的依赖关系管理和优化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/thoth-station/jupyter-nbrequirements) ⭐ 21 | 🐛 12 | 🌐 TypeScript | 📅 2023-05-29 (👨‍💻 12 · 🔀 4 · ⏱️ 21.10.2021):

  ```
  git clone https://github.com/thoth-station/jupyter-nbrequirements
  ```

</details>
<details><summary><b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉9 ·  ⭐ 48 · 💀) - 一组iPython和Jupyter扩展。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/paypal/PPExtensions) ⚠️ Archived (👨‍💻 9 · 🔀 27 · 📦 1 · 📋 38 - 42% open · ⏱️ 07.12.2018):

  ```
  git clone https://github.com/paypal/PPExtensions
  ```
* [PyPi](https://pypi.org/project/ppextensions) (📥 55 / month):
  ```
  pip install ppextensions
  ```

</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉8 ·  ⭐ 400 · 💀) - Jupyter Notebook的黑色格式化程序。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/drillan/jupyter-black) ⭐ 436 | 🐛 12 | 🌐 JavaScript | 📅 2020-02-01 (👨‍💻 2 · 🔀 20 · 📋 21 - 42% open · ⏱️ 01.02.2020):

  ```
  git clone https://github.com/drillan/jupyter-black
  ```

</details>
<details><summary><b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉7 ·  ⭐ 8 · 💀) - Jupyter插件可支持嵌入式终端外壳。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/willkessler/jupyterterminals) ⭐ 13 | 🐛 2 | 🌐 JavaScript | 📅 2023-01-05 (👨‍💻 2 · 🔀 2 · 📦 1 · ⏱️ 17.05.2021):

  ```
  git clone https://github.com/willkessler/jupyterterminals
  ```

</details>
<br>

## Jupyter-magic拓展

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*提供magic命令以访问笔记本中方便功能的扩展。*

<details><summary><b><a href="https://github.com/catherinedevlin/ipython-sql">ipython-sql</a></b> (🥇27 ·  ⭐ 1.6K) - %%sql magic for IPython, hopefully evolving into full SQL client. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/catherinedevlin/ipython-sql) ⭐ 1,798 | 🐛 114 | 🌐 Python | 📅 2024-07-12 (👨‍💻 53 · 🔀 250 · 📦 3.4K · 📋 140 - 71% open · ⏱️ 12.06.2022):

  ```
  git clone https://github.com/catherinedevlin/ipython-sql
  ```
* [PyPi](https://pypi.org/project/ipython-sql) (📥 110K / month):
  ```
  pip install ipython-sql
  ```
* [Conda](https://anaconda.org/conda-forge/ipython-sql) (📥 160K · ⏱️ 13.11.2021):
  ```
  conda install -c conda-forge ipython-sql
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-incubator/sparkmagic">sparkmagic</a></b> (🥇26 ·  ⭐ 1.2K) - Jupyter魔术和内核，可用于远程Spark集群。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter-incubator/sparkmagic) ⭐ 1,366 | 🐛 167 | 🌐 Python | 📅 2025-09-09 (👨‍💻 57 · 🔀 380 · 📦 250 · 📋 400 - 32% open · ⏱️ 02.05.2022):

  ```
  git clone https://github.com/jupyter-incubator/sparkmagic
  ```
* [PyPi](https://pypi.org/project/sparkmagic) (📥 36K / month):
  ```
  pip install sparkmagic
  ```
* [Conda](https://anaconda.org/conda-forge/sparkmagic) (📥 51K · ⏱️ 09.05.2022):
  ```
  conda install -c conda-forge sparkmagic
  ```

</details>
<details><summary><b><a href="https://github.com/rasbt/watermark">watermark</a></b> (🥈23 ·  ⭐ 710) - 一个IPython魔术扩展，用于打印日期和时间戳版本。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/rasbt/watermark) ⭐ 943 | 🐛 18 | 🌐 Python | 📅 2025-12-21 (👨‍💻 19 · 🔀 81 · 📦 1.6K · 📋 44 - 36% open · ⏱️ 27.05.2022):

  ```
  git clone https://github.com/rasbt/watermark
  ```
* [PyPi](https://pypi.org/project/watermark) (📥 28K / month):
  ```
  pip install watermark
  ```
* [Conda](https://anaconda.org/conda-forge/watermark) (📥 220K · ⏱️ 30.05.2022):
  ```
  conda install -c conda-forge watermark
  ```

</details>
<details><summary><b><a href="https://github.com/csurfer/pyheatmagic">heat</a></b> (🥈16 ·  ⭐ 990 · 💤) - IPython魔术命令：格式化单元格中的python代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/csurfer/pyheatmagic) ⭐ 1,031 | 🐛 2 | 🌐 Python | 📅 2024-07-14 (👨‍💻 3 · 🔀 22 · 📦 29 · 📋 5 - 40% open · ⏱️ 10.09.2021):

  ```
  git clone https://github.com/csurfer/pyheatmagic
  ```
* [PyPi](https://pypi.org/project/py-heat-magic) (📥 1.2K / month):
  ```
  pip install py-heat-magic
  ```

</details>
<details><summary><b><a href="https://github.com/ShopRunner/jupyter-notify">jupyter-notify</a></b> (🥈16 ·  ⭐ 560 · 💀) - A Jupyter Notebook magic for browser notifications of cell.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/ShopRunner/jupyter-notify) (👨‍💻 11 · 🔀 34 · 📋 23 - 47% open · ⏱️ 27.04.2021):

  ```
  git clone https://github.com/ShopRunner/jupyter-notify
  ```
* [PyPi](https://pypi.org/project/jupyternotify) (📥 2.3K / month):
  ```
  pip install jupyternotify
  ```

</details>
<details><summary><b><a href="https://github.com/csurfer/blackcellmagic">blackcellmagic</a></b> (🥉15 ·  ⭐ 300 · 💤) - IPython魔术命令：格式化单元格中的python代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/csurfer/blackcellmagic) ⭐ 304 | 🐛 7 | 🌐 Python | 📅 2022-05-31 (👨‍💻 3 · 🔀 12 · 📦 160 · 📋 9 - 44% open · ⏱️ 18.09.2021):

  ```
  git clone https://github.com/csurfer/blackcellmagic
  ```
* [PyPi](https://pypi.org/project/blackcellmagic) (📥 2.9K / month):
  ```
  pip install blackcellmagic
  ```

</details>
<details><summary><b><a href="https://github.com/ResidentMario/py_d3">py_d3</a></b> (🥉12 ·  ⭐ 440) - D3 block magic for Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/ResidentMario/py_d3) ⭐ 450 | 🐛 0 | 🌐 Python | 📅 2022-02-20 (👨‍💻 4 · 🔀 39 · 📋 16 - 6% open · ⏱️ 20.02.2022):

  ```
  git clone https://github.com/ResidentMario/py_d3
  ```
* [PyPi](https://pypi.org/project/py_d3) (📥 97 / month):
  ```
  pip install py_d3
  ```

</details>
<details><summary><b><a href="https://github.com/tmthyjames/SQLCell">SQLCell</a></b> (🥉12 ·  ⭐ 150 · 💀) - SQLCell：Jupyter Notebook的魔术函数。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/tmthyjames/SQLCell) ⭐ 150 | 🐛 70 | 🌐 Python | 📅 2022-08-23 (👨‍💻 14 · 🔀 10 · 📦 1 · 📋 84 - 71% open · ⏱️ 06.10.2020):

  ```
  git clone https://github.com/tmthyjames/SQLCell
  ```
* [PyPi](https://pypi.org/project/sqlcell) (📥 12 / month):
  ```
  pip install sqlcell
  ```

</details>
<details><summary><b><a href="https://github.com/nteract/pick">pick</a></b> (🥉12 ·  ⭐ 31 · 💀) - 在启动时自定义您的内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/nteract/pick) ⚠️ Archived (👨‍💻 5 · 🔀 7 · 📋 9 - 44% open · ⏱️ 04.11.2020):

  ```
  git clone https://github.com/nteract/pick
  ```
* [PyPi](https://pypi.org/project/pick) (📥 49K / month):
  ```
  pip install pick
  ```

</details>
<details><summary><b><a href="https://github.com/krassowski/jupyter-manim">jupyter-manim</a></b> (🥉11 ·  ⭐ 180 · 💤) - manim单元魔术，用于IPython / Jupyter显示输出视频。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/krassowski/jupyter-manim) ⭐ 199 | 🐛 8 | 🌐 Python | 📅 2026-04-13 (👨‍💻 5 · 🔀 11 · 📋 25 - 24% open · ⏱️ 02.01.2022):

  ```
  git clone https://github.com/krassowski/jupyter-manim
  ```

</details>
<br>

## Jupyter内核

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*Jupyter内核以给定的语言运行和内省用户的代码。*

<details><summary><b><a href="https://github.com/gopherdata/gophernotes">gophernotes</a></b> (🥇22 ·  ⭐ 3.4K) - 适用于Jupyter笔记本电脑和nteract的Go内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/gopherdata/gophernotes) ⭐ 3,966 | 🐛 55 | 🌐 Go | 📅 2023-11-03 (👨‍💻 29 · 🔀 220 · 📥 40 · 📦 8 · 📋 170 - 28% open · ⏱️ 08.07.2022):

  ```
  git clone https://github.com/gopherdata/gophernotes
  ```
* [Docker Hub](https://hub.docker.com/r/gopherdata/gophernotes) (📥 86K · ⭐ 7 · ⏱️ 22.12.2018):
  ```
  docker pull gopherdata/gophernotes
  ```

</details>
<details><summary><b><a href="https://github.com/ipython/ipykernel">IPython Kernel</a></b> (🥇22 ·  ⭐ 500 · 📉) - IPython Kernel for Jupyter. <code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/ipython/ipykernel) ⭐ 736 | 🐛 307 | 🌐 Python | 📅 2026-08-12 (👨‍💻 160 · 🔀 300 · 📥 520 · 📋 420 - 51% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/ipython/ipykernel
  ```
* [PyPi](https://pypi.org/project/ipykernel) (📥 10M / month):
  ```
  pip install ipykernel
  ```
* [Conda](https://anaconda.org/anaconda/ipykernel) (📥 380K · ⏱️ 02.05.2022):
  ```
  conda install -c anaconda ipykernel
  ```

</details>
<details><summary><b><a href="https://github.com/IRkernel/IRkernel">IRkernel</a></b> (🥇21 ·  ⭐ 1.6K) - Jupyter的R内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/IRkernel/IRkernel) ⭐ 1,697 | 🐛 75 | 🌐 Jupyter Notebook | 📅 2024-04-30 (👨‍💻 41 · 🔀 290 · 📋 570 - 9% open · ⏱️ 24.06.2022):

  ```
  git clone https://github.com/IRkernel/IRkernel
  ```
* [Conda](https://anaconda.org/r/r-irkernel) (📥 82K · ⏱️ 31.05.2022):
  ```
  conda install -c r r-irkernel
  ```
* [Docker Hub](https://hub.docker.com/r/jupyter/r-notebook) (📥 1.3M · ⭐ 44 · ⏱️ 23.08.2022):
  ```
  docker pull jupyter/r-notebook
  ```

</details>
<details><summary><b><a href="https://github.com/Calysto/octave_kernel">Octave Kernel</a></b> (🥇20 ·  ⭐ 410) - 用于IPython的Octave内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/Calysto/octave_kernel) ⭐ 458 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-08-12 (👨‍💻 18 · 🔀 60 · 📥 50 · 📋 170 - 16% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/calysto/octave_kernel
  ```
* [PyPi](https://pypi.org/project/octave_kernel) (📥 13K / month):
  ```
  pip install octave_kernel
  ```

</details>
<details><summary><b><a href="https://github.com/Calysto/metakernel">Metakernel</a></b> (🥇20 ·  ⭐ 290) - Jupyter/IPython内核工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/Calysto/metakernel) ⭐ 371 | 🐛 0 | 🌐 Python | 📅 2026-08-11 (👨‍💻 31 · 🔀 78 · 📥 42 · 📋 140 - 19% open · ⏱️ 09.08.2022):

  ```
  git clone https://github.com/Calysto/metakernel
  ```
* [PyPi](https://pypi.org/project/metakernel) (📥 71K / month):
  ```
  pip install metakernel
  ```
* [Conda](https://anaconda.org/conda-forge/metakernel) (📥 600K · ⏱️ 09.08.2022):
  ```
  conda install -c conda-forge metakernel
  ```

</details>
<details><summary><b><a href="https://github.com/JuliaLang/IJulia.jl">IJulia.jl</a></b> (🥈19 ·  ⭐ 2.5K) - Jupyter的Julia内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/JuliaLang/IJulia.jl) ⭐ 2,896 | 🐛 36 | 🌐 Julia | 📅 2026-06-23 (👨‍💻 100 · 🔀 380 · 📋 790 - 12% open · ⏱️ 23.06.2022):

  ```
  git clone https://github.com/JuliaLang/IJulia.jl
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-cling">xeus-cling</a></b> (🥈19 ·  ⭐ 2.3K · 💤) - 适用于C++编程语言的Jupyter内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter-xeus/xeus-cling) ⭐ 3,288 | 🐛 179 | 🌐 C++ | 📅 2025-10-27 (👨‍💻 20 · 🔀 240 · 📋 250 - 53% open · ⏱️ 17.01.2022):

  ```
  git clone https://github.com/jupyter-xeus/xeus-cling
  ```
* [Conda](https://anaconda.org/conda-forge/xeus-cling) (📥 160K · ⏱️ 08.03.2022):
  ```
  conda install -c conda-forge xeus-cling
  ```

</details>
<details><summary><b><a href="https://github.com/n-riesco/ijavascript">IJavascript</a></b> (🥈19 ·  ⭐ 1.9K · 💤) - Jupyter笔记本的JavaScript内核。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/n-riesco/ijavascript) ⭐ 2,260 | 🐛 59 | 🌐 JavaScript | 📅 2024-07-03 (👨‍💻 15 · 🔀 150 · 📦 63 · 📋 230 - 23% open · ⏱️ 24.01.2022):

  ```
  git clone https://github.com/n-riesco/ijavascript
  ```
* [NPM](https://www.npmjs.com/package/ijavascript) (📥 2.4K / month):
  ```
  npm install ijavascript
  ```

</details>
<details><summary><b><a href="https://github.com/almond-sh/almond">almond</a></b> (🥈19 ·  ⭐ 1.5K) - Jupyter的Scala内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/almond-sh/almond) ⭐ 1,624 | 🐛 147 | 🌐 Scala | 📅 2026-08-06 (👨‍💻 36 · 🔀 220 · 📥 1.3K · 📋 300 - 32% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/almond-sh/almond
  ```
* [Docker Hub](https://hub.docker.com/r/almondsh/almond) (📥 15K · ⭐ 6 · ⏱️ 16.08.2022):
  ```
  docker pull almondsh/almond
  ```

</details>
<details><summary><b><a href="https://github.com/apache/incubator-toree">Apache Toree</a></b> (🥈19 ·  ⭐ 700) - 适用于Apache Spark的Jupyter内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/apache/incubator-toree) ⭐ 750 | 🐛 20 | 🌐 Scala | 📅 2026-08-07 (👨‍💻 100 · 🔀 210 · ⏱️ 15.03.2022):

  ```
  git clone https://github.com/apache/incubator-toree
  ```
* [PyPi](https://pypi.org/project/toree) (📥 13K / month):
  ```
  pip install toree
  ```

</details>
<details><summary><b><a href="https://github.com/IHaskell/IHaskell">IHaskell</a></b> (🥈18 ·  ⭐ 2.4K) - 用于IPython的Haskell内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/IHaskell/IHaskell) ⭐ 2,646 | 🐛 51 | 🌐 Jupyter Notebook | 📅 2026-07-06 (👨‍💻 110 · 🔀 240 · 📦 4 · 📋 740 - 4% open · ⏱️ 22.07.2022):

  ```
  git clone https://github.com/gibiansky/IHaskell
  ```
* [NPM](https://www.npmjs.com/package/ihaskell_jupyterlab) (📥 13 / month):
  ```
  npm install ihaskell_jupyterlab
  ```

</details>
<details><summary><b><a href="https://github.com/SciRuby/iruby">IRuby</a></b> (🥈18 ·  ⭐ 720) - 官方gem仓库：Jupyter/IPython Notebook的Ruby内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/SciRuby/iruby) ⭐ 927 | 🐛 49 | 🌐 Ruby | 📅 2026-06-30 (👨‍💻 44 · 🔀 18 · 📥 15 · 📦 160 · 📋 190 - 24% open · ⏱️ 05.07.2022):

  ```
  git clone https://github.com/SciRuby/iruby
  ```
* [Docker Hub](https://hub.docker.com/r/rubydata/datascience-notebook) (📥 1.7K · ⭐ 3 · ⏱️ 07.06.2022):
  ```
  docker pull rubydata/datascience-notebook
  ```

</details>
<details><summary><b><a href="https://github.com/Anaconda-Platform/nb_conda_kernels">nb_conda_kernels</a></b> (🥈18 ·  ⭐ 470 · 💀) - Package for managing conda environment-based kernels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/Anaconda-Platform/nb_conda_kernels) ⭐ 645 | 🐛 28 | 🌐 Python | 📅 2026-07-26 (👨‍💻 14 · 🔀 56 · 📋 130 - 26% open · ⏱️ 30.11.2020):

  ```
  git clone https://github.com/Anaconda-Platform/nb_conda_kernels
  ```
* [Conda](https://anaconda.org/conda-forge/nb_conda_kernels) (📥 710K · ⏱️ 14.02.2022):
  ```
  conda install -c conda-forge nb_conda_kernels
  ```

</details>
<details><summary><b><a href="https://github.com/akabe/ocaml-jupyter">OCaml Kernel</a></b> (🥈18 ·  ⭐ 230) - Jupyter（IPython）笔记本的OCaml内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/akabe/ocaml-jupyter) ⭐ 316 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2026-03-12 (👨‍💻 18 · 🔀 29 · 📥 70K · 📋 71 - 4% open · ⏱️ 10.04.2022):

  ```
  git clone https://github.com/akabe/ocaml-jupyter
  ```

</details>
<details><summary><b><a href="https://github.com/sassoftware/sas_kernel">SAS Kernel</a></b> (🥈18 ·  ⭐ 190) - 用于SAS的Jupyter内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/sassoftware/sas_kernel) ⭐ 204 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2026-05-08 (👨‍💻 9 · 🔀 72 · 📋 57 - 5% open · ⏱️ 01.06.2022):

  ```
  git clone https://github.com/sassoftware/sas_kernel
  ```
* [PyPi](https://pypi.org/project/sas_kernel) (📥 2K / month):
  ```
  pip install sas_kernel
  ```

</details>
<details><summary><b><a href="https://github.com/vericast/spylon-kernel">Spylon Kernel</a></b> (🥈18 ·  ⭐ 160 · 💀) - Jupyter kernel for scala and spark. <code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/vericast/spylon-kernel) ⭐ 191 | 🐛 26 | 🌐 Python | 📅 2024-01-11 (👨‍💻 6 · 🔀 28 · 📦 88 · 📋 35 - 48% open · ⏱️ 20.09.2018):

  ```
  git clone https://github.com/Valassis-Digital-Media/spylon-kernel
  ```
* [PyPi](https://pypi.org/project/spylon-kernel) (📥 2.3K / month):
  ```
  pip install spylon-kernel
  ```
* [Conda](https://anaconda.org/conda-forge/spylon-kernel) (📥 95K · ⏱️ 05.10.2018):
  ```
  conda install -c conda-forge spylon-kernel
  ```

</details>
<details><summary><b><a href="https://github.com/SpencerPark/IJava">IJava</a></b> (🥉17 ·  ⭐ 820 · 💀) - 用于执行Java代码的Jupyter内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/SpencerPark/IJava) ⭐ 1,187 | 🐛 94 | 🌐 Java | 📅 2024-06-01 (👨‍💻 4 · 🔀 160 · 📥 89K · 📋 130 - 54% open · ⏱️ 08.12.2019):

  ```
  git clone https://github.com/SpencerPark/IJava
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-server/kernel_gateway">Kernel Gateway</a></b> (🥉17 ·  ⭐ 400) - Jupyter内核网关。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter-server/kernel_gateway) ⭐ 562 | 🐛 25 | 🌐 Python | 📅 2024-03-12 (👨‍💻 44 · 🔀 110 · 📥 100 · 📋 180 - 7% open · ⏱️ 12.03.2022):

  ```
  git clone https://github.com/jupyter/kernel_gateway
  ```
* [PyPi](https://pypi.org/project/jupyter-kernel-gateway) (📥 14K / month):
  ```
  pip install jupyter-kernel-gateway
  ```

</details>
<details><summary><b><a href="https://github.com/scijava/scijava-jupyter-kernel">SciJava Kernel</a></b> (🥉17 ·  ⭐ 180) - 在Jupyter笔记本中编写SciJava脚本。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/scijava/scijava-jupyter-kernel) ⚠️ Archived (👨‍💻 9 · 🔀 42 · 📥 86 · ⏱️ 03.02.2022):

  ```
  git clone https://github.com/scijava/scijava-jupyter-kernel
  ```
* [Conda](https://anaconda.org/conda-forge/scijava-jupyter-kernel) (📥 81K · ⏱️ 03.03.2018):
  ```
  conda install -c conda-forge scijava-jupyter-kernel
  ```

</details>
<details><summary><b><a href="https://github.com/clojupyter/clojupyter">clojupyter</a></b> (🥉16 ·  ⭐ 740 · 💤) - 用于Clojure的Jupyter内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/clojupyter/clojupyter) ⭐ 867 | 🐛 13 | 🌐 Clojure | 📅 2025-03-18 (👨‍💻 26 · 🔀 75 · 📋 97 - 18% open · ⏱️ 29.12.2021):

  ```
  git clone https://github.com/clojupyter/clojupyter
  ```
* [Conda](https://anaconda.org/simplect/clojupyter) (📥 3K · ⏱️ 02.03.2020):
  ```
  conda install -c simplect clojupyter
  ```
* [Docker Hub](https://hub.docker.com/r/simplect/clojupyter) (📥 390 · ⏱️ 25.04.2019):
  ```
  docker pull simplect/clojupyter
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-server/enterprise_gateway">Enterprise Gateway</a></b> (🥉16 ·  ⭐ 520) - 轻量级，多租户，可扩展和安全的网关。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter-server/enterprise_gateway) ⭐ 668 | 🐛 88 | 🌐 Python | 📅 2026-07-14 (👨‍💻 100 · 🔀 180 · 📥 20K · 📋 520 - 9% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/jupyter/enterprise_gateway
  ```
* [PyPi](https://pypi.org/project/jupyter_enterprise_gateway) (📥 1.3K / month):
  ```
  pip install jupyter_enterprise_gateway
  ```

</details>
<details><summary><b><a href="https://github.com/Calysto/matlab_kernel">Matlab Kernel</a></b> (🥉16 ·  ⭐ 440) - Jupyter的Matlab内核。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/Calysto/matlab_kernel) ⭐ 469 | 🐛 28 | 🌐 Jupyter Notebook | 📅 2022-05-09 (👨‍💻 18 · 🔀 73 · 📋 130 - 19% open · ⏱️ 09.05.2022):

  ```
  git clone https://github.com/calysto/matlab_kernel
  ```
* [PyPi](https://pypi.org/project/matlab_kernel) (📥 3.9K / month):
  ```
  pip install matlab_kernel
  ```

</details>
<details><summary><b><a href="https://github.com/WolframResearch/WolframLanguageForJupyter">Wolfram Kernel</a></b> (🥉15 ·  ⭐ 750) - 适用于Jupyter的Wolfram语言内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/WolframResearch/WolframLanguageForJupyter) ⭐ 1,212 | 🐛 50 | 🌐 Mathematica | 📅 2023-12-22 (👨‍💻 7 · 🔀 91 · 📥 6.1K · 📋 96 - 31% open · ⏱️ 19.02.2022):

  ```
  git clone https://github.com/WolframResearch/WolframLanguageForJupyter
  ```

</details>
<details><summary><b><a href="https://github.com/takluyver/bash_kernel">Bash Kernel</a></b> (🥉15 ·  ⭐ 600) - IPython的bash内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/takluyver/bash_kernel) ⭐ 729 | 🐛 23 | 🌐 Python | 📅 2025-01-05 (👨‍💻 14 · 🔀 100 · 📋 94 - 37% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/takluyver/bash_kernel
  ```
* [PyPi](https://pypi.org/project/bash_kernel) (📥 6K / month):
  ```
  pip install bash_kernel
  ```

</details>
<details><summary><b><a href="https://github.com/ansible/ansible-jupyter-kernel">Ansible Kernel</a></b> (🥉15 ·  ⭐ 500) - Jupyter笔记本内核，用于运行Ansible任务。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/ansible/ansible-jupyter-kernel) ⭐ 539 | 🐛 18 | 🌐 Python | 📅 2022-02-11 (👨‍💻 10 · 🔀 54 · 📦 9 · 📋 44 - 34% open · ⏱️ 11.02.2022):

  ```
  git clone https://github.com/ansible/ansible-jupyter-kernel
  ```
* [PyPi](https://pypi.org/project/ansible-kernel) (📥 280 / month):
  ```
  pip install ansible-kernel
  ```
* [Conda](https://anaconda.org/conda-forge/ansible-kernel) (📥 11K · ⏱️ 12.02.2022):
  ```
  conda install -c conda-forge ansible-kernel
  ```
* [Docker Hub](https://hub.docker.com/r/benthomasson/ansible-jupyter-kernel) (📥 66K · ⭐ 2 · ⏱️ 12.12.2018):
  ```
  docker pull benthomasson/ansible-jupyter-kernel
  ```

</details>
<details><summary><b><a href="https://github.com/lfortran/lfortran">LFortran</a></b> (🥉14 ·  ⭐ 370) - https://gitlab.com/lfortran/lfortran的官方镜像。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/lfortran/lfortran) ⭐ 1,227 | 🐛 2,352 | 🌐 C++ | 📅 2026-08-12 (👨‍💻 38 · 🔀 38 · 📋 470 - 95% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/lfortran/lfortran
  ```
* [PyPi](https://pypi.org/project/lfortran) (📥 110 / month):
  ```
  pip install lfortran
  ```
* [Conda](https://anaconda.org/conda-forge/lfortran) (📥 40K · ⏱️ 23.09.2021):
  ```
  conda install -c conda-forge lfortran
  ```

</details>
<details><summary><b><a href="https://github.com/pprzetacznik/IElixir">IElixir</a></b> (🥉14 ·  ⭐ 340 · 💀) - Jupyter的Elixir编程语言内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/pprzetacznik/IElixir) ⭐ 369 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2024-05-26 (👨‍💻 19 · 🔀 39 · 📋 30 - 33% open · ⏱️ 20.03.2021):

  ```
  git clone https://github.com/pprzetacznik/IElixir
  ```
* [Docker Hub](https://hub.docker.com/r/pprzetacznik/ielixir) (📥 340 · ⭐ 1 · ⏱️ 20.03.2021):
  ```
  docker pull pprzetacznik/ielixir
  ```

</details>
<details><summary><b><a href="https://github.com/Cadair/jupyter_environment_kernels">Kernel Detection</a></b> (🥉14 ·  ⭐ 140 · 💀) - 一个Jupyter插件，用于自动检测。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/Cadair/jupyter_environment_kernels) ⭐ 150 | 🐛 7 | 🌐 Python | 📅 2022-11-23 (👨‍💻 6 · 🔀 16 · 📋 29 - 24% open · ⏱️ 12.02.2018):

  ```
  git clone https://github.com/Cadair/jupyter_environment_kernels
  ```
* [PyPi](https://pypi.org/project/environment_kernels) (📥 2.6K / month):
  ```
  pip install environment_kernels
  ```

</details>
<details><summary><b><a href="https://github.com/yunabe/lgo">lgo</a></b> (🥉13 ·  ⭐ 2.3K · 💀) - 使用Jupyter进行交互式Go编程。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/yunabe/lgo) ⭐ 2,455 | 🐛 24 | 🌐 Go | 📅 2020-11-20 (👨‍💻 9 · 🔀 110 · 📋 76 - 30% open · ⏱️ 09.07.2019):

  ```
  git clone https://github.com/yunabe/lgo
  ```

</details>
<details><summary><b><a href="https://github.com/fsprojects/IfSharp">F# Kernel</a></b> (🥉12 ·  ⭐ 430) - F# for Jupyter Notebooks. <code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/fsprojects/IfSharp) ⭐ 444 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2022-03-17 (👨‍💻 28 · 🔀 67 · 📥 5.4K · 📋 140 - 9% open · ⏱️ 17.03.2022):

  ```
  git clone https://github.com/fsprojects/IfSharp
  ```
* [Docker Hub](https://hub.docker.com/r/fsprojects/ifsharp) (📥 680 · ⏱️ 26.03.2019):
  ```
  docker pull fsprojects/ifsharp
  ```

</details>
<details><summary><b><a href="https://github.com/zabirauf/icsharp">ICSharp</a></b> (🥉12 ·  ⭐ 270 · 💀) - Jupyter的C＃内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/zabirauf/icsharp) ⚠️ Archived (👨‍💻 10 · 🔀 57 · 📋 46 - 71% open · ⏱️ 23.09.2018):

  ```
  git clone https://github.com/zabirauf/icsharp
  ```

</details>
<details><summary><b><a href="https://github.com/NII-cloud-operation/sshkernel">SSH Kernel</a></b> (🥉12 ·  ⭐ 53 · 💤) - Jupyter的SSH内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/NII-cloud-operation/sshkernel) ⭐ 75 | 🐛 3 | 🌐 Python | 📅 2021-11-04 (👨‍💻 4 · 🔀 12 · 📦 6 · 📋 8 - 25% open · ⏱️ 04.11.2021):

  ```
  git clone https://github.com/NII-cloud-operation/sshkernel
  ```
* [PyPi](https://pypi.org/project/sshkernel) (📥 79 / month):
  ```
  pip install sshkernel
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-sqlite">xeus-sqlite</a></b> (🥉11 ·  ⭐ 140) - 适用于SQLite的Jupyter内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter-xeus/xeus-sqlite) ⭐ 172 | 🐛 19 | 🌐 C++ | 📅 2026-03-16 (👨‍💻 12 · 🔀 21 · 📋 41 - 26% open · ⏱️ 15.03.2022):

  ```
  git clone https://github.com/jupyter-xeus/xeus-sqlite
  ```

</details>
<details><summary><b><a href="https://github.com/tdaff/remote_ikernel">remote_ikernel</a></b> (🥉10 ·  ⭐ 12 · 💀) - All your Jupyter kernels, on all your machines, in one place. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/tdaff/remote_ikernel) ⭐ 21 | 🐛 14 | 🌐 Python | 📅 2024-08-02 (👨‍💻 7 · 🔀 11 · 📋 27 - 33% open · ⏱️ 08.11.2020):

  ```
  git clone https://github.com/tdaff/remote_ikernel
  ```
* [PyPi](https://pypi.org/project/remote_ikernel) (📥 160 / month):
  ```
  pip install remote_ikernel
  ```

</details>
<details><summary><b><a href="https://github.com/bernhard-42/ssh_ipykernel">ssh_ipykernel</a></b> (🥉7 ·  ⭐ 8 · 💀) - A remote jupyter kernel via ssh. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/bernhard-42/ssh_ipykernel) ⭐ 19 | 🐛 18 | 🌐 Python | 📅 2023-09-08 (👨‍💻 2 · 🔀 2 · ⏱️ 28.06.2021):

  ```
  git clone https://github.com/bernhard-42/ssh_ipykernel
  ```

</details>
<details><summary><b><a href="https://github.com/nteract/kernel-relay">kernel-relay</a></b> (🥉6 ·  ⭐ 11 · 💀) - kernel-relay是与之接口的GraphQL服务。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/nteract/kernel-relay) ⚠️ Archived (👨‍💻 3 · 🔀 5 · 📋 12 - 83% open · ⏱️ 10.07.2019):

  ```
  git clone https://github.com/nteract/kernel-relay
  ```

</details>
<br>

## Jupyter-Notebook分享与格式转换

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*与笔记本文件共享、转换和简化协作的工具（例如，通过git）。*

<details><summary><b><a href="https://github.com/jupyter/nbconvert">nbconvert</a></b> (🥇31 ·  ⭐ 1.4K) - Jupyter Notebook Conversion. <code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter/nbconvert) ⭐ 1,933 | 🐛 602 | 🌐 Python | 📅 2026-08-03 (👨‍💻 250 · 🔀 480 · 📦 160K · 📋 1K - 42% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/jupyter/nbconvert
  ```
* [PyPi](https://pypi.org/project/nbconvert) (📥 12M / month):
  ```
  pip install nbconvert
  ```
* [Conda](https://anaconda.org/conda-forge/nbconvert) (📥 7.9M · ⏱️ 23.08.2022):
  ```
  conda install -c conda-forge nbconvert
  ```

</details>
<details><summary><b><a href="https://github.com/getnikola/nikola">nikola</a></b> (🥇29 ·  ⭐ 2.3K) - 静态网站和博客生成器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/getnikola/nikola) ⭐ 2,741 | 🐛 93 | 🌐 Python | 📅 2026-06-21 (👨‍💻 230 · 🔀 350 · 📦 440 · 📋 2.1K - 2% open · ⏱️ 02.08.2022):

  ```
  git clone https://github.com/getnikola/nikola
  ```
* [PyPi](https://pypi.org/project/nikola) (📥 1.9K / month):
  ```
  pip install nikola
  ```

</details>
<details><summary><b><a href="https://github.com/mwouts/jupytext">Jupytext</a></b> (🥇27 ·  ⭐ 5.5K) - Jupyter Notebooks作为Markdown文档，Julia，Python或R脚本的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/mwouts/jupytext) ⭐ 7,227 | 🐛 167 | 🌐 Python | 📅 2026-08-11 (👨‍💻 72 · 🔀 350 · 📦 3.2K · 📋 530 - 12% open · ⏱️ 29.07.2022):

  ```
  git clone https://github.com/mwouts/jupytext
  ```
* [PyPi](https://pypi.org/project/jupytext) (📥 260K / month):
  ```
  pip install jupytext
  ```
* [Conda](https://anaconda.org/conda-forge/jupytext) (📥 380K · ⏱️ 03.07.2022):
  ```
  conda install -c conda-forge jupytext
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-jupytext) (📥 6.5K / month):
  ```
  npm install jupyterlab-jupytext
  ```

</details>
<details><summary><b><a href="https://github.com/voila-dashboards/voila">Voila</a></b> (🥈26 ·  ⭐ 4.3K) - Voil将Jupyter笔记本变成独立的Web应用程序。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/voila-dashboards/voila) ⭐ 5,941 | 🐛 328 | 🌐 Python | 📅 2026-08-03 (👨‍💻 61 · 🔀 420 · 📥 290 · 📦 7.2K · 📋 610 - 40% open · ⏱️ 11.08.2022):

  ```
  git clone https://github.com/voila-dashboards/voila
  ```
* [PyPi](https://pypi.org/project/voila) (📥 54K / month):
  ```
  pip install voila
  ```
* [Conda](https://anaconda.org/conda-forge/voila) (📥 200K · ⏱️ 18.07.2022):
  ```
  conda install -c conda-forge voila
  ```
* [NPM](https://www.npmjs.com/package/@jupyter-voila/jupyterlab-preview) (📥 3.2K / month):
  ```
  npm install @jupyter-voila/jupyterlab-preview
  ```

</details>
<details><summary><b><a href="https://github.com/damianavila/RISE">RISE</a></b> (🥈24 ·  ⭐ 3.3K) - 实时Reveal.js Jupyter/IPython幻灯片扩展。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/damianavila/RISE) ⭐ 3,739 | 🐛 162 | 🌐 JavaScript | 📅 2023-10-29 (👨‍💻 41 · 🔀 380 · 📦 2K · 📋 430 - 33% open · ⏱️ 28.03.2022):

  ```
  git clone https://github.com/damianavila/RISE
  ```
* [PyPi](https://pypi.org/project/RISE) (📥 5.9K / month):
  ```
  pip install RISE
  ```
* [Conda](https://anaconda.org/conda-forge/rise) (📥 220K · ⏱️ 16.11.2021):
  ```
  conda install -c conda-forge rise
  ```

</details>
<details><summary><b><a href="https://github.com/executablebooks/jupyter-book">Jupyter Book</a></b> (🥈24 ·  ⭐ 3K) - 从Jupyter构建交互式的，具有出版质量的文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/executablebooks/jupyter-book) ⭐ 4,268 | 🐛 668 | 🌐 TypeScript | 📅 2026-08-08 (👨‍💻 110 · 🔀 500 · 📋 1.1K - 41% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/executablebooks/jupyter-book
  ```
* [PyPi](https://pypi.org/project/jupyter-book) (📥 52K / month):
  ```
  pip install jupyter-book
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter/nbdime">nbdime</a></b> (🥈23 ·  ⭐ 2.3K) - 区分和合并Jupyter笔记本的工具。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter/nbdime) ⭐ 2,839 | 🐛 94 | 🌐 TypeScript | 📅 2026-06-10 (👨‍💻 40 · 🔀 130 · 📦 79 · 📋 280 - 22% open · ⏱️ 05.07.2022):

  ```
  git clone https://github.com/jupyter/nbdime
  ```
* [PyPi](https://pypi.org/project/nbdime) (📥 260K / month):
  ```
  pip install nbdime
  ```
* [Conda](https://anaconda.org/conda-forge/nbdime) (📥 610K · ⏱️ 26.10.2021):
  ```
  conda install -c conda-forge nbdime
  ```
* [NPM](https://www.npmjs.com/package/nbdime-jupyterlab) (📥 140K / month):
  ```
  npm install nbdime-jupyterlab
  ```

</details>
<details><summary><b><a href="https://github.com/stencila/stencila">Stencila</a></b> (🥈23 ·  ⭐ 650) - 用于可复制研究的在线文档。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/stencila/stencila) ⭐ 900 | 🐛 131 | 🌐 Rust | 📅 2026-08-12 (👨‍💻 34 · 🔀 34 · 📥 3.1K · 📦 17 · 📋 560 - 11% open · ⏱️ 29.07.2022):

  ```
  git clone https://github.com/stencila/stencila
  ```
* [NPM](https://www.npmjs.com/package/stencila) (📥 360 / month):
  ```
  npm install stencila
  ```
* [Docker Hub](https://hub.docker.com/r/stencila/cloud) (📥 16K · ⏱️ 08.04.2019):
  ```
  docker pull stencila/cloud
  ```

</details>
<details><summary><b><a href="https://github.com/airbnb/knowledge-repo">Knowledge Repo</a></b> (🥈21 ·  ⭐ 5.2K) - 下一代知识共享平台<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/airbnb/knowledge-repo) ⭐ 5,538 | 🐛 137 | 🌐 Python | 📅 2024-09-04 (👨‍💻 68 · 🔀 650 · 📋 290 - 42% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/airbnb/knowledge-repo
  ```
* [PyPi](https://pypi.org/project/knowledge-repo) (📥 280 / month):
  ```
  pip install knowledge-repo
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter/nbviewer">nbviewer</a></b> (🥉19 ·  ⭐ 2K) - nbconvert作为Web服务：将Jupyter Notebooks渲染为静态Web。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter/nbviewer) ⭐ 2,279 | 🐛 204 | 🌐 Python | 📅 2026-07-06 (👨‍💻 91 · 🔀 490 · 📦 7 · 📋 570 - 28% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/jupyter/nbviewer
  ```
* [Docker Hub](https://hub.docker.com/r/jupyter/nbviewer) (📥 2.8M · ⭐ 29 · ⏱️ 22.08.2022):
  ```
  docker pull jupyter/nbviewer
  ```

</details>
<details><summary><b><a href="https://github.com/nteract/bookstore">bookstore</a></b> (🥉19 ·  ⭐ 180 · 💀) - 面向大众的笔记本存储和发布工作流程。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/nteract/bookstore) ⚠️ Archived (👨‍💻 7 · 🔀 19 · 📦 11 · 📋 73 - 46% open · ⏱️ 09.12.2019):

  ```
  git clone https://github.com/nteract/bookstore
  ```
* [PyPi](https://pypi.org/project/bookstore) (📥 29K / month):
  ```
  pip install bookstore
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/binderhub">BinderHub</a></b> (🥉18 ·  ⭐ 2.2K) - 在云端运行您的代码。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/binderhub) ⭐ 2,670 | 🐛 269 | 🌐 Python | 📅 2026-08-05 (👨‍💻 84 · 🔀 320 · 📦 6 · 📋 630 - 28% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/jupyterhub/binderhub
  ```

</details>
<details><summary><b><a href="https://github.com/aaren/notedown">notedown</a></b> (🥉18 ·  ⭐ 830 · 💀) - Markdown = IPython Notebook. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/aaren/notedown) ⭐ 860 | 🐛 46 | 🌐 Jupyter Notebook | 📅 2021-10-18 (👨‍💻 7 · 🔀 91 · 📦 180 · 📋 68 - 57% open · ⏱️ 16.11.2017):

  ```
  git clone https://github.com/aaren/notedown
  ```
* [PyPi](https://pypi.org/project/notedown) (📥 3.8K / month):
  ```
  pip install notedown
  ```
* [Conda](https://anaconda.org/conda-forge/notedown) (📥 34K · ⏱️ 07.06.2018):
  ```
  conda install -c conda-forge notedown
  ```

</details>
<details><summary><b><a href="https://github.com/nteract/scrapbook">scrapbook</a></b> (🥉18 ·  ⭐ 250) - 一个用于在笔记本中记录和读取数据的库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/nteract/scrapbook) ⚠️ Archived (👨‍💻 11 · 🔀 26 · 📦 150 · 📋 48 - 47% open · ⏱️ 13.04.2022):

  ```
  git clone https://github.com/nteract/scrapbook
  ```
* [PyPi](https://pypi.org/project/nteract-scrapbook) (📥 81K / month):
  ```
  pip install nteract-scrapbook
  ```

</details>
<details><summary><b><a href="https://github.com/executablebooks/thebe">ThebeLab</a></b> (🥉17 ·  ⭐ 300 · 💤) - ThebeLab：将静态HTML页面转换为实时文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/executablebooks/thebe) ⭐ 442 | 🐛 116 | 🌐 Jupyter Notebook | 📅 2026-06-23 (👨‍💻 26 · 🔀 57 · 📦 5 · 📋 150 - 42% open · ⏱️ 19.11.2021):

  ```
  git clone https://github.com/executablebooks/thebe
  ```

</details>
<details><summary><b><a href="https://github.com/nteract/commuter">commuter</a></b> (🥉16 ·  ⭐ 440) - 笔记本共享中心。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/nteract/commuter) ⭐ 504 | 🐛 7 | 🌐 JavaScript | 📅 2026-05-14 (👨‍💻 27 · 🔀 63 · 📦 3 · 📋 91 - 57% open · ⏱️ 28.04.2022):

  ```
  git clone https://github.com/nteract/commuter
  ```
* [NPM](https://www.npmjs.com/package/@nteract/commuter) (📥 640 / month):
  ```
  npm install @nteract/commuter
  ```

</details>
<details><summary><b><a href="https://github.com/SamLau95/nbinteract">nbinteract</a></b> (🥉15 ·  ⭐ 220 · 💀) - 从Jupyter Notebooks创建交互式网页。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/SamLau95/nbinteract) ⚠️ Archived (👨‍💻 8 · 🔀 20 · 📦 1 · 📋 70 - 41% open · ⏱️ 15.04.2021):

  ```
  git clone https://github.com/SamLau95/nbinteract
  ```
* [PyPi](https://pypi.org/project/nbinteract) (📥 1.5K / month):
  ```
  pip install nbinteract
  ```

</details>
<details><summary><b><a href="https://github.com/danielfrg/mkdocs-jupyter">mkdocs-jupyter</a></b> (🥉15 ·  ⭐ 150 · 📈) - 在mkdocs中使用Jupyter Notebook。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/danielfrg/mkdocs-jupyter) ⭐ 505 | 🐛 48 | 🌐 Jupyter Notebook | 📅 2026-04-17 (👨‍💻 13 · 🔀 21 · 📋 57 - 22% open · ⏱️ 04.05.2022):

  ```
  git clone https://github.com/danielfrg/mkdocs-jupyter
  ```
* [PyPi](https://pypi.org/project/mkdocs-jupyter) (📥 24K / month):
  ```
  pip install mkdocs-jupyter
  ```

</details>
<details><summary><b><a href="https://github.com/ideonate/cdsdashboards">cdsdashboards</a></b> (🥉14 ·  ⭐ 170) - 用于ContainDS仪表板的JupyterHub扩展。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/ideonate/cdsdashboards) ⚠️ Archived (👨‍💻 13 · 🔀 33 · 📋 88 - 35% open · ⏱️ 29.04.2022):

  ```
  git clone https://github.com/ideonate/cdsdashboards
  ```
* [PyPi](https://pypi.org/project/cdsdashboards) (📥 260 / month):
  ```
  pip install cdsdashboards
  ```
* [Conda](https://anaconda.org/conda-forge/cdsdashboards) (📥 30K · ⏱️ 29.04.2022):
  ```
  conda install -c conda-forge cdsdashboards
  ```

</details>
<details><summary><b><a href="https://github.com/elehcimd/pynb">pynb</a></b> (🥉13 ·  ⭐ 240 · 💀) - Jupyter Notebooks是带有嵌入式Markdown文本的纯Python代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/elehcimd/pynb) ⭐ 249 | 🐛 0 | 🌐 Python | 📅 2020-07-07 (👨‍💻 8 · 🔀 6 · 📦 21 · ⏱️ 07.07.2020):

  ```
  git clone https://github.com/elehcimd/pynb
  ```

</details>
<details><summary><b><a href="https://github.com/nbgallery/nbgallery">nbgallery</a></b> (🥉13 ·  ⭐ 140) - 企业Jupyter笔记本共享和协作应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/nbgallery/nbgallery) ⭐ 150 | 🐛 44 | 🌐 JavaScript | 📅 2026-07-13 (👨‍💻 19 · 🔀 23 · 📋 380 - 18% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/nbgallery/nbgallery
  ```
* [Docker Hub](https://hub.docker.com/r/nbgallery/nbgallery) (📥 160K · ⭐ 3 · ⏱️ 19.08.2022):
  ```
  docker pull nbgallery/nbgallery
  ```

</details>
<details><summary><b><a href="https://github.com/danielfrg/jupyter-flex">jupyter-flex</a></b> (🥉11 ·  ⭐ 260) - 使用Jupyter Notebook构建仪表板。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/danielfrg/jupyter-flex) ⚠️ Archived (👨‍💻 4 · 🔀 46 · 📦 1 · 📋 56 - 21% open · ⏱️ 22.06.2022):

  ```
  git clone https://github.com/danielfrg/jupyter-flex
  ```

</details>
<details><summary><b><a href="https://github.com/line/jnotebook_reader">jnotebook-reader</a></b> (🥉11 ·  ⭐ 99) - 一款很棒的查看器，用于浏览和渲染Jupyter。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/line/jnotebook_reader) ⭐ 104 | 🐛 1 | 🌐 JavaScript | 📅 2022-12-06 (👨‍💻 6 · 🔀 15 · ⏱️ 01.07.2022):

  ```
  git clone https://github.com/line/jnotebook_reader
  ```

</details>
<br>

## Jupyter-Notebook工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*与笔记本文件一起工作或可以在笔记本文件中使用的库和工具。*

<details><summary><b><a href="https://github.com/jupyter/nbclient">nbclient</a></b> (🥇26 ·  ⭐ 100) - 用于执行笔记本的客户端库。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter/nbclient) ⭐ 186 | 🐛 59 | 🌐 Python | 📅 2026-06-05 (👨‍💻 33 · 🔀 45 · 📥 88 · 📦 67K · 📋 91 - 31% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/jupyter/nbclient
  ```
* [PyPi](https://pypi.org/project/nbclient) (📥 9.5M / month):
  ```
  pip install nbclient
  ```
* [Conda](https://anaconda.org/conda-forge/nbclient) (📥 5.1M · ⏱️ 23.08.2022):
  ```
  conda install -c conda-forge nbclient
  ```

</details>
<details><summary><b><a href="https://github.com/pixiedust/pixiedust">PixieDust</a></b> (🥇25 ·  ⭐ 1K · 💀) - 适用于Jupyter Notebook的Python Helper库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/pixiedust/pixiedust) ⭐ 1,041 | 🐛 164 | 🌐 Jupyter Notebook | 📅 2021-02-16 (👨‍💻 33 · 🔀 160 · 📦 240 · 📋 420 - 38% open · ⏱️ 16.02.2021):

  ```
  git clone https://github.com/pixiedust/pixiedust
  ```
* [PyPi](https://pypi.org/project/pixiedust) (📥 11K / month):
  ```
  pip install pixiedust
  ```
* [Conda](https://anaconda.org/conda-forge/pixiedust) (📥 39K · ⏱️ 06.02.2021):
  ```
  conda install -c conda-forge pixiedust
  ```

</details>
<details><summary><b><a href="https://github.com/fastai/nbdev">nbdev</a></b> (🥇24 ·  ⭐ 3.6K) - 使用Jupyter Notebook创建python项目。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/fastai/nbdev) ⭐ 5,301 | 🐛 184 | 🌐 Jupyter Notebook | 📅 2026-08-12 (👨‍💻 20 · 🔀 360 · 📋 560 - 5% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/fastai/nbdev
  ```
* [PyPi](https://pypi.org/project/nbdev) (📥 96K / month):
  ```
  pip install nbdev
  ```

</details>
<details><summary><b><a href="https://github.com/computationalmodelling/nbval">nbval</a></b> (🥈23 ·  ⭐ 390 · 💤) - 一个py.test插件，用于验证Jupyter笔记本。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/computationalmodelling/nbval) ⭐ 453 | 🐛 55 | 🌐 Python | 📅 2025-09-17 (👨‍💻 29 · 🔀 42 · 📦 1.6K · 📋 98 - 36% open · ⏱️ 05.01.2022):

  ```
  git clone https://github.com/computationalmodelling/nbval
  ```
* [PyPi](https://pypi.org/project/nbval) (📥 110K / month):
  ```
  pip install nbval
  ```
* [Conda](https://anaconda.org/conda-forge/nbval) (📥 230K · ⏱️ 31.07.2020):
  ```
  conda install -c conda-forge nbval
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_client">Jupyter Client</a></b> (🥈23 ·  ⭐ 280 · 📈) - Jupyter protocol client APIs. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter/jupyter_client) ⭐ 471 | 🐛 209 | 🌐 Python | 📅 2026-06-12 (👨‍💻 120 · 🔀 230 · 📥 320 · 📋 320 - 43% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/jupyter/jupyter_client
  ```
* [PyPi](https://pypi.org/project/jupyter-client) (📥 12M / month):
  ```
  pip install jupyter-client
  ```

</details>
<details><summary><b><a href="https://github.com/twosigma/beakerx">BeakerX</a></b> (🥈22 ·  ⭐ 2.7K · 💀) - Jupyter Notebook的Beaker扩展。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/twosigma/beakerx) ⭐ 2,894 | 🐛 355 | 🌐 Jupyter Notebook | 📅 2023-12-04 (👨‍💻 43 · 🔀 370 · 📥 31 · 📋 4.5K - 7% open · ⏱️ 21.01.2021):

  ```
  git clone https://github.com/twosigma/beakerx
  ```
* [PyPi](https://pypi.org/project/beakerx) (📥 4.8K / month):
  ```
  pip install beakerx
  ```
* [Conda](https://anaconda.org/conda-forge/beakerx) (📥 530K · ⏱️ 18.11.2021):
  ```
  conda install -c conda-forge beakerx
  ```
* [NPM](https://www.npmjs.com/package/beakerx) (📥 610 / month):
  ```
  npm install beakerx
  ```
* [Docker Hub](https://hub.docker.com/r/beakerx/beakerx) (📥 250K · ⭐ 23 · ⏱️ 02.12.2018):
  ```
  docker pull beakerx/beakerx
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-sphinx">Jupyter Sphinx</a></b> (🥈22 ·  ⭐ 150) - Sphinx扩展，用于呈现Jupyter交互式小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter/jupyter-sphinx) ⭐ 194 | 🐛 51 | 🌐 Python | 📅 2026-08-03 (👨‍💻 25 · 🔀 50 · 📋 120 - 33% open · ⏱️ 25.06.2022):

  ```
  git clone https://github.com/jupyter/jupyter-sphinx
  ```
* [PyPi](https://pypi.org/project/jupyter_sphinx) (📥 130K / month):
  ```
  pip install jupyter_sphinx
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/repo2docker">repo2docker</a></b> (🥈21 ·  ⭐ 1.4K) - 将存储库转换为支持Jupyter的Docker映像。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/repo2docker) ⭐ 1,730 | 🐛 198 | 🌐 Python | 📅 2026-08-03 (👨‍💻 110 · 🔀 300 · 📦 160 · 📋 470 - 31% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/jupyterhub/repo2docker
  ```
* [PyPi](https://pypi.org/project/jupyter-repo2docker) (📥 5K / month):
  ```
  pip install jupyter-repo2docker
  ```

</details>
<details><summary><b><a href="https://github.com/chmp/ipytest">ipytest</a></b> (🥈20 ·  ⭐ 230 · 📈) - IPython笔记本中的Pytest。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/chmp/ipytest) ⭐ 336 | 🐛 4 | 🌐 Python | 📅 2025-02-16 (👨‍💻 4 · 🔀 19 · 📦 200 · 📋 50 - 4% open · ⏱️ 20.02.2022):

  ```
  git clone https://github.com/chmp/ipytest
  ```
* [PyPi](https://pypi.org/project/ipytest) (📥 41K / month):
  ```
  pip install ipytest
  ```

</details>
<details><summary><b><a href="https://github.com/ReviewNB/treon">treon</a></b> (🥈19 ·  ⭐ 280) - Jupyter Notebooks易于使用的测试框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/ReviewNB/treon) ⭐ 313 | 🐛 5 | 🌐 Python | 📅 2022-08-04 (👨‍💻 5 · 🔀 21 · 📦 55 · 📋 13 - 23% open · ⏱️ 04.08.2022):

  ```
  git clone https://github.com/ReviewNB/treon
  ```
* [PyPi](https://pypi.org/project/treon) (📥 9.4K / month):
  ```
  pip install treon
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter/nbformat">nbformat</a></b> (🥈19 ·  ⭐ 180 · 📉) - Jupyter Notebook格式的参考实现。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter/nbformat) ⭐ 311 | 🐛 86 | 🌐 Python | 📅 2026-08-10 (👨‍💻 67 · 🔀 130 · 📋 120 - 39% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/jupyter/nbformat
  ```
* [PyPi](https://pypi.org/project/nbformat) (📥 9.9M / month):
  ```
  pip install nbformat
  ```
* [Conda](https://anaconda.org/conda-forge/nbformat) (📥 9.8M · ⏱️ 03.05.2022):
  ```
  conda install -c conda-forge nbformat
  ```

</details>
<details><summary><b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥉18 ·  ⭐ 2.3K) - Python中的交互式并行计算。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/ipython/ipyparallel) ⭐ 2,648 | 🐛 74 | 🌐 Jupyter Notebook | 📅 2026-08-12 (👨‍💻 110 · 🔀 870 · 📋 330 - 15% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/ipython/ipyparallel
  ```
* [PyPi](https://pypi.org/project/ipyparallel) (📥 110K / month):
  ```
  pip install ipyparallel
  ```
* [Conda](https://anaconda.org/conda-forge/ipyparallel) (📥 660K · ⏱️ 21.06.2022):
  ```
  conda install -c conda-forge ipyparallel
  ```

</details>
<details><summary><b><a href="https://github.com/nbQA-dev/nbQA">nbQA</a></b> (🥉17 ·  ⭐ 560) - 在Jupyter Notebook上运行任何标准的Python代码质量工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/nbQA-dev/nbQA) ⭐ 1,203 | 🐛 22 | 🌐 Python | 📅 2026-08-10 (👨‍💻 20 · 🔀 31 · 📋 250 - 0% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/nbQA-dev/nbQA
  ```
* [PyPi](https://pypi.org/project/nbqa) (📥 37K / month):
  ```
  pip install nbqa
  ```

</details>
<details><summary><b><a href="https://github.com/QuantEcon/sphinxcontrib-jupyter">sphinxcontrib.jupyter</a></b> (🥉17 ·  ⭐ 72 · 💀) - 用于生成Jupyter笔记本的Sphinx扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/QuantEcon/sphinxcontrib-jupyter) ⚠️ Archived (👨‍💻 13 · 🔀 23 · 📦 26 · 📋 180 - 48% open · ⏱️ 18.06.2020):

  ```
  git clone https://github.com/QuantEcon/sphinxcontrib-jupyter
  ```
* [PyPi](https://pypi.org/project/sphinxcontrib-jupyter) (📥 740 / month):
  ```
  pip install sphinxcontrib-jupyter
  ```

</details>
<details><summary><b><a href="https://github.com/tweag/jupyterWith">JupyterWith</a></b> (🥉14 ·  ⭐ 350) - 声明性和可复制的Jupyter环境-由Nix提供支持。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/tweag/jupyterWith) ⭐ 744 | 🐛 56 | 🌐 Nix | 📅 2026-08-09 (👨‍💻 31 · 🔀 79 · 📋 110 - 9% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/tweag/jupyterWith
  ```

</details>
<details><summary><b><a href="https://github.com/nteract/testbook">testbook</a></b> (🥉14 ·  ⭐ 320) - 以正确的方式对Jupyter笔记本进行单元测试。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/nteract/testbook) ⭐ 435 | 🐛 46 | 🌐 Python | 📅 2024-08-25 (👨‍💻 14 · 🔀 30 · 📦 140 · 📋 87 - 47% open · ⏱️ 12.08.2022):

  ```
  git clone https://github.com/nteract/testbook
  ```

</details>
<details><summary><b><a href="https://github.com/treebeardtech/nbmake-action">nbmake-action</a></b> (🥉14 ·  ⭐ 160 · 💤) - GitHub用于测试笔记本的动作。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/treebeardtech/nbmake-action) ⚠️ Archived (👨‍💻 2 · 🔀 6 · 📦 27 · ⏱️ 21.09.2021):

  ```
  git clone https://github.com/treebeardtech/nbmake-action
  ```

</details>
<details><summary><b><a href="https://github.com/takluyver/nbopen">nbopen</a></b> (🥉13 ·  ⭐ 280 · 💀) - Open a Jupyter notebook in the best available server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/takluyver/nbopen) ⭐ 308 | 🐛 40 | 🌐 Python | 📅 2023-09-08 (👨‍💻 10 · 🔀 53 · 📋 63 - 58% open · ⏱️ 25.04.2018):

  ```
  git clone https://github.com/takluyver/nbopen
  ```
* [PyPi](https://pypi.org/project/nbopen) (📥 760 / month):
  ```
  pip install nbopen
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-naas/naas">naas</a></b> (🥉13 ·  ⭐ 200) - Notebook调度工具，像API一样运行它们。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

* [GitHub](https://github.com/jupyter-naas/naas) (👨‍💻 18 · 🔀 20 · 📦 3 · 📋 140 - 18% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/jupyter-naas/naas
  ```
* [PyPi](https://pypi.org/project/naas) (📥 2.7K / month):
  ```
  pip install naas
  ```

</details>
<details><summary><b><a href="https://github.com/takluyver/jupyter_kernel_mgmt">Kernel Management</a></b> (🥉12 ·  ⭐ 13 · 💀) - 针对Jupyter的实验性新内核管理框架。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/takluyver/jupyter_kernel_mgmt) ⭐ 15 | 🐛 11 | 🌐 Python | 📅 2020-08-27 (👨‍💻 74 · 🔀 7 · 📥 17 · 📋 25 - 44% open · ⏱️ 29.01.2020):

  ```
  git clone https://github.com/takluyver/jupyter_kernel_mgmt
  ```
* [PyPi](https://pypi.org/project/jupyter-kernel-mgmt) (📥 38 / month):
  ```
  pip install jupyter-kernel-mgmt
  ```

</details>
<details><summary><b><a href="https://github.com/datitran/jupyter2slides">jupyter2slides</a></b> (🥉11 ·  ⭐ 770 · 💀) - 使用Jupyter Notebook的Cloud Native演示幻灯片<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/datitran/jupyter2slides) ⭐ 792 | 🐛 12 | 🌐 HTML | 📅 2019-09-03 (🔀 170 · 📋 15 - 73% open · ⏱️ 28.12.2018):

  ```
  git clone https://github.com/datitran/jupyter2slides
  ```

</details>
<details><summary><b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉11 ·  ⭐ 150 · 💤) - 适用于GPU和一般设备的jupyter / ipython实验容器。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/stas00/ipyexperiments) ⭐ 236 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-12-15 (👨‍💻 3 · 🔀 11 · 📦 6 · ⏱️ 07.12.2021):

  ```
  git clone https://github.com/stas00/ipyexperiments
  ```
* [PyPi](https://pypi.org/project/ipyexperiments) (📥 110 / month):
  ```
  pip install ipyexperiments
  ```

</details>
<details><summary><b><a href="https://github.com/krassowski/jupyter-helpers">Jupyter Helpers</a></b> (🥉11 ·  ⭐ 40 · 💀) - Jupyter/IPython的帮助程序集合。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/krassowski/jupyter-helpers) ⭐ 48 | 🐛 3 | 🌐 Python | 📅 2021-07-31 (👨‍💻 2 · 🔀 3 · 📋 5 - 60% open · ⏱️ 31.07.2021):

  ```
  git clone https://github.com/krassowski/jupyter-helpers
  ```
* [PyPi](https://pypi.org/project/jupyter_helpers) (📥 110 / month):
  ```
  pip install jupyter_helpers
  ```

</details>
<details><summary><b><a href="https://github.com/Invictify/Jupter-Notebook-REST-API">Jupter-Notebook-REST-API</a></b> (🥉7 ·  ⭐ 51 · 💀) - 将jupyter笔记本作为REST API端点运行。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/Invictify/Jupter-Notebook-REST-API) ⭐ 164 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2022-12-08 (👨‍💻 2 · 🔀 4 · ⏱️ 31.03.2020):

  ```
  git clone https://github.com/Invictify/Jupter-Notebook-REST-API
  ```

</details>
<br>

## JupyterLab渲染器

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*可以呈现和显示特定MIME类型文件的扩展名。*

<details><summary><b><a href="https://github.com/plotly/jupyterlab-dash">JupyterLab Dash</a></b> (🥇20 ·  ⭐ 360 · 💀) - An Extension for the Interactive development of Dash apps in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/plotly/jupyterlab-dash) ⚠️ Archived (👨‍💻 7 · 🔀 57 · 📦 260 · 📋 28 - 71% open · ⏱️ 19.05.2020):

  ```
  git clone https://github.com/plotly/jupyterlab-dash
  ```
* [PyPi](https://pypi.org/project/jupyterlab-dash) (📥 1.3K / month):
  ```
  pip install jupyterlab-dash
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-dash) (📥 12K / month):
  ```
  npm install jupyterlab-dash
  ```

</details>
<details><summary><b><a href="https://github.com/QuantStack/jupyterlab-drawio">JupyterLab Drawio</a></b> (🥈19 ·  ⭐ 540 · 💀) - FOSS drawio/mxgraph程序包的独立嵌入。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/QuantStack/jupyterlab-drawio) ⭐ 622 | 🐛 54 | 🌐 JavaScript | 📅 2024-07-25 (👨‍💻 15 · 🔀 63 · 📦 530 · 📋 65 - 61% open · ⏱️ 29.06.2021):

  ```
  git clone https://github.com/QuantStack/jupyterlab-drawio
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-drawio) (📥 4.3K / month):
  ```
  npm install jupyterlab-drawio
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-latex">JupyterLab Latex</a></b> (🥈18 ·  ⭐ 530) - JupyterLab扩展，用于实时编辑LaTeX文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyterlab-latex) ⭐ 686 | 🐛 32 | 🌐 TypeScript | 📅 2025-12-17 (👨‍💻 22 · 🔀 59 · 📦 2 · 📋 82 - 32% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-latex
  ```
* [PyPi](https://pypi.org/project/jupyterlab_latex) (📥 3.9K / month):
  ```
  pip install jupyterlab_latex
  ```
* [NPM](https://www.npmjs.com/package/@jupyterlab/latex) (📥 1.2K / month):
  ```
  npm install @jupyterlab/latex
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyter-renderers">JupyterLab Renderers</a></b> (🥉17 ·  ⭐ 440) - JupyterLab的渲染器和渲染器扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyter-renderers) ⭐ 518 | 🐛 46 | 🌐 HTML | 📅 2026-03-04 (👨‍💻 25 · 🔀 67 · 📦 1 · 📋 100 - 29% open · ⏱️ 08.07.2022):

  ```
  git clone https://github.com/jupyterlab/jupyter-renderers
  ```
* [NPM](https://www.npmjs.com/package/@jupyterlab/geojson-extension) (📥 1.4K / month):
  ```
  npm install @jupyterlab/geojson-extension
  ```

</details>
<details><summary><b><a href="https://github.com/plotly/jupyterlab-chart-editor">JupyterLab Chart Editor</a></b> (🥉16 ·  ⭐ 210 · 💀) - JupyterLab扩展，用于实时编辑LaTeX文档。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/plotly/jupyterlab-chart-editor) (👨‍💻 5 · 🔀 22 · 📦 3 · 📋 31 - 38% open · ⏱️ 10.03.2021):

  ```
  git clone https://github.com/plotly/jupyterlab-chart-editor
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-chart-editor) (📥 1.1K / month):
  ```
  npm install jupyterlab-chart-editor
  ```

</details>
<details><summary><b><a href="https://github.com/quigleyj97/jupyterlab-spreadsheet">JupyterLab Spreadsheet</a></b> (🥉16 ·  ⭐ 160) - JupyterLab插件，用于查看电子表格。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/quigleyj97/jupyterlab-spreadsheet) ⭐ 201 | 🐛 11 | 🌐 TypeScript | 📅 2023-05-06 (👨‍💻 4 · 🔀 14 · 📦 3 · 📋 23 - 21% open · ⏱️ 18.07.2022):

  ```
  git clone https://github.com/quigleyj97/jupyterlab-spreadsheet
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-spreadsheet) (📥 4K / month):
  ```
  npm install jupyterlab-spreadsheet
  ```

</details>
<details><summary><b><a href="https://github.com/altair-viz/jupyterlab_voyager">JupyterLab Voyager</a></b> (🥉13 ·  ⭐ 270 · 💀) - JupyterLab extension visualize data with Voyager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/altair-viz/jupyterlab_voyager) ⭐ 303 | 🐛 63 | 🌐 TypeScript | 📅 2022-12-06 (👨‍💻 6 · 🔀 32 · 📋 60 - 66% open · ⏱️ 14.08.2019):

  ```
  git clone https://github.com/altair-viz/jupyterlab_voyager
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab_voyager) (📥 68 / month):
  ```
  npm install jupyterlab_voyager
  ```

</details>
<br>

## JupyterLab主题

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*可以自定义JupyterLab外观的扩展。*

<details><summary><b><a href="https://github.com/telamonian/theme-darcula">Darcula Theme</a></b> (🥇19 ·  ⭐ 150) - A handsome Darcula theme for Jupyterlab. The first jlab theme to.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/telamonian/theme-darcula) ⭐ 219 | 🐛 22 | 🌐 CSS | 📅 2023-06-06 (👨‍💻 7 · 🔀 22 · 📦 500 · 📋 23 - 30% open · ⏱️ 20.07.2022):

  ```
  git clone https://github.com/telamonian/theme-darcula
  ```
* [NPM](https://www.npmjs.com/package/@telamonian/theme-darcula) (📥 1.4K / month):
  ```
  npm install @telamonian/theme-darcula
  ```

</details>
<details><summary><b><a href="https://github.com/AllanChain/jupyterlab-theme-solarized-dark">jupyterlab-theme-solarized-dark</a></b> (🥈14 ·  ⭐ 66) - JupyterLab 2.x Solarized Dark扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/AllanChain/jupyterlab-theme-solarized-dark) ⭐ 114 | 🐛 2 | 🌐 SCSS | 📅 2026-04-15 (👨‍💻 2 · 🔀 9 · 📋 3 - 33% open · ⏱️ 21.07.2022):

  ```
  git clone https://github.com/AllanChain/jupyterlab-theme-solarized-dark
  ```
* [PyPi](https://pypi.org/project/jupyterlab_theme_solarized_dark) (📥 6.3K / month):
  ```
  pip install jupyterlab_theme_solarized_dark
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-theme-solarized-dark) (📥 3.8K / month):
  ```
  npm install jupyterlab-theme-solarized-dark
  ```

</details>
<details><summary><b><a href="https://github.com/yeebc/jupyterlab-neon-theme">Neon Theme</a></b> (🥈13 ·  ⭐ 120 · 💀) - JupyterLab的扁平，80年代霓虹灯启发主题。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/yeebc/jupyterlab-neon-theme) ⭐ 162 | 🐛 8 | 🌐 CSS | 📅 2023-03-14 (👨‍💻 3 · 🔀 9 · 📦 1 · 📋 12 - 16% open · ⏱️ 07.03.2021):

  ```
  git clone https://github.com/yeebc/jupyterlab-neon-theme
  ```
* [NPM](https://www.npmjs.com/package/@yeebc/jupyterlab_neon_theme) (📥 1.1K / month):
  ```
  npm install @yeebc/jupyterlab_neon_theme
  ```

</details>
<details><summary><b><a href="https://github.com/oriolmirosa/jupyterlab_materialdarker">Material Darker Theme</a></b> (🥉12 ·  ⭐ 130 · 💤) - JupyterLab的Material Darker主题。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/oriolmirosa/jupyterlab_materialdarker) ⭐ 170 | 🐛 6 | 🌐 CSS | 📅 2026-01-04 (👨‍💻 2 · 🔀 15 · 📦 4 · 📋 17 - 17% open · ⏱️ 31.08.2021):

  ```
  git clone https://github.com/oriolmirosa/jupyterlab_materialdarker
  ```
* [NPM](https://www.npmjs.com/package/@oriolmirosa/jupyterlab_materialdarker) (📥 670 / month):
  ```
  npm install @oriolmirosa/jupyterlab_materialdarker
  ```

</details>
<details><summary><b><a href="https://github.com/mohirio/jupyterlab-horizon-theme">Horizon Theme</a></b> (🥉12 ·  ⭐ 52 · 💀) - JupyterLab的VSCode Horizo​​n主题端口。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/mohirio/jupyterlab-horizon-theme) ⭐ 97 | 🐛 5 | 🌐 CSS | 📅 2024-04-11 (🔀 3 · 📋 5 - 20% open · ⏱️ 11.04.2021):

  ```
  git clone https://github.com/mohirio/jupyterlab-horizon-theme
  ```
* [NPM](https://www.npmjs.com/package/@mohirio/jupyterlab-horizon-theme) (📥 2.7K / month):
  ```
  npm install @mohirio/jupyterlab-horizon-theme
  ```

</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-theme-toggle">Theme Toggle</a></b> (🥉10 ·  ⭐ 11 · 💀) - JupyterLab extension to toggle the theme in the Top Bar area. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jtpio/jupyterlab-theme-toggle) ⚠️ Archived (👨‍💻 2 · 🔀 3 · 📦 2 · 📋 3 - 66% open · ⏱️ 16.06.2021):

  ```
  git clone https://github.com/jtpio/jupyterlab-theme-toggle
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-theme-toggle) (📥 1.5K / month):
  ```
  npm install jupyterlab-theme-toggle
  ```

</details>
<details><summary><b><a href="https://github.com/Rahlir/theme-gruvbox">Gruvbox Theme</a></b> (🥉9 ·  ⭐ 48 · 💀) - Jupyter Lab的Gruvbox黑暗主题。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/Rahlir/theme-gruvbox) ⭐ 51 | 🐛 0 | 🌐 CSS | 📅 2020-04-12 (👨‍💻 3 · 🔀 10 · ⏱️ 12.04.2020):

  ```
  git clone https://github.com/Rahlir/theme-gruvbox
  ```
* [NPM](https://www.npmjs.com/package/@rahlir/theme-gruvbox) (📥 160 / month):
  ```
  npm install @rahlir/theme-gruvbox
  ```

</details>
<details><summary><b><a href="https://github.com/kenshohara/theme-nord-extension">Nord Theme</a></b> (🥉6 ·  ⭐ 24 · 💀) - JupyterLab-Nord主题。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/kenshohara/theme-nord-extension) ⭐ 27 | 🐛 1 | 🌐 CSS | 📅 2020-09-20 (🔀 1 · 📋 5 - 20% open · ⏱️ 20.09.2020):

  ```
  git clone https://github.com/kenshohara/theme-nord-extension
  ```
* [NPM](https://www.npmjs.com/package/@kenshohara/theme-nord-extension) (📥 61 / month):
  ```
  npm install @kenshohara/theme-nord-extension
  ```

</details>
<br>

## JupyterLab扩展

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*扩展JupyterLab自身功能的应用程序插件。*

<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-git">JupyterLab Git</a></b> (🥇27 ·  ⭐ 1.1K) - JupyterLab的Git扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyterlab-git) ⭐ 1,608 | 🐛 141 | 🌐 TypeScript | 📅 2026-08-10 (👨‍💻 76 · 🔀 230 · 📦 15 · 📋 530 - 15% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-git
  ```
* [PyPi](https://pypi.org/project/jupyterlab-git) (📥 150K / month):
  ```
  pip install jupyterlab-git
  ```
* [Conda](https://anaconda.org/conda-forge/jupyterlab-git) (📥 240K · ⏱️ 19.08.2022):
  ```
  conda install -c conda-forge jupyterlab-git
  ```

</details>
<details><summary><b><a href="https://github.com/elyra-ai/elyra">elyra</a></b> (🥇22 ·  ⭐ 1.4K) - Elyra以AI为中心的方法对JupyterLab笔记本进行拓展。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/elyra-ai/elyra) ⭐ 1,996 | 🐛 273 | 🌐 Python | 📅 2026-08-11 (👨‍💻 54 · 🔀 260 · 📦 32 · 📋 1.5K - 14% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/elyra-ai/elyra
  ```
* [PyPi](https://pypi.org/project/elyra) (📥 3.6K / month):
  ```
  pip install elyra
  ```
* [Conda](https://anaconda.org/conda-forge/elyra) (📥 17K · ⏱️ 24.08.2022):
  ```
  conda install -c conda-forge elyra
  ```

</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥇21 ·  ⭐ 4.8K) - 通过WebAssembly进行流式透视显示。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/finos/perspective) ⭐ 11,101 | 🐛 80 | 🌐 Rust | 📅 2026-08-10 (👨‍💻 72 · 🔀 490 · 📦 4 · 📋 540 - 14% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/finos/perspective
  ```
* [PyPi](https://pypi.org/project/perspective-python) (📥 3K / month):
  ```
  pip install perspective-python
  ```
* [NPM](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 1.4K / month):
  ```
  npm install @finos/perspective-jupyterlab
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/debugger">JupyterLab Debugger</a></b> (🥇20 ·  ⭐ 540 · 💀) - 适用于Jupyter笔记本电脑，控制台等的可视调试器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/debugger) ⚠️ Archived (👨‍💻 11 · 🔀 37 · 📋 260 - 6% open · ⏱️ 31.03.2021):

  ```
  git clone https://github.com/jupyterlab/debugger
  ```
* [NPM](https://www.npmjs.com/package/@jupyterlab/debugger) (📥 170K / month):
  ```
  npm install @jupyterlab/debugger
  ```

</details>
<details><summary><b><a href="https://github.com/lckr/jupyterlab-variableInspector">Variable Inspector</a></b> (🥇19 ·  ⭐ 930) - Jupyterlab的变量查看器扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/lckr/jupyterlab-variableInspector) ⭐ 1,168 | 🐛 68 | 🌐 TypeScript | 📅 2026-04-17 (👨‍💻 18 · 🔀 84 · 📦 3 · 📋 160 - 27% open · ⏱️ 01.08.2022):

  ```
  git clone https://github.com/lckr/jupyterlab-variableInspector
  ```
* [NPM](https://www.npmjs.com/package/@lckr/jupyterlab_variableinspector) (📥 5.7K / month):
  ```
  npm install @lckr/jupyterlab_variableinspector
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-toc">JupyterLab TOC</a></b> (🥇19 ·  ⭐ 720 · 💤) - Table of Contents extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyterlab-toc) ⚠️ Archived (👨‍💻 14 · 🔀 100 · 📋 120 - 55% open · ⏱️ 10.08.2021):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-toc
  ```
* [NPM](https://www.npmjs.com/package/@jupyterlab/toc) (📥 180K / month):
  ```
  npm install @jupyterlab/toc
  ```

</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-system-monitor">JupyterLab System Monitor</a></b> (🥇19 ·  ⭐ 250) - JupyterLab扩展以显示系统指标。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jtpio/jupyterlab-system-monitor) ⚠️ Archived (👨‍💻 7 · 🔀 29 · 📦 48 · 📋 42 - 52% open · ⏱️ 15.02.2022):

  ```
  git clone https://github.com/jtpio/jupyterlab-system-monitor
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-system-monitor) (📥 3.7K / month):
  ```
  npm install jupyterlab-system-monitor
  ```

</details>
<details><summary><b><a href="https://github.com/ryantam626/jupyterlab_code_formatter">Code Formatter</a></b> (🥈18 ·  ⭐ 600) - JupyterLab的通用代码格式化工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/ryantam626/jupyterlab_code_formatter) ⭐ 906 | 🐛 27 | 🌐 Python | 📅 2026-08-07 (👨‍💻 37 · 🔀 49 · 📋 160 - 13% open · ⏱️ 11.08.2022):

  ```
  git clone https://github.com/ryantam626/jupyterlab_code_formatter
  ```
* [PyPi](https://pypi.org/project/jupyterlab_code_formatter) (📥 34K / month):
  ```
  pip install jupyterlab_code_formatter
  ```
* [NPM](https://www.npmjs.com/package/@ryantam626/jupyterlab_code_formatter) (📥 4.6K / month):
  ```
  npm install @ryantam626/jupyterlab_code_formatter
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-github">JupyterLab GitHub</a></b> (🥈18 ·  ⭐ 330 · 💤) - GitHub integration for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyterlab-github) ⭐ 437 | 🐛 33 | 🌐 TypeScript | 📅 2024-03-25 (👨‍💻 15 · 🔀 88 · 📦 2 · 📋 57 - 36% open · ⏱️ 10.12.2021):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-github
  ```
* [PyPi](https://pypi.org/project/jupyterlab-github) (📥 1.1K / month):
  ```
  pip install jupyterlab-github
  ```
* [NPM](https://www.npmjs.com/package/@jupyterlab/github) (📥 1.6K / month):
  ```
  npm install @jupyterlab/github
  ```

</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyterlab_templates">JupyterLab Templates</a></b> (🥈18 ·  ⭐ 310) - 在jupyterlab的jupyter-Notebook各种模板。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/jpmorganchase/jupyterlab_templates) ⭐ 413 | 🐛 9 | 🌐 JavaScript | 📅 2026-08-09 (👨‍💻 14 · 🔀 50 · 📦 4 · 📋 78 - 8% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/jpmorganchase/jupyterlab_templates
  ```
* [PyPi](https://pypi.org/project/jupyterlab_templates) (📥 7.2K / month):
  ```
  pip install jupyterlab_templates
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab_templates) (📥 2.9K / month):
  ```
  npm install jupyterlab_templates
  ```

</details>
<details><summary><b><a href="https://github.com/dask/dask-labextension">dask-labextension</a></b> (🥈18 ·  ⭐ 270) - JupyterLab扩展，用于实时编辑LaTeX文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/dask/dask-labextension) ⭐ 329 | 🐛 46 | 🌐 TypeScript | 📅 2025-06-02 (👨‍💻 19 · 🔀 51 · 📋 130 - 28% open · ⏱️ 21.06.2022):

  ```
  git clone https://github.com/dask/dask-labextension
  ```
* [PyPi](https://pypi.org/project/dask-labextension) (📥 13K / month):
  ```
  pip install dask-labextension
  ```
* [Conda](https://anaconda.org/conda-forge/dask-labextension) (📥 620K · ⏱️ 22.06.2022):
  ```
  conda install -c conda-forge dask-labextension
  ```
* [NPM](https://www.npmjs.com/package/dask-labextension) (📥 1.8K / month):
  ```
  npm install dask-labextension
  ```

</details>
<details><summary><b><a href="https://github.com/jwkvam/jupyterlab-vim">JupyterLab Vim</a></b> (🥈17 ·  ⭐ 920 · 💀) - 用于JupyterLab的Vim笔记本cell绑定。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jwkvam/jupyterlab-vim) ⭐ 981 | 🐛 70 | 🌐 TypeScript | 📅 2023-04-05 (👨‍💻 8 · 🔀 73 · 📦 3 · 📋 97 - 56% open · ⏱️ 16.07.2019):

  ```
  git clone https://github.com/jwkvam/jupyterlab-vim
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab_vim) (📥 280 / month):
  ```
  npm install jupyterlab_vim
  ```

</details>
<details><summary><b><a href="https://github.com/rapidsai/jupyterlab-nvdashboard">GPU Dashboards</a></b> (🥈17 ·  ⭐ 470) - 一个JupyterLab扩展，用于显示GPU的仪表板。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/rapidsai/jupyterlab-nvdashboard) ⭐ 680 | 🐛 33 | 🌐 TypeScript | 📅 2026-08-11 (👨‍💻 17 · 🔀 59 · 📋 54 - 42% open · ⏱️ 23.06.2022):

  ```
  git clone https://github.com/rapidsai/jupyterlab-nvdashboard
  ```
* [PyPi](https://pypi.org/project/jupyterlab-nvdashboard) (📥 1.6K / month):
  ```
  pip install jupyterlab-nvdashboard
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-nvdashboard) (📥 1.1K / month):
  ```
  npm install jupyterlab-nvdashboard
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-google-drive">JupyterLab Google Drive</a></b> (🥈17 ·  ⭐ 370) - 使用Google云端硬盘的JupyterLab的云存储。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyterlab-google-drive) ⚠️ Archived (👨‍💻 16 · 🔀 72 · 📦 2 · 📋 98 - 33% open · ⏱️ 28.04.2022):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-google-drive
  ```
* [NPM](https://www.npmjs.com/package/@jupyterlab/google-drive) (📥 1.1K / month):
  ```
  npm install @jupyterlab/google-drive
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/jupyterlab-sidecar">JupyterLab SideCar</a></b> (🥈17 ·  ⭐ 200 · 💀) - JupyterLab的sidecar输出小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter-widgets/jupyterlab-sidecar) ⭐ 263 | 🐛 31 | 🌐 TypeScript | 📅 2026-04-15 (👨‍💻 13 · 🔀 36 · 📦 3 · 📋 32 - 68% open · ⏱️ 04.07.2021):

  ```
  git clone https://github.com/jupyter-widgets/jupyterlab-sidecar
  ```
* [PyPi](https://pypi.org/project/sidecar) (📥 4.5K / month):
  ```
  pip install sidecar
  ```
* [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-sidecar) (📥 550 / month):
  ```
  npm install @jupyter-widgets/jupyterlab-sidecar
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/spellchecker">JupyterLab Spellchecker</a></b> (🥈17 ·  ⭐ 160) - JupyterLab笔记本降价单元的拼写检查器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab-contrib/spellchecker) ⭐ 213 | 🐛 28 | 🌐 TypeScript | 📅 2026-08-11 (👨‍💻 6 · 🔀 18 · 📦 1 · 📋 49 - 32% open · ⏱️ 22.02.2022):

  ```
  git clone https://github.com/ijmbarr/jupyterlab_spellchecker
  ```
* [NPM](https://www.npmjs.com/package/@ijmbarr/jupyterlab_spellchecker) (📥 1.7K / month):
  ```
  npm install @ijmbarr/jupyterlab_spellchecker
  ```

</details>
<details><summary><b><a href="https://github.com/krassowski/jupyterlab-go-to-definition">JupyterLab Go-To-Definition</a></b> (🥈16 ·  ⭐ 220 · 💀) - 变量的定义查看器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/krassowski/jupyterlab-go-to-definition) ⭐ 226 | 🐛 11 | 🌐 TypeScript | 📅 2021-08-23 (👨‍💻 2 · 🔀 8 · 📦 11 · 📋 23 - 43% open · ⏱️ 28.07.2021):

  ```
  git clone https://github.com/krassowski/jupyterlab-go-to-definition
  ```
* [NPM](https://www.npmjs.com/package/@krassowski/jupyterlab_go_to_definition) (📥 2.5K / month):
  ```
  npm install @krassowski/jupyterlab_go_to_definition
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-data-explorer">JupyterLab Data Explorer</a></b> (🥈16 ·  ⭐ 170 · 💀) - JupyterLab中的一流数据集。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyterlab-data-explorer) ⚠️ Archived (👨‍💻 9 · 🔀 34 · 📦 10 · 📋 91 - 62% open · ⏱️ 24.05.2020):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-data-explorer
  ```
* [NPM](https://www.npmjs.com/package/@jupyterlab/dataregistry-extension) (📥 180 / month):
  ```
  npm install @jupyterlab/dataregistry-extension
  ```

</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_iframe">JupyterLab IFrame</a></b> (🥈16 ·  ⭐ 81) - JupyterLab iframe小部件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/timkpaine/jupyterlab_iframe) ⭐ 118 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-11 (👨‍💻 5 · 🔀 15 · 📦 3 · 📋 66 - 6% open · ⏱️ 21.07.2022):

  ```
  git clone https://github.com/timkpaine/jupyterlab_iframe
  ```
* [PyPi](https://pypi.org/project/jupyterlab_iframe) (📥 960 / month):
  ```
  pip install jupyterlab_iframe
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab_iframe) (📥 920 / month):
  ```
  npm install jupyterlab_iframe
  ```

</details>
<details><summary><b><a href="https://github.com/timkpaine/lantern">Lantern</a></b> (🥈15 ·  ⭐ 320) - 数据探索工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/timkpaine/lantern) ⭐ 350 | 🐛 2 | 🌐 Python | 📅 2026-07-20 (👨‍💻 3 · 🔀 20 · 📦 17 · 📋 200 - 5% open · ⏱️ 13.06.2022):

  ```
  git clone https://github.com/timkpaine/lantern
  ```
* [PyPi](https://pypi.org/project/pylantern) (📥 56 / month):
  ```
  pip install pylantern
  ```

</details>
<details><summary><b><a href="https://github.com/chaoleili/jupyterlab_tensorboard">JupyterLab Tensorboard</a></b> (🥈15 ·  ⭐ 300) - Jupyterlab的Tensorboard扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/chaoleili/jupyterlab_tensorboard) ⭐ 312 | 🐛 25 | 🌐 TypeScript | 📅 2022-07-21 (👨‍💻 7 · 🔀 32 · 📦 2 · 📋 27 - 62% open · ⏱️ 18.07.2022):

  ```
  git clone https://github.com/chaoleili/jupyterlab_tensorboard
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab_tensorboard) (📥 6.2K / month):
  ```
  npm install jupyterlab_tensorboard
  ```

</details>
<details><summary><b><a href="https://github.com/deshaw/jupyterlab-execute-time">jupyterlab-execute-time</a></b> (🥈15 ·  ⭐ 230) - 为Jupyter Lab执行时间插件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/deshaw/jupyterlab-execute-time) ⭐ 403 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2026-06-01 (👨‍💻 11 · 🔀 32 · 📋 34 - 11% open · ⏱️ 12.08.2022):

  ```
  git clone https://github.com/deshaw/jupyterlab-execute-time
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-execute-time) (📥 2.7K / month):
  ```
  npm install jupyterlab-execute-time
  ```

</details>
<details><summary><b><a href="https://github.com/bokeh/jupyter_bokeh">Jupyter Bokeh</a></b> (🥈15 ·  ⭐ 200) - 用于在JupyterLab笔记本中呈现Bokeh内容的扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/bokeh/jupyter_bokeh) ⭐ 261 | 🐛 34 | 🌐 TypeScript | 📅 2026-08-10 (👨‍💻 17 · 🔀 41 · 📋 89 - 12% open · ⏱️ 12.08.2022):

  ```
  git clone https://github.com/bokeh/jupyter_bokeh
  ```
* [PyPi](https://pypi.org/project/jupyter-bokeh) (📥 45K / month):
  ```
  pip install jupyter-bokeh
  ```
* [NPM](https://www.npmjs.com/package/@bokeh/jupyter_bokeh) (📥 7.2K / month):
  ```
  npm install @bokeh/jupyter_bokeh
  ```

</details>
<details><summary><b><a href="https://github.com/jtpio/ipylab">ipylab</a></b> (🥈15 ·  ⭐ 110) - 使用Jupyter小部件从Python笔记本控制JupyterLab。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jtpio/ipylab) ⭐ 219 | 🐛 36 | 🌐 TypeScript | 📅 2025-06-26 (👨‍💻 6 · 🔀 7 · 📥 35 · 📋 30 - 36% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/jtpio/ipylab
  ```
* [PyPi](https://pypi.org/project/ipylab) (📥 4.3K / month):
  ```
  pip install ipylab
  ```
* [Conda](https://anaconda.org/conda-forge/ipylab) (📥 13K · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge ipylab
  ```

</details>
<details><summary><b><a href="https://github.com/vatlab/jupyterlab-sos">jupyterlab-sos</a></b> (🥈15 ·  ⭐ 54) - 适用于SoS Polyglot笔记本和工作流程的Jupyterlab扩展<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/vatlab/jupyterlab-sos) ⭐ 79 | 🐛 23 | 🌐 HTML | 📅 2026-02-07 (👨‍💻 4 · 🔀 3 · 📋 59 - 15% open · ⏱️ 02.08.2022):

  ```
  git clone https://github.com/vatlab/jupyterlab-sos
  ```
* [Conda](https://anaconda.org/conda-forge/jupyterlab-sos) (📥 18K · ⏱️ 03.08.2022):
  ```
  conda install -c conda-forge jupyterlab-sos
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-sos) (📥 140 / month):
  ```
  npm install jupyterlab-sos
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/gather">nbgather</a></b> (🥉14 ·  ⭐ 450 · 💀) - Jupyter笔记本分割工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/microsoft/gather) ⚠️ Archived (👨‍💻 12 · 🔀 29 · 📋 27 - 40% open · ⏱️ 14.02.2020):

  ```
  git clone https://github.com/microsoft/gather
  ```
* [NPM](https://www.npmjs.com/package/nbgather) (📥 51 / month):
  ```
  npm install nbgather
  ```

</details>
<details><summary><b><a href="https://github.com/pbugnion/jupyterlab-sql">JupyterLab SQL</a></b> (🥉14 ·  ⭐ 380 · 💀) - JupyterLab的SQL GUI。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pbugnion/jupyterlab-sql) ⭐ 429 | 🐛 57 | 🌐 TypeScript | 📅 2023-01-05 (👨‍💻 2 · 🔀 44 · 📋 74 - 50% open · ⏱️ 04.01.2020):

  ```
  git clone https://github.com/pbugnion/jupyterlab-sql
  ```
* [PyPi](https://pypi.org/project/jupyterlab_sql) (📥 450 / month):
  ```
  pip install jupyterlab_sql
  ```

</details>
<details><summary><b><a href="https://github.com/aquirdTurtle/Collapsible_Headings">Collapsible Headings</a></b> (🥉14 ·  ⭐ 170 · 💀) - 为Jupyter实验室笔记本实现可折叠页眉。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/aquirdTurtle/Collapsible_Headings) ⭐ 187 | 🐛 26 | 🌐 TypeScript | 📅 2023-01-04 (👨‍💻 6 · 🔀 7 · 📋 31 - 29% open · ⏱️ 22.05.2021):

  ```
  git clone https://github.com/aquirdTurtle/Collapsible_Headings
  ```
* [NPM](https://www.npmjs.com/package/@aquirdturtle/collapsible_headings) (📥 1.6K / month):
  ```
  npm install @aquirdturtle/collapsible_headings
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-hdf5">JupyterLab HDF5</a></b> (🥉14 ·  ⭐ 95) - 在JupyterLab中打开和浏览HDF5文件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyterlab-hdf5) ⭐ 118 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2023-10-11 (👨‍💻 6 · 🔀 19 · 📋 44 - 25% open · ⏱️ 21.02.2022):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-hdf5
  ```
* [PyPi](https://pypi.org/project/jupyterlab_hdf) (📥 1K / month):
  ```
  pip install jupyterlab_hdf
  ```
* [NPM](https://www.npmjs.com/package/@jupyterlab/hdf5) (📥 680 / month):
  ```
  npm install @jupyterlab/hdf5
  ```

</details>
<details><summary><b><a href="https://github.com/parente/jupyterlab-quickopen">JupyterLab Quickopen</a></b> (🥉14 ·  ⭐ 75 · 💤) - 通过在JupyterLab中键入文件的一部分来快速打开文件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/parente/jupyterlab-quickopen) ⭐ 89 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-11 (👨‍💻 5 · 🔀 8 · ⏱️ 12.12.2021):

  ```
  git clone https://github.com/parente/jupyterlab-quickopen
  ```
* [PyPi](https://pypi.org/project/jupyterlab-quickopen) (📥 430 / month):
  ```
  pip install jupyterlab-quickopen
  ```
* [NPM](https://www.npmjs.com/package/@parente/jupyterlab-quickopen) (📥 59 / month):
  ```
  npm install @parente/jupyterlab-quickopen
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-kernelspy">JupyterLab Kernelspy</a></b> (🥉14 ·  ⭐ 68) - Jupyter Lab扩展，用于检查往返于邮件的信息。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-kernelspy) ⭐ 85 | 🐛 7 | 🌐 TypeScript | 📅 2026-02-07 (👨‍💻 4 · 🔀 9 · 📦 3 · 📋 13 - 15% open · ⏱️ 20.07.2022):

  ```
  git clone https://github.com/jupyterlab-contrib/jupyterlab-kernelspy
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-kernelspy) (📥 190 / month):
  ```
  npm install jupyterlab-kernelspy
  ```

</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_autoversion">JupyterLab Autoversion</a></b> (🥉14 ·  ⭐ 58) - 在JupyterLab中Jupyter笔记本的自动版本控制。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/timkpaine/jupyterlab_autoversion) ⭐ 83 | 🐛 5 | 🌐 Python | 📅 2026-08-09 (👨‍💻 5 · 🔀 9 · 📋 32 - 9% open · ⏱️ 21.07.2022):

  ```
  git clone https://github.com/timkpaine/jupyterlab_autoversion
  ```
* [PyPi](https://pypi.org/project/jupyterlab_autoversion) (📥 84 / month):
  ```
  pip install jupyterlab_autoversion
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab_autoversion) (📥 69 / month):
  ```
  npm install jupyterlab_autoversion
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-shortcutui">JupyterLab Shortcutui</a></b> (🥉14 ·  ⭐ 55 · 💀) - 一个JupyterLab扩展，用于显示GPU的仪表板。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyterlab-shortcutui) ⚠️ Archived (👨‍💻 8 · 🔀 14 · 📋 13 - 53% open · ⏱️ 17.01.2020):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-shortcutui
  ```
* [NPM](https://www.npmjs.com/package/@jupyterlab/shortcutui) (📥 300 / month):
  ```
  npm install @jupyterlab/shortcutui
  ```

</details>
<details><summary><b><a href="https://github.com/itsjafer/jupyterlab-sparkmonitor">jupyterlab-sparkmonitor</a></b> (🥉13 ·  ⭐ 78) - JupyterLab扩展，可启动监控。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/itsjafer/jupyterlab-sparkmonitor) ⭐ 92 | 🐛 12 | 🌐 JavaScript | 📅 2022-12-27 (👨‍💻 10 · 🔀 20 · 📋 16 - 50% open · ⏱️ 01.04.2022):

  ```
  git clone https://github.com/itsjafer/jupyterlab-sparkmonitor
  ```
* [PyPi](https://pypi.org/project/jupyterlab-sparkmonitor) (📥 3.4K / month):
  ```
  pip install jupyterlab-sparkmonitor
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab_sparkmonitor) (📥 68 / month):
  ```
  npm install jupyterlab_sparkmonitor
  ```
* [Docker Hub](https://hub.docker.com/r/itsjafer/sparkmonitor) (📥 290 · ⏱️ 02.06.2021):
  ```
  docker pull itsjafer/sparkmonitor
  ```

</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyter-fs">jupyter-fs</a></b> (🥉12 ·  ⭐ 120) - 类似文件系统的内容管理器，用于Jupyter中的多个后端。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/jpmorganchase/jupyter-fs) ⭐ 245 | 🐛 27 | 🌐 TypeScript | 📅 2026-07-01 (👨‍💻 9 · 🔀 24 · 📋 55 - 23% open · ⏱️ 29.04.2022):

  ```
  git clone https://github.com/jpmorganchase/jupyter-fs
  ```
* [PyPi](https://pypi.org/project/jupyter-fs) (📥 300 / month):
  ```
  pip install jupyter-fs
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-commenting">JupyterLab Commenting</a></b> (🥉12 ·  ⭐ 93 · 💀) - JupyterLab的注释和注释。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyterlab-commenting) ⭐ 103 | 🐛 26 | 🌐 Jupyter Notebook | 📅 2021-02-10 (👨‍💻 10 · 🔀 22 · 📋 34 - 70% open · ⏱️ 01.05.2020):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-commenting
  ```
* [NPM](https://www.npmjs.com/package/@jupyterlab/commenting-extension) (📥 140 / month):
  ```
  npm install @jupyterlab/commenting-extension
  ```

</details>
<details><summary><b><a href="https://github.com/jpmorganchase/nbcelltests">nbcelltests</a></b> (🥉12 ·  ⭐ 64) - 用于Jupyter笔记本的逐个cell测试工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/jpmorganchase/nbcelltests) ⭐ 97 | 🐛 36 | 🌐 Python | 📅 2026-08-12 (👨‍💻 7 · 🔀 16 · 📋 110 - 27% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/jpmorganchase/nbcelltests
  ```
* [PyPi](https://pypi.org/project/nbcelltests) (📥 24 / month):
  ```
  pip install nbcelltests
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab_celltests) (📥 23 / month):
  ```
  npm install jupyterlab_celltests
  ```

</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-python-file">JupyterLab Python Files</a></b> (🥉12 ·  ⭐ 52 · 💤) - JupyterLab扩展来创建Python文件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jtpio/jupyterlab-python-file) ⚠️ Archived (👨‍💻 4 · 🔀 10 · 📥 77 · 📋 9 - 11% open · ⏱️ 27.08.2021):

  ```
  git clone https://github.com/jtpio/jupyterlab-python-file
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-python-file) (📥 660 / month):
  ```
  npm install jupyterlab-python-file
  ```

</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Flake8</a></b> (🥉12 ·  ⭐ 51) - 一个jupyterlab扩展，可以直接从中发送电子邮件笔记本。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/timkpaine/jupyterlab_email) ⭐ 61 | 🐛 2 | 🌐 Python | 📅 2026-08-11 (👨‍💻 2 · 🔀 2 · 📋 36 - 11% open · ⏱️ 21.07.2022):

  ```
  git clone https://github.com/timkpaine/jupyterlab_email
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-flake8) (📥 200 / month):
  ```
  npm install jupyterlab-flake8
  ```

</details>
<details><summary><b><a href="https://github.com/timkpaine/knowledgelab">KnowledgeLab</a></b> (🥉12 ·  ⭐ 45) - KnowledgeRepo + JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/timkpaine/knowledgelab) ⭐ 48 | 🐛 2 | 🌐 Python | 📅 2026-08-11 (👨‍💻 3 · 🔀 6 · 📦 2 · 📋 27 - 11% open · ⏱️ 13.06.2022):

  ```
  git clone https://github.com/timkpaine/knowledgelab
  ```
* [PyPi](https://pypi.org/project/knowledgelab) (📥 10 / month):
  ```
  pip install knowledgelab
  ```
* [NPM](https://www.npmjs.com/package/knowledgelab) (📥 12 / month):
  ```
  npm install knowledgelab
  ```

</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_commands">jupyterlab_commands</a></b> (🥉12 ·  ⭐ 37) - Add arbitrary python commands to the jupyterlab.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/timkpaine/jupyterlab_commands) ⭐ 63 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-09 (👨‍💻 2 · 🔀 5 · 📦 3 · 📋 24 - 8% open · ⏱️ 21.07.2022):

  ```
  git clone https://github.com/timkpaine/jupyterlab_commands
  ```

</details>
<details><summary><b><a href="https://github.com/krassowski/jupyterlab-lsp">JupyterLab LSP</a></b> (🥉12 · 📉) - JupyterLab的编码帮助（代码导航+悬停）。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/krassowski/jupyterlab-lsp) ⭐ 133 | 🐛 3 | 🌐 TypeScript | 📅 2026-04-01 (👨‍💻 43 · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/krassowski/jupyterlab-lsp
  ```
* [NPM](https://www.npmjs.com/package/@krassowski/jupyterlab-lsp) (📥 4.4K / month):
  ```
  npm install @krassowski/jupyterlab-lsp
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-celltags">jupyterlab-celltags</a></b> (🥉11 ·  ⭐ 110 · 💀) - 一个JupyterLab扩展，用于显示GPU的仪表板。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterlab/jupyterlab-celltags) ⚠️ Archived (👨‍💻 10 · 🔀 25 · 📋 18 - 61% open · ⏱️ 29.04.2020):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-celltags
  ```

</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Email</a></b> (🥉11 ·  ⭐ 51) - 一个jupyterlab扩展，可以直接从中发送电子邮件笔记本。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/timkpaine/jupyterlab_email) ⭐ 61 | 🐛 2 | 🌐 Python | 📅 2026-08-11 (👨‍💻 2 · 🔀 2 · 📋 36 - 11% open · ⏱️ 21.07.2022):

  ```
  git clone https://github.com/timkpaine/jupyterlab_email
  ```
* [PyPi](https://pypi.org/project/jupyterlab_email) (📥 61 / month):
  ```
  pip install jupyterlab_email
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab_email) (📥 21 / month):
  ```
  npm install jupyterlab_email
  ```

</details>
<details><summary><b><a href="https://github.com/mlshapiro/jupyterlab-flake8">jupyterlab-flake8</a></b> (🥉10 ·  ⭐ 110 · 💤) - Jupyterlab用于笔记本和文本文件的python连接器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/mlshapiro/jupyterlab-flake8) ⭐ 111 | 🐛 8 | 🌐 TypeScript | 📅 2021-09-16 (👨‍💻 5 · 🔀 10 · 📋 39 - 15% open · ⏱️ 16.09.2021):

  ```
  git clone https://github.com/mlshapiro/jupyterlab-flake8
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-flake8) (📥 200 / month):
  ```
  npm install jupyterlab-flake8
  ```

</details>
<details><summary><b><a href="https://github.com/ReviewNB/jupyterlab-gitplus">jupyterlab-gitplus</a></b> (🥉9 ·  ⭐ 94 · 💤) - JupyterLab扩展来创建Python文件。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

* [GitHub](https://github.com/ReviewNB/jupyterlab-gitplus) ⭐ 121 | 🐛 10 | 🌐 TypeScript | 📅 2024-06-25 (👨‍💻 2 · 🔀 7 · 📋 10 - 20% open · ⏱️ 06.08.2021):

  ```
  git clone https://github.com/ReviewNB/jupyterlab-gitplus
  ```
* [PyPi](https://pypi.org/project/jupyterlab_gitplus) (📥 150 / month):
  ```
  pip install jupyterlab_gitplus
  ```
* [NPM](https://www.npmjs.com/package/@reviewnb/jupyterlab_gitplus) (📥 95 / month):
  ```
  npm install @reviewnb/jupyterlab_gitplus
  ```

</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-python-bytecode">JupyterLab Bytecode</a></b> (🥉9 ·  ⭐ 59 · 💀) - JupyterLab扩展，以探索CPython字节码。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jtpio/jupyterlab-python-bytecode) ⭐ 62 | 🐛 22 | 🌐 TypeScript | 📅 2023-01-03 (👨‍💻 2 · 🔀 6 · 📋 5 - 40% open · ⏱️ 16.10.2020):

  ```
  git clone https://github.com/jtpio/jupyterlab-python-bytecode
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-python-bytecode) (📥 19 / month):
  ```
  npm install jupyterlab-python-bytecode
  ```

</details>
<details><summary><b><a href="https://github.com/manuzhang/jupyterlab_spark">JupyterLab Spark</a></b> (🥉9 ·  ⭐ 9 · 💤) - JupyterLab的Spark应用程序UI扩展。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/manuzhang/jupyterlab_spark) ⭐ 12 | 🐛 2 | 🌐 TypeScript | 📅 2021-09-05 (👨‍💻 2 · 🔀 2 · 📋 5 - 40% open · ⏱️ 05.09.2021):

  ```
  git clone https://github.com/manuzhang/jupyterlab_spark
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab_spark) (📥 69 / month):
  ```
  npm install jupyterlab_spark
  ```

</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-topbar">JupyterLab Top Bar</a></b> (🥉9 ·  ⭐ 3 · 💤) - JupyterLab顶部栏扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jtpio/jupyterlab-topbar) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2024-02-23 (👨‍💻 4 · 🔀 1 · ⏱️ 07.12.2021):

  ```
  git clone https://github.com/jtpio/jupyterlab-topbar
  ```
* [NPM](https://www.npmjs.com/package/jupyterlab-topbar-extension) (📥 3.9K / month):
  ```
  npm install jupyterlab-topbar-extension
  ```

</details>
<details><summary><b><a href="https://github.com/gavincyi/jupyterlab-executor">jupyterlab-executor</a></b> (🥉8 ·  ⭐ 5 · 💀) - JupyterLab扩展，以探索CPython字节码。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/gavincyi/jupyterlab-executor) ⭐ 18 | 🐛 3 | 🌐 TypeScript | 📅 2023-09-10 (👨‍💻 2 · 📥 3 · ⏱️ 24.03.2021):

  ```
  git clone https://github.com/gavincyi/jupyterlab-executor
  ```
* [PyPi](https://pypi.org/project/jupyterlab-executor) (📥 53 / month):
  ```
  pip install jupyterlab-executor
  ```
* [NPM](https://www.npmjs.com/package/@gavincyi/jupyterlab-executor) (📥 34 / month):
  ```
  npm install @gavincyi/jupyterlab-executor
  ```

</details>
<br>

## JupyterHub认证

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*管理和控制用户如何访问JupyterHub部署的身份验证模块。*

<details><summary><b><a href="https://github.com/jupyterhub/oauthenticator">OAuthenticator</a></b> (🥇22 ·  ⭐ 340) - OAuth + JupyterHub Authenticator = OAuthenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/oauthenticator) ⭐ 444 | 🐛 58 | 🌐 Python | 📅 2026-08-03 (👨‍💻 110 · 🔀 310 · 📦 290 · 📋 230 - 13% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/jupyterhub/oauthenticator
  ```
* [PyPi](https://pypi.org/project/oauthenticator) (📥 40K / month):
  ```
  pip install oauthenticator
  ```
* [Conda](https://anaconda.org/conda-forge/oauthenticator) (📥 27K · ⏱️ 09.06.2022):
  ```
  conda install -c conda-forge oauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/ldapauthenticator">LDAP Authenticator</a></b> (🥇22 ·  ⭐ 180 · 💀) - 用于Jupyter的LDAP Authenticator插件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/ldapauthenticator) ⭐ 213 | 🐛 21 | 🌐 Python | 📅 2026-08-03 (👨‍💻 31 · 🔀 150 · 📦 95 · 📋 140 - 41% open · ⏱️ 27.06.2021):

  ```
  git clone https://github.com/jupyterhub/ldapauthenticator
  ```
* [PyPi](https://pypi.org/project/jupyterhub-ldapauthenticator) (📥 6.5K / month):
  ```
  pip install jupyterhub-ldapauthenticator
  ```
* [Conda](https://anaconda.org/conda-forge/jupyterhub-ldapauthenticator) (📥 26K · ⏱️ 28.08.2020):
  ```
  conda install -c conda-forge jupyterhub-ldapauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/ltiauthenticator">LTI Authenticator</a></b> (🥈18 ·  ⭐ 55) - 用于LTI的JupyterHub身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/ltiauthenticator) ⭐ 73 | 🐛 11 | 🌐 Python | 📅 2026-08-03 (👨‍💻 15 · 🔀 42 · 📦 78 · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/jupyterhub/ltiauthenticator
  ```
* [PyPi](https://pypi.org/project/jupyterhub-ltiauthenticator) (📥 2.6K / month):
  ```
  pip install jupyterhub-ltiauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/nativeauthenticator">Native Authenticator</a></b> (🥈18 ·  ⭐ 53) - JupyterHub本地用户身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/nativeauthenticator) ⭐ 81 | 🐛 38 | 🌐 Python | 📅 2026-08-03 (👨‍💻 21 · 🔀 52 · 📦 40 · 📋 93 - 25% open · ⏱️ 03.08.2022):

  ```
  git clone https://github.com/jupyterhub/nativeauthenticator
  ```
* [PyPi](https://pypi.org/project/jupyterhub-nativeauthenticator) (📥 4.8K / month):
  ```
  pip install jupyterhub-nativeauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/firstuseauthenticator">First Use Authenticator</a></b> (🥈16 ·  ⭐ 40 · 💤) - JupyterHub Authenticator，可以让用户进行设置。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/firstuseauthenticator) ⭐ 50 | 🐛 12 | 🌐 Python | 📅 2026-08-01 (👨‍💻 12 · 🔀 21 · 📦 66 · 📋 23 - 26% open · ⏱️ 28.10.2021):

  ```
  git clone https://github.com/jupyterhub/firstuseauthenticator
  ```
* [PyPi](https://pypi.org/project/jupyterhub-firstuseauthenticator) (📥 3.8K / month):
  ```
  pip install jupyterhub-firstuseauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/dummyauthenticator">dummyauthenticator</a></b> (🥈14 ·  ⭐ 28 · 💀) - 虚拟的JupyterHub Authenticator使测试变得容易。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/dummyauthenticator) ⚠️ Archived (🔀 14 · 📦 100 · 📋 7 - 71% open · ⏱️ 12.02.2021):

  ```
  git clone https://github.com/jupyterhub/dummyauthenticator
  ```
* [PyPi](https://pypi.org/project/jupyterhub-dummyauthenticator) (📥 4.2K / month):
  ```
  pip install jupyterhub-dummyauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/mogthesprog/jwtauthenticator">JWT Authenticator</a></b> (🥉13 ·  ⭐ 41 · 💀) - JupyterHub的令牌验证器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/mogthesprog/jwtauthenticator) ⭐ 54 | 🐛 13 | 🌐 Python | 📅 2021-04-15 (👨‍💻 7 · 🔀 37 · 📦 8 · 📋 17 - 52% open · ⏱️ 13.02.2019):

  ```
  git clone https://github.com/mogthesprog/jwtauthenticator
  ```
* [PyPi](https://pypi.org/project/jupyterhub-jwtauthenticator) (📥 290 / month):
  ```
  pip install jupyterhub-jwtauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/nullauthenticator">Null Authenticator</a></b> (🥉13 ·  ⭐ 7) - Null Authenticator for JupyterHub instances that should have.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/nullauthenticator) ⚠️ Archived (👨‍💻 7 · 🔀 9 · 📦 83 · ⏱️ 17.05.2022):

  ```
  git clone https://github.com/jupyterhub/nullauthenticator
  ```
* [PyPi](https://pypi.org/project/nullauthenticator) (📥 2.2K / month):
  ```
  pip install nullauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/HewlettPackard/jupyterhub-samlauthenticator">SAML Authenticator</a></b> (🥉12 ·  ⭐ 33) - jupyterhub-samlauthenticator。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/HewlettPackard/jupyterhub-samlauthenticator) ⭐ 41 | 🐛 21 | 🌐 Python | 📅 2025-01-25 (👨‍💻 7 · 🔀 20 · 📥 13 · 📋 28 - 50% open · ⏱️ 21.03.2022):

  ```
  git clone https://github.com/HewlettPackard/jupyterhub-samlauthenticator
  ```
* [PyPi](https://pypi.org/project/jupyterhub-samlauthenticator) (📥 460 / month):
  ```
  pip install jupyterhub-samlauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/cwaldbieser/jhub_remote_user_authenticator">Remote User Auth</a></b> (🥉11 ·  ⭐ 33 · 💀) - Jupyterhub的REMOTE_USER身份验证器。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/cwaldbieser/jhub_remote_user_authenticator) ⭐ 43 | 🐛 9 | 🌐 Python | 📅 2022-03-31 (👨‍💻 5 · 🔀 25 · 📋 19 - 42% open · ⏱️ 16.04.2019):

  ```
  git clone https://github.com/cwaldbieser/jhub_remote_user_authenticator
  ```
* [PyPi](https://pypi.org/project/jhub_remote_user_authenticator) (📥 290 / month):
  ```
  pip install jhub_remote_user_authenticator
  ```

</details>
<details><summary><b><a href="https://github.com/cwaldbieser/jhub_cas_authenticator">CAS Authenticator</a></b> (🥉10 ·  ⭐ 18) - Jupyterhub的CAS验证器。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/cwaldbieser/jhub_cas_authenticator) ⭐ 23 | 🐛 3 | 🌐 Python | 📅 2023-03-17 (👨‍💻 4 · 🔀 10 · 📋 12 - 16% open · ⏱️ 28.07.2022):

  ```
  git clone https://github.com/cwaldbieser/jhub_cas_authenticator
  ```
* [PyPi](https://pypi.org/project/jhub_cas_authenticator) (📥 220 / month):
  ```
  pip install jhub_cas_authenticator
  ```

</details>
<details><summary><b><a href="https://github.com/thedataincubator/jupyterhub-hashauthenticator">Hash Authenticator</a></b> (🥉9 ·  ⭐ 4 · 💀) - 使用从其生成的密码对用户进行身份验证。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/thedataincubator/jupyterhub-hashauthenticator) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-07-27 (👨‍💻 3 · 🔀 3 · ⏱️ 09.03.2021):

  ```
  git clone https://github.com/thedataincubator/jupyterhub-hashauthenticator
  ```
* [PyPi](https://pypi.org/project/jupyterhub-hashauthenticator) (📥 36 / month):
  ```
  pip install jupyterhub-hashauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/ucphhpc/jhub-authenticators">Remote Authenticator</a></b> (🥉9 ·  ⭐ 1) - JupyterHub Authenticators的集合。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/ucphhpc/jhub-authenticators) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-03-18 (👨‍💻 5 · 🔀 1 · 📦 1 · ⏱️ 15.04.2022):

  ```
  git clone https://github.com/rasmunk/jhub-authenticators
  ```
* [PyPi](https://pypi.org/project/jhub-authenticators) (📥 78 / month):
  ```
  pip install jhub-authenticators
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/kerberosauthenticator">Keberos Authenticator</a></b> (🥉8 ·  ⭐ 10 · 💀) - 用于LTI的JupyterHub身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/kerberosauthenticator) ⭐ 12 | 🐛 2 | 🌐 Python | 📅 2026-08-01 (👨‍💻 2 · 🔀 5 · 📋 5 - 60% open · ⏱️ 16.07.2019):

  ```
  git clone https://github.com/jupyterhub/kerberosauthenticator
  ```
* [PyPi](https://pypi.org/project/jupyterhub-kerberosauthenticator) (📥 74 / month):
  ```
  pip install jupyterhub-kerberosauthenticator
  ```

</details>
<details><summary><b><a href="https://github.com/andreas-h/sshauthenticator">SSH Authenticator</a></b> (🥉6 ·  ⭐ 6 · 💀) - JupyterHub的简单SSH身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/andreas-h/sshauthenticator) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2019-09-03 (🔀 1 · ⏱️ 03.09.2019):

  ```
  git clone https://github.com/andreas-h/sshauthenticator
  ```

</details>
<br>

## JupyterHub容器等

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*启动、监视和停止单用户笔记本服务器的派生模块。*

<details><summary><b><a href="https://github.com/jupyterhub/dockerspawner">DockerSpawner</a></b> (🥇21 ·  ⭐ 430) - 在Docker容器中生成JupyterHub单用户服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/dockerspawner) ⭐ 543 | 🐛 34 | 🌐 Python | 📅 2026-08-03 (👨‍💻 64 · 🔀 270 · 📦 130 · 📋 260 - 6% open · ⏱️ 05.07.2022):

  ```
  git clone https://github.com/jupyterhub/dockerspawner
  ```
* [PyPi](https://pypi.org/project/dockerspawner) (📥 8.6K / month):
  ```
  pip install dockerspawner
  ```
* [Conda](https://anaconda.org/conda-forge/dockerspawner) (📥 13K · ⏱️ 17.08.2021):
  ```
  conda install -c conda-forge dockerspawner
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/kubespawner">KubeSpawner</a></b> (🥈20 ·  ⭐ 420) - Kubernetes spawner for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/kubespawner) ⭐ 607 | 🐛 107 | 🌐 Python | 📅 2026-08-10 (👨‍💻 73 · 🔀 250 · 📦 110 · 📋 290 - 17% open · ⏱️ 13.08.2022):

  ```
  git clone https://github.com/jupyterhub/kubespawner
  ```
* [PyPi](https://pypi.org/project/jupyterhub-kubespawner) (📥 33K / month):
  ```
  pip install jupyterhub-kubespawner
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/batchspawner">BatchSpawner</a></b> (🥈20 ·  ⭐ 140) - 用于Jupyterhub的自定义Spawner，可按计划批量启动服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/batchspawner) ⭐ 207 | 🐛 73 | 🌐 Python | 📅 2026-08-03 (👨‍💻 40 · 🔀 98 · 📦 21 · 📋 120 - 40% open · ⏱️ 14.04.2022):

  ```
  git clone https://github.com/jupyterhub/batchspawner
  ```
* [PyPi](https://pypi.org/project/batchspawner) (📥 3.3K / month):
  ```
  pip install batchspawner
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/systemdspawner">SystemdSpawner</a></b> (🥉17 ·  ⭐ 79) - 使用Systemd生成JupyterHub单用户笔记本服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/systemdspawner) ⭐ 101 | 🐛 30 | 🌐 Python | 📅 2026-08-01 (👨‍💻 17 · 🔀 40 · 📦 21 · 📋 59 - 45% open · ⏱️ 22.04.2022):

  ```
  git clone https://github.com/jupyterhub/systemdspawner
  ```
* [PyPi](https://pypi.org/project/jupyterhub-systemdspawner) (📥 1.5K / month):
  ```
  pip install jupyterhub-systemdspawner
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/wrapspawner">WrapSpawner</a></b> (🥉14 ·  ⭐ 54) - JupyterHub的生成器的运行时配置机制。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/wrapspawner) ⭐ 65 | 🐛 23 | 🌐 Python | 📅 2024-04-09 (👨‍💻 16 · 🔀 49 · 📦 7 · 📋 31 - 54% open · ⏱️ 04.03.2022):

  ```
  git clone https://github.com/jupyterhub/wrapspawner
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/sudospawner">SudoSpawner</a></b> (🥉14 ·  ⭐ 44 · 💤) - 使用Systemd生成JupyterHub单用户笔记本服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/sudospawner) ⭐ 52 | 🐛 9 | 🌐 Python | 📅 2026-08-05 (👨‍💻 14 · 🔀 36 · 📦 40 · 📋 37 - 45% open · ⏱️ 10.09.2021):

  ```
  git clone https://github.com/jupyterhub/sudospawner
  ```
* [PyPi](https://pypi.org/project/sudospawner) (📥 820 / month):
  ```
  pip install sudospawner
  ```

</details>
<details><summary><b><a href="https://github.com/uktrade/fargatespawner">FargateSpawner</a></b> (🥉11 ·  ⭐ 36 · 💀) - 在Docker容器中生成JupyterHub单用户服务器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/uktrade/fargatespawner) (👨‍💻 3 · 🔀 20 · 📦 1 · 📋 11 - 54% open · ⏱️ 28.06.2020):

  ```
  git clone https://github.com/uktrade/fargatespawner
  ```
* [PyPi](https://pypi.org/project/fargatespawner) (📥 240 / month):
  ```
  pip install fargatespawner
  ```

</details>
<details><summary><b><a href="https://github.com/jupyterhub/yarnspawner">YarnSpawner</a></b> (🥉10 ·  ⭐ 19 · 💀) - 在Hadoop/YARN中生成JupyterHub单用户笔记本服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyterhub/yarnspawner) ⚠️ Archived (👨‍💻 2 · 🔀 9 · 📋 9 - 55% open · ⏱️ 16.07.2019):

  ```
  git clone https://github.com/jupyterhub/yarnspawner
  ```
* [PyPi](https://pypi.org/project/jupyterhub-yarnspawner) (📥 70 / month):
  ```
  pip install jupyterhub-yarnspawner
  ```
* [Conda](https://anaconda.org/conda-forge/jupyterhub-yarnspawner) (📥 29K · ⏱️ 17.11.2021):
  ```
  conda install -c conda-forge jupyterhub-yarnspawner
  ```

</details>
<br>

## Jupyter组件

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*Jupyter架构的核心组件。*

<details><summary><b><a href="https://github.com/ipython/ipython">ipython</a></b> (🥇34 ·  ⭐ 15K) - Official repository for IPython itself. Other repos in the IPython.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/ipython/ipython) ⭐ 16,774 | 🐛 1,286 | 🌐 Python | 📅 2026-08-07 (👨‍💻 890 · 🔀 4.2K · 📥 320K · 📦 300K · 📋 7K - 20% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/ipython/ipython
  ```
* [PyPi](https://pypi.org/project/ipython) (📥 17M / month):
  ```
  pip install ipython
  ```
* [Conda](https://anaconda.org/conda-forge/ipython) (📥 13M · ⏱️ 28.05.2022):
  ```
  conda install -c conda-forge ipython
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter_server">jupyter_server</a></b> (🥉21 ·  ⭐ 330) - The backendi.e. core services, APIs, and REST.. <code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter-server/jupyter_server) ⭐ 567 | 🐛 236 | 🌐 Python | 📅 2026-08-11 (👨‍💻 480 · 🔀 180 · 📥 420 · 📋 290 - 35% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/jupyter-server/jupyter_server
  ```
* [PyPi](https://pypi.org/project/jupyter_server) (📥 1.7M / month):
  ```
  pip install jupyter_server
  ```
* [Conda](https://anaconda.org/conda-forge/jupyter_server) (📥 2M · ⏱️ 06.07.2022):
  ```
  conda install -c conda-forge jupyter_server
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-packaging">jupyter-packaging</a></b> (🥉19 ·  ⭐ 58) - 帮助构建和安装Jupyter Python软件包的工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter/jupyter-packaging) ⭐ 65 | 🐛 16 | 🌐 Python | 📅 2026-08-03 (👨‍💻 29 · 🔀 44 · 📥 28 · 📋 39 - 28% open · ⏱️ 09.08.2022):

  ```
  git clone https://github.com/jupyter/jupyter-packaging
  ```
* [PyPi](https://pypi.org/project/jupyter-packaging) (📥 330K / month):
  ```
  pip install jupyter-packaging
  ```
* [Conda](https://anaconda.org/conda-forge/jupyter-packaging) (📥 300K · ⏱️ 14.07.2022):
  ```
  conda install -c conda-forge jupyter-packaging
  ```

</details>
<br>

## Others

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/holoviz/panel">panel</a></b> (🥇31 ·  ⭐ 2.1K) - 适用于Python的高级应用程序和仪表板解决方案。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/holoviz/panel) ⭐ 5,730 | 🐛 1,111 | 🌐 Python | 📅 2026-08-12 (👨‍💻 100 · 🔀 270 · 📦 4K · 📋 1.9K - 28% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/holoviz/panel
  ```
* [PyPi](https://pypi.org/project/panel) (📥 410K / month):
  ```
  pip install panel
  ```
* [Conda](https://anaconda.org/conda-forge/panel) (📥 590K · ⏱️ 24.05.2022):
  ```
  conda install -c conda-forge panel
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter/qtconsole">qtconsole</a></b> (🥇31 ·  ⭐ 330) - Jupyter Qt Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jupyter/qtconsole) ⭐ 439 | 🐛 118 | 🌐 Python | 📅 2026-03-25 (👨‍💻 120 · 🔀 170 · 📦 110K · 📋 310 - 30% open · ⏱️ 19.06.2022):

  ```
  git clone https://github.com/jupyter/qtconsole
  ```
* [PyPi](https://pypi.org/project/qtconsole) (📥 3.1M / month):
  ```
  pip install qtconsole
  ```
* [Conda](https://anaconda.org/conda-forge/qtconsole) (📥 2.8M · ⏱️ 05.06.2022):
  ```
  conda install -c conda-forge qtconsole
  ```

</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/colabcode">colabcode</a></b> (🥉21 ·  ⭐ 1.8K · 💀) - 在Google Colab或Kaggle笔记本上运行VSCode（代码服务器）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/abhishekkrthakur/colabcode) ⭐ 2,156 | 🐛 64 | 🌐 Python | 📅 2024-09-14 (👨‍💻 8 · 🔀 240 · 📦 78 · 📋 73 - 56% open · ⏱️ 11.06.2021):

  ```
  git clone https://github.com/abhishekkrthakur/colabcode
  ```
* [PyPi](https://pypi.org/project/colabcode) (📥 16K / month):
  ```
  pip install colabcode
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_console">jupyter-console</a></b> (🥉20 ·  ⭐ 200) - Jupyter终端控制台。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jupyter/jupyter_console) ⭐ 280 | 🐛 75 | 🌐 Python | 📅 2025-10-23 (👨‍💻 59 · 🔀 130 · 📥 61 · 📋 140 - 38% open · ⏱️ 22.06.2022):

  ```
  git clone https://github.com/jupyter/jupyter_console
  ```
* [PyPi](https://pypi.org/project/jupyter-console) (📥 3.3M / month):
  ```
  pip install jupyter-console
  ```

</details>

***

## 相关资源

* [**CV项目和资源大全**](https://github.com/HanXinzi-AI/awesome-computer-vision-resources) ⭐ 359 | 🐛 144 | 📅 2024-06-03: 周更新的各种CV板块涉及的项目和工具资源汇集列表
* [**NLP项目和资源大全**](https://github.com/HanXinzi-AI/awesome-NLP-resources) ⭐ 238 | 🐛 0 | 📅 2024-06-03: 周更新的各种NLP板块涉及的项目和工具资源汇集列表
* [**python机器学习资源大全**](https://github.com/HanXinzi-AI/awesome-python-machine-learning-resources) ⭐ 224 | 🐛 110 | 📅 2024-06-06: 周更新的各种python机器学习资源汇集列表
* [**Python资源汇集列表**](https://github.com/HanXinzi-AI/awesome-python-resources) ⭐ 181 | 🐛 112 | 📅 2024-06-06: 周更新的各种应用方向与主题的资源汇集列表
* [**Jupyter及相关工具资源大全**](https://github.com/HanXinzi-AI/awesome-jupyter-resources) ⭐ 103 | 🐛 143 | 📅 2024-06-06: 周更新的各种Jupyter及相关工具资源汇集列表

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
