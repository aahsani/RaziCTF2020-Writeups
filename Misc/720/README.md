## 720

In this challenge we have a zip file. After extracting this file, we see there is some other files. We use `binwalk` tool for each. Two of them have some other files, but just `printui.dll` has a file named `The Flag You Need.txt`. So extract these files using command below:  
```
binwalk -D=".*" printui.dll
```
There is a `98F4` zip file. Extract it. You have the `The Flag You Need.txt` file.   
Flag:  
```
RaziCTF{5pl17_4nd_j01n}
```
