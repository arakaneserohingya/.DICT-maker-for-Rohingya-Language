## .DICT-maker-for-Rohingya-Language

1. Make rohingya_wordlist.combined file using [RohingyaCombinedMaker](https://github.com/arakaneserohingya/RohingyaCombinedMaker)
   which will look like this:

```python
dictionary=main:rhg,locale=rhg,description=Rohingya wordlist,date=02132024,version=1


 word= 𐴉𐴥𐴠𐴓𐴝𐴘 𐴊𐴞𐴘𐴧𐴠, f=254
 word= 𐴈𐴡𐴔, f=254
 word= 𐴁𐴝𐴙𐴄𐴧𐴝𐴒𐴡𐴌𐴥𐴡𐴕, f=254
 word= 𐴁𐴝𐴙𐴄𐴧𐴝, f=254
 word=𐴀𐴠𐴌𐴞 𐴊𐴦𐴡𐴕, f=254
 word= 𐴉𐴠𐴍, f=254
 word=𐴊𐴦𐴝𐴉𐴥𐴝𐴘𐴓𐴡𐴘𐴎𐴦𐴡𐴕 𐴒𐴥𐴡𐴘, f=254
 word= 𐴄𐴤𐴡𐴌𐴦𐴡𐴕, f=254
 word= 𐴃𐴝𐴑𐴡𐴃𐴢, f=254
 word=𐴈𐴝𐴔𐴡𐴃𐴢 𐴀𐴝𐴕𐴦𐴡𐴕, f=254
 word= 𐴒𐴟𐴏𐴡𐴓𐴢, f=254
 word=𐴏𐴥𐴝𐴉𐴢 𐴒𐴡𐴌𐴥𐴠𐴉𐴥𐴠𐴓, f=254
 word=𐴉𐴥𐴠𐴓𐴝𐴘 𐴊𐴥𐴠, f=254
```



2. Download [dicttool_aosp.jar](https://github.com/arakaneserohingya/.DICT-maker-for-Rohingya-Language/blob/main/dicttool_aosp.jar) (taken from https://github.com/remi0s/aosp-dictionary-tools)
3. put dicttool_aosp.jar and rohingya_wordlist.combined in the same directory.

To convert the rohingya_wordlist.combined file to a rohingya.dict file using dicttool_aosp.jar, you would need to run the following command in your terminal or command prompt:
bash


### Locate the file path in terminal
```python
cd /Users/ahkterhusin/PycharmProjects/aosp-dictionaries/
 ```




### Copy this command and run
```bash
 java -jar /Users/ahkterhusin/PycharmProjects/aosp-dictionary-tools/dicttool_aosp.jar makedict -s /Users/ahkterhusin/PycharmProjects/aosp-dictionary-tools/rohingya_wordlist.combined -d /Users/ahkterhusin/PycharmProjects/aosp-dictionary-tools/rohingya.dict
  ```

### This command assumes that:

* dicttool_aosp.jar is located at /Users/ahkterhusin/PycharmProjects/aosp-dictionary-tools/.
* rohingya_wordlist.combined is located at /Users/ahkterhusin/PycharmProjects/aosp-dictionary-tools/.
Make sure to replace the paths with the correct locations of your files on your system. After running this command, the rohingya.dict file should be created in the specified directory.

### FYI

A file with a .dict extension typically refers to a dictionary file. It can contain various types of data structured for use in dictionary applications or software. Here are a few common uses:

* Word Lists: 
.dict files may contain lists of words along with additional information such as definitions, part of speech, pronunciation, or usage examples.

* Language Dictionaries:
These files can store language dictionaries used by software for spell checking or word suggestion purposes.

* Specialized Dictionaries:
Some .dict files may contain specialized dictionaries, such as medical, legal, or technical dictionaries.

* Encoded Data:
In some cases, .dict files might contain encoded or compressed data, used for efficient storage or transmission of dictionary information.

The specific format and content of a .dict file depend on the application or software that uses it. They are typically designed to be easily readable and processed by the corresponding software.
