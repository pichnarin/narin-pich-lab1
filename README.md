# pichnarin-lab1 - CI/CD Pipeline

[![Node.js CI/CD Pipeline (Yarn)](https://github.com/pichnarin/pichnarin-lab1/actions/workflows/ci.yml/badge.svg)](https://github.com/pichnarin/pichnarin-lab1/actions/workflows/ci.yml)

## 📝 Lab Overview

This project demonstrates a complete CI/CD pipeline using GitHub Actions for a Node.js Express application.

## 🚀 Features

- ✅ Express.js web server
- ✅ Automated testing with Mocha & Chai
- ✅ Code linting with ESLint
- ✅ Code coverage reporting with NYC
- ✅ Multi-version Node.js testing (16.x, 18.x)
- ✅ Pull Request workflow automation
- ✅ Automated deployment (configured)

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/pichnarin/pichnarin-lab1.git
cd narin-pich-lab1

# Install dependencies
yarn install
```

## 🧪 Running Locally

### Start the application
```bash
yarn start
# Visit http://localhost:3000
```

### Run tests
```bash
yarn test
```

### Run tests with coverage
```bash
yarn test:coverage
# Open coverage/index.html in browser
```

### Lint code
```bash
yarn lint
```

## 🔄 CI/CD Pipeline

The GitHub Actions workflow automatically:

1. **Builds and Tests** on every push and PR
   - Tests on Node.js 16.x and 18.x
   - Runs ESLint for code quality
   - Executes automated tests
   - Generates code coverage reports

2. **Code Coverage**
   - Uploads coverage reports as artifacts
   - Comments coverage percentage on PRs

3. **Deployment**
   - Automatically deploys to production after tests pass on main branch

## 📊 Workflow Status

Check the [Actions tab](https://github.com/pichnarin/pichnarin-lab1/actions) to see workflow runs.

## 🛠️ Technologies Used

- **Runtime**: Node.js
- **Framework**: Express.js
- **Testing**: Mocha, Chai, Supertest
- **Linting**: ESLint
- **Coverage**: NYC (Istanbul)
- **CI/CD**: GitHub Actions
- **Package Manager**: Yarn

## 📚 Lab Requirements

- [x] Basic Node.js app with Express
- [x] Automated tests
- [x] GitHub Actions CI workflow
- [x] Linting step
- [x] Code coverage reporting
- [x] Pull request workflow
- [x] Deployment configuration

## 👤 Author

**Pichnarin**
- GitHub: [@pichnarin](https://github.com/pichnarin)

## 📄 License

ISC