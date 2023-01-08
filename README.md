# Windows 10-u yenidən möhtəşəm edin
Windows 10-u daha az zəhlətökən və istifadəyə yararlı etmək üçün düzəlişlər.

Bu skript nə edir:

1. Cortana-nı söndürür
2. Bildiriş Mərkəzini deaktiv edir
3. Windows Yeniləmələri quraşdırıldıqdan sonra avtomatik yenidən yükləmələri söndürür
4. Windows Girişindən Microsoft.com hesablarını deaktiv edir
5. Məlum fayl növləri üçün fayl uzantılarını göstərir
6. Explorer-i "Bu kompüter"ə açmaq üçün təyin edir
7. Gizli faylları göstərir (OS faylları daxil deyil)
8. OneDrive-ı silir
9. Masaüstündə "This PC" işarəsini göstərir
10. Tərtibatçı rejimini aktivləşdirir (Linux Alt Sistemi üçün tələb olunur)
11. Linux alt sistemini quraşdırır
12. Powershell Get-Help elementlərini yeniləyir
13. SMBv1-i deaktiv edir
14. Başlat Menyusunun bütün elementlərini çıxarır
15. WPAD-i söndürür

## Quraşdırma
Təəssüf ki, bu skriptdən istifadə etmək üçün "execution policy"-ni məhdudiyyətsiz olaraq təyin etməli olacaqsınız.

Administrator Powershell sorğusundan:
```
Set-ExecutionPolicy Unrestricted
cd MakeWindows10GreatAgain
.\MakeWindows10GreatAgain.ps1
Set-ExecutionPolicy Restricted
```

## Qeydlər

Bu skript Windows 10-un məxfilik problemlərindən heç birini həll etmir, çünki artıq bunu edən bir çox [tool'lar](http://www.ghacks.net/2015/08/14/comparison-of-windows-10-privacy-tools/) var.
