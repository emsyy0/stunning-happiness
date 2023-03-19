# stunning-happiness
def toplama(x, y):
    return x + y

def cikarma(x, y):
    return x - y

def carpma(x, y):
    return x * y

def bolme(x, y):
    return x / y

print("Lütfen seçim yapın.")
print("1: Toplama")
print("2: Çıkarma")
print("3: Çarpma")
print("4: Bölme")

secim = input("Seçiminiz (1/2/3/4): ")

sayi1 = int(input("Birinci sayıyı girin: "))
sayi2 = int(input("İkinci sayıyı girin: "))

if secim == '1':
    print(sayi1, "+", sayi2, "=", toplama(sayi1, sayi2))

elif secim == '2':
    print(sayi1, "-", sayi2, "=", cikarma(sayi1, sayi2))

elif secim == '3':
    print(sayi1, "*", sayi2, "=", carpma(sayi1, sayi2))

elif secim == '4':
    print(sayi1, "/", sayi2, "=", bolme(sayi1, sayi2))

else:
    print("Geçersiz giriş")
