# exercitii-in-Python
###inceput in python###
print ("Hello World")
print ("Salut!")
print (2)

a = 4
nume = "Ramon Nastase"
f = 6
com = 3.14j
adevarat = True

print (a)
print (nume)
print (f)
print (com)
print (adevarat)

print (type(a))
print (type(nume))
print (type(f))
print (type(com))
print (type(adevarat))

suma = a / f

print(suma)

if a > f:
  print ("#1 - variabila a este mai mare decat f")
elif a < f:
  print ("#2 - a < f")

  print ("Valoarea")

elif a == f:
  print ("#3 - Cele 2 variabile sunt egale")
else:
  print ("Nu este adevarat")


print("Hello World!")
print("Salut!")

a = 45.82 #this ia an int
nume = "Maria Atanasiu" #this is a string
f =45.82 #this is a float
com = 3.14j #this is a complex
adevarat = True

print(a)
print(nume)
print(f)
print(com)
print(adevarat)

print(type(a))
print(type(f))
print(type(com))
print(type(nume))
print(type(adevarat))

suma = a + f
print (suma)

#comparare
if a > f:
  print ("#1 - variabila a este mai mare decat f")
elif a < f:
  print ("#2 - a < f")
  sumb = a - f
  print ("Valoarea lui sumb este:", sumb)
elif a == f:
  print ("#3 - Cele 2 variabile sunt egale")
else:
  print ("Nu este adevarat")

#comparare

b = 102
c = -86

if b > c:
  print ("#1 - variabila b este mai mare decat c")
elif b < c:
  print ("#2 - a < f")
  sumd = b - c
  print ("Valoarea lui sumb este:", sumb)
elif b == c:
  print ("#3 - Cele 2 variabile sunt egale")
else:
  print ("Nu este adevarat")

#functia noastra

def comparare(nrA,nrB):
 print("###RULEZ FUNCTIA###")
 if nrA > nrB:
   print ("#1 - variabila nrA este mai mare decat nrB")
 elif nrA < nrB:
   print ("#2 - nrA < nrB")
   sumd = nrA + nrB
   print ("Valoarea lui sumb este:",sumd)
 elif nrA == nrB :
   print ("#3 - Cele 2 variabile sunt egale")
 else:
   print ("Nu este adevarat")



comparare(20,21)
comparare(10,10)
comparare(41.51 , -32.12)


def inmultire(nrA , nrB):
  rez = nrA * nrB
  return rez

var = (inmultire(53, 21))
print(var)

def impartire():
  rez = 25 / 41
  return rez

imp = impartire()

print (imp)

sumFor =(0)

for x in range(1 , 1001):
  sumFor += x

print(sumFor)

rezFor = 0
for i in range(1, 50):
  rezFor = inmultire(i , i+1)
  print(rezFor)

textAnaliza = "masina are mai multe roti"
nrVocale = 0
for cuv in textAnaliza:
  if cuv == "a":
     print("am gasit vocala", cuv)
     nrVocale += 1
  elif cuv == "i":
     print("am gasit vocala", cuv)
     nrVocale += 1
  elif cuv == "e":
     print("am gasit vocala", cuv)
     nrVocale += 1
  elif cuv == "o":
     print("am gasit vocala", cuv)
     nrVocale += 1
  elif cuv == "u":
     print("am gasit vocala", cuv)
     nrVocale += 1
  else:
    print("litera nu este o vocala")

print("Numarul total de vocale" , nrVocale)



i = 20
f = 8.73
a = 'Python , '
b = "Imi place programarea in : "
c = "pentru ca suma acestor doua numere este: "
d= i + f
print(b + a + c )
print(d)
print(b[5:9])


###tipul###
notA = -1
test = 7.23
curs= "Introducere in Python"
print(type(notA))
print(type(test))
print(type(curs))


###introducere date de la tastatura###

nume=input("Cum te numesti ? ")
print("Te numesti " + nume )
varsta=int(input("Cati ani ai ? "))
print("Ai %d " %(varsta) )
anulcurent=2021
anulnasterii=anulcurent - varsta
d=anulnasterii +100
print("Vei implini 100 de ani , in anul %d " %(d))


a=20
b=15
print("%d vs %d "% (a , b))


###am printat cele doua valori, dar le-am convertit###
###  %d inseamna intiger si %s inseamna text###
if a > b:
  print("da,a este mai mare ca b")
else:
  print("a nu este mai mare ca b")
print("nu este adevarat")

###al doilea print va fi executat fiindca nu face parte din conditie###


###un alt exemplu###
a =15
b=15

if a > b:
  print("hey")

  ###asa functioneaza conditia while###
  n = 10
i = 0
while i < n:
  print("I este mai mic decat n: %d" %(i))
  i+=1

  ###while si if###
  n = 10
i = 0
while i < n:
  if i == 1:
    print("i are valoarea 1")

  print("I este mai mic decat n: %d" %(i))
  i+=1

elif a ==b:
  print("yup")

else:
  print("wow")

###nr par si nr impar###
a = int(input("numar introdus ?"))

if a%2==0:
  print("numarul introdus  este par")


else:
  print("numarul introdus  este impar")



###chestionar de intrebari###
nume = input("Cum te numesti ? ")
job = input("Ce job iti doresti ? ")
j = job

timp = int(input("In cat timp crezi ca poti obtine acest job ? "))
t = int(timp)

pasi =input("Care sunt pasii pe care trebuie sa-i urmezi pentru a te putea angaja ? ")
p= pasi

cand =input("Cand doresti sa incepi ? ")
c= cand

print("Candidatul" , nume , " a raspuns astfel la intrebarile de mai sus : ")
print("job-ul  : " , j)
print("timp : " , t)
print("pasi: " , p)
print("cand : " , c)


###este sau nu palidrom ? cuvinte care se citesc la fel de la stanga la dreapta###
a=input("Introdu un cuvant : ")
def my_function(a):
  return a[::-1]

a = my_function(a)
print(a)

if a ==my_function(a):
  print("Este un palindrom")

else:
  print("Nu este un palindrom")


#exercitiu functie ###
sum=0
for i in range(1 , 100):

  sum=sum + i
  print("Suma numerelor de la A la Z este : %d" %(sum))

i = 1
while i<100:
  i = i + 1
  print(i)

print("Suma numerelor de la A la Z este %d " %(sum))

###rezolvare exercitiu###
a = int(input(" Primul numar este : "))
b = int(input("Al doilea numar este : " ))
sum= 0
for i in range(a, b):
  sum =sum + i

while i in range( a , b):
  i= i+ 1
  print("Suma numerelor de la A la Z este : %d"  % (sum))

###exercitiul 3  numere pare divizibile cu 7###
i=0
while i < 3463:
  print(i)
  i=i+7
  if i%2==0:
   break
  i=i+7


###exercitiul 2 (a)###
list=["Mihai" , "Mihai" , "Lucian" , "Cristina" , "Tiberiu" , "Tiberiu" , "Lucian" , "Sorin" , "Ramona" , "Sorin"]

list.sort()
print(list)

x= len(list)
print(x)


###exercitiul 2 (b)###
count=list.count("Mihai")
print("The count of name " "Mihai is : " , count)
count=list.count("Cristina")
print("The count of name Cristina is : " , count )

count=list.count("Lucian")
print("the count of name Lucian is :" , count)

count=list.count("Mihai")
print("The count of name Mihai is : " , count)

count=list.count("Ramona")
print("tha count of name Ramona is :" , count)

count=list.count("Sorin")
print("The count of name Sorin is : " , count)

count=list.count("Tiberiu")
print("The count of name Tiberiu is : " ,  count)

###exercitiul 2 (c)###
for string in list:
  if list.count(string) > 1:
    print("the repetitve str is : " + string)

###exercitiul 2 (d)###
for string in list:
  if list.count(string)<2:
    print("the single elements are: " + string)


###exercitiul 2 (e)###
list.reverse()
print(list)

###exercitiul 2 (b)###
m=(("Cristina " "Lucian") , ("Lucian "  "Mihai") , "Mihai")

x=list(m)
print(x)
x=[('Cristina ' 'Lucian'), ("Lucian Mihai"),'Mihai']
a = x[0]
b=x[1]
c=x[2]
print(len(a))
print(len(b))
print(len(c))
print(len(a) , len(b) ,len(c))


n=(('Ramona', 'Sorin'), ('Sorin', 'Tiberiu') , 'Tiberiu')

y=list(n)
print(y)

y=[('Ramona' 'Sorin'), ('Sorin' 'Tiberiu') , 'Tiberiu']
d = y[0]
e=y[1]
f=y[2]

print(len(d))
print(len(e))
print(len(f))
print(len(d) , len(e) ,len(f))

j=len(a),len(b),len(c),len(d),len(d),len(f)
print(j)
newlist=list(j)
print(newlist)
newlist=[15, 12, 5, 11, 11, 7]
newlist.sort(reverse = True)
print("lista descrescatoare :%s" %(newlist))

###exercitiu1 doar numere pare###
a=[1,4,9,16,25,36,49,64,81,100]

new=[x for x in a if x%2==0]
print(new)

###exercitiul 2 ###

def my_func (txt):

 return txt [:: -1]
 print


txt = input("Intrdu un cuvant sau o fraza : ")
print(my_func(txt))

cu = my_func("python")
print(cu)
m= my_func("45678")
print(m)

###definire functie###

###exercitiul 1###
def my_function(x):
  print(len(x))
  return


cuvinte =input("introdu un cuvant sau o fraza : ")
y = len(cuvinte)
print(y)

a = "programare"
print(len(a))

b = "Python"
my_function(b)
print

c = "eu stiu sa programez si imi place ceea ce fac"
my_function(c)
print

d = "sunt entuziasmat"
my_function(d)
print


###exercitiu explicat in video###
valoare= input("Introdu un numar : ")


def calcul_suma(valoare):
  suma = 0
  for i in range(int(valoare) + 1):
    suma = suma + i

  return suma

rezultat = str(calcul_suma(valoare))
print("Suma pentru  "  + valoare + " este " + rezultat)

x1 = calcul_suma(3)
x2 = calcul_suma(4)

print(" valoare "  + str(x1)  +  "  "  + str(x2) )


a = 15
b = 15
if a < b :

 print("a este mai mare ca b")

elif a==b:

  print("yes")

else:

  print("nu este adevarat")


 ###exercitiu ###
t = int(input("introdu primul nr:"))
u = int(input("introdu al doilea nr:"))
w = u + 1

sumFor = 0

for q in range(t , w):
  sumFor += q

print("suma numerelor de la t la u este :", sumFor)

n = u
total_numbers = n
sum = 0

while (n >= 0):
  sum += n
  n -= 1
  print(" Suma numerelor de la t la u este :" , sum)

  # exercitiul 4 ,punctul 1

sumFor = 0

for x in range(1 , 101):

  sumFor = sumFor + x
  print(sumFor)


while sumFor:
  print(" Suma numerelor de A la Z este :" )
  print(sumFor)
  break

# exercitiul 4 , punctul 2
def myfunc(sumFor = sumFor + x):
  print(sumFor)

myfunc(sumFor)

x = 1
y = 100
sum1 = x + y

myfunc(sum1)

###creaza baza de date si aseaza in ordine alfabetica###
client1= {

 "Nume1":"Amalia" ,

 "Nume2":"Marius" ,

 "Nume3":"Sorin" ,

 "Nume4":"Andreea" ,

 "Nume5":"Camelia" ,

 "Nume6":"Nadia" ,

 "Nume7":"Ofelia" ,

 "Nume8":"Barbu" ,

 "Nume9":"Dana"
}

new=list(client1.values())
print(new)
print(sorted(new))


###produse intr-un dictionar###

produse= {
  "Pantofi":45.50,
  "Geaca":35,
  "Pulover":41.30,
  "Sacou":55,
  "Tricou":24
}
a=list(produse.items())
print(a)
a.pop(1)
a.pop(3)
print(a)
a.reverse()
print(a)
a.insert(1,('Pantofi' , 45.5))
print(a)
a.pop(3)
for x in a:
  print(x)


###baza de date exemplu cu masini###
cars= {
"car" :{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
},


"car1":{
  "brand":"Audi",
  "model": "S5",
  "year":2005
},


"car2" :{
  "brand": "Honda",
  "model": "Civic",
  "year": 1964
},


"car3 ": {
  "brand": "Ford",
  "model": "Focus",
  "year": 1964
},


"car4 ":{
  "brand": "Volkswagen",
  "model": "Tiguan",
  "year": 1964
},


"car5 ":{
  "brand": "Mini",
  "model": "One",
  "year": 1964
},


"car6" :{
  "brand": "Mini",
  "model": "Cooper",
  "year": 1964
},


"car7" : {
  "brand": "Renault",
  "model": "Megan",
  "year": 1964
},


"car8" : {
  "brand": "Renault",
  "model": "Sedan",
  "year": 1964
},


"car9" : {
  "brand": "Renault",
  "model": "Talisman",
  "year": 1964
},


"car10 ": {
  "brand": "Renault",
  "model": "Megan3CC",
  "year": 1964
},
}
a=list(cars.items())
print(a)
print(a[0])

###python obiecte###
class FamiliaMea():
  nr_persoane=0

  def __init__(self,nume,prenume,vara):
    self.nume=nume
    self.prenume=prenume
    self.vara=vara
    self.nr_persoane=self.nr_persoane + 1

  def Getnume(self):
    return self.nume

  def Setnume(self,nume):
   self.nume=nume

  def Getprenume(self):
    return self.prenume

  def Getvara(self):
    return self.vara
pasiuni=[("inot" , "plaja" , "party") , ("pozitia preferata : esuat pe plaja, ca balena"), ("pasiunea ei cea mai mare este Tik-Tok-ul")]

def __init__(motto):
 return ("Ador vara")


p1=FamiliaMea("Serbanescu" , "Ramona", pasiuni[0])
p2=FamiliaMea("Serbanescu", "Sorin", pasiuni[1])
p3=FamiliaMea("Serbanescu", "Madalina" , pasiuni[2])
p3.Setnume("Atanasiu")

print(p1.Getnume())
print(p1.Getprenume())
print(p1.Getvara())
print(p2.Getnume())
print(p2.Getprenume())
print(p2.Getvara())
print(p3.Getnume())
print(p3.Getprenume())
print(p3.Getvara())

###citirea si scrierea datelor intr-un fisier###

lista = []

with open("fisier1.txt") as f1:
    for linie1 in f1:
        linie1 = linie1.strip()
        lista.append(int(linie1))
f1.close()

with open("fisier2.txt") as f2:
    for linie2 in f2:
        linie2 = linie2.strip()
        lista.append(int(linie2))
f2.close()

with open("fisier3.txt") as f3:
    for linie3 in f3:
        linie3 = linie3.strip()
        lista.append(int(linie3))
f3.close()

lista.sort()

with open('rezultat.txt', 'w') as f4:
  f4.write(str(max(lista))+" "+str(len(lista))+"\n")
  for nr in lista:
    f4.write(str(nr)+"\n")
f4.close()

###model facut de ramon la scrierea si citirea datelor dintr-un fisier###
f = open("/Users/ofeliamariaatanasiu/Desktop/numere/fisier1.txt" , "r+")
text = " "
l = [" "]
while text != " ":
    text = f.read()
    l.append(text)
    print(text)
for i in l:
    print(i)

f.close()
