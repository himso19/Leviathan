# Leviathan
I was on Blue Team, building active defenses. My job was to make systems proactively hostile to attackers. I used Kyverno for security-as-code, Cosign to cryptographically lock down software supply chain, planted honeytokens to detect intruders, and use Chaos Mesh to break things on purpose, ensuring defenses held under pressure.
---
# Phase 1 - Container Image Signing with Cosign

This repository contains artifacts for Phase 1 of the project.

## Files
- cosign.pub → Public key used for verification.
- verification.log → Output of cosign verification.
- README.md → Documentation for this phase.

## Steps Performed
1. Tagged and pushed nginx image to Docker Hub.
2. Signed image using cosign with a private key.
3. Verified the image with the public key.

