# remove-special-characters-from-input
This code can be used to remove any special characters and number from any text input
string='HE*L_LO NIiC3E DAY!!! G0OOD1 DAY5*_ T$H7ANK# YOU'
special=['*','_','i','3','!','0','1','5','-','$','7','#']
for i in special:
    string=string.replace(i,"")
print(string)
import re
new_str = re.sub('[^a-zA-Z0-9\n\.]', ' ', string)
print(new_str)
