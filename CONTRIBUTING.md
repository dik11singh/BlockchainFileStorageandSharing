# Contributing to Blockchain File Storage and Sharing

First off, thank you for considering contributing to this project! It’s people like you who make the decentralized web a better place.

---

## 📜 Code of Conduct
By participating in this project, you agree to abide by basic professional standards:
* Be respectful and inclusive.
* Focus on constructive feedback.
* Keep the security of decentralized data a top priority.

## 🛠️ How Can I Contribute?

### 1. Reporting Bugs
* Check the **Issues** tab to see if the bug has already been reported.
* If not, open a new issue. Include:
    * Steps to reproduce the bug.
    * Your environment (Browser, MetaMask version, Network).
    * Expected vs. Actual behavior.

### 2. Suggesting Enhancements
* Open an issue with the tag `enhancement`.
* Explain why this feature would be useful and how it fits the goal of decentralized storage.

### 3. Pull Requests
1. **Fork** the repository.
2. **Clone** your fork:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/BlockchainFileStorageandSharing.git](https://github.com/YOUR_USERNAME/BlockchainFileStorageandSharing.git)

   Create a branch for your fix or feature:

```Bash

git checkout -b feature/your-feature-name
```
Commit your changes:

Use clear, descriptive commit messages.

If fixing a bug, reference the issue number.

Push to your fork:
```
Bash

git push origin feature/your-feature-name
Open a Pull Request against the main branch.
```
🏗️ Development Guidelines
Smart Contract Changes
All contracts are located in the /contracts folder.

Ensure you add/update tests in the /test folder using Hardhat.

Run tests before submitting:

```Bash

npx hardhat test
```
Frontend Changes
Follow the existing folder structure in /src.

Ensure the UI remains responsive and provides clear feedback for blockchain transactions (loading states, error handling).

Documentation
If you add a new feature, please update the README.md to reflect the changes.

📬 Questions?
If you have any questions, feel free to open an issue or reach out to the maintainer: revxi.
