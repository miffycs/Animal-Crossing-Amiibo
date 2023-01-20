# Animal Crossing Amiibo

Step-by-step instructions on how to recreate Amiibo cards for Animal Crossing: New Horizons. For educational purposes only.

## Disclaimer

This repo is for educational purposes only, clone at your own risk. I do not own any of the Amiibo contents posted, nor am I encouraging any behavior. All rights go to Nintendo.

## Required Materials

- Android
  - Android Phone (with NFC capabilities)
  - Google Play account
- iOS
  - iPhone 7 or later (iPads don't have the NFC module required)
  - App Store account
- Blank [NFC 215 tags (NTAG215)](https://www.amazon.com/s?k=nfc+215&ref=nb_sb_noss_2) (any card/sticker will do, must be blank and NTAG215. This is what official Amiibos use. 213, 216 and other commonly found tags will not work!)

## iOS Instructions

1. Download iOS app [Tagmiibo](https://apps.apple.com/app/apple-store/id1578966288?pt=122926471&ct=github&mt=8).
2. Follow the instructions [here](https://amiibodoctor.com/2022/01/04/the-complete-guide-to-tagmiibo-for-iphone-amiibo-bin-files/).

## Android Instructions

### Set-up

1. Download all contents in this repo using `$ git clone` or download as .zip

2. Using the same Google account as your Google Play account, save all contents into a Google Drive folder.

3. Go to your Android Phone, under Settings > Security, find Unknown Sources and turn it on.

4. Use your phone to access the Google Drive folder > `TagMo_Installer` folder, install `TagMo.apk`, which is the latest release of the [TagMo](https://github.com/HiddenRamblings/TagMo/releases) app grabbed from their GitHub.

5. Launch the TagMo app, click the menu icon on the upper right corner > Load key(s) file, and select the `unfixed-info.bin` and `locked-secret.bin` files also found in the `TagMo_Installer` folder in your Google Drive folder.

### Cloning Amiibos

- Click `LOAD TAG` to load Amiibo data of the villager you want.
- Click `SAVE TAG` to save chosen Amiibo data on to the tag of your choice.

*Be aware that the NFC tags are **NOT** re-writable in this case, as official Nintendo Amiibos also lock in character data during manufacturing to prevent accidental rewrites/deletions. Ours need to do the same to fool your Switch and your ACNH game copy. So if you want to make more than one villager, the smart thing to do would be to buy the NFC tags in bulk just to be safe.

## Credits

- [Nintendo](https://animal-crossing.com/amiibo/) - All Amiibo data belongs to Nintendo, courtesy of [NFC-Bank](https://nfc-bank.com/bins.php?do=download&downloadid=1355) (site was [shut down in late 2020](https://amiibodoctor.com/2020/12/29/whatever-happened-to-nfc-bank/)).
- [u/amiibolover99](https://www.reddit.com/user/amiibolover99/) - Special thanks to u/amiibolover99 for providing Series 5 .bin data ripped from real Amiibo cards.
- [TagMo](https://github.com/HiddenRamblings/TagMo) - without them NFC cloning is impossible (all other apps suck).
- [Miffy Chen](https://www.linkedin.com/in/miffychen/) - Software Engineer / Technical Project Manager at [Bolt](https://www.bolt.com/).
On a mission to democratize commerce. We are hiring, happy to refer!
