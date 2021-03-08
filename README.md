![NFTC](logo.jpg "NTFC")

# NFT Cars

## Description
NFTC is a collection of 16,384 unique digital pictures.
By holding the artwork, you accumulate the NCT token on a daily basis, which allows you to choose a name for your picture on the Binance Smart Chain.

## Distribution
All pictures are rare, but some are rarer than others.
To ensure a fair distribution, the user will not know what picture they purchase for the first 21 days of the sale.
All NFTCs are already generated, but not indexed yet.
There is a predetermined sequence of pictures, but which one will be the first picture will only be determined at the end of the sale using a random mechanism on-chain.
This method guarantees a fair distribution.

## Sale
The pictures are being sold according to the schedule below:
Round   | Price (BNB)   | Picture
------- | ------------- | -------
1       | 0.25          | 0-2999
2       | 0.75          | 3000-6999
3       | 1.25          | 7000-10999
4       | 2             | 11000-14999
5       | 3             | 15000-15999
6       | 5             | 16000-16380
7       | 100           | 16381-16384

After 21 days or when all the pictures are sold (whichever is earlier), the contribution period concludes and your pictures will be revealed.
Unsold pictures from Stage 7 will be randomly distributed to the sale participants who have purchased at least 3 pictures.

## Smart contracts

### NFTC
* _Standart_: [ERC721](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md)
* _Name_: NFT Cars
* _Ticker_: NFTC
* _Emission_: Single, 16 384 tokens
* _Fiat dependency_ : No
* _Token offers_ : 1
* _Purpose_: Main token confirming the holder's ownership rights

### NCT
* _Standart_: [ERC20](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md)
* _Name_: Name Changing Token
* _Ticker_: NCT
* _Decimals_: 18
* _Emission_: Сontinuous
* _Emission duration_: 10 years
* _Emission rate_: 10 NCT per day
* _Fiat dependency_ : No
* _Token offers_ : 1
* _Purpose_: Token allowing to change the name of the NFTC
* _The value needed to change the name_: 1 830 NCTs (about ½ years worth of NCTs)

### CommonSale
* _Name_: CommonSale
* _Purpose_: Sale contract - registers NFTC holders for subsequent token distribution
* _Number of stages_: 7
* _Token cap_: 16 384 NFTC
* _Time cap_: 21 days
* _Extra_: Unsold NFTCs from Stage 7 will be randomly distributed among the participants who have purchased at least 3 NFTCs during the sale.


