# LaiKungSticker

## Sticker art and app requirements

- Only .png or .WebP
- Size of sticker: ```512px``` * ```512px```
- Each sticker pack must have a minimum of 3 stickers and a maximum of 30 stickers
- Each sticker must be less than 100KB
- Sticker Picker/Tray Icon(Thumbnail for the sticker)
- Provide an image that will be used to represent your sticker pack in the WhatsApp sticker picker/tray
- This image should be 96 x 96 pixels
- Max file size of 50KB

## procedure
- Follow and Thanks [Unwire](https://unwire.hk/2018/11/06/whatsappstickerdiy/life-tech/) and [Whatsapp](https://github.com/WhatsApp/stickers/tree/master/iOS)

**TLDR**
1. git clone from whatsapp git repo
2. In ```WAStickersThirdParty```, change the ```Display name``` and ```Bundle Identifier``` and Select Team from ```signing```
3. Replace all simpleSticker images from simpleSticker to your images(change type to ```Data```)
4. Update JSON in ```sticker_packs.wasticker```
5. Update App images in ```Assets.xcassets >> App```
6. Build
