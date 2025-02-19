#  Labwork for RISC-V software toolchain

 RV_D1SK2_L1_C Program To Compute Sum From 1 to N

- we created a simple program in c:

![image](https://github.com/user-attachments/assets/d821cd6b-7930-484d-8ac2-f67a4e27e7cc)

- we got this as output:

![image](https://github.com/user-attachments/assets/4a1e425a-77ee-499b-9b14-f0850f48a47e)

- run in gcc compiler with O1 as an option, l means long integer p means pointer march for architecture which is riscv with 64 bit:

![image](https://github.com/user-attachments/assets/60ea760f-c028-44d2-8e36-e7c45de2f5e6)

- creating the file:

![image](https://github.com/user-attachments/assets/1c2e6c69-da84-46f1-8d21-d10abbbc5ca2)

- part of the assembly code using the following command :

![image](https://github.com/user-attachments/assets/b85f0efe-fbf2-49af-b852-aa508aa896c4)

![image](https://github.com/user-attachments/assets/f1b00470-1b36-4a16-b820-92f72948711e)

- the part we are interested in for our code:

![image](https://github.com/user-attachments/assets/3ee058fb-3f53-426f-808e-5e1b17a36329)

- when we used fast as an option, the number of instructions reduced from 15 to 12:

![image](https://github.com/user-attachments/assets/2d4ac4a5-dc58-4e90-8389-f082a2913438)

- we entered the follwoing command to debug, until means from the begining until this line:

![image](https://github.com/user-attachments/assets/c20293d8-db92-41de-8ba8-4943575bd42f)

- here we used reg to see the components of a0 after and before li command:

![image](https://github.com/user-attachments/assets/3adcd66b-4f06-43aa-bcae-0aefc17d3ca3)
