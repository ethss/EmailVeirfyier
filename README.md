# 📧 Roblox Email Verification Script 📧

This script automates the process of verifying emails for Roblox accounts. It utilizes a temporary email service to receive verification emails and extracts the verification ticket to complete the process.

## 🌟 Features 🌟
- 📨 Generate a temporary email
- 📤 Send a verification request to Roblox
- 📬 Fetch the verification email
- 🔍 Extract the verification ticket
- ✅ Verify the email using the ticket

## 🛠️ Setup 🛠️
1. 📥 **Install Dependencies:**
    Make sure you have `requests`, `rich`, and `re` libraries installed. You can install them using pip:
    ```sh
    pip install requests rich
    ```

2. 📄 **Create a `cookies.txt` File:**
    In the same directory as your script, create a `cookies.txt` file containing Roblox security cookies. Each line should have one cookie in the format:
    ```plaintext
    YOUR_ROBLOSECURITY_COOKIE_1
    YOUR_ROBLOSECURITY_COOKIE_2
    ```

3. 📝 **Run the Script:**
    Execute the script to start the email verification process.
