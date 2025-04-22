# Privacy Policy for kook-notify Dify Plugin

Last Updated: 2025-04-22

This Privacy Policy describes how the kook-notify Dify plugin ("Plugin") handles your information when you use it within the Dify platform.

**Information We Use**

The Plugin requires the following information to function:

1.  **Kook Bot Token:** Your Kook Bot authentication token is required to authorize requests to the Kook API on your behalf. This token is securely stored by Dify as a credential and is only used to send messages via the Kook API.
2.  **Kook Channel ID:** The specific Kook channel ID where you want the notifications to be sent. This is also stored by Dify as a credential.
3.  **Message Content (Title, Content, Type):** The information you provide (title, content, type) to be included in the notification message sent to Kook.

**How We Use Information**

The information listed above is used solely for the purpose of sending notification messages to the specified Kook channel via the official Kook API.

*   The Kook Bot Token and Channel ID are passed directly to the Kook API for authentication and message delivery.
*   The Message Content (Title, Content, Type) is formatted and included in the payload sent to the Kook API.

**Information Storage and Security**

*   **We do not store your Kook Bot Token, Channel ID, or message content within the Plugin itself.**
*   Your Kook Bot Token and Channel ID are managed and stored securely by the Dify platform as credentials. Please refer to Dify's privacy policy for details on how they handle credentials.
*   Message content is processed in memory only during the execution of the notification request and is not logged or stored by the Plugin.

**Third-Party Services**

The Plugin interacts directly with the Kook API (developer.kookapp.cn). Your use of the Kook service is subject to Kook's own privacy policy and terms of service.

**Data Sharing**

We do not share any of your information with third parties, other than sending the necessary data (token, channel ID, message content) to the Kook API to fulfill the notification request.

**Changes to This Policy**

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy within the Plugin's description or associated documentation.

**Contact Us**

If you have any questions about this Privacy Policy, please contact the plugin author, jingfelix. Or check Kook's [official documentation](https://www.kookapp.cn/privacy.html) for more information on their privacy practices.