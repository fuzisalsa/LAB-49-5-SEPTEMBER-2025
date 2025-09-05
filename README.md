# LAB-49-5-SEPTEMBER-2025

**berikut beberapa video yang bersangkutan dengan Vidio yang akan di buat**
1. https://youtu.be/Eq55upUAJdo?si=VaajGSBBxYcOJz_E
2. https://youtu.be/YoasEqujUhM?si=5AkElW2B6st5PAmq
3. https://youtu.be/_pT4qXrS1PM?si=bxcmnWdRTiFsUtun
4. https://youtu.be/zdEQa6Cc4mI?si=uIyCmNNZrsGxfi1k
5. https://youtu.be/wTnkFQqAZpg?si=o2ed5CZsL-lMp-r5
6. https://youtu.be/-308OOgvROY?si=Z-ph3wqvLy_NDVCO
7. https://youtu.be/vH8iQSsjNgk?si=HHzogQt_9qytkbo7
8. https://youtu.be/QOiwfWnnYG4?si=glBlPIxCMTihsHB9
9. https://youtu.be/0H7sruQJJJ0?si=ceBaCcDrZi6Q3FSI
10. https://youtu.be/gQ7woFTu4zI?si=Knc3ObTIaTeM09VK

# konfigurasi
tentang: Advance DHCP, Firewall filter, Firewall mangle, Qudue tree, HTB, dan addresslist.

**1. Firewall filter**   
disini saya akan mlakukan konfigurasi agar client hanya bisa mengakses situs tertentu        

    a. buka winbox    
    b. lakukan konfigurasi dasar hingga terhubung ke internet   
    c. pilih menu ip > firewall 
    d. nah pertama kita akan memasukan website apa saja yang bole di akses ke addresslist di tab addresslist

![](wwww.PNG)

    e. lalu pilih tab firewall filter untuk melakukan blokir website yang tidak termasuk ke dftar addresslist dan memasukan addreslist website yang bole di akses tadi

*accept*

![](c1.PNG)

![](c2.PNG)

![](C3.PNG)

*drop*

![](d1.PNG)

![](d2.PNG)

    f. pengujian, di sini saya akan mencoba membuka tik tok

![](ttk.PNG)

*ternyata tidak bisa karena tiktok termasuk ke web yang tidak di izin kan dan akhirnya di drop di firewall filter*

    g. dan saya akan mencoba mengakses web web yang di perbolehkan tadi apa kah bisa atau malah di tidak? mari kita lihat

![](bisa.PNG)

*ternyata bisa berarti konfigurasi yang telah kita lakukan tadi berhasil*

**2.**
