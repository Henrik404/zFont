# zFont - Font Configuration Profile Generator for iOS/iPadOS

A Progressive Web Application (PWA) that enables users to create and install custom font configuration profiles (.mobileconfig) on iOS and iPadOS devices. zFont provides a user-friendly interface for converting TTF and OTF fonts into installable Apple configuration profiles.

## Key Features

- Convert TrueType (.ttf) and OpenType (.otf) fonts to .mobileconfig profiles
- Handle multiple font files in a single configuration profile
- Progressive Web App capabilities for offline usage
- Intuitive drag-and-drop interface
- Customizable profile names and descriptions
- Client-side processing for enhanced privacy
- Responsive design powered by Tailwind CSS
- Support for files up to 20MB
- Secure installation process via Apple's configuration profile system

## Quick Start

1. Access the web application through your browser
2. Upload font files using one of these methods:
   - Click the upload zone to select files
   - Drag and drop files directly into the upload area
3. Customize the profile settings (optional):
   - Set a meaningful profile name
   - Add a descriptive profile description
4. Generate the configuration profile by clicking "Generate Profile"
5. Install the downloaded .mobileconfig file on your iOS/iPadOS device

## Local Development Setup

1. Clone this repository:
```
git clone https://github.com/Henrik404/zFont.git
cd zFont
```

2. Open index.html in your preferred browser

## PWA Features

- Offline functionality
- Installable on supported devices
- Responsive design for all screen sizes
- Cache management for improved performance

## Technical Details

- Pure client-side JavaScript implementation
- No server-side processing required
- Uses native browser APIs for file handling
- Implements service workers for PWA functionality
- Tailwind CSS for styling
- Generates Apple-compliant configuration profiles

## Browser Support

- Safari on iOS/iPadOS (recommended for direct installation)
- Chrome, Firefox, Edge, and other modern browsers for profile generation

## Security

- All processing occurs locally in the browser
- No file uploads to external servers
- Generated profiles follow Apple's security guidelines
- Transparent code available for review

## License

Copyright 2024 Henrik404

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this files except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Contributions

Contributions are welcome! Please feel free to submit a Pull Request.
