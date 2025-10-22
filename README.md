# ACME Company Documentation Starter Kit

A comprehensive starter kit for building beautiful, functional documentation with Documentation.AI. This starter kit is designed for ACME Company and can be customized for any SaaS product.

## 🚀 What's Included

This starter kit provides a complete documentation foundation with:

### 📖 **Complete Documentation Structure**
- **Getting Started** - Introduction, quickstart, and core concepts
- **Guides** - Installation, configuration, and best practices  
- **Component Examples** - All major Documentation.AI components demonstrated
- **API Reference** - Complete ACME Company API with authentication

### 🎨 **All Major Components Showcased**
- **Text & Formatting** - Typography, lists, and content structure
- **Code Examples** - Syntax highlighting, multiple languages, interactive features
- **Callouts & Alerts** - Information boxes for tips, warnings, and important notes
- **Images & Media** - Optimized images, videos, and responsive media
- **Tables & Lists** - Data presentation and structured information
- **Expandables & Tabs** - Interactive, organized content sections

### 🔧 **Ready-to-Use Configuration**
- **Simplified documentation.json** - Essential navigation and branding
- **SaaS-friendly structure** - Organized for any software product
- **Complete OpenAPI spec** - ACME Company API for demonstration
- **Responsive design** - Works perfectly on all devices

## 📋 Prerequisites

Before using this starter kit, make sure you have:

- A [Documentation.AI account](https://dashboard.documentationai.app/signup)
- Basic familiarity with Markdown (helpful but not required)
- Your brand assets (logo, colors) if you want to customize immediately

## 🎯 Quick Start (2 minutes)

### Option 1: Use with Documentation.AI Web Editor

1. **Create a new project** in your Documentation.AI dashboard
2. **Download this starter kit** as a ZIP file
3. **Upload the contents** to your project using the web editor
4. **Customize** the content for your product
5. **Publish** your documentation

### Option 2: Use with Git Integration

1. **Fork this repository** to your GitHub account
2. **Connect your repository** to Documentation.AI
3. **Customize** the content by editing MDX files
4. **Push changes** to automatically deploy updates

## 📁 Project Structure

```
DocumentationAI-Starter-Kit/
├── 📄 documentation.json          # Site configuration and navigation
├── 📁 getting-started/           # Introduction and onboarding
│   ├── introduction.mdx           # Welcome page and overview
│   ├── quickstart.mdx            # Step-by-step setup guide
│   └── core-concepts.mdx         # Understanding your product
├── 📁 guides/                    # Detailed how-to guides
│   ├── installation.mdx          # Setup and installation
│   ├── configuration.mdx         # Advanced configuration
│   └── best-practices.mdx        # Optimization and tips
├── 📁 components/                # Component demonstrations
│   ├── components-overview.mdx    # Introduction to all components
│   ├── text-and-formatting.mdx   # Typography and structure
│   ├── code-examples.mdx         # Code blocks and highlighting
│   ├── callouts-and-alerts.mdx   # Information boxes
│   ├── images-and-media.mdx      # Visual content
│   ├── tables-and-lists.mdx      # Data presentation
│   └── expandables-and-tabs.mdx  # Interactive content
├── 📁 api-reference/             # API documentation
│   ├── petstore-openapi.yaml     # Complete OpenAPI specification
│   ├── authentication.mdx        # API authentication guide
│   └── getting-started.mdx       # First API calls tutorial
└── 📄 README.md                  # This file
```

## ⚙️ Customization Guide

### 1. Update Basic Information

**Edit `documentation.json`** to match your product:

```json
{
  "name": "Your Product Name",           // Update with your product name
  "logo-light": "your-logo-url",         // Add your logo URLs
  "logo-dark": "your-logo-dark-url",
  "colors": {
    "light": { "brand": "#your-color" }, // Your brand colors
    "dark": { "brand": "#your-dark-color" }
  },
  "navbar": {
    "actions": {
      "primary": {
        "title": "Get Started",
        "link": "https://your-app.com/signup"  // Your signup URL
      }
    }
  }
}
```

### 2. Replace Placeholder Content

**Update these key files first**:

- `getting-started/introduction.mdx` - Replace with your product introduction
- `getting-started/quickstart.mdx` - Update with your actual setup process
- `api-reference/` - Replace Pet Store API with your actual API (or remove if not applicable)

**Find and replace these placeholders throughout**:
- `Your SaaS Product` → Your actual product name
- `acme.com` → Your actual domain
- `support@acme.com` → Your support email
- Example URLs and API endpoints → Your actual endpoints

### 3. Customize Navigation

**Modify the navigation structure** in `documentation.json` to match your needs:

```json
{
  "navigation": {
    "tabs": [
      {
        "tab": "Documentation",
        "groups": [
          // Add, remove, or modify groups as needed
          {
            "group": "Your Section Name",
            "pages": [
              // Your pages here
            ]
          }
        ]
      }
    ]
  }
}
```

### 4. Add Your Branding

- **Upload your logos** (recommended: 200x50px for main logo, 32x32px for favicon)
- **Update brand colors** in the configuration
- **Replace placeholder images** with your actual screenshots and diagrams
- **Customize the favicon** and meta tags

## 🎨 Component Examples

This starter kit demonstrates every major Documentation.AI component:

### 📝 Content Components
```jsx
<Callout kind="info">
  Important information for your users
</Callout>

<Expandable title="Click to expand">
  Hidden content that users can reveal
</Expandable>
```

### 💻 Code Components
```jsx
<CodeGroup tabs="JavaScript,Python,cURL">
// Multi-language code examples
</CodeGroup>
```

### 📊 Data Components
- **Tables** for structured data and comparisons
- **Lists** for features, steps, and options
- **Parameter documentation** for API references

### 🖼️ Media Components
- **Responsive images** with optimization
- **Video embedding** from popular platforms
- **Interactive demos** and prototypes

## 🔧 Advanced Features

### API Documentation

The included Pet Store API demonstrates:

- **Complete OpenAPI 3.0 specification** with all major features
- **Authentication examples** (API keys and JWT tokens)  
- **Comprehensive endpoint documentation** with request/response examples
- **Multi-language code samples** for easy integration
- **Error handling** and status code documentation

### Interactive Elements

- **Expandable sections** for organizing complex information
- **Tabbed interfaces** for multi-format content
- **Collapsible FAQ sections** for support content
- **Progressive disclosure** patterns for better UX

### Content Patterns

Examples of effective documentation patterns:
- **Step-by-step tutorials** with visual guidance
- **Troubleshooting guides** with common solutions
- **Feature comparisons** with decision-making tables
- **Migration guides** for existing users

## 🚀 Deployment Options

### Documentation.AI Hosting (Recommended)

1. **Push to Git** or upload via web editor
2. **Configure custom domain** (optional)
3. **Automatic SSL** and global CDN included
4. **Zero configuration** required

**Your site will be available at**: `https://your-project.documentationai.io`

### Custom Deployment

For self-hosting or custom infrastructure:

1. **Export your site** from Documentation.AI
2. **Deploy to any static hosting** (Netlify, Vercel, S3, etc.)
3. **Configure your build process** as needed
4. **Set up custom analytics** and monitoring

## 📚 Learning Resources

### Documentation.AI Resources

- **[Official Documentation](https://docs.documentationai.com)** - Complete platform guide
- **[Component Reference](https://docs.documentationai.com/components)** - All available components
- **[API Documentation](https://docs.documentationai.com/api)** - Platform API reference
- **[Community Forum](https://community.documentationai.com)** - Get help and share tips

### Best Practices from this Kit

- **Progressive disclosure** - Start simple, add detail in expandables
- **Consistent formatting** - Use the same patterns throughout
- **Visual hierarchy** - Clear headings and scannable structure  
- **Practical examples** - Always show real-world usage
- **Multiple formats** - Code examples in multiple languages

## 🤝 Contributing

Want to improve this starter kit? We welcome contributions!

### How to Contribute

1. **Fork this repository**
2. **Create a feature branch** (`git checkout -b improve-api-examples`)
3. **Make your changes** and test thoroughly
4. **Submit a pull request** with a clear description

### What We're Looking For

- **Additional component examples** and use cases
- **Improved content patterns** and templates
- **Better placeholder content** that's more universally applicable
- **Bug fixes** and typo corrections
- **Performance improvements** and optimizations

## 🐛 Issues and Support

### Common Issues

**Problem: Images not displaying**
- Solution: Ensure image URLs are absolute and accessible
- Upload images through Documentation.AI editor for automatic optimization

**Problem: Navigation not working**  
- Solution: Check that all file paths in `documentation.json` match actual files
- Ensure MDX files have proper frontmatter

**Problem: Components not rendering**
- Solution: Verify component syntax matches the examples exactly
- Check for missing closing tags or incorrect prop names

### Getting Help

- **[GitHub Issues](https://github.com/documentationai/starter-kit/issues)** - Report bugs or request features
- **[Documentation.AI Support](mailto:support@documentationai.app)** - Platform-specific help
- **[Community Discord](https://discord.gg/documentationai)** - Chat with other users
- **[Example Repository](https://github.com/documentationai/examples)** - More example implementations

## 📄 License

This starter kit is released under the MIT License. Feel free to use it for any project, commercial or personal.

## 🙏 Acknowledgments

Created by the Documentation.AI team with contributions from the community. Special thanks to all the teams who provided feedback and real-world usage examples.

---

## 🎉 Ready to Build Amazing Documentation?

1. **[Download this starter kit](https://github.com/documentationai/starter-kit/archive/main.zip)**
2. **[Sign up for Documentation.AI](https://dashboard.documentationai.app/signup)** if you haven't already
3. **[Join our community](https://community.documentationai.com)** to connect with other documentation creators
4. **Start building!** Your users will thank you for clear, beautiful documentation

**Questions?** Reach out to us at [hello@documentationai.app](mailto:hello@documentationai.app) or start a conversation in our [community forum](https://community.documentationai.com).

Happy documenting! 📚✨
