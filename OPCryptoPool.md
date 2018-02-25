# Getting started mining with OPCrypto

### Goal
At the end of this setup, you'll have a miner with your name and the logo of your choice on our site [http://pool.opcryptos.com](http://pool.opcryptos.com).


### Suggested Hardware
Before you get started, let's make sure you have the necessary hardware to efficiently mine on the blockchain.  While there are countless setups, some are more profitable than others. The suggested hardware is one that has proven to be a profitable configuration, but others most certainly exist. If there's interest, we will add additional configurations and guides for common scenarios.

 - A modern PC with at least one PCIE port - *standard graphics cord port*
 - 400 watt or better power supply - *some cards may require more, please refer to the specifications of the card you intend to mine with*
 - Stable internet connection - *wifi is fine so long as it doesn't have frequent disconnects*
 - A modern Nvidia GPU (GTI 1070 or newer) - *AMD GPUs and CPU Mining will certainly work, but Nvidia currently has an advantage. This setup is specific to NVIDIA hardware.*
 
 ### Software needed
 - Windows 10 - *Other versions of Windows, OSX and Linux will work however, this guide assumes a Windows 10, 64 bit)*
 - [Vertcoin Wallet] (https://github.com/vertcoin-project/vertcoin-core/releases)
 - [7Zip] (http://www.7-zip.org/)
 - [Notepad++] (https://notepad-plus-plus.org/download/v7.5.4.html)
 - ccminer 
    - [64-bit ccminer](https://github.com/tpruvot/ccminer/releases/download/2.2.4-tpruvot/ccminer-x64-2.2.4-cuda9.7z)
    - [32-bit ccminer](https://github.com/tpruvot/ccminer/releases/download/2.2.4-tpruvot/ccminer-x86-2.2.4-cuda9.7z)
  
## I'm ready to mine!  What do I do next?

### Step 1, Download a Vertcoin wallet
 - Update the drivers for your GPU (graphics card) by running Windows update until no more updates are available.
 - Download the Vertcoin Wallet that is correct for your Operating System, for this example we'll be using vertcoin-v0.12.0-windows-64bit.zip
 - Once downloaded, extract the contents of the zipfile to a folder you'll remember. We'll be using c:\VTCWallet.
 - Once extracted, run the vertcoin-qt.exe executable to begin the synchronization with the chain network.
 ### Step 2, Download the miner
 - Download and Install 7-zip on the machine 
 - Using 7-Zip, extract the contents of the CCMiner program into any folder you'd like. For this example, we'll use c:\VTCMiner.
 - Once extracted, navigate to the folder in Windows Explorer (c:\VTCMiner).
 ### Step 3, Configure the miner
 - In the c:\VTCMiner folder, we will be creating a new batch file, we call "run.bat". We use Notepad++ to create a new text file.
 - In the newly created file, enter the
