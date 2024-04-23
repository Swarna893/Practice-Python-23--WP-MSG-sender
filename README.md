# Practice-Python-23--WP-MSG-sender

# import pywhatkit as pyw
# pyw.sendwhatmsg('+919434750567', 'What are you doing....!!!', 20, 29)
# print("Message Delivered..!!!!!")


import pyautogui
import time
time.sleep(5)
count = 0
while count <= 100:
    pyautogui.typewrite("Happy New Yeal GHOTO DIDI....!!!!--"+str(count))
    pyautogui.press("enter")
    count = count+1

