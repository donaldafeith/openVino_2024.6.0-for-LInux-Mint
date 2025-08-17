# OpenVINO 2024.6.0 for Linux Mint Cinnamon

## Overview

This repository provides a customized version of [OpenVINO™ Toolkit 2024.6.0](https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit/overview.html) specifically edited and tested to work on **Linux Mint Cinnamon**. OpenVINO™ (Open Visual Inference and Neural Network Optimization) is Intel’s toolkit for deploying high-performance computer vision and deep learning inference.

**Note:** Compatibility with other Linux Mint editions (e.g., XFCE, MATE) or other Linux distributions is **unknown**. This version is tailored for Linux Mint Cinnamon and may require additional modifications for other environments.

---

## Features
- All core OpenVINO™ functionality for deep learning inference
- Pre-built Python bindings and C/C++ sample applications
- Dependency installation scripts adapted for Linux Mint Cinnamon
- Documentation and sample code included

---

## Getting Started

### 1. Prerequisites
- Linux Mint Cinnamon (tested on 21.x)
- Python 3.8+
- CMake, GCC, and other build tools (see `install_dependencies/install_openvino_dependencies.sh`)

### 2. Install Dependencies
Run the provided script to install all required dependencies:

```bash
cd install_dependencies
bash install_openvino_dependencies.sh
```

### 3. Set Up Environment
Source the environment setup script before using OpenVINO:

```bash
source setupvars.sh
```

You can add this line to your `~/.bashrc` or `~/.profile` for convenience.

### 4. Run Samples
Explore the `samples/` directory for C, C++, and Python sample applications. For example, to run a Python sample:

```bash
cd samples/python/hello_classification
python3 hello_classification.py
```

---

## Documentation
- See the `docs/` folder for HTML and text documentation.
- Official OpenVINO documentation: [OpenVINO Docs](https://docs.openvino.ai/)

---

## Limitations
- **Tested only on Linux Mint Cinnamon.**
- Functionality on other Linux Mint editions or distributions is not guaranteed.
- Some hardware-specific features may require additional drivers or configuration.

---

## Contributing
Pull requests for Linux Mint compatibility improvements are welcome! Please specify your Mint edition and version in any issues or PRs.

---

## License
See `docs/licensing/` for license details. OpenVINO™ is distributed under the Apache License 2.0 and other third-party licenses.

---

## Credits
- [Intel® OpenVINO™ Toolkit](https://github.com/openvinotoolkit/openvino)
- Adapted for Linux Mint Cinnamon by the community
- **Edited and maintained by Donalda Feith**
	- Senior AI Engineer | Full Stack Developer | AGI Researcher
	- Specialized in LLMs, NLP, scalable systems, and ethical AI
	- [GitHub](https://github.com/DonaldaFeith) | [LinkedIn](https://www.linkedin.com/in/donaldafeith/) | [Medium](https://medium.com/@donalda) 

For a full professional background, references, and certifications, please contact Donalda Feith directly.

---

## Acknowledgments & Legal Notices

This project is based on the official Intel® OpenVINO™ Toolkit. All intellectual property, trademarks, and copyrights for OpenVINO™ and related technologies belong to Intel Corporation and its contributors.

- **Intel, the Intel logo, and OpenVINO are trademarks of Intel Corporation or its subsidiaries.**
- This repository is an unofficial adaptation and is not affiliated with or endorsed by Intel Corporation.
- All original code, documentation, and binaries are © Intel Corporation and/or its contributors, used here under the terms of the Apache License 2.0 and other third-party licenses as described in `docs/licensing/`.
- For official support, downloads, and documentation, visit the [Intel OpenVINO™ website](https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit/overview.html).

Special thanks to the Intel OpenVINO™ development team and the open source community for their ongoing work and support.

---

## Disclaimer
This is an unofficial adaptation. Not affiliated with or endorsed by Intel. Use at your own risk.
