# Claude Chroma Marketplace

Official plugin marketplace for [Claude Chroma](https://github.com/bradleytangonan/claude-chroma) - ChromaDB MCP server management for Claude Code.

## Installation

**Step 1: Add this marketplace**
```bash
/plugin marketplace add bradleytangonan/claude-chroma-marketplace
```

**Step 2: Install Claude Chroma plugin**
```bash
/plugin install claude-chroma@claude-chroma-marketplace
```

That's it! You can now use `/chroma:setup`, `/chroma:validate`, `/chroma:migrate`, and `/chroma:stats`.

## Available Plugins

### Claude Chroma

**ChromaDB MCP server management plugin with path validation, migration utilities, and best practices enforcement.**

**Commands:**
- `/chroma:setup` - Set up ChromaDB MCP server for your project
- `/chroma:validate` - Validate ChromaDB paths and configuration
- `/chroma:migrate` - Migrate ChromaDB data from external volumes to local storage
- `/chroma:stats` - Show ChromaDB statistics and collection info

**Features:**
- ✅ Automated Setup - Quick ChromaDB MCP configuration
- 🔍 Path Validation - Detect and prevent path issues from external volumes
- 🚚 Data Migration - Safely move ChromaDB data from external drives
- 📊 Statistics Dashboard - Monitor collections and storage usage
- 🛡️ Pre-Tool Hooks - Automatic path validation before operations

**Repository:** https://github.com/bradleytangonan/claude-chroma
**Version:** 1.0.0
**License:** MIT

## About

This marketplace provides easy access to the Claude Chroma plugin ecosystem. More plugins coming soon!

## Support

- 🐛 **Issues**: [GitHub Issues](https://github.com/bradleytangonan/claude-chroma/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/bradleytangonan/claude-chroma/discussions)

---

**Made with ❤️ for the Claude Code community**
