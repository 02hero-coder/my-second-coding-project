# my-second-coding-project
import time

password = "987"
atempts = int(3)
while atempts > 0:
    user_input = input("Enter password: ")
    if user_input == password:
        print("Welcome!")
        breakةةة
    else:
        atempts = atempts - int(1)
        print("Wrong! Remaining attempts:", atempts)
    if atempts == int(0):
        print("System Locked Please wait 10 seconds....")
        if atempts == int(0):
            time.sleep(10)
            atempts = int(3)
            for i in range(30, 0, -1):
                print("wait for", {i})
                time.sleep(1)
