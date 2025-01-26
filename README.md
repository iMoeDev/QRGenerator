
# QRGenerator

## Installation

### Clone the repository:
```bash
git clone <repository-url>
cd <repository-folder>
```

### Install dependencies:
```bash
npm install inquirer qr-image
```

### Run the application:
```bash
node index.js
```

## Usage

1. The program will prompt you to enter a URL.
2. Enter the desired URL when prompted.
3. The program will:
   - Generate a QR code and save it as `qr_img.png`.
   - Save the URL in `URL.txt`.

## Example

### Input:
```
Type in your URL: https://example.com
```

### Output:
- A QR code image file named `qr_img.png`.
- A text file named `URL.txt` containing the URL.

## Error Handling

- If the terminal does not support interactive prompts, you'll see:
  ```
  Prompt couldn't be rendered in the current environment.
  ```
- If any other error occurs, the program will log the error message.

## License

This project is open-source and free to use.
