compile:
	gcc helperFunction.h -o helperFunction
	gcc readFile.h -o readFile
	gcc encrypt.h -o encrypt
	gcc writeFile.h -o writeFile
	gcc decrypt.h -o decrypt
	gcc masterFile.c -o masterFile -lm
encipher:
	./masterFile ../Text\ Files/textFile.txt ../Text\ Files/encrypt.txt ENCRYPT
decipher:
	./masterFile ../Text\ Files/encrypt.txt ../Text\ Files/decrypt.txt DECRYPT