# Multi-Platform Matrix Build Demo

This repository demonstrates a GitHub Actions workflow with matrix build strategy and artifact management.

## Features

- **Matrix Strategy**: Builds across multiple OS platforms (Ubuntu, Windows, macOS) and Node.js versions (16, 18, 20)
- **Parallel Execution**: All matrix variants run simultaneously
- **Artifact Management**: Each job generates and uploads unique build artifacts
- **Identifier**: Contains the required `matrix-fd172b8` step identifier

## Matrix Configuration

The workflow generates 7 parallel jobs:
- Ubuntu + Node 18, 20, 16
- Windows + Node 18, 20
- macOS + Node 18, 20

## Artifacts

Each job uploads an artifact named: `build-fd172b8-{os}-node{version}`

Example artifacts:
- `build-fd172b8-ubuntu-latest-node18`
- `build-fd172b8-windows-latest-node20`
- `build-fd172b8-macos-latest-node18`

## Contact

Email: 24f3002271@ds.study.iitm.ac.in
