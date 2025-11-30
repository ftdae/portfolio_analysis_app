#### 📢 Announcement 
Good news! You can now use a patched version of the library [empyrical](https://github.com/quantopian/empyrical) through EigenLedger! 🎉
<br>
👉 Learn [how to use it here](https://eigenledger.gitbook.io/eigenledger/using-empyrical/using-empyrical) and read more in [this announcement post](https://github.com/santoshlite/EigenLedger/discussions/128).
<br>

# By Investors, For Investors.
<br>
<div align="center">
<img src="https://github.com/user-attachments/assets/470f1d59-09c6-4b95-af7e-f142764d8195"/>
<br><br><br><br>

![](https://img.shields.io/badge/Downloads-245k-brightgreen)
![](https://img.shields.io/badge/license-MIT-orange)
![](https://img.shields.io/badge/version-2.1.6-blueviolet)
![](https://img.shields.io/badge/language-python🐍-blue)
![](https://img.shields.io/badge/Open%20source-💜-white)	
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1TyNgudyFcsgob7o49PwfDJHLaHvluxaU?usp=sharing)
  
 </div>

<br>

Want to read this in **Mandarin 🇨🇳**? Click [**here**](README_CN.md)

EigenLedger (prev. "Empyrial") is a Python-based **open-source quantitative investment** library dedicated to **financial institutions** and **retail investors**, officially released in 2021. Already used by **thousands of people working in the finance industry**, EigenLedger aims to become an all-in-one platform for **portfolio management**, **analysis**, and **optimization**.

EigenLedger **empowers portfolio management** by bringing the best of **performance and risk analysis** in an **easy-to-understand**, **flexible** and **powerful framework**.

With EigenLedger, you can easily analyze security or a portfolio in order to **get the best insights from it**. This is mainly a **wrapper** of financial analysis libraries such as **Quantstats** and **PyPortfolioOpt**.

<br>

<br>



<div align="center">
  
| Table of Contents 📖 | 
| --                     
| 1. [Installation](#installation) | 
| 2. [Documentation](#documentation) | 
| 3. [Quickstart](#quickstart) |
	
</div>




## Installation

You can install EigenLedger using pip:

```
pip install EigenLedger
```

For a better experience, **we advise you to use EigenLedger on a notebook** (e.g., Jupyter, Google Colab)

_Note: macOS users will need to install [Xcode Command Line Tools](https://osxdaily.com/2014/02/12/install-command-line-tools-mac-os-x/)._

_Note: Windows users will need to install C++. ([download](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16), [install instructions](https://drive.google.com/file/d/0B4GsMXCRaSSIOWpYQkstajlYZ0tPVkNQSElmTWh1dXFaYkJr/view))_



## Documentation

Here is our full [documentation](https://eigenledger.gitbook.io/documentation)! Check it out our full documentation for detailed guides, all features, and tips on getting the most out of this library.



## Quickstart

```py
from EigenLedger import portfolio_analysis, Engine

portfolio = Engine(
    start_date = "2018-08-01", 
    portfolio = ["BABA", "PDD", "KO", "AMD","^IXIC"], 
    weights = [0.2, 0.2, 0.2, 0.2, 0.2],  # equal weighting is set by default
    benchmark = ["SPY"]  # SPY is set by default
)

portfolio_analysis(portfolio)
```



<div align="center">

![image](https://user-images.githubusercontent.com/61618641/126879140-ea03ff17-a7c6-481a-bb3e-61c055b31267.png)
![image](https://user-images.githubusercontent.com/61618641/126879203-4390813c-a4f2-41b9-916b-e03dd8bafffb.png)
![image](https://user-images.githubusercontent.com/61618641/128025087-04afed7e-96ab-4730-9bd8-98f5491b2b5d.png)
![image](https://user-images.githubusercontent.com/61618641/126879204-01fe1eca-00b8-438e-b489-0213535dd31b.png)
![image](https://user-images.githubusercontent.com/61618641/126879210-9fd61e2b-01ab-4bfd-b679-3b1867d9302d.png)
![image](https://user-images.githubusercontent.com/61618641/126879215-e24c929a-55be-4912-8e2c-043e31ff2a95.png)
![image](https://user-images.githubusercontent.com/61618641/126879221-455b8ffa-c958-4ac9-ae98-d15b4c5f0826.png)
![image](https://user-images.githubusercontent.com/61618641/126879222-08906643-16db-441e-a099-7ac3b00bdbd7.png)
![image](https://user-images.githubusercontent.com/61618641/126879223-f1116dc3-cceb-493c-93b3-2d3810cae789.png)
![image](https://user-images.githubusercontent.com/61618641/126879225-dc879b71-2070-46ed-a8ad-e90880050be8.png)
![image](https://user-images.githubusercontent.com/61618641/126879297-cb78743a-6d43-465b-8021-d4b62a659828.png)

</div>


## Stargazers over time

<div align="center">
	
![追星族的时间](https://starchart.cc/ssantoshp/empyrial.svg)
	
</div>
