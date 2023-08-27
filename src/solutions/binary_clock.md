# Binäruhr
```py
import time
import os

def get_binary_time():
    hour = time.strftime("%H")
    minute = time.strftime("%M")
    second = time.strftime("%S")
    return get_binary(hour), get_binary(minute), get_binary(second)

def get_binary(number):
    binary = ""
    for i in range(0, 6):
        if int(number) % 2 == 0:
            binary = "0" + binary
        else:
            binary = "1" + binary
        number = int(number) / 2
    return binary

def print_binary_clock(hour, minute, second):
    os.system('cls')
    print("Binary Clock: ")
    print(hour)
    print(minute)
    print(second)

while True:
    hour, minute, second = get_binary_time()
    print_binary_clock(hour, minute, second)
    time.sleep(1)
```