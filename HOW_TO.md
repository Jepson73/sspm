# HOW_TO Guide

**Version:** 1.0.0  
**Last updated:** 2025-05-23

This guide describes how to use SuperSecurePM version 1.0.0. For other versions, please refer to the corresponding documentation in the `releases/` folder.

# How to Use SuperSecure Password Manager

This guide will help you get started with the SuperSecure Password Manager, understand its features, and maintain a secure and organized vault of your credentials.

## 1. Setup and First Use

### Step 1: Open the Application
- Locate the `supersecurePM-x.y.z.html` file on your machine.
- Open it with any modern web browser (Chrome, Firefox, Edge, etc.).

### Step 2: Create a Vault
- On first use, you'll be prompted to enter a **master password**.
- Choose a strong, memorable password. This encrypts and secures your vault.
- Click **"Create New Vault"**.

## 2. Logging In

- Enter your master password into the input field.
- Click **"Unlock Vault"** to decrypt and access your stored passwords.

> If the password is incorrect, decryption will fail and the vault won't open.

## 3. Managing Passwords

### Adding a New Password
- Click the **"Add Password"** button.
- Enter the required details:
  - Site or Service Name
  - Username or Email
  - Password
  - Optional Notes
- Click **"Save Password"**.

### Editing a Password
- Locate the password in your list.
- Click **"Edit"**.
- Modify the details and save.

### Deleting a Password
- Click **"Delete"** under the entry.
- Confirm the deletion.

## 4. Using the Password Generator

- Click **"Generate Password"**.
- Set desired length and character types.
- Click **"Generate"**.
- Copy the result to use immediately or save it in a new vault entry.

## 5. Importing and Exporting Vaults

### Exporting
- Click **"Export Vault"**.
- A JSON file will be downloaded containing your encrypted passwords.
- Store this file safely.

### Importing
- Click **"Import Vault"**.
- Select your export file and enter the master password used for that file.
- Choose to **merge** with or **replace** your current vault.
- Click **"Import Vault"** to proceed.

## 6. Searching Passwords

- Use the search bar at the top of the vault section.
- Filter results by site name, username, or notes content.

## 7. Clipboard Safety

- Any password copied to the clipboard is automatically cleared after 15 seconds.
- You'll receive a notification once it's cleared.

## 8. Auto Logout

- If there's no activity for 5 minutes, the vault will auto-lock.
- Simply re-enter your master password to regain access.

## Best Practices

- **Use a unique, strong master password** and never share it.
- **Regularly export and back up your vault** in a secure location.
- **Avoid accessing the manager on public computers**.
- **Do not disable browser security features**; they are crucial for encryption.

## Troubleshooting

- If your vault won't open, ensure the master password is correct.
- If you lose your master password, **there is no way to recover your data**.

## Questions?

As this is a standalone HTML application, there is no customer support. Consider reading or modifying the source code if you need to make custom changes.

