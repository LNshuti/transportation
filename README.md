# U.S. Transportation Equities Market Technical Indicator Visualization 

This Python [application](https://huggingface.co/spaces/LeonceNsh/transportation) allows users to visualize stock data and technical indicators **(SMA, MACD, RSI, Bollinger Bands)** for selected companies. The app fetches historical stock data using Yahoo Finance, computes various technical indicators, and displays the plots interactively through a Gradio interface.

This tool provides an intuitive way for business users and analysts to quickly visualize key technical indicators without needing deep expertise in coding or data processing, making stock analysis more accessible and engaging.


**Exhibit 1. XPO Logistics -- Simple Moving Average**

![image](https://github.com/user-attachments/assets/d07415f3-59c2-4915-b59a-9b8b08ea7339)

## Customize this Application with your own Stock List

### Clone this Repository

```bash
git clone https://github.com/LNshuti/transportation.git
```

### Setup your Environment
```bash
conda env create --file=environment.yaml
```

### Activate your Environment
```bash
conda activate logistics
```

### Install Dependencies
```bash 
pip install -r requirements.txt
```

### Customize the Ticker List
You can modify the `COMPANY_TICKERS` dictionary in the Python file to add or remove companies based on your needs.

```python
COMPANY_TICKERS = {
    'Constellation Energy Corp': 'CEG',
    'Chevron Corporation': 'CVX',
    'Total Energies': 'TTE',
    'Exxon Mobil': 'XOM',
    'BP': 'BP',
    'Royal Dutch Shell': 'SHEL',
    'ConocoPhillips': 'COP',
    # Add more companies here...
}
```

### Run the **app.py** to Launch the Gradio Application
```bash
python app.py
```
