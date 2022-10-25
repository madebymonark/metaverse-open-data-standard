# metaverse-open-data-standard
**M.O.D.S is a public and open Metaverse Metadata Standard developed by Monark Market to help Metaverse NFT Creators more easily categorize their work for discoverability.**

Intended to be used inside Metaverse Marketplaces or to prepare Metaverse Assets for secondary markets, M.O.D.S is designed to be general, expandable, and flexible as more parties become part of the Metaverse conversation and clearer standards are defined.

To use M.O.D.S., simply integrate some or all of the metadata traits listed below while minting your NFTs. The more creators who integrate similar metadata into their NFT assets, the more likely those traits will be integrated into marketplace or application searches, increasing the likelihood of them being found and creating a better discovery experience for consumers.

We'll discuss each section of metadata below and their associated attributes. The full standard is available from this repo in multiple formats, so feel free to use whichever makes it easier to integrate into your workflow.

Interested in helping to expand M.O.D.S.? Join the conversation in our Discord - https://discord.gg/CEXW9vtgkz - or submit a Pull Request from this repo.

## Metadata

| Attributes | Values[Format] | Description |
| ------ | ------ | ------ |
| Creator | [Name] | The name of the artist or creator of the given asset |
| Publisher | [Name] | The name of the marketplace or toolset that initially minted the collection, i.e. "Monark Market" or "Manifold Studio" |
| License | [Name] | Designed for future flexibility, this allows the creator to name and link to the end user license given to the owner of this asset. Printed to the Blockchain, this will help make these licenses more enforceable as the are publicly discoverable by secondary marketplaces.
| License URL | [URL] | A URL that points to a public permalink for the selected license. |
| Website URL | [URL] | A URL that points to more information about the asset or collection as a whole. This can be the creator's website or a link to the marketplace listing from which they were originally minted|
| Asset URL | [URL] | A URL that points to an token-gated unlockable asset portal where a user can unlock additional content with the NFT|
| Cagetgory | - Animals & Creatures<br /> - Architecture & Environments<br /> - Art & Abstract<br /> - Cars & Vehicles<br /> - Characters & People<br /> - Electronics & Gadgets<br /> - Fashion & Style<br /> - Food & Drink<br /> - Furniture & Home<br /> - History & Heritage<br /> - Music & Events<br /> - Nature & Plants<br /> - News & Politics<br /> - Science & Technology<br /> - Sports & Fitness<br /> - Weapons & Military | An initial broad categorization of the asset this NFT houses, further refined by "Type" in the next property|
| Type | - Environment<br /> - Object<br /> - Skybox<br /> - Kit<br /> - Bundle<br /> - Wearable<br /> - Furniture<br /> - Avatar | A specific categorization of the usage of the asset within the Metaverse |
| File Type | - GLB<br /> - GLTF<br /> - FBX<br /> - Blend<br /> - Unity<br /> - Zip<br /> - Jpg<br /> - Png<br /> - Mp4<br /> - Multi-File  | A specific categorization of the underlying asset(s) this NFT represents |
| Compatibility | - Spatial<br /> - Mona<br /> - OnCyber<br /> - Decentraland<br /> - The Sandbox<br /> - Voxels<br /> - Somnium Space<br />- NFT Worlds<br /> - VR Chat<br /> - Unreal Engine 5<br /> - Nvidia Omniverse<br /> - Unity<br />| A description of which platforms or metaverses this asset is compatible with. This will be an ever expanding list, and may evolve into compatibility standards in the future. For now, we suggest simply naming the platform(s) |
| File Size | - 1 - 50mb<br /> - 51 - 100mb<br /> - 101 - 500mb<br /> - 500mb+ | The size of the underlying asset(s) represented by this NFT |

## How to use M.O.D.S.

M.O.D.S. is at it's simplset form a suggested collection of metadata properties and attributes you can utilize when minting your NFTs. You're always welcome to add more properties to your specific NFTs. Our hope is that by more people using the properties within M.O.D.S., the data that backs the metaverse will be easier to filter, sort, and use.


If you're a developer, we've included a JSON file you can use as your base metadata that includes all current properties. 

If you're minting your NFTs on a marketplace like OpenSea or Monark Market, simply enter your metadata in the appropriate fields in the NFT creation screen, making sure to not mispell the properties or attributes so they will match all other NFTs using the standard.

For some metadata attributes, if you would like to select multiple values (i.e. compatible with Spatial and OnCyber), simple add the attribute to your NFT multiple times with a different value for the same property.
