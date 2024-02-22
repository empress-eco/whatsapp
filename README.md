<div align="center">
    <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo">
</div>

An effective tool to integrate WhatsApp with your applications, enhancing efficiency and user experience. Specially designed for developers looking to streamline communication within their applications, it allows seamless integration of WhatsApp, enabling direct messaging and notification features without the need for third-party involvement.

- [Explore the Docs](https://empress.eco/)
- [Report Bug](https://github.com/empress-eco/whatsapp/issues)
- [Request Feature](https://github.com/empress-eco/whatsapp/issues)

## About The Project

The WhatsApp Integration Tool lets you directly connect your applications with WhatsApp via meta APIs, send WhatsApp notifications based on document events, create templates for streamlined message formatting, and receive incoming messages via a setup webhook.

## Getting Started

### Prerequisites

You should have a general knowledge of working with APIs and development experience.

### Installation

Clone the repository and install the app on your instance/site:

```sh
# Clone the repository
git clone https://github.com/empress-eco/whatsapp.git

# Get the app
bench get-app Empress_whatsapp

# Install the app on any instance/site
bench --site [sitename] install-app Empress_whatsapp
```

## Usage

Once installed, you can send WhatsApp notifications from your app based on document events. Additionally, you can create message templates for consistent formatting and receive incoming messages via a setup webhook.

To start sending messages:

1. You need to get your WhatsApp credentials. Follow the guide [here](https://developers.facebook.com/docs/whatsapp/cloud-api/get-started).
2. Enter your WhatsApp credentials in the WhatsApp settings of the app.
3. Create a template for your messages.
4. Create notifications based on document events.
5. You can also send a text message without creating a template by creating an entry in the WhatsApp message. On save, it will trigger the WhatsApp API to send a message.
6. To receive messages, setup a webhook on meta and add appropriate webhook fields.

## Contributing

We value your contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

This project is under the MIT License. Your contributions are also licensed under the same.

Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.