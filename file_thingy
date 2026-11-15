list_of_things = ['chrome', 'youtube', 'tiktok']

bad_things = ['viruses', 'malware', 'trojan', 'cryptoclipper', 'stealer']
   
   
def write():
    with open('list_of_programs.txt', 'w', encoding='utf-8') as file:
         for lists in list_of_things:
          file.write(f"{lists}/n")
def edit():        
    with open('list_of_programs.txt', 'a') as file:
       file.write(user_response) 
    
user_response = input("Enter what you want to enter into your computer " "> ").lower()

with open('list_of_programs.txt', 'a+') as file:
     file.seek(0)   
content = file.read

if content:
   print("Stuff is in here")
   edit()
else:
   write()

if user_response in bad_things:
    print("YOU CANNOT HAVE THAT IN YOUR COMPUTER")
    exit()
else:
    print("No bad things in this program")
if user_response in list_of_things:
   print("Its already there")
   exit()
else:
   print("It has been added to your list of programs")
list_of_things.append(user_response)

print(list_of_things)





   
