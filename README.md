start_time = time.time()

for i in range(20000000):
    pass

end_time = time.time()

exc_time = end_time - start_time
print('Execution time :', exc_time)
