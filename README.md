## Aim - The T code CS15 only takes one material and then checks in the system for where used list in BOM via BAPI - CS_WHERE_USED_MAT
## But, with the following custom program, we can input multiple materials and then get the result of where used list. 

![image](https://github.com/user-attachments/assets/200d8872-9a31-4be5-bf89-41bd5f746eff)

## The program used here, wraps the standard program - RCS15001, which is called via CS15 in the MPP. 

![image](https://github.com/user-attachments/assets/df5540ba-80a6-4765-be54-fe3dce32e8cb)

### Test Case Used - 

#### BOM #1 

![image](https://github.com/user-attachments/assets/ddf8bff4-4fea-409e-9b54-c5a7e7de7436)


#### BOM #2 ( repeats the components in BOM1 )

![image](https://github.com/user-attachments/assets/07e92c07-6a87-4268-8795-a3a4401c57d5)



### Following is the output of the selection screen and the ALV. 
#### Selection Screen - 

![image](https://github.com/user-attachments/assets/5dff3970-147c-4e0b-bb1a-11241759d145)

![image](https://github.com/user-attachments/assets/954eb1b8-6443-423a-b5c2-d2fd38520520)

#### ALV - 

![image](https://github.com/user-attachments/assets/acbd75a7-94fb-494f-933c-9f8af8554035)

