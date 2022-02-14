# HELLO-WORD
Time = int (input("Enter time in second:"))
print(f"{Time // 3600}.{(Time - (3600 * (Time // 3600))) // 60}.{Time - (3600 * (Time // 3600)) - (60*((Time - (3600 * (Time // 3600))) // 60))}")
