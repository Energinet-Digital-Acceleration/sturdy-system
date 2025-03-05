# 🌍 Open Source Evaluation Checklist

### 1) Is It a Good Fit for Open Source?

* [x] Provides value to the community (Energinet)
* [x] Doesn’t contain sensitive or proprietary code.
* [x] Doesn’t rely on non-open-source dependencies

### 2) Open Source Setup

* [x] Choose a license (see table*)
* [x] Write a __CONTRIBUTING.md__ file (See example file)
* [x] Doesn’t rely on non-open-source dependencies.

### 3) Security & Maintenance

* [x] Don't allow hardcoded credentials.
* [x] Don't allow sensitive data. 
* [x] Vet who is allowed to make pull requests (Energinet employees only to start of with)

# Licenses

| License Type           | Pros | Cons |
|------------------------|------|------|
| **MIT License**        | - Very permissive, allowing almost unrestricted use.  <br> - Simple and widely adopted.  <br> - Allows commercial use. | - No patent protection.  <br> - No requirement for modifications to be shared. |
| **Apache 2.0**         | - Includes an explicit patent grant, reducing legal risk.  <br> - Allows commercial use and modifications.  <br> - Requires modifications to include attribution. | - More complex than MIT due to additional clauses.  <br> - Some businesses may find patent clause restrictive. |
| **Business Source License (BSL)** | - Allows source code visibility while restricting certain commercial uses.  <br> - Can later convert to an open-source license (e.g., after X years).  <br> - Good for monetization while still sharing code. | - Not OSI-approved, so not considered true open source.  <br> - Can limit adoption by open-source communities.  <br> - Legal complexity around usage restrictions. |
| **No License**         | - Keeps the code private by default (all rights reserved).  <br> - Maintains full control over who can use the software. | - Legally, others cannot use or modify the code without explicit permission.  <br> - Discourages contributions and public adoption.  <br> - Potential legal uncertainty in different jurisdictions. |
