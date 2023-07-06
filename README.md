# Creating-Hash-Values

On this project I was tasked with creating hash values to implement security controls to protect  my organization against a range of threats.

I started by displaying the contents of my current working directory:

![image](https://github.com/MarcoSantibanez/Creating-Hash-Values/assets/138132151/2c2cf718-b62b-4bad-8b4c-d796c7a1058f)

Then proceeded to analyse both files located in the directory:

![image](https://github.com/MarcoSantibanez/Creating-Hash-Values/assets/138132151/e38fb2fd-963b-4775-a234-5fd8f917aba5)

![image](https://github.com/MarcoSantibanez/Creating-Hash-Values/assets/138132151/d580dedc-8c49-4d50-b36f-009e0e4e4903)

Further analysed both files using sha256sum command to generate the hash values for both files:

![image](https://github.com/MarcoSantibanez/Creating-Hash-Values/assets/138132151/d32551b9-b79f-4e63-9552-92f149fda4e0)

Then used sha256sum command to generate the hash of the file1.txt file, and send the output to a new file called file1hash
& file2.txt file, and send the output to a new file called file2hash:

![image](https://github.com/MarcoSantibanez/Creating-Hash-Values/assets/138132151/03da6648-f464-4bb5-a75e-9e4514050b97)


Next used the cat command to display the hash values:

![image](https://github.com/MarcoSantibanez/Creating-Hash-Values/assets/138132151/01e35318-add1-4bd1-bf80-492f4cd6f0a3)

Used the cmp command to compare the hash values:

![image](https://github.com/MarcoSantibanez/Creating-Hash-Values/assets/138132151/6849ea68-daed-49fe-b6b6-14292e296153)

Summary: I was able to succesfully generate and compare digest. 





