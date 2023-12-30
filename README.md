# sentinelLoop2



def sentinel_loop():
    total = 0
    count = 0
    xstr = input("What is a number, empty to quit: ")
    while xstr != "":
        x = float(xstr)
        total += x
        count += 1
        xstr = input("What is a number, empty to quit: ")
    print("Average of the numbers is", total / count)

sentinel_loop()
