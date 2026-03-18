# Ransomware
Ransomware is malware that employs encryption to hold a victim’s information at ransom. A user or organization’s critical data is encrypted so that they cannot access files, databases, or applications. A ransom is then demanded to provide access.

# Attack Tactics
The gcdlcm folder is a library where people can import it inside their code to find out the GCD and LCM of any two numbers. It will work perfectly, but the gcdlcm library is ransomware. It will affect the specific folder of your computer, or you can destroy the entire operating system of your victim.

# Note
This project is designed solely for learning, research, and defensive cybersecurity development. Please, do not intend to harm people, as it can be destructive.

# Demo

## Folder Creation
When the demo starts, a dedicated test folder is automatically generated to simulate a user’s directory. This folder is used to demonstrate ransomware behavior in a safe and controlled environment, ensuring no real user files are affected.
<img width="951" height="566" alt="ram_sam_1" src="https://github.com/user-attachments/assets/80c44863-a5b9-422e-bc5c-37d4a5f0836f" />
<img width="914" height="488" alt="ram_sam_3" src="https://github.com/user-attachments/assets/d464cb1f-c672-4686-8d76-f99c6cd69376" />

## Folder Structure & Initial State
The folder contains sample files that act as targets for the simulation. Screenshots and logs illustrate the folder’s structure and the state of files before any encryption takes place, providing a clear starting point for the demo.
<img width="1445" height="981" alt="ram_sam_2" src="https://github.com/user-attachments/assets/2bde9445-d7fc-427d-96eb-f4f65e327052" />

## Run GCD-LCM Code
In this step, the demo executes the GCD-LCM code, which functions normally to calculate greatest common divisors and least common multiples. However, for demonstration purposes, a simulated “malicious code” has been injected into the script. When the code runs, it performs its intended mathematical calculations perfectly, while also illustrating how hidden or malicious logic can be embedded within seemingly harmless programs. This highlights the importance of code review, auditing, and safe execution practices, showing how malicious activity can hide inside legitimate code. Screenshots demonstrate both the correct output of the calculations and the execution of the injected logic in a controlled, safe environment.
<img width="1916" height="1029" alt="ram_sam_4" src="https://github.com/user-attachments/assets/21e77b8c-9a42-415f-811e-6343cafc7f32" />

## Encryption Simulation
The main script applies controlled transformations to the files, simulating ransomware activity. This process demonstrates how ransomware typically encrypts files, while keeping all changes fully reversible and safe. Screenshots show the folder after encryption, highlighting the changes in a visual and understandable way.
<img width="1550" height="979" alt="ram_sam_7" src="https://github.com/user-attachments/assets/c45b9e6e-607d-4613-b248-511e5fbe1d3a" />

## Decryption Process
Using decryption.py, the demo restores all files back to their original state. This step completes the full workflow, showing how encrypted files can be safely recovered. Screenshots display the folder after decryption, confirming that all files are intact and unchanged.
<img width="1222" height="640" alt="ram_sam_6" src="https://github.com/user-attachments/assets/55d7e496-8fd5-4d9a-ba18-7943b099eca8" />
<img width="1916" height="628" alt="ram_sam_8" src="https://github.com/user-attachments/assets/cc0b1b51-06ad-40e7-a36e-62909618acb6" />
