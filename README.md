# Cover Whale Claude Code Guide

🐋 **Internal Documentation for Claude Code at Cover Whale**

A comprehensive guide to mastering Claude Code for Cover Whale team members. From first-time setup to advanced automation workflows—everything you need to supercharge your productivity with AI-assisted development.

## 🌐 Live Guide

Visit the guide at: **[https://dmedina5.github.io/CW-Claude-Code-Guide/](https://dmedina5.github.io/CW-Claude-Code-Guide/)**

## 🔐 Authentication

This guide is **restricted to CoverWhale team members only**. Authentication is enforced via Google OAuth:

- ✅ Only `@coverwhale.com` email addresses can access
- 🔒 Authentication backend: [https://coverwhale-auth.vercel.app](https://coverwhale-auth.vercel.app)
- 🚀 Automatic redirect to Google sign-in for unauthorized users

## 📚 What's Inside

- **Quick Start Guide** - For new users getting started with Claude Code
- **Mental Model** - Understanding how Claude Code really works
- **Foundational Setup** - CLAUDE.md, slash commands, context hygiene
- **Claude-Specific Tips** - Prompt patterns and best practices
- **Cover Whale Use Cases** - Insurance-specific workflows and examples
- **Common Failure Modes** - What goes wrong and how to fix it
- **Workflow Frameworks** - Advanced patterns for maximum productivity
- **Advanced Techniques** - Headless automation, MCP, parallel instances

## 🛠️ Tech Stack

- **Authentication**: Custom Google OAuth with CoverWhale domain restriction
- **Hosting**: GitHub Pages
- **Design**: Custom CSS with Cover Whale branding
- **Source**: Adapted from "Mastering Claude Code" by Devansh

## 📝 Attribution

This guide is adapted from the original "Mastering Claude Code" by [Devansh](https://artificialintelligencemadesimple.substack.com/) (Chocolate Milk Cult Newsletter), enhanced and customized for Cover Whale's team with:

- Additional beginner content and installation guides
- Cover Whale-specific use cases and examples
- Internal branding and styling
- Authentication for internal access only

## 🚀 Local Development

To run locally:

```bash
# Clone the repository
git clone git@github.com:dmedina5/CW-Claude-Code-Guide.git
cd CW-Claude-Code-Guide

# Open in browser
open index.html
# or
python3 -m http.server 8000
```

**Note**: Authentication will work on GitHub Pages but not on localhost (unless you update the auth.js redirect URI).

## 📄 Repository Structure

```
CW-Claude-Code-Guide/
├── index.html          # Main guide HTML with authentication
├── auth.js             # Google OAuth authentication logic
└── README.md           # This file
```

## 🔧 Maintenance

- **Owner**: Daniel Medina (daniel.medina@coverwhale.com)
- **Last Updated**: January 2026
- **Updates**: Pull requests welcome from CoverWhale team members

## 📞 Support

- **Questions about Claude Code?** Reach out to IT Support or your team lead
- **Feedback on this guide?** Contact the Core Systems team
- **Authentication issues?** Email daniel.medina@coverwhale.com

## 📖 Additional Resources

- [Official Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code)
- [Claude.ai Help Center](https://support.anthropic.com)
- [Anthropic News & Updates](https://www.anthropic.com/news)

---

**Internal Use Only** • Cover Whale Insurance • 2026
