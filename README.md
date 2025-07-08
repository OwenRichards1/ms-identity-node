# Code samples for Microsoft identity platform documentation - Node.js & JavaScript

Welcome to the Microsoft Identity Platform Node.js & JavaScript Code Samples repository!

This repository provides a comprehensive set of end-to-end samples demonstrating how to integrate Microsoft Entra ID authentication and authorization into Node.js applications. The samples are organized by scenario and technology, making it easy to find the right starting point for your needs.

## 📁 Repository Structure

The samples are grouped into several main categories, each corresponding to a common application scenario:

- `ms-identity-javascript-nodejs-console/` – Node.js console/daemon applications
- `ms-identity-javascript-nodejs-desktop/` – Electron desktop applications
- `ms-identity-javascript-nodejs-tutorial/` – Multi-chapter tutorial for Node.js & Express web apps, including authentication, authorization, deployment, access control, and advanced scenarios
- `ms-identity-node/` – Standalone Express web app sample

Each scenario folder contains one or more samples, each with its own README and instructions.

---

## 🗂️ Sample Scenarios

| Folder                                         | Description                                                                                      |
|------------------------------------------------|--------------------------------------------------------------------------------------------------|
| **ms-identity-javascript-nodejs-console**      | Node.js console/daemon app using MSAL Node to acquire tokens and call web APIs.                  |
| **ms-identity-javascript-nodejs-desktop**      | Electron desktop app demonstrating interactive authentication and API calls.                      |
| **ms-identity-javascript-nodejs-tutorial**     | Multi-chapter tutorial covering authentication, authorization, deployment, access control, and advanced scenarios (BFF, React SPA, CAE, etc.) in Node.js & Express. |
| **ms-identity-node**                           | Standalone Express web app with MSAL Node for sign-in and Microsoft Graph calls.                 |

---

## 🚀 Getting Started

1. **Browse the scenario folders** above to find the sample that matches your use case.
2. **Read the sample’s README.md** for prerequisites, setup instructions, and code walkthroughs.
3. **Clone and run the sample** following the provided steps.

All samples use the latest supported Node.js versions and Microsoft Authentication Library (MSAL) for Node.js.

---

## 🔍 Finding the Right Sample

- **By scenario:** Start with the folder that matches your application type (console, desktop, web app, advanced).
- **By technology:** Within each folder, samples are organized by technology (e.g., Express, Electron).
- **By feature:** Each sample README highlights the authentication flow, APIs called, and any advanced features.

---

## 📝 Configuration & Security

- **Configuration** is managed via environment variables or configuration files (e.g., `authConfig.js`).
- **Secrets and credentials** should never be committed to source control. Use [Azure Key Vault](https://learn.microsoft.com/azure/key-vault/general/basic-concepts) or environment variables for sensitive data.
- **PowerShell scripts** are provided where helpful for Microsoft Entra app registration.

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
| ms-identity-javascript-nodejs-console            | Console/daemon app      | Token acquisition, web API calls                         | MSAL Node                     |
| ms-identity-javascript-nodejs-desktop            | Electron desktop app    | Interactive login, token acquisition, web API calls      | MSAL Node                     |
| ms-identity-javascript-nodejs-tutorial           | Web app (multi-scenario)| Authentication, authorization, deployment, access control, advanced scenarios | MSAL Node, Express, React     |
| ms-identity-node                                 | Express web app         | Sign-in, token acquisition, Microsoft Graph calls        | MSAL Node, Express            |

## Resources

- Documentation on learn.microsoft.com
  - [Microsoft identity platform product documentation](https://learn.microsoft.com/entra/identity-platform/)
  - [Microsoft Authentication Library (MSAL) documentation](https://learn.microsoft.com/entra/identity-platform/msal-overview)
- Authentication library source code on GitHub
  - [Microsoft Authentication Library for JavaScript](https://github.com/AzureAD/microsoft-authentication-library-for-js)