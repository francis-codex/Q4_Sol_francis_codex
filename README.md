# Q4_Sol_francis_codex

My work from the Turbin3 Q4 2024 Solana cohort, in TypeScript and Rust.

## `ts/cluster1`

- **SPL tokens:** `spl_init.ts`, `spl_mint.ts`, `spl_metadata.ts`, `spl_transfer.ts`: create a mint, mint supply, attach Metaplex metadata, transfer.
- **NFTs:** `nft_image.ts`, `nft_metadata.ts`, `nft_mint.ts`: upload an image and metadata, then mint the NFT.
- **Vault program:** `vault_init.ts`, `vault_deposit.ts`, `vault_deposit_spl.ts`, `vault_deposit_nft.ts`, `vault_close.ts`: drive an Anchor vault that holds SOL, SPL tokens and NFTs.

## `rs`

Rust versions of the prerequisites (`prereqs.rs`) and cluster work (`cluster1.rs`), with the program bindings in `src/programs`.

Stack: `@solana/web3.js`, `@solana/spl-token`, Metaplex, Anchor, Rust. Devnet.
