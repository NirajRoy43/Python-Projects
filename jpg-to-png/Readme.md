STEPS TO FOLLOW : Using VS Code
1. Make a new file with .py extension
2. Run the code below in Terminal

```
pip install pillow
```

3. Then type the following code
4. Replace "Your_File_Location"
```
from PIL import Image
im=Image.open(r"Your_File_Location.jpg")
im.save(r"Your_File_Location.png")
```
 
NOTE : You can also change jpg or png to PDF , just change the respective extensions !
