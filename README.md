# Dark Web Monitoring with NLP

## Overview
This project monitors dark web marketplaces and forums using Natural Language Processing (NLP) techniques. It extracts and analyzes data from .onion sites to detect illicit activities, threats, and cybersecurity risks. The tool leverages advanced keyword scanning mapped to the MITRE ATT&CK framework and generates visual insights to aid cybersecurity defense.

## Features
- Crawls and scrapes dark web .onion sites via Tor
- Extracts relevant textual data and metadata
- Applies NLP to identify cyber threat indicators and patterns
- Maps detected keywords to MITRE ATT&CK tactics and techniques
- Generates visual charts and reports for analysis
- Supports proxy and Tor integration for anonymous access

## Technologies Used
- Python 3
- Requests, BeautifulSoup (web scraping)
- SpaCy (NLP processing)
- Matplotlib (visualization)
- Tor proxy (socks5h)
- MITRE ATT&CK framework mapping

## Installation
Clone the repository:
   
   git clone https://github.com/Chali-lab/dark-web-monitoring-nlp.git
   cd dark-web-monitoring-nlp
Create and activate a Python virtual environment:

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Make sure Tor is installed and running locally on port 9050 or 9150.

Usage
Run the main script to start monitoring:

python dark_web_monitor.py
The program will:

Access specified dark web URLs via Tor

Extract and analyze text data using NLP

Map findings to MITRE ATT&CK techniques

Save charts and reports locally for review

Contribution
Contributions are welcome! Feel free to open issues or submit pull requests.
License: MIT
Copy
Edit
