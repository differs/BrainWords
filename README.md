# BrainWords
## Find Lost Bitcoin Passphrases

**Find your lost passphrase get 50% of the find**</br>
Finds up to $100 are yours 100%, in return you will receive a decrypted private key (WIF)</br>
If the amount is over $100 you will be paid 50%<hr>


Search passphrases on the fastest program in the world</br>
[18,972](https://allprivatekeys.com/hacked-brainwallets-with-balance) passphrases were found, an estimated 5,000 passphrases are lost</br>
They were found on a processor with a maximum speed of 100,000 characters per second.</br>
Challenge Speed 3090 = 180,000,000/sec. It's 1800 times faster.</br>
The fact that one 3090 GPU runs in 24 hours is a [legendary CPU program](https://github.com/ryancdotorg/brainflayer) in 5 years.</br>

## How to search for old lost passphrases:</br>

Telegram group [**BTC Hunters**](https://t.me/wif500)




### Windows:
#### Prefix + Combinations<br>
TestA ->  TestB -> TestC -> Testzzzzz -> Testzzzzzzzzzzzzzz<br>
Run ```BrainWords.exe -v --bits 18 --root Test --suffix 0 --inputAddress addresses.txt -d 0```

Test test A ->  Test test B -> Test test C -> Test test zzzzz -> Test test zzzzzzzzzzzzzz<br>
Run ```BrainWords.exe -v --bits 18 --root "Test test " --suffix 0 --inputAddress addresses.txt -d 0```<hr>

#### Combinations + Suffix<br>
A@gmail.com ->  B@gmail.com -> C@gmail.com -> zzzzz@gmail.com -> zzzzzzzzzzzzzz@gmail.com<br>
Run ```BrainWords.exe -v --bits 18 --rootsuffix @gmail.com --suffix 0 --inputAddress addresses.txt -d 0```</br>

A Test test ->  B Test test -> C Test test -> zzzzz Test test -> zzzzzzzzzzzzzz Test test</br>
Run ```BrainWords.exe -v --bits 18 --rootsuffix " Test test" --suffix 0 --inputAddress addresses.txt -d 0```<hr>

#### Finding passphrases from a text file</br>
Run ```BrainWords.exe -v --inputPhrase dictionary.txt --inputAddress addresses.txt -d 0```<hr>

-d ? (GPU card number, id)</br>
--bits 4, 8, 16, 24, 25, 26</br>
--eth (ETH address search) --inputAddress addrEth.txt


### Linux:
Run ```chmod +x BrainWords-30xx```</br>
Run ```./BrainWords-30xx -v --bits 18 --root Test --suffix 0 --inputAddress addresses.txt -d 0```

### Example test
Passphrase: PaSs'?Z*x </br>
Address: 1HrWJahBjukPACj7QLUPrr6vNXpYxycREc (Add to base.txt)</br>

Run ```BrainWords.exe -v --bits 18 --root PaSs --suffix 0 --inputAddress addresses.txt -d 0```

![Passphrase](https://user-images.githubusercontent.com/82582647/189755356-33b1c813-0e9c-4701-9444-abcf4bb140dd.png)


| GPU card   | -bits    | Speed       |
|------------|----------|-------------|
| A100       | 26       | 200 Mkeys   |
| A6000      | 25       | 180 Mkeys   |
| 3090       | 25       | 180 Mkeys   |
| 3080 Ti    | 24       | 170 Mkeys   |
| 3080       | 24       | 150 Mkeys   |
| 3070 Ti    | 24       | 120 Mkeys   |
| 3070       | 24       | 110 Mkeys   |
| 3060       | 24       | 70 Mkeys    |
| 2080 S     | 24       | 70 Mkeys    |
| 2070       | 24       | 50 Mkeys    |
<hr>

## Frequently asked Questions
### Question answer:

Where can I get a base of addresses to start?</br>
You can download the database of addresses [**HERE**](https://github.com/phrutis/BrainWords/releases/tag/1.0)<hr>

Why did the program freeze at startup?</br>
She didn't hang up! Program start 3090 --bits25 (25 min.)</br>
The program creates tables and downloads to the device</br>
One card requires 4GB or more of RAM to work.</br>
The consumption depends on the size of the table (--bits) and the size of the address file.<hr>

What address formats can be uploaded?</br>
BTC bc.., 3.., 1.., or ETH in a text file from a new line</br>
It is recommended to use only [OLD addresses 1... from $2](https://github.com/phrutis/BrainWords/releases/tag/1.0)<hr>

How to continue searching after stopping the program?</br>
The program saves the position every 5 minutes.</br>
Copy the startup line from the tex file GPU_0_Continue.txt and run the program.<hr>

Explain what we are looking for?</br>
How it works? What's this?</br>
[Here is a good example](https://allprivatekeys.com/try-your-passphrase) of work for you.</br>
Enter passphrase: fhqyqzhao123 pay attention to the address 1MVFUmYLKmLyC1m3WfyHkEJTZfoHjwDeXE</br>
The difference is that instead of requests to the blockchain.</br> 
The program checks against the database of addresses with a positive balance.<hr>

I found. What to do?</br>
When you find the passphrase, a message will appear in the window.</br>
====== FOUND ======</br>
Address: 1.....</br>
Privkey: XXX...</br>
===================</br>
The address and key will also be written to the text file FOUND.txt</br>
Do not tell anyone the found key!</br>
Write me a private message in telegram phrutis<hr>

Why does the program use a lot of RAM?</br>
The program creates the necessary tables and stores them in memory.<hr>

Does the program require an internet connection?</br>
No, the program is looking for the key offline.<hr>

Why is the program without source codes?</br>
The program includes a range, decoders and more.</br>
Knowing them, there is no point in the challenge.<hr>

If I find the key can I take all the coins for myself?</br>
No, you will find BTC address and the encrypted key.</br>
Only the organizers of the challenge can decrypt this key and pay you a 50% from balance<hr>

Can you sell me the full version of the program?</br>
No, the program is not for sale.<hr>

What guarantees are there that you will pay me 50% when I find the private key?</br>
If you have found several addresses, start small and build up.</br>
The challenge is designed for trust.<hr>

I have a RTX 3060 TI card, and I have a low speed, how can speed up?</br>
In the new drivers for 30xx Ti, a limiter is installed that slows down the speed by half.</br>
You need to download the old driver from six months ago. 496.13</br>
Delete the new driver, install the old driver, the speed will increase x2</br>
After searching, you can install new drivers.<hr>

I have other questions.</br>
Write questions in a telegram [**BTC Hunters**](https://t.me/wif500)

