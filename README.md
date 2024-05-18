This repository contains a simple NFT (Non-Fungible Token) management system implemented in JavaScript. It allows you to mint NFTs, list their metadata, and get the total supply of NFTs minted.

Assessment Requirements
Create a variable that can hold a number of NFTs.
Inside the mintNFT function, create an object to hold the metadata for NFTs, which will be passed as parameters.
Implement the listNFTs function to print all NFT metadata to the console.
Implement the getTotalSupply function to return the total number of NFTs created.
Implementation Details
A variable NFTs is created to hold the NFTs, initialized as an empty array.
The mintNFT function creates an NFT object with provided metadata parameters and stores it in the NFTs array.
The listNFTs function iterates through the NFTs array and prints each NFT's metadata.
The getTotalSupply function logs the total number of NFTs in the NFTs array.
Usage
To use this NFT management system:

Ensure you have a JavaScript environment set up.
Copy and paste the provided code into your JavaScript environment.
Call the mintNFT function with the desired metadata parameters to create NFTs.
Call the listNFTs function to print the metadata of all minted NFTs.
Call the getTotalSupply function to get the total number of minted NFTs.
Example
javascript
Copy code
mintNFT("Bella", "Pink", "Sweater", "Earrings");
mintNFT("Cine", "Violet", "Dress", "Bracelet");
mintNFT("Ysa", "Blue", "Pants", "Necklace");
mintNFT("Franz", "Green", "Shirt", "Choker");

listNFTs();
// Output:
// ID:         1
// Name:       Bella
// Eyecolor:   Pink
// Shirt Type: Sweater
// Bling:      Earrings
//
// ID:         2
// Name:       Cine
// Eyecolor:   Violet
// Shirt Type: Dress
// Bling:      Bracelet
//
// ID:         3
// Name:       Ysa
// Eyecolor:   Blue
// Shirt Type: Pants
// Bling:      Necklace
//
// ID:         4
// Name:       Franz
// Eyecolor:   Green
// Shirt Type: Shirt
// Bling:      Choker

getTotalSupply();
// Output:
// 4
License
This project is licensed under the MIT License - see the LICENSE file for details.

make that readme file
ChatGPT
markdown
Copy code
# NFT Management System Readme

This repository contains a simple NFT (Non-Fungible Token) management system implemented in JavaScript. It allows you to mint NFTs, list their metadata, and get the total supply of NFTs minted.

## Assessment Requirements

- Create a variable that can hold a number of NFTs.
- Inside the `mintNFT` function, create an object to hold the metadata for NFTs, which will be passed as parameters.
- Implement the `listNFTs` function to print all NFT metadata to the console.
- Implement the `getTotalSupply` function to return the total number of NFTs created.

## Implementation Details

- A variable `NFTs` is created to hold the NFTs, initialized as an empty array.
- The `mintNFT` function creates an NFT object with provided metadata parameters and stores it in the `NFTs` array.
- The `listNFTs` function iterates through the `NFTs` array and prints each NFT's metadata.
- The `getTotalSupply` function logs the total number of NFTs in the `NFTs` array.

## Usage

To use this NFT management system:

1. Ensure you have a JavaScript environment set up.
2. Copy and paste the provided code into your JavaScript environment.
3. Call the `mintNFT` function with the desired metadata parameters to create NFTs.
4. Call the `listNFTs` function to print the metadata of all minted NFTs.
5. Call the `getTotalSupply` function to get the total number of minted NFTs.

## Example

```javascript
mintNFT("Bella", "Pink", "Sweater", "Earrings");
mintNFT("Cine", "Violet", "Dress", "Bracelet");
mintNFT("Ysa", "Blue", "Pants", "Necklace");
mintNFT("Franz", "Green", "Shirt", "Choker");

listNFTs();
// Output:
// ID:         1
// Name:       Bella
// Eyecolor:   Pink
// Shirt Type: Sweater
// Bling:      Earrings
//
// ID:         2
// Name:       Cine
// Eyecolor:   Violet
// Shirt Type: Dress
// Bling:      Bracelet
//
// ID:         3
// Name:       Ysa
// Eyecolor:   Blue
// Shirt Type: Pants
// Bling:      Necklace
//
// ID:         4
// Name:       Franz
// Eyecolor:   Green
// Shirt Type: Shirt
// Bling:      Choker

getTotalSupply();
// Output:
// 4
