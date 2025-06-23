# GNUS.ai SuperGenius Token Information

This repository contains token information for the GNUS.ai SuperGenius network, including JSON schema definitions and sample token data.

## Overview

The repository provides:

- A JSON schema (`super_genius_token_schema.json`) defining the structure for child tokens in the GNUS.ai SuperGenius network.
- Sample token data (e.g., `gnus_token_sample.json`) conforming to the schema.
- Token icon images stored in the `images/` directory.

## Token Schema

The token schema defines:

- `id`: A 256-bit identifier as a 64-character hexadecimal string.
- `name`: The token's name (1-100 characters).
- `iconUrl`: A URL to the token's image/icon (PNG, JPG, JPEG, SVG, or WEBP).

See `super_genius_token_schema.json` for the full schema.

## Sample Token

A sample token for GNUS is provided in `gnus_token_sample.json`, with:

- ID: `0000000000000000000000000000000000000000000000000000000000000000`
- Name: `GNUS`
- Icon URL: `https://raw.githubusercontent.com/GeniusVentures/tokeninfo/main/images/GNUS.png`

## Usage

1. **Validate Token Data**: Use the JSON schema to validate token JSON files.
2. **Access Images**: Token icons are stored in the `images/` directory and accessible via raw GitHub links.
3. **Contribute**: Add new token JSON files or images following the schema.

## Directory Structure

```
├── images/
│   └── GNUS.png
├── super_genius_token_schema.json
├── gnus_token_sample.json
├── README.md
└── LICENSE
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

Contributions are welcome! Please:

1. Fork the repository.
2. Create a new branch for your changes.
3. Submit a pull request with a clear description of your changes.

Ensure all token JSON files conform to the schema and images are in supported formats.

## Contact

For questions or support, open an issue on this repository or contact the Genius Ventures team.