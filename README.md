# Ethereum Balance Checker

## Project Overview
This project provides a simple Python script to check the balance of an Ethereum address using the Etherscan API. It's designed to be easy to use and serves as an example of interacting with the Ethereum blockchain.

## Features
- Fetch and display the ETH balance of a given Ethereum address.
- Simple command-line interface for easy use.
- Utilizes the Etherscan API for accurate and up-to-date balance information.

## Prerequisites
- Python 3.x
- `requests` library
- An API key from Etherscan.io

## Installation
1. Clone this repository to your local machine.

git clone https://github.com/ykeremozcan/eth-balance-checker

2. Navigate to the project directory.

cd ethereum-balance-checker

3. Install the required Python packages.

pip install -r requirements.txt


## Configuration
Before running the script, you must obtain an API key from [Etherscan.io](https://etherscan.io/apis) and add it to the script. Replace `YOUR_ETHERSCAN_API_KEY_HERE` in the script with your actual API key.

## Usage
To run the script, use the following command:

python get_eth_balance.py

Follow the prompt to enter an Ethereum address. The balance (in ETH) will be displayed on the screen.

## Contributing
Contributions are welcome! If you have suggestions for improvements or bug fixes, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer
This project is for educational purposes only. Use at your own risk. The creator is not responsible for any loss or damage caused by the use of this script.

## Acknowledgments
- Thanks to Etherscan.io for providing the API used in this project.
