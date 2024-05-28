# Project-Create-a-NFT-Collection-

Code Explanation:

1. Array Declaration:
    . const myNFTs = [];
    . This line declares an empty array named myNFTs which will hold our NFT objects.

2. Function to Create a New NFT:
    . createNFT(name, eyeColor, shirtType, bling) { ... }
    . This function takes four parameters: name, eyeColor, shirtType, and bling (bling refers to decorative 
      accessories).
    . Inside the function, it creates an NFT object with properties name, eyeColor, shirtType, and bling, and then           pushes it into the myNFTs array.

3. Function to Display NFTs:
    . showNFTs() { ... }
    . This function iterates over each NFT object in the myNFTs array and displays its properties using console.log().

4. Function to Get Total Number of NFTs:
    . getTotalNFTs() { ... }
    . This function simply prints the total number of NFTs in the collection by outputting the length of the myNFTs           array.

5. Creating NFTs:
    . Three NFTs are created using the createNFT() function, each with a unique combination of name, eyeColor,               shirtType, and bling.

6. Displaying NFTs:
    . The showNFTs() function is called to display all NFTs in the collection.

7. Getting Total NFTs:
    . The getTotalNFTs() function is called to display the total number of NFTs in the collection.

