# Caesar Cipher Cracker

message =  'guv6Jv6Jz!J6rp5r7Jzr66ntrM'
SYMBOLS = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz1234567890 !?.'

# Loop through every possible key
for key in range(len(SYMBOLS)):
    translated = ''
    
    # Loop through each symbol in the message
    for sybol in message:
        if symbol in SYMBOLS:
            symbolIndex = SYMBOLS.find(symbol)
            translatedIndex = symbolIndex - key
            
            # Handle the wraparound
            if translatedIndex < 0:
                translatedIndex = translatedIndex + len(SYMBOLS)
                
            # Append the decrypted symbol
            translated = translated + SYMBOLS[translatedIndex]
            
        else:
            # Append the symbol with out encrypting/decrypting
            translated = translated + symbol
    # Display every possible decryption:
    print('Key #%s: %s' % (key, translated))
            
