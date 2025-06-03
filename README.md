# sb-themes

A styling library for Sunbird projects that provides SCSS components and stylesheets.

### Local Development

1. Fork the repository on GitHub

2. Clone your fork:

``` 
 git clone https://github.com/your-username/sb-themes.git

cd sb-themes
```
3. Install dependencies:

```
npm i 
```

### This project uses GitHub Actions for automated builds and security scanning.

## PR Build
1. Performs static code analysis with CodeQL for security vulnerabilities

### How It Works

When a PR is opened, the workflow:

1. Sets up the Node.js environment
1. Installs dependencies
1. Runs security scans

## Release process

### Prerequisite
- Set the `NPM_TOKEN` secret in your GitHub repository settings

When tags are pushed, the workflow automatically:

- Publishes to NPM registry

## Link