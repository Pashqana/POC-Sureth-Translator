# POC-Sureth-Translator
A Proof of Concept translator for East Assyrian (Sureth)

Modern translators, like Google translate, are surprisngly not as difficult to make as they may seem. For over a decade now, They've been using Neural machine translation (NMT)
which uses translation pairs (a sentence and another language's translation of it) to train the AI to spot patterns in grammar, voacb, and writing. Thankfully, there are models
such as NLLB-200 that not only come pre-configured with 200 languages trained into it, but have the capibility to add new languages to it. In this repo, I add Sureth to NLLB
with approx 24k translation pairs. (100k+ high quality translation pairs are recommended for decent translation)

## Important warnings
The translation pairs I used here were not the best organized and I had got in around 2-3 days via scraping Wictionary and translations of the bible. Please, do not expect high
quality or reliable translations from this. the 24k translation pairs I used were not of as high quality and are not enough to provide decent, reliable translations. Do not use
this for production purposes. This project is a proof of concept that an Assyrian translator is possible, and with enough effort from our community, we can make an accurate translator
to preserve this language

## Usage
You will need python and 8+ gigabytes of ram recommended. 
Start by running setup.py and let it install the needed packages
After it is done installing, you may run main.py to open the Translator
 - A gui will pop up, it may take some time to fully load as the model is initiated

## Any issues?
You can open an issue in the repo

## How can I help/contribute?
If you can speak, read, and write Sureth, you can contribute for free by going to pashqana.xyz and creating and submitting a translation pair. Thank you!
