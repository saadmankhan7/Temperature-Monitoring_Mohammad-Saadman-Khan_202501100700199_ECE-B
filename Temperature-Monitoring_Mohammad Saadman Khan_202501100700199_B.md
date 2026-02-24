# Temperature-Monitoring_Mohammad-Saadman-Khan_202501100700199_ECE-B
import random
import time

min_temp = float(input("Enter minimum temperature limit: "))
max_temp = float(input("Enter maximum temperature limit: "))

print("\nTemperature Monitoring Started...\n")

while True:
    temp = random.randint(0, 100)
    
    print("Current Temperature:", temp)

    if temp > max_temp:
        print("Alert: Temperature is too high")
    elif temp < min_temp:
        print("Alert: Temperature is too low")
    else:
        print("Temperature is within acceptable limit")

    print("-----------------------------")

    time.sleep(2)


    Enter minimum temperature limit: 10
Enter maximum temperature limit: 100

Temperature Monitoring Started...

Current Temperature: 42
Temperature is within acceptable limit
-----------------------------
Current Temperature: 32
Temperature is within acceptable limit
-----------------------------
Current Temperature: 62
Temperature is within acceptable limit
-----------------------------
Current Temperature: 65
Temperature is within acceptable limit
-----------------------------
Current Temperature: 27
Temperature is within acceptable limit
-----------------------------
