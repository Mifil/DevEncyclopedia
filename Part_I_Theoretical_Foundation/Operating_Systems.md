Навигационный шаблон: “Операционные системы”
(Стратегия → Тактика → Операция → Применение)

📌 1. Что такое операционная система?
Что означает термин “операционная система”?
Какие задачи она решает и зачем вообще нужна?
Чем отличается ОС от прошивки/bootloader?
Какие основные компоненты есть в любой ОС?
Как ОС соотносится с архитектурой компьютера?
🔹 Блок в главе: Введение, понятия, история, роль в системном программировании.

🧠 2. Основные функции ОС
Каковы ключевые функции операционной системы:
Управление процессами
Управление памятью
Файловая система
Ввод/вывод (драйверы)
Сетевая подсистема
Планировщик задач
Безопасность и права доступа
Какие типы ресурсов контролирует ОС?
Как реализуется многозадачность и многопоточность?
🔹 Блок в главе: Таблица функций ОС с примерами, интерфейс ядра.

🖥️ 3. Типы операционных систем
Какие типы ОС бывают:
Моно/многозадачные
Однопользовательские и многопользовательские
Реального времени (RTOS)
Серверные, встраиваемые, мобильные, настольные
Чем отличается RTOS от general-purpose ОС?
В каких случаях стоит использовать RTOS (например, FreeRTOS, Zephyr)?
Какие особенности ОС в embedded-устройствах?
🔹 Блок в главе: Сравнительная таблица, диаграмма вариантов ОС.

🧩 4. Архитектура ОС
Из чего состоит архитектура ОС:
Ядро (Kernel)
Системные вызовы (Syscalls)
Пользовательское пространство (User space)
Сервисы и демоны
Что такое монолитное ядро, микроядро, гибридное ядро?
Чем отличаются Linux, Windows, QNX, VxWorks?
Какой тип ядра используется в STM32 + FreeRTOS?
🔹 Блок в главе: Архитектурные схемы, плюсы/минусы разных ядер.

⚙️ 5. Управление процессами
Что такое процесс, поток (thread), контекст выполнения?
Как ОС создаёт, переключает, завершает процессы?
Что такое планировщик задач (scheduler) и как он работает?
Какие существуют типы планирования: round-robin, приоритетное, preemptive, cooperative?
Как отследить или управлять процессами в Linux (top, ps, kill)?
Что такое контекст переключения (context switch) и зачем он важен?
🔹 Блок в главе: Графика потоков, переключение задач, демо с RTOS.

🧠 6. Управление памятью
Как ОС управляет оперативной памятью?
Разделение памяти на сегменты
Виртуальная память
Стек и куча
Что такое paging, segmentation, MMU?
Как ОС обеспечивает защиту памяти между процессами?
Как работают аллокаторы (например, malloc, new) под капотом?
Что такое memory leak, stack overflow, heap corruption?
🔹 Блок в главе: Схемы памяти, пример трассировки утечки.

💾 Файловая система
Как ОС управляет данными на диске?
Что такое inode, каталоги, дескрипторы файлов?
Какие бывают файловые системы (ext4, FAT32, NTFS)?
Что такое монтаж файловых систем, разделы, точки монтирования?
Как работают системные вызовы (open, read, write, close)?
Что происходит при вызове fopen("data.txt", "r") в C?
🔹 Блок в главе: Дерево директорий, примеры файловых операций в C/Linux.

🔄 Ввод/вывод и драйверы
Как ОС взаимодействует с внешними устройствами?
Что такое драйвер устройства, абстракция устройства?
Как устроена модель device file в Linux (/dev/ttyUSB0, /dev/gpio)?
Что такое буферизация, асинхронный I/O, прерывания?
Как написать или использовать драйвер на STM32?
🔹 Блок в главе: Архитектура ввода-вывода, трассировка UART.

🔐 Безопасность, пользователи, права
Как ОС ограничивает доступ к ресурсам?
Что такое права доступа к файлам (chmod, chown)?
Как работает разграничение пользователей: root, sudo, guest?
Что такое UID, GID, ACL, SELinux?
Какие механизмы аутентификации и контроля сессий используются?
🔹 Блок в главе: Матрица прав, схемы безопасности, примеры скриптов.

🧪 Примеры ОС и применение
Какие ОС и RTOS популярны в практике:
Linux (Ubuntu, Debian, Yocto)
Windows
FreeRTOS, Zephyr, RT-Thread
QNX, VxWorks, μC/OS
Какие особенности имеет Linux как Embedded-платформа?
Как настроить и собрать своё ядро Linux?
Где применяются STM32 + FreeRTOS?
🔹 Блок в главе: Сценарии выбора ОС, примеры под STM32, Linux-сборки.

🧰 Инструменты и диагностика
Какие утилиты помогают изучать поведение ОС:
top, htop, strace, lsof, iotop
Как посмотреть таблицу процессов, использование памяти, файловые дескрипторы?
Как отлаживать ядро, трассировать системные вызовы?
Что такое gdb, valgrind, perf, dmesg, journalctl?
🔹 Блок в главе: Сессии диагностики, live-разбор логов.

✅ Чек-лист самопроверки
 Я знаю архитектуру ОС и её модули
 Я умею работать с процессами и потоками
 Я могу объяснить работу аллокатора и стек/куча
 Я понимаю, как ОС взаимодействует с устройствами
 Я могу отследить поведение процесса в Linux
 Я знаю особенности RTOS и могу выбрать подходящую под проект

📚 Куда копать дальше
Modern Operating Systems — Andrew Tanenbaum
Linux Kernel Development — Robert Love
OSTEP: Operating Systems: Three Easy Pieces (онлайн бесплатно)
👉 https://pages.cs.wisc.edu/~remzi/OSTEP/
Курсы: MIT 6.828, Harvard CS50, Embedded Linux от Bootlin
