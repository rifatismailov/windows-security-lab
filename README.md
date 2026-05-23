# Структура документів

### Тренінг I: Microsoft Active Directory

| Файл | Тема |
|------|------|
| [01_Overview_Windows_Central_Management_AD_UA.md](01_Overview_Windows_Central_Management_AD_UA.md) | Огляд централізованого управління Windows + AD |
| [02_Setting_up_ADDS_UA.md](02_Setting_up_ADDS_UA.md) | Розгортання Active Directory Domain Services |
| [03_Join_Ubuntu_to_AD.pdf](03_Join_Ubuntu_to_AD.pdf) | Приєднання Linux (Ubuntu) до AD |
| [04_Windows_Events.pdf](04_Windows_Events.pdf) | Windows Events та пересилання подій |
| [05_PowerShell_Overview.pdf](05_PowerShell_Overview.pdf) | Основи Windows Scripting / WMI / PowerShell |
| [06_LAB_PowerShell_and_AD.pdf](06_LAB_PowerShell_and_AD.pdf) | Лабораторні роботи PowerShell + AD |
| [07_DSC_Desired_State_Configuration.pdf](07_DSC_Desired_State_Configuration.pdf) | Desired State Configuration |

---

### Тренінг I: Windows Security

| Файл | Тема |
|------|------|
| [08_Additional_Windows_Security_Topics.pdf](08_Additional_Windows_Security_Topics.pdf) | Огляд: Mimikatz, BloodHound, AMSI, WPAD, SID History, AdminSDHolder, NLA, PowerUp |
| [09_LAPS.pdf](09_LAPS.pdf) | LAPS — керування паролями локальних адміністраторів |
| [10_IPSec.pdf](10_IPSec.pdf) | IPSec — шифрування мережевого трафіку |
| [11_Microsoft_Baselines.pdf](11_Microsoft_Baselines.pdf) | Microsoft Security Baselines — еталонні налаштування безпеки |

---

### Тренінг II: Linux

| Файл | Тема |
|------|------|
| [12_Linux_Hardening.pdf](12_Linux_Hardening.pdf) | Захист Linux систем (hardening) |

---

## Логіка вивчення тем

```
01 Основи Windows / AD
  └── 02 Розгортання AD (ADDS)
        └── 03 Приєднання Linux до AD
              └── 04 Моніторинг (Windows Events)
                    └── 05 Автоматизація (PowerShell)
                          └── 06 Лаби PowerShell + AD
                                └── 07 Інфраструктура як код (DSC)
                                      └── 08 Додаткові теми безпеки
                                            └── 09 LAPS
                                                  └── 10 IPSec
                                                        └── 11 Microsoft Baselines
                                                              └── 12 Linux Hardening
```
