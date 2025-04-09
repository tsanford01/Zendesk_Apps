# Organization Banner for Zendesk

A Zendesk application that displays organization-specific banners in the ticket sidebar.

## Description

This Zendesk application enhances the support experience by displaying customized banners for different organizations in the ticket sidebar. It's designed to work specifically with the Stellar Cyber Zendesk instance.

## Features

- Displays organization-specific banners in the ticket sidebar
- Supports multiple organizations
- Localization support through translations
- Clean and responsive interface
- Special handling indicators for:
  - Premium Support customers
  - Escalated accounts
  - Important accounts
  - Custom support requirements
  - Renewal alerts
  - Closed environments
  - Legacy DTonomy customers

## Installation

1. Download or clone this repository
2. Zip the contents of the `OrgBanners` directory
3. Upload the zipped file to your Zendesk instance through the Admin interface
4. Configure the app settings as needed

## Technical Details

- **Version**: 1.1.0
- **Framework Version**: 2.0
- **Supported Locations**: Ticket Sidebar
- **Domain Whitelist**: stellarcyber.zendesk.com
- **Single Install**: Yes

## Project Structure

```
OrgBanners/
├── assets/           # Contains iframe.html and icons
├── translations/     # Localization files
├── manifest.json     # App configuration
└── translations.zip  # Compiled translations
```

## Development

To modify or enhance this application:

1. Make your changes in the relevant files
2. Update the translations if adding new strings
3. Test the changes locally using the Zendesk Apps Tools (ZAT)
4. Update the version number in manifest.json if necessary

## Author

- **Name**: Stellar Cyber
- **Contact**: tsanford@stellarcyber.ai

## Last Updated

April 9, 2025

## License

Private - All rights reserved

---

For support or questions, please contact the development team at Stellar Cyber.
