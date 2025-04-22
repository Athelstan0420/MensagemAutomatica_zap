    # pip install pywhatkit para enviar a mensagem;
    
    """
    #Comando para saber a posição do mouse no linux:
    sudo apt install xdotool
    em seguida,
    watch -n 1.0 xdotool getmouselocation
    """
    
    
    import pywhatkit
    import pyautogui
    import time
    
    def auto_zap():
            
        numero = "+55dddnumero"
        mensagem = ""
        hora = 4
        minutos = 5
    
        pywhatkit.sendwhatmsg(numero,mensagem,hora, minutos)
        time.sleep(70)
        pyautogui.moveTo(1328, 687)
        pyautogui.click()
    
    auto_zap()
    
    
    
    
