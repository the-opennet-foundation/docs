# Paxeer Network Documentation

Professional documentation for Paxeer Network, built with [Mintlify](https://mintlify.com) framework inspired by [Optimism's documentation structure](https://github.com/ethereum-optimism/docs).

## 🚀 Quick Start

```bash
# Install Mintlify CLI
npm install -g mintlify

# Preview documentation locally
mintlify dev

# Build for production
mintlify build
```

## 📁 Documentation Structure

### Core Documentation (Root Level)

```
/root/docs/
├── index.mdx                    # Home page
├── quickstart.mdx              # Getting started guide
├── configuration.mdx           # Network configuration
├── contracts.mdx               # Smart contracts guide
├── api-reference.mdx           # JSON-RPC API reference
├── rpc.mdx                     # RPC methods testing
├── examples.mdx                # Code examples
├── tools.mdx                   # SDKs and tools
├── paxdex.mdx                 # PaxDex protocol
├── lending.mdx                # Lending protocol
├── ctm.mdx                    # Computable Token Machine
├── blockscout-api.mdx         # BlockScout API
└── docs.json                  # Mintlify configuration
```

### App Developers Section

```
app-developers/
├── guides/
│   ├── building-apps.mdx              # Development guide
│   ├── testing-apps.mdx               # Testing best practices
│   └── transactions/
│       ├── fees.mdx                   # Fee structure
│       ├── estimates.mdx              # Cost estimation
│       ├── parameters.mdx             # Gas parameters
│       ├── statuses.mdx               # Transaction states
│       └── troubleshooting.mdx        # Common issues
└── [tutorials, reference folders ready for expansion]
```

### Node Operators Section

```
node-operators/
└── guides/
    └── running-a-node.mdx             # Node setup guide
```

### Concepts Section

```
concepts/
├── architecture/
│   └── overview.mdx                   # Architecture overview
├── security/
│   └── best-practices.mdx             # Security guide
└── transactions/
    └── transaction-flow.mdx           # Transaction lifecycle
```

## 🎨 Framework Features

Based on [Optimism's Professional Documentation](https://docs.optimism.io):

### Mintlify Features
- ✅ **Multi-tab navigation** - Organized by user type
- ✅ **Global anchors** - Quick access to key resources
- ✅ **Feedback system** - Thumbs rating, suggest edits, raise issues
- ✅ **SEO optimization** - Complete meta tags and social cards
- ✅ **Dark/Light mode** - Automatic theme switching
- ✅ **Search** - Full-text documentation search
- ✅ **Code groups** - Multi-language examples
- ✅ **Interactive components** - Tabs, accordions, cards
- ✅ **Contextual AI** - ChatGPT and Claude integration

### Custom Configuration
- **Brand Colors:** Orange/Red theme (`#FF4500`)
- **Dark Mode Default:** Optimized for developer experience
- **Social Links:** Discord, Twitter, GitHub
- **Global Anchors:** Explorer, PaxDex, Faucet, Status
- **Primary CTA:** "Get Started" button
- **Top Bar:** GitHub link + Launch App button

## 📚 Documentation Coverage

### ✅ Complete Pages (24 total)

#### Getting Started
1. **index.mdx** - Network overview with navigation
2. **quickstart.mdx** - Step-by-step setup guide

#### Core Documentation
3. **configuration.mdx** - wagmi, viem, ethers.js, web3.js
4. **contracts.mdx** - Hardhat, Foundry, Remix deployment
5. **api-reference.mdx** - Complete JSON-RPC API
6. **rpc.mdx** - RPC method testing guide
7. **examples.mdx** - Integration examples
8. **tools.mdx** - Development tools & SDKs

#### Ecosystem Protocols
9. **paxdex.mdx** - DEX protocol (REST + WebSocket)
10. **lending.mdx** - Lending protocol with credit scoring
11. **ctm.mdx** - Computable Token Machine guide
12. **blockscout-api.mdx** - Explorer API documentation

#### App Developer Guides
13. **app-developers/guides/building-apps.mdx**
14. **app-developers/guides/testing-apps.mdx**
15. **app-developers/guides/transactions/fees.mdx**
16. **app-developers/guides/transactions/estimates.mdx**
17. **app-developers/guides/transactions/parameters.mdx**
18. **app-developers/guides/transactions/statuses.mdx**
19. **app-developers/guides/transactions/troubleshooting.mdx**

#### Node Operators
20. **node-operators/guides/running-a-node.mdx**

#### Concepts
21. **concepts/architecture/overview.mdx**
22. **concepts/security/best-practices.mdx**
23. **concepts/transactions/transaction-flow.mdx**

#### Configuration
24. **docs.json** - Complete Mintlify configuration

## 🎯 Navigation Structure

### Tab 1: App Developers
- **Getting Started** → index, quickstart
- **Guides** → building-apps, testing-apps, transactions (5 pages)
- **Core Documentation** → configuration, contracts, api-reference, rpc
- **Code Examples** → examples, tools

### Tab 2: Ecosystem
- **Protocols** → PaxDex, Lending, CTM
- **APIs** → BlockScout API

### Tab 3: Node Operators
- **Guides** → Running a node

### Tab 4: Concepts
- **Architecture** → Overview
- **Security** → Best practices
- **Transactions** → Transaction flow

## 🔧 Technical Specifications

### Network Details
- **Chain ID:** 229
- **Currency:** PAX (Paxeer)
- **Block Time:** ~2 seconds
- **Gas Limit:** 30,000,000
- **RPC URL:** https://public-rpc.paxeer.app/rpc
- **Explorer:** https://scan.paxeer.app

### Ecosystem
- **PaxDex:** DEX with 0.3% fees, 12 tokens, WebSocket support
- **Lending:** Credit scoring, dynamic APY, multi-asset
- **CTM:** Diamond Standard (EIP-2535) token implementation

## 📖 Content Features

### MDX Components Used
- `<Card>` / `<CardGroup>` - Navigation and feature cards
- `<Tabs>` / `<Tab>` - Multi-framework examples
- `<Accordion>` / `<AccordionGroup>` - Expandable content
- `<Steps>` / `<Step>` - Step-by-step guides
- `<CodeGroup>` - Multi-language code examples
- `<Info>`, `<Warning>`, `<Tip>`, `<Note>` - Callouts
- `<ParamField>` - API parameter documentation

### Code Examples Coverage
- ✅ TypeScript / JavaScript
- ✅ Python
- ✅ Bash / cURL
- ✅ Solidity
- ✅ ethers.js v6
- ✅ viem
- ✅ wagmi
- ✅ web3.js v4

### Documentation Quality
- ✅ Proper frontmatter (title, description, icon)
- ✅ Syntax highlighting
- ✅ Working code examples
- ✅ Error handling examples
- ✅ Best practices sections
- ✅ Troubleshooting guides
- ✅ Cross-references
- ✅ External resource links

## 🚀 Deployment

### Deploy to Mintlify

1. **Connect Repository:**
   ```bash
   # Push to GitHub
   git init
   git add .
   git commit -m "Initial Paxeer Network documentation"
   git remote add origin https://github.com/yourusername/paxeer-docs
   git push -u origin main
   ```

2. **Link to Mintlify:**
   - Go to [mintlify.com](https://mintlify.com)
   - Connect your GitHub repository
   - Auto-deploy on push

3. **Custom Domain (Optional):**
   - Configure in Mintlify dashboard
   - Point DNS to Mintlify
   - Example: `docs.paxeer.app`

### Local Development

```bash
# Install dependencies
npm install -g mintlify

# Run dev server
mintlify dev

# Open browser
open http://localhost:3000
```

## 📝 Content Sources

### Converted from v0-paxeer-network-docs
- Original: Next.js/React application
- Converted: 12 core MDX pages
- Format: Proper MDX with code snippets

### Inspired by Optimism Docs
- Framework: Professional Mintlify structure
- Navigation: Multi-tab organization
- Content: Technical depth and quality
- Components: Rich MDX components

## 🎨 Customization

### Colors
Primary: `#FF4500` (Orange-Red)
Light: `#FF6B35`
Dark: `#E63E00`

### Branding
- Logo: `/logo/light.svg` and `/logo/dark.svg`
- Favicon: `/favicon.svg`
- OG Image: `/og-image.png`

## 📊 Analytics

Add your analytics IDs in `docs.json`:

```json
"analytics": {
  "ga4": {
    "measurementId": "G-XXXXXXXXXX"
  },
  "mixpanel": {
    "projectToken": "your_token_here"
  }
}
```

## 🔗 Important Links

- **Website:** https://paxeer.app
- **Explorer:** https://scan.paxeer.app
- **RPC:** https://public-rpc.paxeer.app/rpc
- **Discord:** https://discord.gg/paxeer
- **GitHub:** https://github.com/paxeer

## 📄 License

MIT License - See LICENSE file for details

## 🤝 Contributing

Contributions welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Add/update documentation
4. Test locally with `mintlify dev`
5. Submit a pull request

## 📞 Support

- **Discord:** [discord.gg/paxeer](https://discord.gg/paxeer)
- **GitHub Issues:** [github.com/paxeer/docs/issues](https://github.com/paxeer/docs/issues)
- **Email:** support@paxeer.app

---

**Built with ❤️ by the Paxeer team**

**Framework:** Inspired by [Optimism Docs](https://github.com/ethereum-optimism/docs) • **Platform:** [Mintlify](https://mintlify.com)
