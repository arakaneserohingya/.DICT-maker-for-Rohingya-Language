## .DICT-maker-for-Rohingya-Language

1. Make rohingya_wordlist.combined file using [RohingyaCombinedMaker](https://github.com/arakaneserohingya/RohingyaCombinedMaker)
   which will look like this:



2. download dicttool_aosp.jar from this repo.
3. put dicttool_aosp.jar and rohingya_wordlist.combined in the same directory.

   To convert the rohingya_wordlist.combined file to a rohingya.dict file using dicttool_aosp.jar, you would need to run the following command in your terminal or command prompt:
bash

# Copy code
* java -jar /Users/ahkterhusin/PycharmProjects/aosp-dictionary-tools/dicttool_aosp.jar makedict -s /Users/ahkterhusin/PycharmProjects/aosp-dictionary-tools/rohingya_wordlist.combined -d /Users/ahkterhusin/PycharmProjects/aosp-dictionary-tools/rohingya.dict

This command assumes that:

* dicttool_aosp.jar is located at /Users/ahkterhusin/PycharmProjects/aosp-dictionary-tools/.
* rohingya_wordlist.combined is located at /Users/ahkterhusin/PycharmProjects/aosp-dictionary-tools/.
Make sure to replace the paths with the correct locations of your files on your system. After running this command, the rohingya.dict file should be created in the specified directory.
