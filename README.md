# 🔐 Developer Secret Generator

A world-class tool for generating secure secrets and tokens for modern web development. Built with professional UI/UX focused on security, usability, and developer experience.

## ✨ Features

### 🔒 Comprehensive Secret Generators
- **NextAuth Secret** - Base64-encoded secrets for NextAuth session encryption
- **JWT Signing Secret** - HMAC signing keys for JSON Web Tokens
- **API Key** - URL-safe keys with "sk_" prefix for API authentication
- **Database Password** - Secure alphanumeric passwords with special characters
- **Encryption Key (AES)** - Hexadecimal keys for AES-128/256 encryption
- **Session Secret** - Base64-encoded secrets for cookie/session signing
- **CSRF Token** - URL-safe tokens for cross-site request forgery protection
- **OAuth Client Secret** - URL-safe secrets for OAuth 2.0 authentication
- **Webhook Secret** - Base64 secrets with "whsec_" prefix for webhook verification
- **Random UUID v4** - Standard RFC 4122 compliant unique identifiers

### 🎨 Professional Design
- **Modern Minimalism Premium** aesthetic (inspired by Stripe, Linear, Vercel)
- **Mobile-responsive** design (3-column → 2-column → 1-column grid)
- **World-class typography** using Inter font family
- **Cryptographic security** conveyed through professional, trustworthy design
- **Accessibility compliant** (WCAG AA standards)

### 🚀 Developer Experience
- **One-click generation** for all secret types
- **Instant copy-to-clipboard** with visual feedback
- **Length customization** via intuitive sliders
- **Show/hide toggle** for security-conscious secret viewing
- **Real-time generation** using Web Crypto API (CSPRNG)

## 🔐 Security Standards

- **Cryptographically Secure Random Number Generation (CSPRNG)** using Web Crypto API
- **Client-side generation** - secrets never stored or transmitted
- **Industry compliance** with NIST SP 800-133 and OWASP guidelines
- **Proper entropy** for all secret types
- **Format-specific generation** (base64, hex, URL-safe, UUID)

## 🛠️ Technical Stack

- **React 18.3** with TypeScript
- **Vite 6.0** build tool
- **TailwindCSS** with custom design system
- **Lucide React** icons
- **Web Crypto API** for secure random generation

## 📖 Usage

1. **Visit the application** and choose your desired secret type
2. **Customize the length** (where applicable) using the slider
3. **Click "Generate Secret"** for instant generation
4. **Copy to clipboard** with one click
5. **Use securely** in your environment variables and configurations

## 🔒 Security Best Practices

- ✅ **Use environment variables** for production secrets
- ✅ **Rotate secrets regularly** and after any security incident
- ✅ **Never commit secrets** to version control
- ✅ **Use different secrets** for different environments
- ✅ **Monitor secret usage** and access logs
- ✅ **Use secret management services** in production (AWS Secrets Manager, HashiCorp Vault, etc.)

## 🚀 Live Demo

**GitHub Pages:** https://mipeal.github.io/secret-generator/

## 📱 Browser Support

- **Modern browsers** with Web Crypto API support
- **Chrome/Edge 37+**
- **Firefox 34+**
- **Safari 7+**
- **Mobile browsers** with ES6 support

## 🏗️ Development

### Prerequisites
- Node.js 18+
- npm or pnpm

### Setup
```bash
# Clone the repository
git clone https://github.com/mipeal/secret-generator.git

# Navigate to project
cd developer-secret-generator

# Install dependencies
pnpm install

# Start development server
pnpm dev

# Build for production
pnpm build
```

### Architecture
- **Single Page Application (SPA)** for fast, responsive experience
- **Component-based architecture** with reusable secret generators
- **Design system** with consistent tokens and components
- **Cryptographic security** through proper API usage

## 🏷️ Secret Types Reference

| Secret Type | Format | Use Case | Typical Length |
|-------------|--------|----------|----------------|
| NextAuth Secret | base64 | Session encryption | 32 bytes |
| JWT Secret | base64 | Token signing | 32 bytes |
| API Key | URL-safe + prefix | Authentication | 16-64 bytes |
| Database Password | alphanumeric + symbols | Database auth | 16-64 bytes |
| Encryption Key | hex | Data encryption | 16-32 bytes |
| Session Secret | base64 | Cookie signing | 32-64 bytes |
| CSRF Token | URL-safe | Security tokens | 16-64 bytes |
| OAuth Secret | URL-safe | OAuth 2.0 | 32-64 bytes |
| Webhook Secret | base64 + prefix | Webhook verification | 32-64 bytes |
| UUID v4 | hyphens | Identifiers | 36 chars |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **NIST** for cryptographic standards and guidelines
- **OWASP** for security best practices
- **React** and **Vite** teams for excellent development tools
- **TailwindCSS** for utility-first styling
- **Lucide** for beautiful icons

---

**Built with ❤️ by MiniMax Agent**

*All secrets are generated using cryptographically secure random number generation (CSPRNG) and never stored or transmitted to any server.*
