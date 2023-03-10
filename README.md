
<p align="center">
  <img src="https://img.shields.io/badge/LICENSE-MIT-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/VERSION-1.0-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/PYTHON-purple?style=for-the-badge">
  
</p>
  
<h1 align="center">ＷＥＬＣＯＭＥ</h1>

<div align="center">
  <img src="https://b.top4top.io/p_2620fnslu1.png" alt="example">
</div>

<p align="center">ninja_Cy0x.1337 is a python script that automatically performs recon on a </br>given URL. It combines the outputs of other known tools into a single one.</p>

****

## :rocket: Getting Started
<p align="center"><b>To start, make sure that you're using a Debian-based distro, like <a href="https://www.kali.org/get-kali/">Kali Linux</a>, for example. Since the script uses <a href="https://www.python.org/downloads/">Python3</a> to run, it's essential to have it installed on your machine.<b></p>

  1. Cloning the project:</br>
  ```bash
  
  git clone https://github.com/Cy0x1337/ninja.git
 
  
  ```
  2. Get into the project' folder:</br>
  ```bash
  
  cd Cy0x/
  
  ```
  3. Install all dependencies
  ```bash
  
  chmod +x install.sh & sudo ./install.sh
  
  ```
  4. Run the script
  ```bash
  
  python3 Cy0x.py --url owasp.org
  
  ```
 </br>

## 	:oncoming_police_car: Features:


* Port Scanning</br>
  * <a href="https://nmap.org/">nmap</a>



 </br>

## 	:pencil: TODO's:
This script needs a lot of improvements, which I'll definitely add with time. I'll list some of them below:
- [ ] Fine-tune some parameters from:
  - [ ] NMAP
  - [ ] AMASS
- [ ] Add subdomain takeover detection with <a href="https://github.com/haccer/subjack">subjack</a>.
- [ ] Add visual recon, <a href="https://github.com/michenriksen/aquatone">aquatone</a> would be nice for that.
- [ ] Add permutation scanning using <a href="https://github.com/ProjectAnte/dnsgen">dnsgen</a>.
- [ ] Add certificate search from <a href="https://crt.sh/">crt.sh</a>. (<a href="https://github.com/eslam3kl/crtfinder">automated script</a>)
- [ ] Add GitHub recon.
