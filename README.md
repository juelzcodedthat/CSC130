banana = float(input('How much is a banana : '))
apple = float(input('How much is a apple : '))
orange = float(input('How much is a orange : '))

average = (banana + apple + orange) / 3

average = (f'{average:.1f}')
currency = '$'

print(f' The formatted average is {currency + str(average)}')
