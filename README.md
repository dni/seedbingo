# bitcoin seed bingo via nostr
## WIP WIP WIP
## just random notes

emits a bip39 word per day from a pre defined 24 words private key.

- starts at 12. word
- periodically release a new word via nostr dm

- participants gather via nostr
- every participant can choose 42 bip39 words
- participants negotiate a seed together
- a multisig/script with the participants seed and the initiator is made.

- if a participant guesses the words
- participants until initator cannot redeem until 22. word +6h # todo calc how fast you can bruteforce the last words


- initiator locks 1m
- 10x participants lock 100k
- initiator prepares psbt one utxo for his x% for running the service and
  another one locked to the negoatiated participants address which can spend the rest
-  broadcasts periodically via nostr dms
