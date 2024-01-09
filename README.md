# GlobalCountryData

## Introduction
Welcome to GlobalCountryData! This repository is a comprehensive collection of country-specific data in JSON format. It includes essential details like country names, ISO codes, emojis, Unicode representations, international dialing codes, and direct links to flag images. This resource is perfect for developers, data scientists, and anyone needing standardized country information for a range of applications, from web development to data analysis.

## Data Format
Each entry in the JSON data set includes the following fields:
- `name`: The country's official name.
- `code`: The two-letter ISO country code.
- `emoji`: The country's flag emoji.
- `unicode`: The Unicode representation of the flag emoji.
- `dial_code`: The country's international dialing code.
- `image`: A direct link to an SVG image of the country's flag.

Example:
```json
{
  "name": "Afghanistan",
  "code": "AF",
  "emoji": "🇦🇫",
  "unicode": "U+1F1E6 U+1F1EB",
  "dial_code": "+93",
  "image": "https://cdn.jsdelivr.net/npm/country-flag-emoji-json@2.0.0/dist/images/AF.svg"
}
```

## How to Use
You can clone this repository or directly use the JSON file in your projects by fetching it from the provided URL. This data can be easily integrated into web applications, data analysis tools, and any system that requires comprehensive country data.

## Contributing
Contributions to improve GlobalCountryData are always welcome. Whether it's adding more data, refining the existing dataset, or fixing errors, your input is valued. Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
