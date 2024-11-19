# Registering and Licensing Open Educational Resources with Verifiable Credentials

Welcome to the repository accompanying the **3rd OER World Congress** in Dubai on **November 19-20, 2024**. This project demonstrates how **Verifiable Credentials (VCs)** can be used to properly register and license an **Open Educational Resource (OER)**.

## Table of Contents

- [Introduction](#introduction)
- [Use Cases](#use-cases)
- [Project Overview](#project-overview)
- [Verifiable Credential Details](#verifiable-credential-details)
- [Presentation Slides](#presentation-slides)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

This repository showcases a proof of concept for leveraging Verifiable Credentials to:

- **Ensure the integrity of educational materials**
- **Authenticate the identity of authors**
- **Apply and verify open license conditions**

By embedding metadata, timestamping, and author credentials into a cryptographically verifiable package, we provide a robust method to manage Open Educational Resources.

---

## Use Cases

This approach addresses the following critical challenges in managing Open Educational Resources:

1. **Identify Newly Published OER**
   - Enables tracking of the first publication of any digital resource to ensure proper attribution and licensing.

2. **Pinpoint Authors**
   - Links publications to verified human authors, ensuring transparency and accountability.

3. **Discover and Re-Use OER Ethically**
   - Allows users to respect license conditions when using, adapting, or republishing OER materials.

4. **Track Citations**
   - Facilitates the use of citations to measure the impact and identify the best OER.

---

## Project Overview

This repository includes:

- A **Verifiable Credential** (`oer-credential.json`) that demonstrates the integration of UUID metadata, timestamp, author identity, and licensing into a digitally signed package.
- A **PowerPoint presentation** (`OER_World_Congress_Presentation.pptx`) used at the 3rd OER World Congress.
- A **Policy Brief** (`policy-brief.pdf`) for UNESCO describing the concept in more detail

---

## Verifiable Credential Details

The Verifiable Credential integrates:

- **Creative Work Metadata**: UUID and metadata ensure the uniqueness of the resource.
- **Timestamp**: Indicates the publication date of the resource.
- **Author Identity Credential**: Verifies the author's identity using a national ID system.
- **Open Licence Conditions**: Specifies licensing directly within the credential subject using Creative Commons.
- **Proof**: A cryptographic signature ensuring the integrity and authenticity of the resource and its metadata.

---

## Presentation Slides

The accompanying PowerPoint presentation provides a detailed walkthrough of this proof of concept:


## License

This project is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

**You are free to:**

- **Share** — copy and redistribute the material in any medium or format.
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

**Under the following terms:**

- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.

---


---

For questions or discussions, feel free to open an issue or contact me directly.
