# Industrial Spy Ransomware Decryption tool

# Description
This is a proof-of-concept decryptor for Industrial Spy ransomware. Note the RSA private key is required to decrypt files.

# Usage
decryptor_poc.py [-h] [--path PATH] -n MODULUS -d EXPONENT
                                   [--debug]

# Example
```
python decryptor_poc.py --path encrypted_files -n 8ace3a217ad16591beaaa1d18da007e3171b7cb971ab1b669325a1cb7cf1892e13e5b688e6ee94faac06f9702d847bfea774c4dca9962fa99b7f9496a14c733480dec424ebd917a6b8437c89424cd64e4510fcc063ba8a197249466bfc34053a7311e745c241a25b4b7d46c8090f23240bc0dac0dabe83e0f6275966ecceca6b -d 25e50f71bc7a1664a7cd25c87405d0a16ad9923f7e8cdc3a30ca0155f092708527e17ae7fd43fd60423ed5328efab06f61803b8e92adf1ed380aa8a246fefc245cb30313d33aa4ff27dab51f704b9126db86f16acecb7a15bf59d85fa36aa29b7e36b231bfac629cdf570f91963f35ca60adb8daa94b76c676e72b8121694301
```
