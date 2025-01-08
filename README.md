                                       Python Cafe Management System
                                       
This Python-based GUI app manages cafe orders with a user-friendly interface for menu selection, order summaries, payment options, and QR code generation.
Perfect for exploring Python's GUI capabilities and utility integration.


Features:-

Menu Management: Select items, adjust quantity with +/-, and pocket-friendly prices.
Order Summary: Displays items, allows single-item deletion, and auto-updates total price.
Payment Options: Choose "Cash" or "Online". Generates UPI QR codes and sends order details via WhatsApp.
Vibrant UI: Clean design with blue-red color themes, optimized for full-screen.

Technology Stack:
Python with Tkinter.

Utilities: qrcode, pywhatkit, and PIL.

How to Run

Clone the repo:

git clone https:https://github.com/rydhmm/python_cafe

Install dependencies:
pip install pywhatkit qrcode pillow

Run the app:
python cafe_management.py

Usage
Select Items: Use the dropdown to choose items, adjust quantities with +/-.
Add to Order: Add items to the summary.
Modify Order: Delete specific items from the summary.
Payment: Select "Cash" or "Online" and scan QR codes for payment or kitchen orders.
Contributions welcome! Fork and create pull requests.

