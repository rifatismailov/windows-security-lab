# Навчальний візит до Таллінна, Естонія
## Квітень 2024

**Організатор:** CybExer Technologies / e-Governance Academy  
**Фінансування:** EU — European Peace Facility (Cyber Defence Capacity Building)  
**Дати:** 8–18 квітня 2024  
**Учасники:** 12 осіб з України  
**Тренер:** Tanel Tetlov (penetration tester, NATO CCDCOE)

---

## Структура документів

### Довідкові документи
| Файл | Зміст |
|------|-------|
| [00_Course_Info_Package.pdf](00_Course_Info_Package.pdf) | Програма курсу Microsoft Active Directory |
| [00_Study_Visit_Agenda.pdf](00_Study_Visit_Agenda.pdf) | Повний розклад поїздки до Таллінна |

---

### Тренінг I: Microsoft Active Directory (10–12 квітня)

**День 1 — 10.04**
| Файл | Тема | Час |
|------|------|-----|
| [01_Overview_Windows_Central_Management_AD.pdf](01_Overview_Windows_Central_Management_AD.pdf) | Огляд централізованого управління Windows + AD | 09:00–10:45 |
| [02_Setting_up_ADDS.pdf](02_Setting_up_ADDS.pdf) | Розгортання Active Directory Domain Services | 11:00–14:45 |
| [05_PowerShell_Overview.pdf](05_PowerShell_Overview.pdf) | Основи Windows Scripting / WMI / PowerShell | 15:00–16:00 |

**День 2 — 11.04**
| Файл | Тема | Час |
|------|------|-----|
| [02_Setting_up_ADDS.pdf](02_Setting_up_ADDS.pdf) | Лаби: розгортання AD через консоль | 09:00–10:45 |
| [03_Join_Ubuntu_to_AD.pdf](03_Join_Ubuntu_to_AD.pdf) | Приєднання Linux (Ubuntu) до AD | 09:00–10:45 |
| [04_Windows_Events.pdf](04_Windows_Events.pdf) | Windows Events та пересилання подій | 11:00–13:00 |
| [05_PowerShell_Overview.pdf](05_PowerShell_Overview.pdf) | PowerShell scripting + remote management | 13:45–17:00 |

**День 3 — 12.04**
| Файл | Тема | Час |
|------|------|-----|
| [06_LAB_PowerShell_and_AD.pdf](06_LAB_PowerShell_and_AD.pdf) | Лабораторні роботи PowerShell + AD | 09:00–10:45 |
| [07_DSC_Desired_State_Configuration.pdf](07_DSC_Desired_State_Configuration.pdf) | Desired State Configuration — теорія | 11:00–13:00 |
| [07_DSC_Desired_State_Configuration.pdf](07_DSC_Desired_State_Configuration.pdf) | Лаби: розгортання AD через DSC | 13:45–14:45 |

---

### Додатковий блок: Windows Security (окремий модуль)

| Файл | Тема |
|------|------|
| [08_Additional_Windows_Security_Topics.pdf](08_Additional_Windows_Security_Topics.pdf) | Огляд: Mimikatz, BloodHound, AMSI, WPAD, SID History, AdminSDHolder, NLA, PowerUp |
| [09_LAPS.pdf](09_LAPS.pdf) | LAPS — керування паролями локальних адміністраторів |
| [10_IPSec.pdf](10_IPSec.pdf) | IPSec — шифрування мережевого трафіку |
| [11_Microsoft_Baselines.pdf](11_Microsoft_Baselines.pdf) | Microsoft Security Baselines — еталонні налаштування безпеки |

---

### Тренінг II: Linux (12, 15, 16 квітня)

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
