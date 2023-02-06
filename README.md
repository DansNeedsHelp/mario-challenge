# # Forensics Challenge
Difficulty: Hard
Description: 
Once upon a time, in the Mushroom Kingdom, Mario and his friends were hosting a big racing tournament. The winner of the race would receive a grand prize and be crowned the fastest racer in the land. But, little did the racers know, there was a catch to winning the race. At various points along the track, there would be questions to answer about forensics and web, the racers would need to answer the questions correctly. He needs your help to chase after bowser in order to gain access and find out where bowser is!

https://drive.google.com/file/d/1Hwo7y_XH1sZQXVfwntLYUb99ufE7LGFo/view?usp=sharing 

## Concept
Players will be required unpack the disk image with a tool such as FTK Imager, then dig around the filesystem to find a word document. The word document is in docx format and will lead the user to where the attack is being hosted at over at the domain name. The follina exploit hosting domain would be included in one of the files in the word document when it is extracted.

## Solution
1.Open up the website link and answer the question correctly.
2. Open disk image in FTK Imager
3. Navigate to John's Downloads folder and find readme.docx
4. Extract readme.docx
5. Rename readme.docx to readme.zip and extract files
6. View word/_rels/document.xml.rels and find http://157.245.205.29:8080/exp.html
7. Navigate to http://157.245.205.29:8080/exp.html
8. Read comments


## Flag
TPCTF{f0ll1n4_c4llb4ck}
