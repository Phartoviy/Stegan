# Stegan
# 1. Шифрование
stegx encode -i commands.png -f secret.txt -o stego.png --dual-cipher --adaptive --matrix-embedding

# (Программа запросит пароль для шифрования)

# 2. Расшифровка
stegx decode -i stego.png -d extract/
