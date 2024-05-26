## stprotdam: A Unique Approach to Monetizing AI-Generated Content

### Overview

stprotdam is an innovative platform leveraging the power of AI-generated content (AIGC) and blockchain technology to revolutionize the creation, monetization, and trading of digital assets. By integrating AI models directly into the platform, stprotdam allows users to infer, mint, and trade AIGC NFTs on-chain, ensuring transparent and fair compensation for creators using opML and ERC-7007 standards.

### Key Features

- **Integrated AI Models**: Users can create unique AIGC NFTs directly on the platform.
- **Transparent Compensation**: Utilizing opML and ERC-7007, creators receive fair and transparent payments.
- **Story Protocol IPA**: Provides a seamless registration and licensing process, allowing users to monetize remixes of AIGC NFTs.

### Contract Addresses

### Cross-Chain Integration

**CCIP for Cross-Chain AIGC Prompt Registry and Revenue Sharing:**
- **Sepolia**: 0x0Cb620DD13478ce259705A79e4166a3ab02a3Bbd
- **Mumbai**: 0x54F4Ada25fa21aC2f4C5A63aa692bb1b8CC00952

By creating a prompt registry contract on Sepolia and Mumbai, stprotdam ensures that prompts registered after minting an AIGC NFT are synchronized across both chains. This allows for consistent revenue sharing based on the initial prompt's token ID.

### Monetization with Story Protocol IPA

With Story Protocol IPA, stprotdam offers a streamlined process for registering and licensing AIGC NFTs. This enables users to directly profit from their remixes and original creations, fostering a vibrant ecosystem for AI-driven creativity.

### Text to Video Integration

stprotdam also supports text-to-video functionality, allowing users to generate and upload videos to LivePeer. Here's a sample API call to generate a video:

```bash
curl -X POST http://localhost:9000/genVideo \
-H "Content-Type: application/json" \
-d '{"text": "cat is playing ball"}'
```

### Installation and Deployment

To get started with stprotdam, follow these steps:

1. **Install Dependencies**:
    ```bash
    yarn install
    ```

2. **Deploy Contract**:
    ```bash
    npx hardhat run script/1_deploy_AIGC.cjs --network sepolia
    ```

### Conclusion

stprotdam represents a significant leap forward in the monetization of AI-generated content. By combining advanced AI capabilities with blockchain technology, it provides a fair, transparent, and efficient platform for creators to showcase and profit from their work.