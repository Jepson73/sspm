# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Semantic Versioning](https://semver.org/) — MAJOR.MINOR.PATCH — where:

- MAJOR version increments indicate breaking changes,
- MINOR versions add functionality in a backward-compatible manner,
- PATCH versions are for backward-compatible bug fixes.

---

## [1.0.0] - 2025-05-23

### Added
- Initial release of SuperSecure Password Manager.
- Master password-protected vault with AES-GCM and PBKDF2 encryption.
- Password manager with full CRUD (create, read, update, delete) functionality.
- LocalStorage-based encrypted vault.
- Password generator with customizable rules.
- Password strength meter with visual feedback.
- Import/export functionality for encrypted vaults in JSON format.
- Search functionality across site, username, and notes.
- Statistics dashboard for total, strong, and weak passwords.
- Clipboard auto-clear after 15 seconds.
- Auto logout after 5 minutes of inactivity.
- Responsive design supporting mobile and desktop layouts.
- Modal interfaces for adding/editing passwords, generating passwords, and importing data.

---

# Planned Versions

## [1.1.0] - TBD

### Added
- Dark Mode toggle
- Basic tagging support for password entries
- Visual auto-save indicator

### Changed
- Improved mobile UI layout and spacing

## [1.2.0] - TBD

### Added
- Secure Notes (encrypted free-text storage)
- Vault password history and restore
- Custom timeout and clipboard clearing options

## [2.0.0] - TBD

### Breaking
- Full refactor into a modular architecture (separate JS/CSS)
- Biometric unlock support (WebAuthn)
- Optional 2FA (TOTP)

---

# Version Management Guidelines

1. Update the version in the `<title>` tag and in this changelog file.
2. Use `1.x.x` for stable feature releases.
3. Reserve `2.0.0` for breaking changes such as structural refactors or encryption scheme changes.
4. Always document new features, changes, fixes, and removals in this file.
5. Distribute new versions with updated file names (e.g., `supersecurePM-1.1.0.html`).

