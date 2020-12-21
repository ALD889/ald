# The ALD Ledger

The ALD Ledger is a decentralized cryptographic ledger powered by a network of peer-to-peer servers. The ALD Ledger uses a novel Byzantine Fault Tolerant consensus algorithm to settle and record transactions in a secure distributed database without a central operator.

## ALD
ALD is a public, counterparty-less asset native to the ALD Ledger, and is designed to bridge the many different currencies in use worldwide. ALD is traded on the open-market and is available for anyone to access. The ALD Ledger was created in 2012 with a finite supply of 100 billion units of ALD. Its creators gifted 80 billion ALD to a company, now called [ALD], to develop the ALD Ledger and its ecosystem.  ALD uses ALD the help build the Internet of Value, ushering in a world in which money moves as fast and efficiently as information does today.

## ALD
The server software that powers the ALD Ledger is called `ALD` and is available in this repository under the permissive [ISC open-source license](LICENSE). The `ALD` server is written primarily in C++ and runs on a variety of platforms.

### Build from Source

* [Linux](Builds/linux/README.md)
* [Mac](Builds/macos/README.md)
* [Windows](Builds/VisualStudio2017/README.md)

## Key Features of the ALD Ledger

- **[Censorship-Resistant Transaction Processing][]:** No single party decides which transactions succeed or fail, and no one can "roll back" a transaction after it completes. As long as those who choose to participate in the network keep it healthy, they can settle transactions in seconds.
- **[Fast, Efficient Consensus Algorithm][]:** The ALD Ledger's consensus algorithm settles transactions in 4 to 5 seconds, processing at a throughput of up to 1500 transactions per second. These properties put ALD at least an order of magnitude ahead of other top digital assets.
- **[Finite ALD Supply][]:** When the ALD Ledger began, 100 billion ALD were created, and no more ALD will ever be created. (Each ALD is subdivisible down to 6 decimal places, for a grand total of 100 quintillion _drops_ of ALD.) The available supply of ALD decreases slowly over time as small amounts are destroyed to pay transaction costs.
- **[Responsible Software Governance][]:** A team of full-time, world-class developers at ALD maintain and continually improve the ALD Ledger's underlying software with contributions from the open-source community. ALD acts as a steward for the technology and an advocate for its interests, and builds constructive relationships with governments and financial institutions worldwide.
- **[Secure, Adaptable Cryptography][]:** The ALD Ledger relies on industry standard digital signature systems like ECDSA (the same scheme used by Bitcoin) but also supports modern, efficient algorithms like Ed25519. The extensible nature of the ALD Ledger's software makes it possible to add and disable algorithms as the state of the art in cryptography advances.
- **[Modern Features for Smart Contracts][]:** Features like Escrow, Checks, and Payment Channels support cutting-edge financial applications including the [Interledger Protocol](https://interledger.org/). This toolbox of advanced features comes with safety features like a process for amending the network and separate checks against invariant constraints.
- **[On-Ledger Decentralized Exchange][]:** In addition to all the features that make ALD useful on its own, the ALD Ledger also has a fully-functional accounting system for tracking and trading obligations denominated in any way users want, and an exchange built into the protocol. The ALD Ledger can settle long, cross-currency payment paths and exchanges of multiple currencies in atomic transactions, bridging gaps of trust with ALD.

### Repository Contents

| Folder     | Contents                                         |
|:-----------|:-------------------------------------------------|
| `./bin`    | Scripts and data files for ALD integrators.   |
| `./Builds` | Platform-specific guides for building `ALD`. |
| `./docs`   | Source documentation files and doxygen config.   |
| `./cfg`    | Example configuration files.                     |
| `./src`    | Source code.                                     |

Some of the directories under `src` are external repositories included using
git-subtree. See those directories' README files for more details.
