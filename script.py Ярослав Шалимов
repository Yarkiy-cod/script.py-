temperatura = float(input("Введите температуру (в градусах Цельсия):"))
if temperatura <= 0:
    outfit = "Наденьте пуховик."
else:
     osadki = input("Есть ли осадки?(да/нет):")
     if 20 < temperatura < 30:
        if osadki == "да":
           outfit = "Наденьте футболку, шорты и дождевик."
        else:
           outfit = "Наденьте футболку и шорты."
     else:
        if temperatura > 0:

          if osadki == "нет":
            outfit = "Наденьте пальто."
          else:
            strong_osadki = input("Осадки сильные? (да/нет): ")

            if strong_osadki != "нет":
                outfit = "Наденьте пальто, резиновые сапоги и зонт."
            else:
                outfit = "Наденьте пальто и дождевик."


print(outfit)
