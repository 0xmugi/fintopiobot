# Fintopio Bot

## Features

- Secure authentication for multiple accounts
- Automated daily check-ins
- Smart farming management (start, monitor, and claim)
- Real-time balance tracking
- Colorful and informative console output
- Intelligent waiting system with animated countdown

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v12.0.0 or higher)
- npm (usually comes with Node.js)

## Getting Started

Follow these steps to get the Fintopio Automation Tool up and running:

1. **Clone the repository**

   ```bash
   git clone https://github.com/Galkurta/Fintopio-BOT.git
   cd Fintopio-BOT
   ```

2. **Install dependencies**

   Run the following command to install all required packages:

   ```bash
   npm install
   ```

3. **Set up your accounts**

   Edit`data.txt`. Add your Fintopio account data, one per line, in the following format:

   ```
   user=
   query_id=
   ```

   Make sure to replace the values with your actual Fintopio account data.

4. **Run the program**

   Start the Fintopio Automation Tool with:

   ```bash
   node main.js
   ```

5. **Enjoy the show!**

   Sit back and watch as the tool manages your Fintopio accounts with colorful, informative output in your console.

## Understanding the Colors

The tool uses a variety of colors to make the output easy to read:

- 🟢 Green: Successful operations
- 🔵 Blue: General information
- 🟡 Yellow: Warnings or important notices
- 🔴 Red: Errors or failed operations
- 🟣 Magenta: Highlighted information
- 🟠 Cyan: Balance information

## ⚠️ Important Notes

- Keep your `data.txt` file secure and never share it with others.
- This tool is for educational purposes only. Use it responsibly and in accordance with Fintopio's terms of service.
- The tool includes built-in delays to prevent overwhelming Fintopio's servers. Please do not modify these delays.
