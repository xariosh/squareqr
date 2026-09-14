# SquareQR

A simple Python command-line tool that generates QR codes from any URL.

## Features

- Generate a QR code image from any URL you provide
- Lightweight — built on the `qrcode` and `Pillow` libraries
- Output saved directly to the project folder

## Prerequisites

- Python 3.7+
- pip

## Installation

1. Clone the repository

   ```bash
   git clone https://github.com/xariosh/squareqr.git
   cd squareqr
   ```

2. Create and activate a virtual environment

   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
   ```

3. Install the required dependency

   ```bash
   pip install qrcode[pil]
   ```

## Usage

Run the script:

```bash
python mainqr.py
```

You'll be prompted to enter the URL you want to encode. Once submitted, the QR code will be generated and saved in the project folder as:

```
qrcode.png
```

## Example

```
$ python mainqr.py
Enter the URL: https://github.com/xariosh/squareqr
QR code generated successfully -> qrcode.png
```

## License

This project is open source and available under the [MIT License](LICENSE).
