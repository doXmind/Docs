# DocMindLLM Documentation

This repository contains the official documentation for DocMindLLM, built with [Mintlify](https://mintlify.com).

## 🚀 Getting Started

### Prerequisites

- Node.js 18.x or higher
- npm or yarn

### Installation

```bash
# Install Mintlify CLI
npm i -g mintlify

# Clone this repository
git clone https://github.com/docmindllm/docs.git
cd docs

# Start the development server
mintlify dev
```

The documentation will be available at `http://localhost:3000`.

## 📁 Project Structure

```
.
├── mint.json              # Mintlify configuration
├── introduction.mdx       # Homepage
├── quickstart.mdx        # Getting started guide
├── development.mdx       # Development guide
├── essentials/           # Core documentation
│   ├── markdown.mdx
│   ├── code.mdx
│   └── ...
├── api-reference/        # API documentation
│   ├── introduction.mdx
│   └── endpoint/
│       ├── create.mdx
│       ├── get.mdx
│       └── ...
└── logo/                 # Logo assets
```

## 🎨 Customization

### Theme Configuration

Edit `mint.json` to customize:
- Colors and branding
- Navigation structure
- Social links
- API settings

### Adding New Pages

1. Create a new `.mdx` file in the appropriate directory
2. Add frontmatter with title and description
3. Update the navigation in `mint.json`

## 🚀 Deployment

### Mintlify Hosting

The easiest way to deploy is using Mintlify's hosting:

```bash
# Deploy to Mintlify
mintlify deploy
```

### Custom Domain

1. Add your custom domain in the Mintlify dashboard
2. Update DNS records as instructed
3. SSL certificates are automatically provisioned

### Self-Hosting

You can also build and host the documentation yourself:

```bash
# Build static files
mintlify build

# The output will be in the .mintlify/dist directory
```

## 📝 Writing Documentation

### Markdown Features

Mintlify supports:
- Standard Markdown syntax
- MDX components
- Code blocks with syntax highlighting
- Custom components (Cards, Tabs, etc.)

### Best Practices

1. Use clear, descriptive titles
2. Include code examples
3. Add helpful descriptions
4. Use components for better UX
5. Keep content up-to-date

## 🤝 Contributing

We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This documentation is licensed under the MIT License.

## 🔗 Links

- [DocMindLLM Website](https://docmindllm.com)
- [API Status](https://status.docmindllm.com)
- [Support](mailto:support@docmindllm.com)