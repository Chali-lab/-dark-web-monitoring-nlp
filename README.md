## Installation

Clone the repository:

```bash
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

Contribution:
Contributions are welcome! Feel free to open issues or submit pull requests.

License:
This project is licensed under the MIT License.
