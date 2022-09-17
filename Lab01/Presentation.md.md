﻿---
marp: true
---

# Лабораторная работа №1

## Установк а и конфигурация операционной системы на виртуальную машину

### Гудиева Мадина Куйраевна


---


#### Цель работы

##### Приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.


---



Я создала новую виртуальную машину, указав имя виртуальной машины - Info-sec, тип
операционной системы - Linux, RedHat, размер основной памяти виртуальной машины
 2048. Помимо этого я задала размер диска - 40 ГБ, проверила, что конфигурация
жесткого диска - загрузочный, VDI, динамический виртуальный диск

![1](01.png)

---

![2](02.png)

---


![3](03.png)

---


![4](04.png)


---

• После того, как виртуальная машина появилась в окне менеджера VirtualBox, я перешла в её настройки, где добавила новый привод оптических дисков и выбрала образ CentOS-7- x86\_64-DVD-2009.iso.

![5](05.png)

---

• Я запустила виртуальную машину и выбрала установку системы на жёсткий диск, установила язык для интерфейса.

![7](07.png)

---

![6](06.png)

---

• В качестве имени узла сети указала gudievamadina.localdomain

![8](08.png)


---


• Выбрала для установки сервер с GUI и средства разработки

![9](09.png)

---


• Проверив остальные данные на корректность и отключив KDUMP, я начала установку. В ходе установки я задала пароль root и пользователя gudievamadina согласно соглашению об именовании.

![10](10.png)

---

![11](11.png)

---


![12](12.png)

---


• Получила следующую информацию.

• 1. Версию ядра Linux (Linux version).
![13](13.png)

• 2. Частоту процессора (Detected Mhz

processor).
![17](17.png)

---

• 3. Модель процессора (CPU0).
![14](14.png)

---

• 4. Объем доступной оперативной памяти

(Memory available).
![15](15.png)

---

• 5. Тип обнаруженного гипервизора (Hypervisor

detected).
![16](19h.png)

---

• 6. Тип файловой системы корневого

раздела.
![17](20th.png)

---

• 7. Последовательность монтирования

файловых систем
![16](18.png)

