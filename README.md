# Crypto Ticker 🚀

## Overview 📄

This project is a real-time cryptocurrency price tracker that allows users to view the current
prices of various cryptocurrencies in their preferred currency. It's built with Flutter, making it a
cross-platform application that can run on both Android and iOS devices.

## Features 🌟

- **Real-Time Price Updates:** Stay updated with the latest prices of popular cryptocurrencies like
  Bitcoin (BTC), Ethereum (ETH), and Litecoin (LTC).
- **Multiple Currencies:** Supports various fiat currencies including USD, EUR, GBP, and many more,
  allowing you to view crypto prices in your preferred currency.
- **Cross-Platform:** Developed using Flutter, ensuring a seamless experience across both Android
  and iOS devices.
- **Simple & Intuitive UI:** A user-friendly interface that makes tracking cryptocurrency prices
  effortless and enjoyable.

## Getting Started 🚀

To get started with this project, follow these simple steps:

1. **Clone the repository:**

```bash
git clone https://github.com/Mohanish-25/crypto_ticker.git
```

2. **Navigate to the project directory:**

```bash
cd crypto_ticker
```

3. **Install dependencies:**

Make sure you have Flutter installed on your machine. Then, run the following command:

```bash
flutter pub get
```

4. **API Key 🔑**

This project uses the CoinAPI for fetching cryptocurrency prices. You need to sign up
at [CoinAPI](https://coinapi.io/) to get your API key and add it to your .env file:

```bash
API_KEY=your_coinapi_key_here
```

5. **Run the app:**

Connect your device or use an emulator, then execute:

```bash
flutter run
```

## Dependencies 📦

- [http](https://pub.dev/packages/http) : Used for making network requests to fetch cryptocurrency
  prices.

- [flutter_dotenv](https://pub.dev/packages/flutter_dotenv) : For loading API keys and other
  environment variables.