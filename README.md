# EC2 Instance Name Generator 

This Python script generates fun, randomized names for your EC2 instances.  
Each name is made up of:
- Your department name  
- A randomly chosen dog breed  
- A unique instance number  

Example: HR--Schnauzer-058



---

## How It Works

1. You are prompted for:
   - **Number of EC2 instances** you want names for  
   - **Your department name**  

2. The script randomly selects:
   - A dog breed (from `Schnauzer`, `Yorkie`, `Greyhound`, `Westie`, `Labrador`)  
   - A random number between `1` and `200`  

3. The result is printed for each requested instance in the format:

HR--Schnauzer-05
HR--Schnauzer-60
HR--Schnauzer-80

#Requirements
-Python 3.13.1 was used for this specific project
-Random module

#Installation
Run python ec2_name_generator.py
