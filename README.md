teksts = input("Ievadiet skaitli: ")
def countNumber(teksts):
  summa = 0
  for simbols in teksts:
    summa = summa + int(simbols)
    print(summa)
  return summa
countNumber(teksts)

