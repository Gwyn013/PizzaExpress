# PizzaExpress Rider App

A cross-platform React Native mobile application for pizza delivery riders to manage and complete delivery orders.

## Overview

The app allows riders to:

- Log in securely
- View assigned delivery orders
- Check order details (customer info, address)
- Mark orders as delivered
- Access personal account information

## Features

- **User Authentication**: Secure login
- **Order Management**: Real-time order list
- **Order Details**: Detailed view per order
- **Delivery Confirmation**: Mark orders as completed
- **Personal Center**: Account and settings access
- Cross-platform (iOS & Android) with TypeScript
- Mock data mode for development
- Global state management
- Toast notifications for feedback

## Tech Stack

- **Framework**: React Native 0.58.5  
- **Language**: TypeScript, JavaScript  
- **Navigation**: React Navigation 3.3.2  
- **UI Components**: React Native Elements 1.1.0  
- **HTTP Client**: Axios 0.18.0  
- **Icons**: React Native Vector Icons 6.3.0  

## Installation

```bash
git clone <repository-url>
cd pizzaExpress-master
npm install
# or yarn install

# iOS only
cd ios
pod install
cd ..

# Run on iOS
npm run ios
# or Android
react-native run-android
# Start Metro Bundler
npm start
```

## Project Structure

<img width="400" height="400" alt="Project Structure" src="https://github.com/user-attachments/assets/c54e7a18-be05-4555-b90c-b0dcfd02708d" />

## API Endpoints

- **Login**: `POST /deliver/deliverlogin`
- **Get Orders**: `POST /expressorder/getexpresscontent`
- **Finish Order**: `POST /deliver/deliverfinishoneorder`

## Contributing

- Fork the repository
- Create a feature branch
- Commit changes
- Push to the branch
- Open a Pull Request

## License

Private and proprietary
