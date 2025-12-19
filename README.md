# Twilio & Stytch SDKs

A comprehensive reference guide for all available SDKs from Twilio and Stytch.

---

## Twilio SDKs

### Server-Side SDKs

Twilio's server-side SDKs make it easy to use Twilio's REST APIs, generate TwiML, and perform common server-side programming tasks.

- **[C# / .NET](https://github.com/twilio/twilio-csharp)** - Server-side SDK for .NET applications
- **[Java](https://github.com/twilio/twilio-java)** - Server-side SDK for Java applications
- **[Node.js](https://github.com/twilio/twilio-node)** - Server-side SDK for Node.js applications
- **[PHP](https://github.com/twilio/twilio-php)** - Server-side SDK for PHP applications
- **[Python](https://github.com/twilio/twilio-python)** - Server-side SDK for Python applications
- **[Ruby](https://github.com/twilio/twilio-ruby)** - Server-side SDK for Ruby applications
- **[Go](https://github.com/twilio/twilio-go)** - Server-side SDK for Go applications

### JavaScript SDKs

Browser-based JavaScript SDKs for building rich communication experiences.

- **[Voice](https://www.twilio.com/docs/voice/sdks/javascript)** - Make VoIP phone calls in the browser
- **[Conversations](https://www.twilio.com/docs/conversations/javascript/changelog)** - Real-time omnichannel chat
- **[Video](https://www.twilio.com/docs/video/javascript)** - Create video conversations
- **[TaskRouter](https://www.twilio.com/docs/taskrouter/js-sdk)** - Task routing and workforce management
- **[Sync](https://www.twilio.com/docs/sync/javascript/changelog)** - Real-time state synchronization

### iOS SDKs

Native iOS SDKs for building communication features in iPhone and iPad apps.

- **[Voice](https://www.twilio.com/docs/voice/sdks/ios)** - VoIP calling for iOS
- **[Conversations](https://www.twilio.com/docs/conversations/ios/changelog)** - Real-time chat for iOS
- **[Video](https://www.twilio.com/docs/video/ios)** - Video conversations for iOS
- **[Sync](https://www.twilio.com/docs/sync/ios/changelog)** - State synchronization for iOS

### Android SDKs

Native Android SDKs for building communication features in Android apps.

- **[Voice](https://www.twilio.com/docs/voice/sdks/android)** - VoIP calling for Android
- **[Conversations](https://www.twilio.com/docs/conversations/android/changelog)** - Real-time chat for Android
- **[Video](https://www.twilio.com/docs/video/android)** - Video conversations for Android
- **[Sync](https://www.twilio.com/docs/sync/quickstart/android)** - State synchronization for Android

### React Native SDK

Cross-platform mobile SDK for React Native applications.

- **[Voice](https://www.twilio.com/docs/voice/sdks/react-native)** - Add VoIP calling to React Native apps

### Flex SDKs

SDKs for customizing Twilio Flex contact center platform.

- **[Flex UI](https://www.twilio.com/docs/flex/developer/ui)** - Customize Flex interface with JavaScript and React
- **[Flex WebChat](https://www.twilio.com/docs/flex/developer/messaging/webchat/setup)** - Add web chat to Flex

### OpenAPI Specification

- **[Twilio OpenAPI Spec](https://github.com/twilio/twilio-oai)** - Generate clients in 40+ languages
- **[Postman Collections](https://www.twilio.com/docs/openapi/using-twilio-postman-collections)** - Pre-built API collections
- **[Mock API Generation](https://www.twilio.com/docs/openapi/mock-api-generation-with-twilio-openapi-spec)** - Create mock APIs for testing

---

## Stytch SDKs

### Backend SDKs

Official server-side SDKs for authentication and authorization.

- **[Python](https://github.com/stytchauth/stytch-python)** - Backend SDK for Python applications
- **[Node.js](https://github.com/stytchauth/stytch-node)** - Backend SDK for Node.js applications
- **[Go](https://github.com/stytchauth/stytch-go)** - Backend SDK for Go applications
- **[Ruby](https://github.com/stytchauth/stytch-ruby)** - Backend SDK for Ruby applications
- **[Java / Kotlin / JVM](https://github.com/stytchauth/stytch-java)** - Backend SDK for JVM-based applications
- **[PHP](https://github.com/stytchauth/stytch-php)** - Backend SDK for PHP applications

### Frontend SDKs

Browser-based SDKs with pre-built UI components and direct API access.

- **[@stytch/vanilla-js](https://www.npmjs.com/package/@stytch/vanilla-js)** - Vanilla JavaScript SDK
- **[@stytch/react](https://www.npmjs.com/package/@stytch/react)** - React SDK with components
- **[@stytch/nextjs](https://www.npmjs.com/package/@stytch/nextjs)** - Next.js SDK with App Router support

### Mobile SDKs

Native mobile SDKs for iOS and Android applications.

- **[iOS](https://github.com/stytchauth/stytch-ios)** - Native SDK for iOS (Swift)
- **[Android](https://github.com/stytchauth/stytch-android)** - Native SDK for Android (Kotlin)

### Supported Authentication Methods

Stytch SDKs support the following authentication products:

- Email magic links
- One-time passcodes (SMS & Email)
- OAuth / Social login
- WebAuthn / Passkeys
- TOTP (Time-based One-Time Passwords)
- Crypto wallets (Web3)
- Passwords
- Session management
- User management
- Fraud & Risk Prevention

---

## Contributing

We welcome contributions from the community! This repository serves as a reference guide for developers working with Twilio and Stytch SDKs.

### How to Contribute

1. **Fork the repository** and create a new branch for your changes
   ```bash
   git checkout -b feature/update-sdk-info
   ```

2. **Make your changes** following these guidelines:
   - Keep the existing structure and formatting
   - Maintain alphabetical or logical ordering within sections
   - Include links to official documentation or GitHub repositories
   - Verify all links are working and up-to-date

3. **Commit your changes** with a clear, descriptive message
   ```bash
   git commit -m "Add new SDK or Update SDK documentation"
   ```

4. **Push to your fork** and submit a Pull Request
   ```bash
   git push origin feature/update-sdk-info
   ```

### What to Contribute

- **New SDKs**: Add newly released SDKs from Twilio or Stytch
- **Updates**: Update links, descriptions, or features for existing SDKs
- **Corrections**: Fix broken links, typos, or inaccurate information
- **Enhancements**: Improve documentation structure or add helpful context

### Pull Request Guidelines

- **Title**: Use a clear, descriptive title (e.g., "Add Twilio Flutter SDK" or "Update Stytch iOS SDK link")
- **Description**: Explain what changes you made and why
- **Testing**: Verify all links work before submitting
- **One concern per PR**: Keep changes focused on a single update or addition

### Suggesting Changes

If you're not ready to submit a PR, you can:
- Open an issue to suggest additions or corrections
- Report broken links or outdated information
- Request coverage of additional SDK features

---

## Resources

### Twilio
- [Twilio Documentation](https://www.twilio.com/docs)
- [Twilio Libraries Overview](https://www.twilio.com/docs/libraries)
- [Twilio GitHub](https://github.com/twilio)

### Stytch
- [Stytch Documentation](https://stytch.com/docs)
- [Stytch API Reference](https://stytch.com/docs/api)
- [Stytch GitHub](https://github.com/stytchauth)
- [Stytch Quickstarts](https://stytch.com/docs/quickstarts)

---

*Last updated: December 19, 2025*
