print("Hesap makinesine hoşgeldiniz.")

print("Bu uygulama Schmetterling tarafından kodlanmıştır.")

sayı1 = int(input("İlk sayıyı giriniz:"))
sayı2 = int(input("İkinci sayıyı giriniz."))
seçim = int(input("Lütfen yapmak istediğiniz işlemin numarasını yazınız:"))
if seçim == 1:
    print("Sonuç {}".format(sayı1+sayı2))

if seçim == 2:
    print("Sonuç{}".format(sayı1-sayı2))

if seçim == 3:
    print("Sonuç {}".format(sayı1*sayı2))

if seçim == 4:
    print("Sonuç{}".format(sayı1/sayı2))
