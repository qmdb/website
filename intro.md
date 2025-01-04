# QMDB: Quick Merkle Database

QMDB is a high-performance authenticated data structure (ADS) designed to solve the key bottleneck in modern blockchains: state management. It combines lightning-fast performance with resource efficiency, making it ideal for both high-throughput applications and decentralized networks.

## Key Innovations

- **Single-Layer Architecture**: Unifies world state and Merkle tree storage for maximum efficiency
- **In-Memory Merkleization**: Zero disk reads/writes for Merkleization operations
- **Append-Only Design**: SSD-optimized storage with minimal write amplification
- **Resource Efficient**: Runs efficiently on both consumer hardware and enterprise servers

## Performance Highlights

- Up to 8x faster than state-of-the-art verifiable databases
- Achieves 2.28M updates/second on high-end hardware
- Supports 150K updates/second on consumer hardware ($540 mini PC)
- Scales to hundreds of billions of entries

## Technical Features

- **Efficient State Operations**:
  - State reads: 1 disk read
  - State updates: O(1) disk IO
  - Merkleization: Zero disk operations

- **Flexible Deployment**:
  - In-memory indexer for maximum performance
  - Hybrid indexer for larger datasets
  - Supports both consumer and enterprise hardware

## Documentation

For detailed technical specifications and implementation details:
- [PDF Documentation](docs/qmdb.pdf)
- [GitHub Repository](https://github.com/qmdb/qmdb)

## License

MIT License