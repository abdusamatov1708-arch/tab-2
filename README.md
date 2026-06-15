# tab-2

# ==============================================================================
# DASTUR TAVSIFI:
# Ushbu dastur foydalanuvchining shaxsiy ma'lumotlarini (ismi, yoshi, kasbi, 
# qiziqishlari va hayotiy maqsadlari) konsolga chiroyli formatda chiqaradi.
# Dasturda kamida 6 ta print(), maxsus bezaklar hamda sep/end parametrlari ishlatilgan.
# ==============================================================================

# 1-chaqiruv: Dastur sarlavhasi (Asosiy bezak)
print("=" * 60)
print("FOYDALANUVCHI HAQIDA MA'LUMOTLAR")
print("=" * 60)

# 2-chaqiruv: Ism va Yosh (sep= parametri bilan ajratilgan)
print("Foydalanuvchi:", "Ali Valiyev", "| Yoshi:", "20 da", sep="   ")

# 3-chaqiruv: Kasbi (maxsus minus belgisi bilan bezatilgan)
print("-" * 25, "Kasbi: Dasturchi va Tahlilchi", "-" * 25)

# 4-chaqiruv: Qiziqishlar (Matn oxiriga yangi qator o'rniga maxsus belgi qo'yiladi)
print("Qiziqishlari: Kompyuter o'yinlari, matematika va fizika masalalari. ", end="--> ")

# 5-chaqiruv: Qiziqishlarning davomi (end= tufayli shu qatordan davom etadi)
print("Shuningdek, kompyuter jihozlarini modernizatsiya qilish.")

# 6-chaqiruv: Hayotiy maqsad va yakuniy bezak
print("Hayotiy maqsad: Kuchli mutaxassis bo'lish va yirik loyihalarni yaratish.")
print("*" * 60)
