# CoreDNS+

Welcome to **CoreDNS+**, a powerful, modern, and open-source DNS filtering application for Android.

## Features

- **Advanced DNS Filtering**: Block unwanted domains, ads, and trackers at the DNS level before they even reach your device.
- **Battery & Performance Optimized**: Designed to run seamlessly in the background with minimal battery footprint and zero bloated background processes.
- **Customizable Host Lists**: Easily import and manage your own custom blocklists.
- **Privacy First**: All filtering happens locally on your device. We do not track you, and your DNS queries are never sent to a third-party analytics server.
- **Open Source**: Fully transparent and driven by the community. You can review every line of code.

## Getting Started

### Prerequisites
- Android Studio (latest recommended)
- Android SDK API 34+
- Gradle 8.0+

### Building from Source
1. Clone the repository:
   ```bash
   git clone https://github.com/mehmetym/CoreDNSPlus.git
   ```
2. Open the project in Android Studio.
3. Sync the Gradle files.
4. Click **Run** to build and deploy to your connected device or emulator.

## How it Works

CoreDNS+ operates by setting up a local VPN service on your device. Unlike traditional VPNs that route all your traffic to a remote server, CoreDNS+ only intercepts DNS requests locally. It checks these requests against your configured blocklists and either allows or blocks the resolution, saving bandwidth and protecting your privacy.

## Contributing

We welcome contributions from the community! Whether you're fixing bugs, improving the UI, or adding new features, please adhere to our coding standards and submit a Pull Request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the GNU General Public License v2.0 - see the LICENSE file for details.
