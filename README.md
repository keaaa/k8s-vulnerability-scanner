# radix-image-scanner

The radix-image-scanner gives radix-pipeline access to security scan the images produced during build.

Build is done using Github actions. There are secrets defined for the actions to be able to push to radixdev, radixprod and radixus. These are the corresponding credentials for radix-cr-cicd-dev and radix-cr-cicd-prod service accounts

[![Build Status](https://github.com/equinor/radix-image-scanner/workflows/radix-image-scanner-build/badge.svg)](https://github.com/equinor/radix-image-scanner/actions?query=workflow%3Aradix-image-scanner-build)
