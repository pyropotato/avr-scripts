# avr-scripts
bash script to make compilation and upload to avr boards using using USBasp programmers on LInux easy.

Steps to follow:
1. In the compile script change the "-mmcu=atmega16" to the microcontroller used.
2. Make sure the script is in the same folder as your c program.
3. In your terminal use 'cd' to navigate to the folder containing the c program.
4. Execute "sudo bash ./compile_script program_name.c" without quotes. Replace program_name suitably.
5. In the upload_script change the -p m16 to your microcontroller.
6. To upload code to microcontroller execute "sudo bash ./upload_script program_name".
