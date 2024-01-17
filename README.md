# Unofficial AEPAssurance SDK Podspec
The AEPAssurance sdk fails to archive in the pipline when adding `arm64` to `Excluded Architectures` build setting. This repo adds the official Adobe AEPAssurnce XCFramework to a Podspec. The XCFramework works when excluding `arm64` locally and in the pipeline.

## Usage:
    pod 'AEPAssurance', :git => 'https://github.com/mikemike396/aepsdk-assurance-ios-xcframework.git'

## Versions:
[v4.1.1](https://github.com/adobe/aepsdk-assurance-ios/releases/tag/4.1.1)
[v3.1.1](https://github.com/adobe/aepsdk-assurance-ios/releases/tag/3.1.1)

## Official Library

https://github.com/adobe/aepsdk-assurance-ios
