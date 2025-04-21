# AnimReader

This is a program indented for importing unity animations into blender.

Before even starting this program, I kinda almost gave up just because I couldn't find a fast yaml library that was well documented. The problem was that my original test file has above 5 million lines of data thus taking a lot of time to parse.

But after coming back to this project and finding out that Unity itself uses a custom optimized yaml library called [UnityYaml](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwilpJ7zw-iMAxXF4ckDHRwRJ5IQFnoECAkQAQ&url=https%3A%2F%2Fdocs.unity3d.com%2FManual%2FUnityYAML.html&usg=AOvVaw0E_syC0ijM1S_uKNUW69p3&opi=89978449), I was able to find a python library that supports this specific format. I am also using a yaml file I found off of a gitlab gist repo with a little under 6,000 lines of data. This file will be successfully parsed within mere seconds and is ideal for testing. I will put a link in the `tests` folder.


#TODO:
1. ~~Import yaml and parse in python at fast speeds (or implement a progress bar when parsing yaml).~~ No need as explained above.
2. Decipher the yaml and plan from there to possibly make a rig.

## License

All files in this current repository except for the `Armature_walk.anim` file located in the `tests` subdirectory fall under the GNU GPL v2.
