# Offline Invoice & Receipt Generator

A simple, self-contained web application for creating, managing, and printing invoices and receipts. Built entirely with HTML, CSS (Tailwind), and vanilla JavaScript, this tool runs completely offline in your browser and uses `localStorage` for data persistence.

![Screenshot Placeholder - Add a screenshot/GIF of the app here!](placeholder.png)

## Features

* **100% Offline:** No internet connection needed after the initial load.
* **Single File:** The entire application is contained within a single `.html` file, making it highly portable.
* **Create Invoices/Receipts:**
    * Add your business details (name, logo, address, contact info).
    * Input client information.
    * Set the invoice date.
    * Add line items with description, quantity, and unit price.
    * Automatic calculation of item totals, subtotal, tax amount, and grand total.
    * Optional discount amount and tax percentage.
* **Printable Output:** Generates a clean, professional layout suitable for printing (`window.print()`).
* **Data Persistence:**
    * Automatically saves the current invoice details to your browser's `localStorage`.
    * Load the last saved invoice with a single click.
    * Export invoices as `.json` files for backup or sharing.
    * Import invoices from `.json` files.
* **Settings Page:**
    * Configure and save your business details (including logo upload/preview).
    * Saved settings are automatically pre-filled on new invoices.
* **User-Friendly:**
    * Dynamically add or remove item rows.
    * Live calculation updates.
    * Simple tabbed interface for navigation.

## How to Use

1.  **Download:** Download the `invoice_generator.html` file (or clone this repository).
2.  **Open:** Open the file directly in your web browser (like Chrome, Firefox, Edge, Safari).
3.  **Configure:** Navigate to the **Settings** tab, enter your business information (name, address, contact, logo), and click **Save Settings**.
4.  **Create:** Go to the **Invoice Builder** tab, fill in client details, add items, set discount/tax if needed.
5.  **Print/Save:**
    * Click **Print Invoice** to print.
    * Click **Save Current** to ensure the current state is saved in `localStorage`.
    * Click **Export as JSON** to save the invoice data as a file.
    * Use **Load Last Saved** or **Import from JSON** to retrieve previous data.

## Tech Stack

* **HTML5:** Structure and content.
* **CSS3 / Tailwind CSS:** Styling and layout (Tailwind loaded via CDN).
* **Vanilla JavaScript:** Application logic, DOM manipulation, calculations.
* **Browser `localStorage`:** Data storage for settings and current invoice state.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for bug fixes or feature enhancements.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details (You'll need to add a LICENSE.md file - the MIT license is a common choice for open-source projects).
