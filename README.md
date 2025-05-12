# CryptoTrack - Real-time Cryptocurrency Tracker

A sleek, modern cryptocurrency tracking application built with React and TypeScript that provides real-time data for the top 100 cryptocurrencies.

![CryptoTrack Screenshot](https://images.pexels.com/photos/843700/pexels-photo-843700.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

## Features

- 🚀 Real-time cryptocurrency price updates
- 🌓 Dark/Light theme support
- 📱 Responsive design for all devices
- ⭐ Personal watchlist functionality
- 🔍 Advanced filtering and sorting options
- 🌎 Regional cryptocurrency categorization
- 📊 Detailed market statistics
- 📈 24-hour price change tracking
- 🔄 Auto-refresh every 60 seconds

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Vite
- CoinGecko API
- Lucide React Icons
- React Hot Toast

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Usage

### View Modes
- Toggle between grid and list views using the view switcher in the top right
- Grid view provides a card-based layout
- List view shows detailed information in a table format

### Filtering
- Search by cryptocurrency name or symbol
- Filter by region
- Toggle watchlist-only view
- Clear all filters with one click

### Sorting
- Sort by market cap rank
- Sort by current price
- Sort by 24h price change
- Sort by market cap
- Sort by volume

### Watchlist
- Click the star icon to add/remove cryptocurrencies from your watchlist
- Toggle watchlist view to see only your tracked cryptocurrencies
- Watchlist persists across sessions using local storage

## Data Updates

- Cryptocurrency data is fetched from the CoinGecko API
- Prices and market data auto-refresh every 60 seconds
- Manual refresh available via the refresh button in the header

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Data provided by [CoinGecko API](https://www.coingecko.com/en/api)
- Icons by [Lucide](https://lucide.dev/)
