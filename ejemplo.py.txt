
import pygame
import random

#crear una ventana 
#inicializar pygame
pygame.init()

#definir las dimensiones de la pantalla
dimensiones=(500, 500)
miVentana= pygame.display.set_mode(dimensiones)
x=250
y=250
while True:
    #rellenar de rojo
    miVentana.fill((255,0,0))
    
    pygame.draw.circle(miVentana,(255,255,255), (x, y), 50)
    pygame.display.update()
    
    X=random.randint(1,500)
    Y=random.randint(1,500)
    
 
