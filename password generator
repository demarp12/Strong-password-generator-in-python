import json
import string
import random
import time
import requests
import pynput
char = string.ascii_letters + string.digits + '!@#$%^&*'
url = 'http://www.google.com'

names = json.loads(open('names.json').read())

try:
    while True:
        username = ''.join(random.choice(char) for i in range(10))
        print('Generating strong password: ' + username)
        time.sleep(1)
except KeyboardInterrupt:
    print('\nStopping process......') 

input('press enter to exit')
