# Bip39-diceware

Generate a Bip39 Wallet Mnemonic using plain six sided dice and a coin

http://github.com/taelfrinn/Bip39-diceware/raw/master/coin_plus_d6_bip39.pdf



Generate a bip39 passphrase using a coin and four standard 6 sided dice.
Generate each of the words by flipping the coin (t/h) and rolling the dice (1-6).
Consistently and fairly, to avoid bias, arrange the dice in order left to right.
Look up the result in the attached table. If you flip tails and get a dice value larger
than 4362 then you will have to flip+roll over again. After you are finished all 12
words, the last word may need adjustment in order to meet the checksum requirements.
Using a bip39 wallet try each of the words in the block of 16 that the last
word is found inside; one and only one word will work from the group.

You have now generated a bip39 compliant wallet using manual entropy!
