# topshiriq
talaba={}
while True:
    ism=input("Ism kiriting: ")
    yosh=int(input("Yosh kiriting: "))
    manzil=input("Manzil kiriting: ")
    talaba[ism]=yosh,manzil.title()
    savol=input('yana talaba kiritaszmi(ha yoki yoq)')
    if savol=='yoq':
        break
for ism,value in talaba.items():
    print(ism.title(),':',value)
