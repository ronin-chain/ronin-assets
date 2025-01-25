# Ronin Assets
[![Upload to CDN](https://github.com/ronin-chain/ronin-assets/actions/workflows/upload.yml/badge.svg)](https://github.com/ronin-chain/ronin-assets/actions/workflows/upload.yml)

## Overview

The Ronin Assets repository serves as a CMS for managing token assets on the Ronin blockchain, including the Saigon Testnet.
The Ronin ecosystem will utilize token assets sourced from this repository.

## How to add token logo and banner

### Requirements

**ERC-721 & ERC-1155**
- Logo
  - File extension: `png`
  - File name: `logo.png`
  - Size: 512x512 and less then 100KB

  **Example:**

    <img src="https://cdn.skymavis.com/ronin/2020/erc721/0xd78efaec85c1a4f42e6edb7209067702a2be8c90/logo.png" width="70"/>
    <img src="https://cdn.skymavis.com/ronin/2020/erc721/0x1f7c16fce4fc894143afb5545bf04f676bf7dcf3/logo.png" width="70"/>
    <img src="https://cdn.skymavis.com/ronin/2020/erc721/0xa038c593115f6fcd673f6833e15462b475994879/logo.png" width="70"/>
- Banner
  - File extension: `png`
  - File name: `banner.png`
  - Size: 2560x640 and less then 1MB

  **Example:**

    <img src="https://cdn.skymavis.com/ronin/2020/erc721/0xa038c593115f6fcd673f6833e15462b475994879/banner.png" width="500"/>
    <img src="https://cdn.skymavis.com/ronin/2020/erc721/0xd78efaec85c1a4f42e6edb7209067702a2be8c90/banner.png" width="500"/>
**ERC-20**
- Logo
  - File extension: `png`
  - File name: `logo.png`
  - Size: 512x512 and less then 100KB
  - Background: should have the background, if not the background default will be grey

  **Example:**

  <img src="https://cdn.skymavis.com/ronin/2020/erc20/0x7eae20d11ef8c779433eb24503def900b9d28ad7/logo.png" alt="drawing" width="50"/>
  <img src="https://cdn.skymavis.com/ronin/2020/erc20/0xa8754b9fa15fc18bb59458815510e40a12cd2014/logo.png" alt="drawing" width="50"/>
  <img src="https://cdn.skymavis.com/ronin/2020/erc20/0x97a9107c1793bc407d6f527b77e7fff4d812bece/logo.png" alt="drawing" width="50"/>
  <img src="https://cdn.skymavis.com/ronin/2020/ron/logo.png" alt="drawing" width="50"/>


- Transparent Logo (optional)
  - File extension: `png`
  - File name: `logo-transparent.png`
  - Size: 512x512 and less then 100KB
- Background: transparent

  **Example:**

  <img src="https://cdn.skymavis.com/ronin/2020/erc20/0x7eae20d11ef8c779433eb24503def900b9d28ad7/logo-transparent.png" alt="drawing" width="50"/>
  <img src="https://cdn.skymavis.com/ronin/2020/erc20/0xa8754b9fa15fc18bb59458815510e40a12cd2014/logo-transparent.png" alt="drawing" width="50"/>
  <img src="https://cdn.skymavis.com/ronin/2020/erc20/0x97a9107c1793bc407d6f527b77e7fff4d812bece/logo-transparent.png" alt="drawing" width="50"/>
  <img src="https://cdn.skymavis.com/ronin/2020/ron/logo-transparent.png" alt="drawing" width="50"/>

#### 1. Submit pull request

- Fork this repository
- Add your token information (by clone to your local computer or Github web UI)
- Submit a pull request to the project owner.


#### 2. Wait for approval

## How to consume assets

The workloads will upload all files in this repository to the CDN with the format:
- https://cdn.skymavis.com/ronin/${chainID}/${ercType}/${tokenAddress}/logo.png
- https://cdn.skymavis.com/ronin/ron/logo.png

**_Example:_**
- [https://cdn.skymavis.com/ronin/2020/erc1155/0x02286d77425ae3287335ff28b264109225ed6991/logo.png](https://cdn.skymavis.com/ronin/2020/erc1155/0x02286d77425ae3287335ff28b264109225ed6991/logo.png)
- [https://cdn.skymavis.com/ronin/2020/erc1155/0x02286d77425ae3287335ff28b264109225ed6991/banner.png](https://cdn.skymavis.com/ronin/2020/erc1155/0x02286d77425ae3287335ff28b264109225ed6991/banner.png)
