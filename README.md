<h1 align="center">.💣 Torpeda Bomber for Termux 💣 </h1> 
<div align="center">
<img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg"> <img src="https://svgshare.com/i/ZhY.svg"> <img src="https://img.shields.io/github/forks/nordbearbotdev/Torpeda?style=social&label=Fork&maxAge=2592000"> <img src="https://img.shields.io/github/stars/nordbearbotdev/Torpeda?style=social&label=Star&maxAge=2592000"> <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square"> 
</div>


# 📥 Установка

 <h2>Linux</h2><img src="https://cdn.pixabay.com/photo/2017/01/31/15/33/linux-2025130_1280.png width="50" height="50">

```
sudo apt update
sudo apt install python3 python3-pip git -y
git clone https://github.com/nordbearbotdev/Torpeda
cd Torpeda
pip3 install -r requirements.txt or python -m pip install -r requirements.txt
python.py
```

<h2>Termux</h2><img src="https://brandslogos.com/wp-content/uploads/images/large/terminal-logo.png" width="50" height="50">  

```
apt update
apt upgrade
git clone https://github.com/nordbearbotdev/Torpeda
cd Torpeda
pip install -r requirements.txt
python main.py
```

## ❓ Как использовать прокси?
Основная команда чтоб использовать прокси.

```python
proxies = {
 "http": "http://10.10.10.10:8000",
 "https": "http://10.10.10.10:8000",
}
```
