print("\nGoodmorning Students! Welcome to Phinma COC.")
print("------------------------------")
print("   "," **SHIFTS SCHEDULE**\n")
print("      ",   "Shift A\n")
print("      ",   "Shift B\n")
print("      ",   "Shift C\n")
print("------------------------------")
print("    "," *DAYS* ")
print("      ",   "1. Monday\n")
print("      ",   "2. Tuesday\n")
print("      ",   "3. Wednesday\n")
print("      ",   "4. Thursday\n")
print("      ",   "5. Friday\n")
print("      ",   "6. Saturday\n")
print("      ",   "7. Sunday\n")
print("------------------------------")
shift = input("What shift are you?")
if shift == 'A':
      print("------------------------------")
      print(" ", " DAYS IN SHIFT A\n ")
      print("", "1. Monday\n")
      print("", "2. Tuesday\n")
      print("", "3. Wednesday\n")
      day = int(input("What day today?\n"))
      if day == 1:
            print("--------------------------------------------------------------------------")
            print("        ",  " *REMINDER*")
            print("    ","You should wear the following according to it's day:\n")
            print("    ","MON/TUE/SAT - School uniform and ID\n")
            print("    ","WED/SUN     - Washing day and ID\n")
            print("    ","THU/FRI    - School uniform and ID\n")
            print("    ","If you only wear uniform without ID or only ID without any of the uniform ")
            print("    ","you can't enter the campus. \n")
            print("--------------------------------------------------------------------------")

            uniform = input(" Did you wear School uniform? ")
            Id= input(" Did you wear your ID? ")
            if uniform == 'Yes' and Id == 'Yes':
                  print("--------------------------------------------------------------------------")
                  print("   ", "You can enter the campus.")
            else:
                  print("   ", "You can't enter the campus.")

      if day == 2:
            print("--------------------------------------------------------------------------")
            print("        ", " *REMINDER*")
            print("    ", "You should wear the following according to it's day:\n")
            print("    ", "MON/TUE/SAT - School uniform and ID\n")
            print("    ", "WED/SUN     - Washing day and ID\n")
            print("    ", "THU/FRI    - School uniform and ID\n")
            print("    ", "If you only wear uniform without ID or only ID without any of the uniform ")
            print("    ", "you can't enter the campus. \n")
            print("--------------------------------------------------------------------------")

            uniform = input(" Did you wear School uniform? ")
            Id = input(" Did you wear your ID? ")
            if uniform == 'Yes' and Id == 'Yes':
                  print("--------------------------------------------------------------------------")

                  print("   ","You can enter the campus.")
            else:
                  print("   ","You can't enter the campus.")
      if day == 3:
            print("--------------------------------------------------------------------------")
            print("        ", " *REMINDER*")
            print("    ", "You should wear the following according to it's day:\n")
            print("    ", "MON/TUE/SAT - School uniform and ID\n")
            print("    ", "WED/SUN     - Washing day and ID\n")
            print("    ", "THU/FRI    - School uniform and ID\n")
            print("    ", "If you only wear uniform without ID or only ID without any of the uniform ")
            print("    ", "you can't enter the campus. \n")
            print("--------------------------------------------------------------------------")

            washday = input(" Did you wear your Wash day uniform?")
            id = input(" Did you wear your ID?")
            if washday == 'Yes' and id == 'Yes':
                  print("--------------------------------------------------------------------------")

                  print("   ","You can enter the campus.")
            else:
                  print("   ","You can't enter the campus.")

if shift == 'B':
      print("------------------------------")
      print(" ", " DAYS IN SHIFT B\n"     
            "",  "4. Thursday\n"
            "",  "5. Friday\n"
            "",  "6. Saturday\n")
      a = int(input("What day today?\n"))
      if a == 4:
            print("--------------------------------------------------------------------------")
            print("        ", " *REMINDER*")
            print("    ", "You should wear the following according to it's day:\n")
            print("    ", "MON/TUE/SAT - School uniform and ID\n")
            print("    ", "WED/SUN     - Washing day and ID\n")
            print("    ", "THU/FRI    - School uniform and ID\n")
            print("    ", "If you only wear uniform without ID or only ID without any of the uniform ")
            print("    ", "you can't enter the campus. \n")
            print("--------------------------------------------------------------------------")

            school = input(" Did you wear your school uniform?")
            i = input(" Did you wear your ID?")
            if school == 'Yes' and i == 'Yes':
                  print("--------------------------------------------------------------------------")

                  print("   "," You can enter the campus.")
            else:
                  print("   ","You can't enter the campus.")
      if a == 5:
            print("--------------------------------------------------------------------------")
            print("        ", " *REMINDER*")
            print("    ", "You should wear the following according to it's day:\n")
            print("    ", "MON/TUE/SAT - School uniform and ID\n")
            print("    ", "WED/SUN     - Washing day and ID\n")
            print("    ", "THU/FRI    - School uniform and ID\n")
            print("    ", "If you only wear uniform without ID or only ID without any of the uniform ")
            print("    ", "you can't enter the campus. \n")
            print("--------------------------------------------------------------------------")

            s = input(" Did you wear your school uniform?")
            d = input(" Did you wear your ID?")
            if s == 'Yes' and d == 'Yes':
                  print("--------------------------------------------------------------------------")

                  print("   "," You can enter the campus.")
            else:
                  print("   ","You can't enter the campus.")
      if a == 6:
            print("--------------------------------------------------------------------------")
            print("        ", " *REMINDER*")
            print("    ", "You should wear the following according to it's day:\n")
            print("    ", "MON/TUE/SAT - School uniform and ID\n")
            print("    ", "WED/SUN     - Washing day and ID\n")
            print("    ", "THU/FRI    - School uniform and ID\n")
            print("    ", "If you only wear uniform without ID or only ID without any of the uniform ")
            print("    ", "you can't enter the campus. \n")
            print("--------------------------------------------------------------------------")

            c = input(" Did you wear your school uniform?")
            y = input(" Did you wear your ID?")
            if c == 'Yes' and y == 'Yes':
                  print("--------------------------------------------------------------------------")

                  print("   "," You can enter the campus.")
            else:
                 print("   ","You can't enter the campus.")


if shift == 'C':
      print("------------------------------")
      print(" ", " DAY'S IN SHIFT C\n"
            "", "7. Sunday\n"
            "", "1. Monday\n"
            "", "2. Tuesday\n")
      m= int(input("What day today?\n"))
      if m == 7:
            print("--------------------------------------------------------------------------")
            print("        ", " *REMINDER*")
            print("    ", "You should wear the following according to it's day:\n")
            print("    ", "MON/TUE/SAT - School uniform and ID\n")
            print("    ", "WED/SUN     - Washing day and ID\n")
            print("    ", "THU/FRI    - School uniform and ID\n")
            print("    ", "If you only wear uniform without ID or only ID without any of the uniform ")
            print("    ", "you can't enter the campus. \n")
            print("--------------------------------------------------------------------------")

            w = input(" Did you wear your Wash day uniform?")
            n = input(" Did you wear your ID?")
            if w == 'Yes'  and n == 'Yes':
                  print("--------------------------------------------------------------------------")

                  print("   "," You can enter the campus.")
            else:
                  print("   ","You can't enter the campus.")

      if m == 1:
            print("--------------------------------------------------------------------------")
            print("        ", " *REMINDER*")
            print("    ", "You should wear the following according to it's day:\n")
            print("    ", "MON/TUE/SAT - School uniform and ID\n")
            print("    ", "WED/SUN     - Washing day and ID\n")
            print("    ", "THU/FRI    - School uniform and ID\n")
            print("    ", "If you only wear uniform without ID or only ID without any of the uniform ")
            print("    ", "you can't enter the campus. \n")
            print("--------------------------------------------------------------------------")

            f = input(" Did you wear School uniform?")
            r = input(" Did you wear your ID?")
            if f == 'Yes' and r == 'Yes':
                  print("--------------------------------------------------------------------------")

                  print("   ","You can enter the campus.")
            else:
                  print("   ","You can't enter the campus.")

      if m == 2:
            print("--------------------------------------------------------------------------")
            print("        ", " *REMINDER*")
            print("    ", "You should wear the following according to it's day:\n")
            print("    ", "MON/TUE/SAT - School uniform and ID\n")
            print("    ", "WED/SUN     - Washing day and ID\n")
            print("    ", "THU/FRI    - School uniform and ID\n")
            print("    ", "If you only wear uniform without ID or only ID without any of the uniform ")
            print("    ", "you can't enter the campus. \n")
            print("--------------------------------------------------------------------------")

            o = input(" Did you wear School uniform?")
            t = input(" Did you wear your ID?")
            if o == 'Yes' and t == 'Yes':
                  print("--------------------------------------------------------------------------")

                  print("   ","You can enter the campus.")
            else:
                 print("   ","You can't enter the campus.")