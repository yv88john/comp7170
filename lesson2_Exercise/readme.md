# Command for CTF
openssl enc -K 00112233445566778899aabbccddeeff -in input.csv -aes-128-ecb -out cipher.enc
openssl enc -d -K 00112233445566778899aabbccddeeff -in cipher.enc -aes-128-ecb -out decrypt.csv
