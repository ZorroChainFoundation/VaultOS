### zorroGARD/README.md
```markdown
# ZorroGARD: VaultOS Security LLM Assistant

**ZorroGARD** (Guardian AI for Resilient Defense) is the onboard intelligence module for VaultOS. It provides interactive guidance, policy enforcement, and cryptographic operations via a local LLM, gated by TPM attestation.

## 🗂 Directory Structure

```text
zorroGARD/
├── model/                  # Quantized model weights for the LLM (e.g., 7B parameter binary)
├── prompts/                # Prompt templates, system and user prompt configurations
├── service/                # systemd unit and startup scripts
│   ├── zorrogard.service   # systemd unit to launch the ZorroGARD daemon
│   └── start-zorrogard.sh  # Initialization wrapper to prepare TPM and keys
├── cli/                    # CLI interface and utilities
│   └── zorrogard           # Interactive CLI binary or script
└── README.md               # This file

   <!--
ZorroChain Core Protocol  
Copyright (c) 2025–present ZorroChain Foundation

Licensed under the Mozilla Public License, v. 2.0  
https://mozilla.org/MPL/2.0/
-->
