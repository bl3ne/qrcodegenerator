# QR Code Generator in HTML


![prev](https://github.com/user-attachments/assets/8ac3e70d-277c-47d1-8218-ca9365943edc)

***

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [How to Use](#how-to-use)
- [Project Philosophy](#project-philosophy)
- [License](#license)

***

## Features

This isn't just another QR code generator. It's an exploration of brutalist design principles applied to a common web utility.

- **🎨 Brutalist Design System:**
    - Pure black-and-white aesthetic with sharp, 90-degree angles.
    - Strong, 2px borders for a raw, unapologetic look.
    - Zero shadows or gradients. Maximum contrast and readability.

- **🌓 Dark/Light Mode Toggle:**
    - A clean, satisfying toggle switch to move between light and dark themes.
    - The theme choice is automatically saved in your browser's `localStorage`.
    - The QR code itself intelligently adapts its colors to the selected theme.

- **📱 Fully Responsive UI:**
    - The user interface dynamically expands to accommodate larger QR codes, ensuring nothing ever breaks or overflows.
    - A smooth CSS transition makes the resizing feel fluid and intentional.
    - Perfect for both desktop and mobile screens.

- **⚙️ Customizable QR Codes:**
    - **3 Sizes:** Choose between Small (128px), Medium (256px), and Large (512px).
    - **4 Error Correction Levels:** Select from Low, Medium, High, or Maximum to ensure your QR code remains scannable even if partially damaged.

- **📥 Instant Download:**
    - Download your generated QR code as a high-quality `.png` file with a single click.

- **🚀 Lightweight and Fast:**
    - Built with zero frameworks or dependencies, just pure vanilla JavaScript for maximum performance.

***

## Tech Stack

- **HTML5:** For the core structure.
- **CSS3:** For all styling, using CSS Variables for easy theming and a brutalist aesthetic.
- **Vanilla JavaScript:** For all logic, including QR code generation and the dark/light mode theme switcher.
- **[qrcode.js](https://github.com/davidshimjs/qrcodejs):** A lightweight, cross-browser JavaScript library for generating QR codes.

***

## How to Use

**Live Version:**
1.  Navigate to the [**Live Demo**]([https://bl3ne.github.io/qrcodegenerator/](https://raw.githack.com/bl3ne/qrcodegenerator/main/qrcodegenerator.html)).
2.  Enter any text or URL.
3.  Select your options and click "Generate".

**Local Version:**
1.  Clone the repository:
    ```bash
    git clone https://github.com/bl3ne/qrcodegenerator.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd qrcodegenerator
    ```
3.  Open the `index.html` file in your browser. That's it!

***

## Project Philosophy

The goal was to create a simple, highly functional web tool while adhering to a strict and raw design philosophy. This project serves as a practical example of how brutalist design can be applied to create user interfaces that are both striking and incredibly usable. It's a statement against over-designed, bloated web apps.

***

## License

This project is open-source and available under the [MIT License](LICENSE).

