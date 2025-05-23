# SuperSecure Password Manager

SuperSecure is a secure, client-side password manager that runs entirely in your browser. It allows you to store, generate, and manage your passwords with strong encryption, no server dependency, and full control over your data.

## Features

- Master Password Encryption  
  Your data is encrypted using AES-GCM with a key derived from your master password via PBKDF2.

- Local Vault Storage  
  All passwords are stored locally in your browser's localStorage. No data is ever sent over the internet.

- Password Strength Meter  
  Visual feedback on password strength during creation and editing.

- Custom Password Generator  
  Generate strong passwords with options for length, uppercase, lowercase, numbers, and symbols.

- Searchable Vault  
  Quickly find saved credentials using a built-in search function.

- Vault Import and Export  
  Export your encrypted vault to a file for backup or transfer. Import files back using the correct master password.

- Vault Statistics  
  Overview dashboard shows total, strong, and weak password counts.

- Clipboard Auto-Clear  
  Passwords copied to clipboard are automatically cleared after 15 seconds.

- Auto Logout  
  The application automatically logs out after 5 minutes of inactivity.

- Responsive Interface  
  Works across desktop and mobile browsers with a clean, adaptive design.

## Technologies Used

- HTML, CSS, JavaScript (Vanilla)
- WebCrypto API (AES-GCM, PBKDF2)
- Browser LocalStorage
- CSS Grid and Flexbox

## Getting Started

1. Open `supersecurePM.html` in a modern web browser.
2. Set a strong master password to initialize your vault.
3. Add, manage, and generate passwords as needed.
4. Export your vault regularly for backup purposes.

## Security Considerations

- Use a long, unique master password. This is the only key to your encrypted data.
- This application performs all encryption locally using the browser’s WebCrypto API.
- Avoid usage on shared or public computers to prevent unauthorized access.

## File Structure

- `supersecurePM.html` — Standalone HTML file containing the entire application.
- Vault data is stored in browser localStorage under the keys `vault_data` and `vault_salt`.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute it.

## Author

Built with a traditional focus on user sovereignty and secure local-first design principles.
