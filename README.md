# String Formatter

A simple web application that formats input data into a specific command string format.

## Features

- **Input Fields**: Voucher code, password, IP address, and MAC address
- **Auto-Formatting**: Automatically generates formatted output when all fields are filled
- **One-Click Copy**: Copy the formatted output to clipboard instantly
- **MAC Address Normalization**: Automatically converts MAC addresses to lowercase
- **Responsive Design**: Works on desktop and mobile devices
- **No Dependencies**: Pure HTML, CSS, and JavaScript

## Usage

1. Open `index.html` in any web browser
2. Fill in the four input fields:
   - Voucher Code
   - Password
   - IP Address
   - MAC Address
3. The formatted output will appear automatically
4. Click "Copy to Clipboard" to copy the result

## Output Format

The app generates output in this format:
```
/ip hotspot active login user=voucher_code password=password mac-address=aa:bb:cc:dd:ee:ff ip=192.168.1.100
```

## Requirements

- Any modern web browser
- No installation or setup required

## License

This project is open source and available under the MIT License.
