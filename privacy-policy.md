An Android application for tracking product expiration dates and managing inventory.

## Features
- Product expiration tracking
- Customizable notifications
- Barcode scanning
- Multi-language support
- Offline-first design

## Privacy Policy

### Data Collection
🚫 **StoreCheck does NOT collect any personal data**  
The app operates completely offline by default. All product data is stored locally on the user's device.

### Data Storage
- Product information (names, expiry dates, quantities) is stored in a local SQLite database
- Optional encrypted backups to user's Google Drive (requires explicit user permission)

### Permissions
| Permission | Purpose |
|------------|---------|
| `RECEIVE_BOOT_COMPLETED` | Restart alarms after device reboot |
| `SCHEDULE_EXACT_ALARM` | Precise expiry notifications |
| `POST_NOTIFICATIONS` | Show expiry alerts |

### Security
- All local data is encrypted using Android's built-in SQLite encryption
- No third-party analytics or tracking
- Network access only used for optional backup features

### Contact
For privacy concerns:  
📧 **Email**: [capitan132000@gmail.com](mailto:capitan132000@gmail.com)
