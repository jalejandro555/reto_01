# reto_01
ANO BISIESTO
```
year=int(input("Ingrese un año: "));
mes=int(input("Ingrese un mes (1 - 12): "));
nm = "";
if (year % 4 == 0 and year % 100 != 0 or year % 400 == 0):
    match mes:
        case 1:
            ndias=31;
            nm="Enero";
        case 2:
            ndias=29;
            nm="Febrero";
        case 3:
            ndias=31;
            nm="Marzo";
        case 4:
            ndias=30;
            nm="Abril";
        case 5:
            ndias=31;
            nm="Mayo";
        case 6:
            ndias=30;
            nm="Junio";
        case 7:
            ndias=31;
            nm="Julio";
        case 8:
            ndias=31;
            nm="Agosto";
        case 9:
            ndias=30;
            nm="Septiembre";
        case 10:
            ndias=31;
            nm="Octubre";
        case 11:
            ndias=30;
            nm="Noviembre";
        case 12:
            ndias=31;
            nm="Diciembre";
        case _:
            print("Mes no valido");
    print (year, "si es bisiesto");
    print (nm, " ( Mes ",mes,") tiene ", ndias, " días.");
else:
    match mes:
        case 1:
            ndias=31;
            nm="Enero";
        case 2:
            ndias=28;
            nm="Febrero";
        case 3:
            ndias=31;
            nm="Marzo";
        case 4:
            ndias=30;
            nm="Abril";
        case 5:
            ndias=31;
            nm="Mayo";
        case 6:
            ndias=30;
            nm="Junio";
        case 7:
            ndias=31;
            nm="Julio";
        case 8:
            ndias=31;
            nm="Agosto";
        case 9:
            ndias=30;
            nm="Septiembre";
        case 10:
            ndias=31;
            nm="Octubre";
        case 11:
            ndias=30;
            nm="Noviembre";
        case 12:
            ndias=31;
            nm="Diciembre";
        case _:
            print("Mes no valido");
    print (year, "no es bisiesto");
    print (nm, " ( Mes ",mes,") tiene ", ndias, " días.")
```
    
