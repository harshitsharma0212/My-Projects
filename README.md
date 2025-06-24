# My-Projects
This repository contains a PDF file explaining various Information Gathering Tools available in Kali Linux, including tools like Nmap, Whois, Dig, Maltego, Recon-ng, and more. Helpful for cybersecurity beginners and ethical hacking students.

# 🛠️ Information Gathering Tool

A simple Python-based information gathering tool that fetches the **IP address** and **location** details of any given website using public APIs.

## 📌 Objective

The main objective of this project was to create a tool that demonstrates **basic reconnaissance techniques** in the initial phase of cybersecurity. This includes:

- Resolving domain names to IP addresses
- Fetching geolocation and ISP data using a public API
- Parsing and displaying JSON data in a clean format

## 🧰 Tools and Technologies Used

- **Programming Language**: Python
- **Libraries Used**:
  - `socket`
  - `sys`
  - `request`
  - `json`
- **API Used**: [ipinfo.io](https://ipinfo.io/)
- **Operating System**: Kali Linux

## 🚀 How the Tool Works

1. User enters the website name via command line:
   ```bash
   python infotool.py <website_url>

   2.The script:

Resolves the IP address using socket.gethostbyname()

Sends the IP to the ipinfo.io API

Fetches location details in JSON

Prints the output using json.dumps() in readable format




🖥️ Installation & Usage

1. Clone this repository:

git clone https://github.com/your-username/information-gathering-tool.git


2. Navigate into the project directory:

cd information-gathering-tool


3. Run the tool:

python infotool.py example.com



✅ Sample Output

{
  "ip": "142.250.183.206",
  "city": "Mountain View",
  "region": "California",
  "country": "US",
  "loc": "37.3860,-122.0838",
  "org": "AS15169 Google LLC",
  "postal": "94035",
  "timezone": "America/Los_Angeles"
}
