import pyautogui
import keyboard

# Defina suas funções para cada tecla
def acao_f1():
    pyautogui.press('1')  # Simula a pressão da tecla 1

def acao_f2():
    pyautogui.press('2')  # Simula a pressão da tecla 2

def acao_f3():
    pyautogui.press('3')  # Simula a pressão da tecla 3

def acao_f4():
    pyautogui.press('4')  # Simula a pressão da tecla 4

# Loop para monitorar as teclas F1 a F4
while True:
    if keyboard.is_pressed('f1'):
        acao_f1()
    if keyboard.is_pressed('f2'):
        acao_f2()
    if keyboard.is_pressed('f3'):
        acao_f3()
    if keyboard.is_pressed('f4'):
        acao_f4()
