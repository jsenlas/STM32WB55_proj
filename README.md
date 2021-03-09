# STM32WB55_proj

# Changelist
v01 
pred touto verziou boli len inicializacne commity
Zacal som minimalizaciu (susciastky blizsie a hustejsie), napriek tomu, ze este nemam spatnu vazbu, no je lepsie ked si prejdem umiestnenie a rozlozenie vsetkych suciastok.
Differential pair pre USB W0.341mm Separator0.2mm to by malo zarucit 90Ohm impedanciu.
Upratovanie Silkscreenu
Pridane 3d Modely .step subory

v02 8.3.2021
- otrasovane
- vyplnene plochy GND
- opravene vsetky chyby, ktore vznikali pri design rules checku
- pridanych par obrazkov, v ktorych je ulozene nastavenie pre niektore operacie, hlavne zony

v03 9.3.2021
- opravene RF trasy - zaoblenie, solder mask, vzdialenost vzhladom na dlzku anteny
- posunute USB dalej, aby som vytvoril priestor a napravil tak dalsie chyby kde sa mi prekryvali suciastky

ToDo:
- doplnit "ohradu" z  GND vias okolo RF tras
- vyplnit priestor s vias na GND
- nepaci sa mi ako je poprepajane I2C (chaos) a USB (+ a - su prilis blizko pri sebe v USBLC6-2SC6)
