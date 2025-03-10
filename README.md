# Receipt Processor Challenge

## Requirements

- Python 3.9+
- Flask
- Docker (for containerized deployment)

## Installation

1. Clone repo:

   git clone https://github.com/alvinnm/receipt-processor-challenge.git
   cd receipt-processor-challenge

2. Virtual environment setup:
   
   python3 -m venv venv
   source venv/bin/activate

3. Install dependencies:
   
   pip install -r requirements.txt

### Run With Docker

1. Build:
   
   docker build -t receipt-processor .

2. Run container:
   
   docker run -p 5000:5000 receipt-processor

3. API will be accessible at http://localhost:5000. If port is taken, try docker run -p 5001:5000 receipt-processor and access API at http://localhost:5001.
