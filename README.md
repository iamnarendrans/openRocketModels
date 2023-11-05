# OpenRocket Design Importer

This repository provides a simple guide to installing OpenRocket and importing your rocket designs into the application.

## Installation

### Prerequisites

Before you begin, ensure you have the following installed:
- Java Development Kit (JDK) 11 or later
- Git (for cloning this repository)

### Steps

1. **Clone the OpenRocket repository**

    ```bash
    git clone https://github.com/openrocket/openrocket.git
    ```

2. **Install OpenRocket**

    - If you have a pre-built JAR file:
    
        ```bash
        java -jar openrocket.jar
        ```
    
    - If you have the source code:
    
        ```bash
        cd openrocket
        ./gradlew run
        ```

3. **Import Your Rocket Design**

    Once OpenRocket is running, follow these steps to import your design:
    
    - Click on the "File" menu.
    - Select "Open...".
    - Choose your rocket design file (e.g., .ork format).
    - Follow the prompts to import and view your design within OpenRocket.

## Contributing

Contributions and improvements to this guide are welcome! To contribute:
- Fork this repository.
- Make your changes.
- Create a pull request with a detailed explanation of your modifications.

## Troubleshooting

For any issues or troubleshooting help, refer to [OpenRocket's official documentation](https://openrocket.info/).

## License

This project is licensed under the [GNU Lesser General Public License](https://www.gnu.org/licenses/lgpl-3.0.html). Please review the license before using this code.

## Disclaimer

Please note that this repository only provides installation instructions for OpenRocket. The OpenRocket application itself is developed and maintained by its respective contributors.

