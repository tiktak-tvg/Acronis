# Acronis

##### Установка агента acronis для ESXi

Устанавливаем ``агента acronis`` в Esxi на вкладке -> Виртульные машины.

Далее подключаем его.

![image_2025-03-15_13-33-45](https://github.com/user-attachments/assets/014c8917-c3c8-4d30-8421-d92d4f52bd1b)

IP адрес агента acronis

![image_2025-03-15_13-34-56](https://github.com/user-attachments/assets/2d5a6cca-e5d8-4a74-9ab0-fbc4c2d5b3cf)

Пароль для агента acronis можно оставить по умолчанию как у сервера Esxi или сделать свой.

![image_2025-03-15_13-36-32](https://github.com/user-attachments/assets/9fbf7d0a-6d6b-459e-aec8-7cc79a053f6f)

![image_2025-03-15_13-38-14](https://github.com/user-attachments/assets/b3174ffb-3827-41a3-a197-5afc2db4fbce)

##### Обновление и повторное развертывание виртуального устройства

Чтобы обновить виртуальное устройство версии 15.24426 или более поздней:

Загрузите пакет обновления для Agent for VMware со страницы Download (см. http://kb.acronis.com/latest для получения дополнительной информации).<br>
Сохраните файл tar.bz пакета обновления (или замените существующий) в следующем каталоге машины сервера управления:

- Windows: C:\Program Files\Acronis\VirtualAppliances\va-updates
- Linux: /usr/lib/Acronis/VirtualAppliances/va-updates

В веб-консоли Cyber Protect нажмите Настройки > Агенты.

Программа отобразит список машин. Машины с устаревшими виртуальными устройствами отмечены оранжевым восклицательным знаком.

Выберите машины, на которых необходимо обновить виртуальные устройства. Эти машины должны быть в сети.

Нажмите Обновить агент.

Выберите агент развертывания.

Укажите учетные данные учетной записи с правами администратора на целевой машине.

Выберите имя или IP-адрес, который агент будет использовать для доступа к серверу управления.

По умолчанию выбрано имя сервера. Вам может потребоваться изменить этот параметр, если DNS-сервер не может преобразовать имя в IP-адрес, что приводит к ошибке при регистрации виртуального устройства.

Ход обновления отображается на вкладке Activities (Деятельность ).
