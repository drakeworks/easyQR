# EasyQR

A simple web-based QR code generator that creates QR codes from text input.

## Features

- Generate QR codes from any text input
- Real-time QR code generation as you type
- Dark/light theme toggle
- Smart input validation for common formats
- No server required - runs entirely in the browser
- Responsive design for mobile and desktop

## Usage

1. Open `easyQR.html` in any modern web browser
2. Enter the text you want to convert to a QR code
3. Click "Generate QR Code" or press Enter
4. The QR code will appear below the input field

## Input Validation

The app recognizes and validates:
- Email addresses and URLs
- Phone numbers and GPS coordinates
- Cryptocurrency addresses (Bitcoin, Ethereum, Tron, Solana, Cardano, Polkadot, XRP, Litecoin, Bitcoin Cash, Stellar, NEO, VeChain, Chainlink, Uniswap)
- Social media handles (Twitter, Instagram, TikTok)
- File URLs (images, videos, audio, documents)
- Programming links (GitHub, GitLab)
- App store links (App Store, Google Play)
- Payment links (PayPal, Venmo)
- Shipping tracking numbers (UPS, FedEx, USPS)
- Color codes (hex, RGB)
- Hash formats (MD5, SHA-1, SHA-256)
- Contact formats (vCard, MeCard)
- Technical standards (domains, ports, timezones, currencies, languages, versions)
- Mathematical expressions

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- Uses the qrcode-generator library for QR code creation
- Supports up to 500 characters of input text
- Generates QR codes with medium error correction level

## Requirements

- Any modern web browser with JavaScript enabled
- No additional software or dependencies required

## License

This project is open source and available under the MIT License.