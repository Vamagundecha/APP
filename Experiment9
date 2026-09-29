import re 

text = """

Hello student !
For any queries,contact abc@gmail.com or teacher123@college.edu.
You can also conctact support@yahoo.com.
"""

email_pattern = r'[a-zA-Z0-9.%+-]+@[a-zA-Z0-9.-]+\,[a-zA-Z]{2,}'

emails=re.findall(email_pattern , text)

print("Email adresses found:")

for email in emails:
     print(email)
