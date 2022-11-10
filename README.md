tab [10, ,15,19,23,32,65,68,99]
elem=32
deb=0
fin=len (tab)-1
m (deb+fin) 1/2
trouve-False
while deb<=fin:
     if tab[m] ==elem:
         trouve-True
         break
     elif tab[m]>elem:
         fin m-1
     else:
         deb_m+1
     m (deb+fin) 1/2
 if trouve:
    print('I) indice de d\ 'élement recherché est +str(m))I
