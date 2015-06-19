__author__ = 'MaYaSeVeN'

from random import randint
results = []
result = 0
for i in range(2, 14):
    random_number = randint(0, 9)
    result += i * random_number
    results.append(random_number)
results = results[::-1]
results = map(str, results)
last_number = 11 - result % 11
print ''.join(results) + str(last_number)[-1]
