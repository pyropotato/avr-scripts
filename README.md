# avr compilation and upload scripts
bash script to make compilation and upload to avr boards using using USBasp programmers on LInux easy.

Steps to follow:
 
 **--Compilation:**
1. In the compile script change the ```-mmcu=atmega16``` to the microcontroller used.
2. Make sure the script is in the same folder as your c program.
3. In your terminal use ```cd``` to navigate to the folder containing the c program.
4. Execute:
    ``` bash 
    sudo bash ./compile_script program_name.c
     ``` 
    Replace ```program_name``` suitably.
    
    
 
 
 
 **--Uploading:** 
 
5. In the upload_script change the ```-p m16``` to your microcontroller.
6. Execute:
    ```bash
    sudo bash ./upload_script program_name
    ```
