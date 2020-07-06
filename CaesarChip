# Author : Sultan Raja Marlindo { ./Syncrone }
# Baturaja1337
# Learn Code,Write Code and Exploit With Code

# import pyperclip

Message = input('Masukan Pesan >>> ')
Key = int(input('Enter key >>> '))
Mode = input('encrypt or decrypt ?\n>>>').lower()
Letters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
Translated = ""
Message = Message.upper()

for symbol in Message:
    if symbol in Letters:
        num = Letters.find(symbol)
        if Mode == 'encrypt':
            num = num + Key
        elif Mode == 'decrypt':
            num = num - Key

        # letters or less than 0

        if num >= len(Letters):
            num = num - len(Letters)
        elif num < 0:
            num = num + len(Letters)

        Translated = Translated + Letters[num]
    else:
        Translated = Translated + symbol

print(Translated)
