# Exchange Rate Converter : https://kajaani-balabavan.github.io/Exchange-Rate-converter/

I created this **Currency Converter** web application as a project to get familiar with the **useEffect** hook in React. This project helped me understand how to handle side effects and API calls within a React component.

---

## Installation

### Prerequisites

Ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v14 or later)
- npm package manager

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Kajaani-Balabavan/Exchange-Rate-converter.git
   cd Exchange-Rate-converter
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Application**

   ```bash
   npm run dev
   ```

4. **Open in Browser**
   Navigate to the URL shown in the terminal (e.g., `http://localhost:5173`) to view the application.

---

## Usage

1. Enter the amount to convert in the **Amount** field.
2. Select the currency you want to convert **from** using the **From Currency** dropdown.
3. Select the currency you want to convert **to** using the **To Currency** dropdown.
4. The converted amount will display automatically below the form.

---

## API Used

This application fetches real-time exchange rates from:

- [ExchangeRate API](https://api.exchangerate-api.com)

### Example Endpoint:

```
https://api.exchangerate-api.com/v4/latest/USD
```

---

## Acknowledgements

Thanks to [ExchangeRate API](https://api.exchangerate-api.com) for providing the exchange rate data.
