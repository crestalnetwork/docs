Welcome to the **Crestal Docs** repository! This documentation hub is designed to guide developers in integrating with Crestal's tools and APIs.

## Getting Started

### Prerequisites

To run this documentation locally, ensure you have the following:

1. **Node.js** - [Download here](https://nodejs.org/en/download/)
2. **Yarn** - [Install Yarn](https://yarnpkg.com/getting-started/install)
3. **Mintlify CLI** - Install Mintlify via npm:
   ```bash
   npm install -g mintlify
   ```

### Local Setup

To set up and run the Crestal Docs locally using Mintlify, follow these steps:

**1. Clone the Repository**

Clone the Crestal Docs repository and navigate to the project directory:

```bash
git clone https://github.com/crestalnetwork/docs.git
cd docs
cd mintlify-docs
```

**2. Install Dependencies**

Use Yarn to install the project's dependencies:

```bash
yarn install
```

**4. Run the Mintlify Development Server***

Use the Mintlify CLI to run the documentation server locally:

```bash
mintlify dev
```

The server will be available at `http://localhost:3000`, where you can view and edit the documentation in real-time.

**5. Build for Production (Optional)**

If you need to generate a production-ready build, use:

```bash
mintlify build
```

This command will create a static output of your documentation in the `dist` folder, ready for deployment.

## Contributing

We welcome contributions! To get started:

1. **Fork the Repo**: Fork `https://github.com/crestalnetwork/docs.git` and clone it locally.

2. **Create a Branch**: Create a new branch for your changes:
```bash
git checkout -b feature/your-feature-name
```

3. **Make Changes**: Edit the documentation and preview using:
```bash
mintlify dev
```

4. **Commit and Push**: Commit your changes and push to your fork:
```bash
git add .
git commit -m "Brief description of your changes"
git push origin feature/your-feature-name
```

5. **Open a Pull Request**: Submit a pull request to the main branch of the original repository.

Thanks for contributing!

