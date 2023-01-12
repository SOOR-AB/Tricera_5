# ARviewer

## link: https://dimakuzov.github.io/ARviewre/

## description
This repo allows you to show .reality or .usdz models in AR for iOS and .glb for Android. You can also set the values for the banner by setting them in a json file.

## iOS
![](https://dimakuzov.github.io/ARviewre/image/iOSBanner.png)

## Android
![](https://dimakuzov.github.io/ARviewre/image/AndroidBanner.png)

## json data example:

```
{
    "bannerBlueText": ["Buy now"],
    "bannerTitle": ["Avian Rising", "Avian Swedish"],
    "bannerSubtitle": ["Shagwon Point", "Montauk"],
    "androidBannerTitle": ["Avian Rising", "Avian Swedish"],
    "price": "100",
    "bannerURL": "https://www.lawrenceleyderman.com/photo/avianrising/"
}
```

## link example:

https://dimakuzov.github.io/ARviewre/?id=LL_AvianRising&lang=1


'id' - name of picture

'lang' - language. It is index of arrays in json, 0 - english (defolt), 1 - Sweden (If it is not exist, English will be selected), (2, 3, 4... any number of languages can be set)
