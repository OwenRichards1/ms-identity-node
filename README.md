# Code samples for Microsoft ide1. **Browse the scenario folders** above to find the sample that matches your use case.
2. **Read the sample's README.md** for prerequisites, setup instructions, and code walkthroughs.
3. **Clone and run the sample** following the provided steps.

All samples use the latest supported Node.js versions and Microsoft Authentication Library (MSAL) for Node.js.

### Sample Categories Overview

**🌐 Server-side Applications (9 samples)**
- Express web applications with various authentication patterns
- Console and daemon applications for service-to-service scenarios
- From basic authentication to advanced features like RBAC and Microsoft Graph integration

**💻 Client-side Applications (1 sample)**
- React Single Page Applications with Backend-for-Frontend architecture

**🖥️ Desktop Applications (1 sample)**
- Electron-based desktop applications with interactive authentication

**🚀 Advanced Scenarios (2 samples)**
- Complete Backend-for-Frontend implementations
- Multi-tier architectures with React frontends and Express backends platform documentation - Node.js

Welcome to the Microsoft Identity Platform Node.js Code Samples repository!

This repository provides a comprehensive set of end-to-end samples demonstrating how to integrate Microsoft Entra ID authentication and authorization into Node.js applications. The samples are organized by scenario and technology, making it easy to find the right starting point for your needs.

## 📁 Repository Structure

The samples are grouped into five main categories, each corresponding to a common application scenario:

| Folder            | App description                                                                                  | Authentication libraries                      |
|-------------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------|
| [1-server-side](./1-server-side)      | Node.js & Express web applications, console applications, and daemon services with Microsoft Entra sign-in | MSAL Node<br>MSAL Node Wrapper        |
| [2-client-side](./2-client-side)      | Client-side React Single Page Applications with Backend-for-Frontend pattern              | React<br>MSAL Node (BFF backend)        |
| [3-desktop](./3-desktop)  | Electron desktop applications with interactive authentication                                                | MSAL Node |
| [4-advanced](./4-advanced) | Advanced scenarios including Backend for Frontend (BFF) architectures with React SPA and Express backend | MSAL Node<br>React<br>MS Graph SDK                                    |
| [5-samples-index](./SAMPLES_INDEX.md) | Complete index of all samples with detailed descriptions and feature mappings | All libraries                                    |

---

Each folder contains one or more samples, each with its own README and instructions.

---

## 🚀 Getting Started

1. **Browse the scenario folders** above to find the sample that matches your use case.
2. **Read the sample’s README.md** for prerequisites, setup instructions, and code walkthroughs.
3. **Clone and run the sample** following the provided steps.

All samples use the latest supported Node.js versions and Microsoft Authentication Library (MSAL) for Node.js.

---

## 🔍 Finding the Right Sample

**By Application Type:**
- **Web Applications**: Start with `1-server-side/express-web-app-auth` for basic authentication
- **API Integration**: Try `1-server-side/express-web-app-graph` for Microsoft Graph calls
- **Desktop Apps**: Use `3-desktop/nodejs-desktop` for Electron applications
- **Services/Daemons**: Check `1-server-side/nodejs-console-daemon` for background services
- **Single Page Apps**: Explore `2-client-side/react-spa-bff` for React applications

**By Authentication Flow:**
- **Authorization Code Flow**: Most Express web applications
- **Client Credentials Flow**: Console daemon applications
- **Interactive Flow**: Desktop and client-side applications

**By Complexity Level:**
- **Beginner**: `express-web-app-auth` (basic authentication)
- **Intermediate**: `express-web-app-graph` (with API calls)
- **Advanced**: `call-graph-bff` (full BFF architecture)

---

## 📝 Configuration & Security

- **Configuration** is managed via environment variables or configuration files (e.g., `authConfig.js`).
- **Secrets and credentials** should never be committed to source control. Use [Azure Key Vault](https://learn.microsoft.com/azure/key-vault/general/basic-concepts) or environment variables for sensitive data.
- **PowerShell scripts** are provided in the top-level `AppCreationScripts/` folder for Microsoft Entra app registration.
- **Environment files** (`.env`) are included in `.gitignore` files across all samples for security.

## 🛠️ Prerequisites

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [Microsoft Entra ID tenant](https://learn.microsoft.com/entra/identity-platform/quickstart-create-new-tenant)
- [Visual Studio Code](https://code.visualstudio.com/) (recommended for development)

---

## 🤝 Contributing

We welcome contributions!  
Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on submitting new samples or improvements.

---

## 📢 Support & Feedback

- For questions, open an issue in this repository.
- For Microsoft identity platform documentation, visit [learn.microsoft.com/entra/identity-platform](https://learn.microsoft.com/entra/identity-platform).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Happy coding!

## Contents

| Sample directory                                 | Application type         | Feature(s) demonstrated                                  | Authentication libraries used |
|:-------------------------------------------------|-------------------------|----------------------------------------------------------|-------------------------------|
| **1-server-side/express-App**                   | Express web app         | Basic authentication, sign-in, user profile             | MSAL Node                     |
| **1-server-side/express-web-app-auth**          | Express web app         | Basic authentication with msal-node-wrapper             | MSAL Node Wrapper             |
| **1-server-side/express-web-app-graph**         | Express web app         | Authentication, Microsoft Graph calls                   | MSAL Node Wrapper, MS Graph SDK |
| **1-server-side/express-web-app-deployment**    | Express web app         | Production deployment patterns                           | MSAL Node Wrapper             |
| **1-server-side/express-web-app-roles**         | Express web app         | Role-based access control (RBAC)                        | MSAL Node Wrapper             |
| **1-server-side/express-web-app-groups**        | Express web app         | Security groups-based access control                    | MSAL Node Wrapper             |
| **1-server-side/nodejs-call-graph**             | Express web app         | Authentication, Microsoft Graph calls, multiple APIs    | MSAL Node Wrapper, MS Graph SDK |
| **1-server-side/nodejs-console-daemon**         | Console/daemon app      | Client credentials flow, daemon services                | MSAL Node                     |
| **1-server-side/node-console-app**              | Console/CLI app         | Interactive CLI authentication                           | MSAL Node                     |
| **2-client-side/react-spa-bff**                 | React SPA               | Single Page Application with BFF pattern                | React                         |
| **3-desktop/nodejs-desktop**                    | Electron desktop app    | Interactive login, token acquisition, web API calls     | MSAL Node                     |
| **5-advanced/bff-backend**                      | Express BFF backend     | Backend for Frontend server implementation              | MSAL Node, MS Graph SDK       |
| **5-advanced/call-graph-bff**                   | React SPA + Express BFF | Complete BFF architecture with React SPA and Express backend | MSAL Node, React        |

## Resources

- Documentation on learn.microsoft.com
  - [Microsoft identity platform product documentation](https://learn.microsoft.com/entra/identity-platform/)
  - [Microsoft Authentication Library (MSAL) documentation](https://learn.microsoft.com/entra/identity-platform/msal-overview)
- Authentication library source code on GitHub
  - [Microsoft Authentication Library for JavaScript](https://github.com/AzureAD/microsoft-authentication-library-for-js)