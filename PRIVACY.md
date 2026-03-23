# Privacy Policy for CoreDNS+

**Last Updated: March 24, 2026**

CoreDNS+ ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how we treat your information when you use the CoreDNS+ mobile application.

### 1. Zero Data Collection Policy
CoreDNS+ is built with a "Privacy by Design" philosophy. 
- **No Personal Data:** We do not collect, store, or transmit any personal identifiable information (PII) such as your name, email address, phone number, or location.
- **No Browsing History:** We do not monitor, log, or track the websites you visit or the applications you use. All DNS filtering logic happens locally on your device.
- **No Account Required:** You do not need to create an account to use the application.

### 2. Local Processing
CoreDNS+ operates as a local DNS proxy. When you enable the service:
- It creates a local VPN tunnel on your device to intercept DNS queries.
- These queries are compared against your locally stored blocklists.
- **None of this data is ever sent to our servers.** Your DNS traffic remains private and under your control.

### 3. Permissions and Their Usage
To provide its core functionality, CoreDNS+ requires the following permissions:
- **VPN Service:** Necessary to intercept DNS queries locally and apply filtering. This does not route your actual data traffic to any external VPN server.
- **Network Access:** Required to resolve allowed DNS queries via your chosen DNS provider.
- **Storage Access:** Required ONLY if you choose to import custom blocklists from your device's internal storage.
- **Notifications:** Used to show the service status in the system tray, as required by Android for foreground services.

### 4. Third-Party Services
CoreDNS+ does not include any third-party analytics, tracking SDKs, or advertising networks. We do not share any data with third parties because we do not collect any data in the first place.

### 5. Third-Party DNS Providers
While CoreDNS+ filters your traffic locally, the "allowed" queries must be resolved by a DNS provider (e.g., Cloudflare, Google, Quad9). Please note that these providers have their own privacy policies regarding how they handle DNS queries. You can configure your preferred provider within the app settings.

### 6. Children's Privacy
Since we do not collect any personal information, our application is safe for users of all ages and complies with the Children's Online Privacy Protection Act (COPPA).

### 7. Changes to This Policy
We may update our Privacy Policy from time to time. Any changes will be reflected by the "Last Updated" date at the top of this document. We encourage you to review this policy periodically.

### 8. Contact Us
If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us through our official GitHub repository:
[https://github.com/mehmetym/CoreDNSPlus](https://github.com/mehmetym/CoreDNSPlus)
