# Налаштування Active Directory (Setting Up Active Directory)

---

## Сторінка 1

![Сторінка 1](images/02/page_001.png)

---

## Сторінка 2

![Сторінка 2](images/02/page_002.png)

# СТВОРЕННЯ ЛІСУ ACTIVE DIRECTORY ТА ПЕРШОГО ДОМЕНУ З КОНТРОЛЕРОМ ДОМЕНУ (Creating Active Directory Forest and First Domain With Domain Controller)

---

## Сторінка 3

![Сторінка 3](images/02/page_003.png)

**Спочатку отримайте доступ до сервера через RDP (Remote Desktop Protocol)**

- За замовчуванням RDP (Remote Desktop Protocol — протокол віддаленого робочого столу) **не ввімкнений** на щойно встановленому сервері
- Тому для першого підключення слід використовувати консольний доступ (console access), щоб увімкнути RDP

---

## Сторінка 4

![Сторінка 4](images/02/page_004.png)

**Натисніть «REMOTE CONSOLE» і увійдіть, використовуючи:**

- Логін: `administrator`
- Пароль: `Cool2Pass`

---

## Сторінка 5

![Сторінка 5](images/02/page_005.png)

**У диспетчері сервера (Server Manager) натисніть «Local Server» → «Remote Desktop» і виберіть «Allow remote….»**

---

## Сторінка 6

![Сторінка 6](images/02/page_006.png)

**Виберіть «Manage» → «Add Roles and Features» і натисніть «Next»**

---

## Сторінка 7

![Сторінка 7](images/02/page_007.png)

**Залиште вибраним «Role-based or feature-based installation» (Встановлення на основі ролей або компонентів) і натисніть «Next»**

---

## Сторінка 8

![Сторінка 8](images/02/page_008.png)

**Виберіть запропонований `dc1` зі списку і натисніть «Next»**

---

## Сторінка 9

![Сторінка 9](images/02/page_009.png)

**Виберіть «Active Directory Domain Services» (Служби домену Active Directory)**

---

## Сторінка 10

![Сторінка 10](images/02/page_010.png)

**У спливаючому вікні (popup) додайте всі компоненти (features) разом із запропонованими засобами управління (management tools)**

---

## Сторінка 11

![Сторінка 11](images/02/page_011.png)

**Натисніть «Next» у вікні вибору компонентів (features selection)**

---

## Сторінка 12

![Сторінка 12](images/02/page_012.png)

**У розділі «Active Directory Domain Services» натисніть «Next»**

---

## Сторінка 13

![Сторінка 13](images/02/page_013.png)

**Поставте прапорець «Restart the destination server automatically if required» (Автоматично перезапустити сервер призначення у разі потреби) і натисніть «Install»**

---

## Сторінка 14

![Сторінка 14](images/02/page_014.png)

**Після завершення встановлення натисніть «Close»**

---

## Сторінка 15

![Сторінка 15](images/02/page_015.png)

**Після встановлення натисніть на жовте сповіщення (yellow notification) і виконайте підвищення сервера до рівня контролера домену (promote the server to domain controller)**

---

## Сторінка 16

![Сторінка 16](images/02/page_016.png)

**У діалоговому вікні (dialog box) виберіть «Add new forest» (Додати новий ліс) і як ім'я кореневого домену (root domain name) використовуйте синтаксис:**

```
int.icXX.jc.crp
```

*де `XX` — номер студента (31 у прикладі)*

---

## Сторінка 17

![Сторінка 17](images/02/page_017.png)

**Виберіть функціональний рівень лісу та домену (forest and domain functional level)**

- Залиште обидва на рівні **«2016»**
- Введіть пароль DSRM (Directory Services Restore Mode): `Cool2Pass`
- Залиште вибраними можливості DNS та GC (Global Catalog)

---

## Сторінка 18

![Сторінка 18](images/02/page_018.png)

**Натисніть «Next»**

---

## Сторінка 19

![Сторінка 19](images/02/page_019.png)

**Залиште `INT` як ім'я NetBIOS (NetBIOS name)**

---

## Сторінка 20

![Сторінка 20](images/02/page_020.png)

**Залиште запропоновані шляхи до папок (folder options)**

---

## Сторінка 21

![Сторінка 21](images/02/page_021.png)

**Перегляньте вибрані параметри (Review selections) і натисніть «Next»**

---

## Сторінка 22

![Сторінка 22](images/02/page_022.png)

**Натисніть «Install»**

---

## Сторінка 23

![Сторінка 23](images/02/page_023.png)

**Комп'ютер буде автоматично перезавантажено**

---

## Сторінка 24

![Сторінка 24](images/02/page_024.png)

**Сервер тепер є контролером домену (domain controller) для щойно створеного домену**

---

*Кінець документа. Всього перекладено: 24 сторінки.*
