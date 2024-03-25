# Inbound-Outbound-SMS
# Twilio SMS Application

This project consists of two servlets that handle inbound and outbound SMS functionality using the Twilio API.

## Features

- **Receive Servlet**: Handles incoming messages and responds with a TwiML XML.
- **OutboundSms Servlet**: Sends messages to a specified phone number and logs the message SID.

## Prerequisites

- Java Development Kit (JDK)
- Apache Tomcat or any other JSP/Servlet container
- Twilio Account SID and Auth Token

## Installation

1. Ensure you have Java and a servlet container installed.
2. Clone the repository to your local machine.
3. Import the project into your favorite IDE (e.g., NetBeans, Eclipse).
4. Add the Twilio Java helper library to your project dependencies.

## Configuration

Set your Twilio Account SID and Auth Token in the `OutboundSms` servlet. Update the `toPhoneNumber` and `fromPhoneNumber` with the desired numbers.

## Usage

Deploy the application to your servlet container. The `Receive` servlet will be triggered by Twilio when an SMS is received, and the `OutboundSms` servlet can be triggered by making a POST request with the `toPhoneNumber` and `message` parameters.

## Contributing

Feel free to fork the project and submit pull requests.

## License

This project is open-sourced under the MIT license.

## Acknowledgments

- Twilio API
- Java Servlet API

## Contact Information
- GitHub: [[Your GitHub Profile](https://github.com/AsmaaElhadad10/Inbound-Outbound-SMS/)https://github.com/AsmaaElhadad10/Inbound-Outbound-SMS/]
