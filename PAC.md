# Contribution Guide

Thank you for your interest in contributing to Wina WebPark IDE! Please read the following guide to learn how to participate.  

##  🚀  Start contributing

1. **Fork Warehouse**
Click the `Fork` button in the upper right corner of the GitHub page to create your copy  

2. **Clone repository**
```bash
git clone  https://github.com/wina005/webpark.git
cd wina-webpark-ide
```

3. **Set up the development environment**
None now.

4. **Create a branch**
```bash
git checkout -b feature/your-feature-name  
```

##  🧪  development process

### Run the project
```bash
Npm install # Install dependencies
Npm run dev # Start development server
```

### Code specifications
- Using ESLint to check code: ` npm run lint `  
- Follow the [JavaScript Style Guide](https://github.com/wina005/webpark/blob/main/docs/STYLE_GUIDE.md)  
- Ensure all tests pass before submission: npm test`  

### Submit changes
```bash
git add .
Git commit - m `type: descriptive information`
git push origin feature/your-feature-name
```

**Submission Information Format**:
```
Feature: Add user authentication function  
Fix: Fix file saving issues  
Docs: Update installation instructions  
Refactor: Refactor editor components  
```

##  🔁  Create Pull Request

1. Visit your fork's GitHub repository  
2. Click on `Compare&Pull Request`  
3. Fill in the PR template:  
- **Describe the problem/function**: Clearly explain the changes made  
- **Associate Issues**: Use `Close # 123` or `Fix # 456`  
- **Screenshot/GIF**: Display visual effects (if applicable)  

##  🐛  Report a Problem

Discovered a bug? Please go through the [Issues page](https://github.com/wina005/webpark/issues) report  
**Please include**:  
1. Detailed reproduction steps  
2. Expected behavior vs actual behavior  
3. Environmental information (browser, OS, version)  
4. Error logs or screenshots  

##  📚  Document contribution
Helping to improve documents is equally important! Please:  
- Fix spelling errors or outdated content  
- Example of adding new features for use  
- Translate documents (create directories such as `docs/korea/`)  

##  💡  Propose new features
1. First, search for similar proposals in Issues to see if they already exist  
2. Create a `Feature Request` issue  
3. Description:  
- Problem solved by functionality  
- Suggested implementation plan  
- Possible alternative solutions  

##  🏷️  Code of Conduct
Please abide by our Code of Conduct (CODE_SOF-CONDUCT. md) and maintain a friendly and inclusive community.  
