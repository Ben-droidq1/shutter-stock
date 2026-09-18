# Local development configuration. Provider credentials/endpoints remain blank until verified.
NODE_ENV=development
PORT=8080
DATABASE_URL=postgresql://neondb_owner:npg_q0d9hfICjLbN@ep-misty-bonus-b4sh1r9z-pooler.c-6.us-east-2.aws.neon.tech/neondb?sslmode=require&channel_binding=require
POLLAR_API_BASE_URL=https://server.api.pollar.xyz
POLLAR_SECRET_KEY=sec_testnet_e271bfea5e4acf86408e96a7e8fa6fd494d58832eda728fca64fbe8c49d8c5a4
POLLAR_AUTH_HEADER=x-pollar-api-key
POLLAR_NETWORK=testnet
POLLAR_QUOTE_URL=
POLLAR_SWAP_URL=
POLLAR_OFFRAMP_URL=
POLLAR_OFFRAMP_AUTH_HEADER=x-pollar-api-key
POLLAR_DEFAULT_COUNTRY=NG
POLLAR_DEFAULT_ASSET=USDC
POLLAR_DEFAULT_CURRENCY=USD
POLLAR_DEFAULT_FEE_BPS=75
POLLAR_WEBHOOK_SECRET=
EVM_RPC_URL=
EVM_NETWORK=ethereum
EVM_CONFIRMATIONS=12
FRONTEND_ORIGIN=http://localhost:5173
WEBHOOK_SECRET=7191f6eca77733a59bf489bb4bec150e046ec30704ccd0c7f37b2b9808f8ac73
INTERNAL_API_KEY=210bc3aa27cffb235c6a76391209768b23f6995c7573388ddafae15327c7fbdc
DEFAULT_FEE_BPS=75
SUPPORTED_ASSETS=USDC,XLM
SUPPORTED_CURRENCIES=NGN,GHS,BOB,USD,EUR,GBP
RATE_PROVIDER_URL=
RATE_PROVIDER_API_KEY=
KYC_MODE=disabled
KYC_PROVIDER_URL=
KYC_PROVIDER_API_KEY=# Shutter Stock

An image gallery website where users can search for millions of readily available images from various sources.

## Features

- 🔍 **Advanced Search** - Search for millions of images with powerful filtering options
- 📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- ⚡ **Fast Performance** - Built with modern web technologies for optimal speed
- 🎨 **Beautiful UI** - Clean and intuitive user interface
- 💾 **Easy Access** - Quick and simple image browsing and discovery

## Tech Stack

- **Frontend Framework**: React
- **Build Tool**: Vite
- **Styling**: CSS
- **Language**: JavaScript (85%), CSS (11.4%), HTML (3.6%)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ben-droidq1/shutter-stock.git
   cd shutter-stock
   ```

2. Install dependencies:
   ```bash
   cd vite-project
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal)

### Building for Production

```bash
npm run build
```

The optimized build will be in the `dist` directory.

## Project Structure

```
shutter-stock/
├── vite-project/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   ├── public/
│   ├── package.json
│   └── vite.config.js
└── README.md
```

## Usage

1. Search for images using the search bar
2. Browse through the search results
3. Click on an image to view it in detail
4. Download or save images to your collection

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Contact

For questions or suggestions, please reach out to the project maintainer.

---

Built with ❤️ using React and Vite
