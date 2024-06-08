
import pyautogui
import keyboard

while True:
    if keyboard.is_pressed('q') == False:
        try:
            friends_enemy = pyautogui.locateOnScreen("friends_enemy.png", region=(),confidence=0.8)

            keyboard.press_and_release('p')
            print('Нажал ')
            pyautogui.sleep(20)
            keyboard.press_and_release('p')

            pyautogui.sleep(2040)
        except:
            print('gg')
