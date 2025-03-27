# Tampa/Hillsborough County Designated Access Points App
## Overview
This repository contains a simple, accessible web application designed to help individuals experiencing homelessness in Tampa/Hillsborough County quickly find the appropriate dedicated access point based on their situation and last name.

The tool implements the Tampa Hillsborough Homeless Initiative's (THHI) Coordinated Entry referral system, making it easier for individuals in need and service providers to navigate the proper channels for assistance.

## Features
- **Simple User Flow**: Guides users through a few simple questions to identify the correct contact information
- **Mobile-Friendly**: Responsive design works on smartphones, tablets, and desktop computers
- **Accessibility-Focused**: High contrast design, screen reader compatibility, and keyboard navigation
- **Lightweight**: Fast loading with no server-side requirements
- **Up-to-Date**: Based on THHI's Coordinated Entry 4.0 (updated 6/16/2023)

## Installation

### Local Development
1. Clone this repository:
   ```
   git clone https://github.com/your-username/tampa-homeless-resource-finder.git
   ```
2. Open the `index.html` file in any modern web browser

### Deployment
This is a static HTML site that can be deployed to any web hosting service:

1. GitHub Pages: Enable GitHub Pages in repository settings
2. Netlify: Drag and drop the folder into Netlify's upload area
3. Any web hosting service: Upload the HTML file via FTP

## Usage
The application guides users through a simple process:

1. Confirm if the person is experiencing unsheltered homelessness
2. Select the appropriate family situation (Youth, Family with children, Single adult, or Veteran)
3. Select the first letter of their last name
4. View the appropriate contact information with a convenient "Call Now" button

A working demo can be found at: https://wan03.github.io/thrf/

## Technology Stack
- HTML5
- CSS3
- Vanilla JavaScript (ES6)
- No external dependencies or frameworks

## File Structure
```
tampa-homeless-resource-finder/
│
├── index.html       # Main application file (HTML, CSS, and JavaScript)
├── README.md        # This documentation file
└── LICENSE          # License information
```

## Maintenance
The contact information is based on THHI's Coordinated Entry document version 4.0 (updated 6/16/2023, expires 9/30/2024). The application should be updated when new information becomes available.

To update the contact information:
1. Modify the `resourceDirectory` object in the JavaScript section of `index.html`
2. Update the creation/update dates in the header

## Contributing
Contributions to improve this tool are welcome. Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Test thoroughly on multiple devices
5. Submit a pull request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- Tampa Hillsborough Homeless Initiative (THHI) for providing the Coordinated Entry system and contact information
- All service providers who work to address homelessness in Tampa/Hillsborough County

## Contact
For questions or support regarding this application, please [open an issue](https://github.com/your-username/tampa-homeless-resource-finder/issues) in this repository.
