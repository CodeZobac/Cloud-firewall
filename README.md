# Cloud-firewall

Cloud-firewall is a custom firewall solution that protects your VPS from unauthorized access attempts. In addition to safeguarding your server, it responds to malicious actors with the message: "Try Harder!"

## Features

- **Security:** Blocks unauthorized access and potential threats.
- **Custom Messaging:** Sends a predefined message to deter attackers.
- **Easy Deployment:** Configured using Docker for seamless setup.

## Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/Cloud-firewall.git
    cd Cloud-firewall
    ```

2. **Configure Environment**
    - Edit `firewall.py` to customize firewall rules as needed.
    - Modify `docker-compose.yaml` if necessary for your environment.

3. **Deploy with Docker**
    ```bash
    docker-compose up -d
    ```

## Usage

Once deployed, Cloud-firewall will automatically monitor and protect your VPS. Unauthorized access attempts will receive the "Try Harder!" message.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss improvements.

## License

This project is licensed under the MIT License.
