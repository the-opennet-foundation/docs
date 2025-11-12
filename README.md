# Paxeer Network Documentation

This directory contains the complete documentation for Paxeer Network, converted from the v0-paxeer-network-docs Next.js application into proper MDX format for documentation platforms like Mintlify.

## Conversion Summary

All content from `/root/v0-paxeer-network-docs` has been successfully converted from React/TypeScript components to MDX documentation format with proper:

- ✅ MDX frontmatter with titles, descriptions, and icons
- ✅ Proper code snippets with syntax highlighting
- ✅ Tab groups for multi-language examples
- ✅ Accordion groups for expandable sections
- ✅ Card components for navigation
- ✅ Callout components (Info, Warning, Tip, Note)
- ✅ Step-by-step guides
- ✅ API reference documentation
- ✅ Complete code examples

## Documentation Structure

### Core Documentation

1. **index.mdx** - Home page with network overview and quick navigation
2. **quickstart.mdx** - Getting started guide with wallet setup and wagmi configuration
3. **configuration.mdx** - Network configuration for wagmi, viem, ethers.js, and web3.js
4. **contracts.mdx** - Smart contract deployment with Hardhat, Foundry, and Remix
5. **api-reference.mdx** - Complete JSON-RPC API reference
6. **rpc.mdx** - Interactive RPC method testing guide
7. **examples.mdx** - Code examples for wallet connection, transactions, and contracts
8. **tools.mdx** - SDKs and development tools

### Ecosystem Protocols

9. **paxdex.mdx** - Decentralized exchange protocol documentation
   - REST API endpoints
   - WebSocket integration
   - Smart contract addresses
   - Swap implementation examples

10. **lending.mdx** - Lending protocol documentation
    - API endpoints
    - Smart contract functions
    - Credit scoring system
    - Integration guides

11. **ctm.mdx** - Computable Token Machine documentation
    - Diamond Standard (EIP-2535) implementation
    - Program creation guide
    - Security best practices
    - Advanced examples

12. **blockscout-api.mdx** - BlockScout API documentation
    - Search and discovery
    - Transaction queries
    - Address information
    - Token data
    - Network statistics

## Network Information

- **Chain ID:** 229
- **Currency:** PAX (Paxeer)
- **RPC URL:** https://public-rpc.paxeer.app/rpc
- **Block Explorer:** https://scan.paxeer.app
- **Explorer API:** https://scan.paxeer.app/api

## Key Features Documented

### Developer Tools
- Hardhat configuration and deployment
- Foundry setup and usage
- Remix IDE integration
- wagmi React hooks
- viem TypeScript integration
- ethers.js v6 examples
- web3.js v4 examples

### Protocols
- **PaxDex**: DEX with 0.3% fees, 12 tokens, WebSocket support
- **Lending**: Credit scoring, dynamic APY, multi-asset support
- **CTM**: Revolutionary token standard with modular programs

### APIs
- JSON-RPC Ethereum-compatible API
- PaxDex REST API
- Lending REST API
- BlockScout REST API
- Real-time WebSocket feeds

## MDX Components Used

The documentation uses standard MDX components compatible with Mintlify:

- `<Card>` - Clickable navigation cards
- `<CardGroup>` - Grid layouts for cards
- `<Tabs>` / `<Tab>` - Tabbed content
- `<Accordion>` / `<AccordionGroup>` - Expandable sections
- `<Steps>` / `<Step>` - Step-by-step guides
- `<CodeGroup>` - Multi-language code examples
- `<Info>`, `<Warning>`, `<Tip>`, `<Note>` - Callout boxes
- `<ParamField>` - API parameter documentation

## Code Examples

All code examples include:
- Syntax-highlighted code blocks
- Multiple language versions (TypeScript, JavaScript, Python, Bash)
- Working examples that can be copy-pasted
- Proper error handling
- Best practices

## Notes

- The Smart Library and ERC20 Library pages were originally interactive file browsers, so they weren't converted to static MDX (marked as cancelled in todos)
- The API Explorer was also an interactive tool and wasn't converted (marked as cancelled)
- All static content has been successfully converted with proper formatting
- Code snippets use proper language tags for syntax highlighting
- All network-specific information has been preserved

## Next Steps

To use this documentation:

1. Set up a Mintlify project or similar documentation platform
2. Copy these MDX files to your docs directory
3. Configure your `docs.json` or equivalent navigation file
4. Deploy your documentation

## Original Source

Converted from: `/root/v0-paxeer-network-docs`
- Original format: Next.js/React/TypeScript application
- Converted to: MDX documentation format
- Conversion date: 2025-11-12
