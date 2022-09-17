<h1 align="center"> ZeroPool </h1>

### Neden umarım github'ım kapatılmaz dedim? Malum 🌪️ olayı yüzünden. (şaka)

## Zeropool'u kovan'da test ediyorum canım sıkıldıkça, sizede yazayım dedim, malum içerik üretmiyorum pek.

<h1 align="center"> Wallet </h1>

## Öncelikle [buradan](https://testnet.app.zeropool.network/register) bir cüzdan oluşturuyoruz.

 * export seed ile kopyalayabilirsiniz
 * burada cüzdan oluşturduktan sonra bu kısmıda test edebilirsiniz ancak ben kovan ağında göstereceğim
 * burası goerli, neden burayı göstermiyorum? mantık aynı, kendiniz yapabilirsiniz bence
 * göstereceğim yere geçelim

![image](https://user-images.githubusercontent.com/101149671/190872562-a1f936c1-676a-4958-875a-0ba7b25ce621.png)

## [Buradan](https://kovan.testnet.console.v2.zeropool.network/) test edeceğimiz yere girelim.

 * Kullanıcı adı
 * Şifre
 * Seed (12 kelime)
 * Üstte ki linkte oluşturmuştuk

![image](https://user-images.githubusercontent.com/101149671/190872658-caa061a2-4ca7-4cf5-9daa-b39d2ce3cd68.png)

## 0x ile başlayan cüzdan adresimizi öğrenelim ve not edelim:
```
get-address
```

## Bu komutlada private edresimizi alalım:
```
gen-shielded-address
```

## Şimdi tilkimask cüzdanında, kovan ağın'dan 0xli cüzdanımıza biraz test tokeni ETH atalım

 * Eğer kovan ağı test bakiyeniz yoksa discord faucet kanal [linki](discord.gg/ruescommunity)

## Token attıktan sonra terminalde test tokeni mintleyelim

 * Hocam zaten ETH atmamışmıydık bir daha niye mintliyoruz? - Bu testETH işlem ücretleri içindi..

```
testnet-mint 5000000000000000000
```

 * Biraz zaman geçtikten sonra bakiyenize bakabilirsiniz:
```
get-shielded-balance
```

## Mintlediğimiz tokeni deposit edelim:
```
deposit-shielded 2000000000000000000
```

## Yukarıda private adresimizi almıştık, şimdi transfer işlemi yapalım:

 * private adres kısmına adresinizi girin

```
transfer-shielded PRİVATE ADRES 10000000000
```

## Withdraw işlemi:
```
withdraw-shielded 2000000000000000000
```

# İşlemler bu kadar, gerisi size kalmış :)





