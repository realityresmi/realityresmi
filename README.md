import random
import time
for i in range(1,2):
    print('Kura Başlıyor')
count = 0
total = int(input('Kurada kaç kişi var?'))

def draw(count , total):

    while total > count:
        list1 = []
        count += 1
        name = input('Katılımcıların ismi: ')
        list1.append(name)
    winner = random.choice (list1)
    print('kazanan...')
    time.sleep(1)
    print(3)
    time.sleep(1)
    print(2)
    time.sleep(1)
    print(1)
    time.sleep(1)
    print('^-' + winner +'-^')
draw(count , total)
