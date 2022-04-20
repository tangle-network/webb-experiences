<h1 align="center">Webb Product Stack 🚀🚀</h1>
<div align="center">
<a href="https://www.webb.tools/">
    <img alt="Webb Logo" src="./assets/webb-icon.svg" width="15%" height="30%" />
  </a>
  </div>
<div align="center">
  <strong>Open Product Development</strong>
</div>
<div align="center">
  A repo dedicated to Webb's product stack.
</div>

<!-- Social links -->
<div align="center">
  <h3>
    <a href="https://www.webb.tools/">
      Website
    </a>
    <span> | </span>
    <a href="http://docs.webb.tools/">
      Docs
    </a>
    <span> | </span>
    <a href="https://discord.com/invite/cv8EfJu3Tn">
      Discord
    </a>
        <span> | </span>
    <a href="https://t.me/webbprotocol">
      Telegram
    </a>
      <span> | </span>
    <a href="https://twitter.com/webbprotocol">
      Twitter
    </a>
    <span> | </span>
    <a href="https://github.com/webb-tools/webb-experiences/blob/main/.github/CONTRIBUTING.md">
      Contributing
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->
<h2 id="table-of-contents"> Table of Contents 📖</h2>

<details open="open">
  <summary>Table of Contents</summary>
  <ul>
    <li><a href="#start"> Overview</a></li>
    	<ul>
        <li><a href="#repo">Repo structure</a></li>
		  </ul>
    <li><a href="#vision">Product Vision</a></li>
      <ul>
        <li><a href="#board">Vision Board</a></li>
		  </ul>
    <li><a href="#map"> Product Roadmap</a></li>
      <ul>
        <li><a href="#guide">Roadmap Guide</a></li>
		  </ul>
    <li><a href="#contribute">Contributing</a></li>
</details>

<h2 id="start"> Overview </h2>

Webb's software is open-source by default so should its product development. This repo aims to  provide transparency, promote community collaboration, and gather immediate feedback throughout Webb's product stack development lifecycle. In this repo you will find a collection of product related material, illustrations, documents, and analysis.

We are motivated to build amazing products for our community, to deliver a seamless experience and to deeply understand our users needs. This is a dedicated space aimed at achieving those goals, where users can provide feedback, inspiration, and even contribute to Webb's product stack.

Have feedback on how to improve Webb's products? Or have a specific question to ask? Checkout the [Webb Feedback Discussions](https://github.com/webb-tools/feedback/discussions) 💬.

<h3 id="repo"> Repo structure 🏢 </h3>

The content of this repo is divided by individual product categories. Currently, the products described in this repo include the following:
- **Anchor Protocol:** A private bridge protocol 
- **DKG:** A distributed key generation protocol

```
├── anchor-protocol/
│   ├── feature-requests
│   │    └── .. 
│   ├── user-maps
│   │    └── ..   
│   └── user-stories
│        └── ..
├── bridge-alternatives/
├── dapp-designs/
├── dkg/
│   ├── feature-requests
│   │    └── .. 
│   ├── user-maps
│   │    └── ..   
│   └── user-stories
│        └── ..
└──product-ideas/
```

| Directories           | Description                                                      |
| --------------------- | ---------------------------------------------------------------- |
| `bridge-alternatives` | Product substitutes for transferring assets                      |
| `dapp-designs`        | Planned designs for Webb's Dapp                                  |
| `feature-requests`    | Desirable product enhancements that require further planning     |
| `product-ideas`       | Blue ocean ideas to further the Webb ecosystem                   |
| `user-maps`           | Visual illustrations of a user's experience with Webb's products |
| `user-stories`        | Descriptive product outcomes from an end users perspective       |

<h2 id="vision"> Webb Ecosystem Vision 👓 </h2>

The vision for the Webb ecosystem is to empower developers to build interoperable privacy preserving applications with incredible ease. To achieve this vision we have built a private bridge system called the
Webb Anchor Protocol.  

The intended purpose of the Webb Anchor Protocol is to enable developers to build their own cross-chain, zero-knowledge applications on top of. The first application of this kind is Webb's transfer asset protocol which allows users to move private assets across EVM and Substrate chains using zero-knowledge proofs and a configurable token re-wrapping system. We intend to support additional chains to extend users ability to privately move assets in the future.

<h3 id="board"> Product Vision Board - Webb Anchor Protocol </h3>

The below table concisely outlines the product vision for Webb's Anchor Protocol. It's intended purpose is to simplify communicating the desirable outcome for the Webb Anchor Protocol product, as well as, motivate, and inspire development teams, users, and additional stakeholders.

<table>
    <thead>
        <tr>
            <td colspan=4><b>👁️‍🗨️ Product Vision</b></br> To empower developers to build interoperable privacy preserving applications with incredible ease. 
        </tr>
    </thead>
</table>

<table>
  <tr style="align=center;">
    <th>🎯 Target Group</th>
    <th>❤️ Needs</th>
    <th>🖥️ Product</th>
    <th>💰 Business Goals</th>
  </tr>
  <tr>
    <td>The primary target audience are developers. </td>
    <td>Easily create applications that are cross-chain and private by default.</td>
    <td>Product will provide support for multiple chain implementations, and a zero-knowledge system to enable private cross-chain messaging.</td>
    <td>The primary business goal is to build and foster applications on top of the Anchor Protocol. Proving out the system, and its convenient usage for other development teams..</td>
  </tr>
</table>

<h2 id="map"> Product Roadmap 🛣️ </h2>

❇️ View the [official Webb public product roadmap](https://github.com/orgs/webb-tools/projects/8/views/3)

The roadmap offers insight and visibility into our plan of action for each 'area' that makes up the Webb ecosystem, outlines future product functionality that we are considering, and a very rough estimation on new feature releases. Have any questions or comments about items on the roadmap? Share your feedback via [Webb public feedback discussions](https://github.com/webb-tools/feedback/discussions). 

<h3 id="guide"> Guide to the roadmap </h3>

Every item on the roadmap is an issue, with a label that indicates each of the following:

- A **release phase** that describes the next expected phase of the roadmap item. See below for a guide to release phases. 

- A **product area** that indicates the area of the product to which the item belongs. For a list of current product areas, see below.

- Once a feature is delivered, the **shipped** label will be applied to the roadmap issue and the issue will be closed with a comment linking to the relevant closed PR.

#### Release phases

Release phases indicate the stages that the product or feature goes through, from early testing to public availability.

- **alpha:** *Primarily for testing and feedback*\
Features still under heavy development, and subject to change. Not for production use, and no documentation, or support provided.

- **beta:** *Publicly available in full or limited capacity*\
Features mostly complete and documented. Minor fixes may be required, but available for public usage.

- **in design:**\
Feature in discovery phase. We have decided to build this feature, but are still in the process of planning, creating a specification, checklist or need to triage resources.

- **exploring:**\
Feature under consideration. We are considering building this feature, and gathering feedback and research on it.

#### Roadmap stages

The roadmap is arranged on a project board to give a sense for how far out each item is on the horizon. Every product or feature is added to a particular project board column according to the quarter in which it is expected to ship next. Be sure to read the [disclaimer](#disclaimer) below since the roadmap is subject to change, especially further out on the timeline.
### Product Areas

The following is a list of our current product areas:

- **dkg:** Distributed Key Generation Protocol ([repo](https://github.com/webb-tools/dkg-substrate))
- **webb-dapp:** Front-end for Webb Protocol ([repo](https://github.com/webb-tools/webb-dapp))
- **api:** API for interface and developer usage ([repo](https://github.com/webb-tools/webb.js))
- **protocol:** Contract implementations ([solidity](https://github.com/webb-tools/protocol-solidity), [substrate](https://github.com/webb-tools/protocol-substrate), [coswmwam](https://github.com/webb-tools/protocol-cosmwasm))
- **relayer:** Webb relayer network ([repo](https://github.com/webb-tools/relayer))
- **zk:** Zero knowledge system ([repo](https://github.com/webb-tools/arkworks-gadgets))


<h2 id="contribute"> Contributing ✍️  </h2>

Interested in contributing to the future of Webb products? Thank you so much for your interest! We are always looking for improvements to our product planning, analysis, strategies and contributions from open-source community are greatly appreciated.

If you have a contribution in mind, please check out our [Contribution Guide](https://github.com/webb-tools/webb-experiences/blob/main/.github/CONTRIBUTING.md) for information on how to do so. We are excited for your first contribution!
 
 ### Disclaimer 

Any statement in this repository that is not purely historical is considered a forward-looking statement. Forward-looking statements included in this repository are based on information available to Webb as of the date they are made, and Webb assumes no obligation to update any forward-looking statements. The forward-looking product roadmap, user-stories, user-maps or anything within this repository does not represent a commitment, guarantee, obligation or promise to deliver any product or feature, or to deliver any product and feature by any particular date, and is intended to outline the general development plans. Users should not rely on this repository to make any purchasing decision.