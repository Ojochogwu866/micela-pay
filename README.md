# Micela Pay - Frontend

## Overview
Micela Pay is a fullstack application that facilitates secure money transfers and receipts using the Chimoney API. This repository contains the frontend codebase, built with Next.js and TypeScript, providing a seamless user interface for financial transactions.

![Dashboard Preview](https://imgur.com/a/G71BeUO)

## Features
- Secure user authentication
- Send money to multiple recipients simultaneously
- Receive payments via email
- Real-time transaction history viewing
- User search functionality with email and name filters
- Live balance updates (may require refresh in some cases)
- Email-based payment verification using transaction IDs

## Technology Stack
- Next.js
- TypeScript
- React
- Axios for API calls
- Styled-components for styling

## Getting Started

### Prerequisites
- Node.js (v14 or later)
- npm or yarn

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/Ojochogwu866/micela-pay-frontend.git
   cd micela-pay-frontend
   ```
2. Install dependencies:
   ```
   npm install
   ```
3. Set up environment variables:
   Copy `.env.example` to `.env.local` and fill in the required values.

### Running the Application
1. Start the development server:
   ```
   npm run dev
   ```
2. Access the application at `http://localhost:3000`

## API Integration
This frontend interacts with the Micela Pay API. For API documentation and setup, please refer to the [backend repository](https://github.com/Ojochogwu866/Chi_api).


## Contributing
We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for more details.


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Contact
For any queries or support, please open an issue in this repository or contact the maintainers directly.
