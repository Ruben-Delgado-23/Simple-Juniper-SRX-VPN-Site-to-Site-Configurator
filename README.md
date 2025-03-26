# 🛡️ Juniper SRX VPN Site-to-Site Configurator

This is a web-based tool designed to help network engineers and security professionals quickly generate configuration commands for establishing **Site-to-Site VPNs on Juniper SRX firewalls**.

## 🔧 What it does

This tool allows you to input key VPN parameters using a guided web form and instantly generates the necessary Junos configuration commands for:

- ✅ Security zones and address-book entries
- ✅ IKE policies and pre-shared secrets
- ✅ IKE gateway setup
- ✅ IPSec proposals and policies
- ✅ VPN tunnel configuration
- ✅ Tunnel interface and static routing

## 💻 Technologies Used

- Python 3
- Flask
- HTML/CSS/JavaScript
- Docker (optional)

## 🚀 How to Run (Locally)

```bash
git clone https://github.com/your-username/vpn-configurator.git
cd vpn-configurator
pip install -r requirements.txt
python app.py
```

Then visit: [http://localhost:5000](http://localhost:5000)

## 🐳 Run with Docker

```bash
docker build -t vpn-configurator .
docker run -p 5000:5000 vpn-configurator
```

## 📷 Screenshot

*Include a screenshot here showing the diagram and form UI if possible.*

## 🙌 Author

Created by **Ruben** – Network & Security Engineer
