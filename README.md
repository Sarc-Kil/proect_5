
# Proect_5

## Описание

Это проект, разработанный Имбецилом из группы П22-3.1, который демонстрирует систему авторизации с использованием Entity Framework и SQL Server. Проект включает в себя окна и окно подключения пользователей.

## Функционал

- **Окно входа**: Позволяет пользователям входить в систему.

- **Обработка ошибок**: Отображает ошибки при вводе данных в окне регистрации.
- **Окно подключения позователей**: Позволяет подключать пользователей.
- **Успешный вход**: Подтверждение успешного входа в учетную запись.


## Скриншоты

   1. Окно входа
![](https://github.com/Sarc-Kil/proect_5/blob/master/screnchot/Снимок5.1.PNG)
   2. Окно входа(Ошибка ввода)
![](https://github.com/Sarc-Kil/proect_5/blob/master/screnchot/Снимок5.2.PNG)
      
## Установка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/Sarc-Kil/proect_5.git
    ```
   2. Откройте проект в Visual Studio:
   - Запустите Visual Studio.
   - Выберите **"Открыть проект"** и перейдите к папке, куда вы клонировали репозиторий.
   - Выберите файл решения (`.sln`) и откройте его.

3. Убедитесь, что у вас установлен SQL Server и Entity Framework:
   - Убедитесь, что у вас установлен SQL Server (можно использовать SQL Server Express).
   - Убедитесь, что у вас установлены необходимые пакеты NuGet для Entity Framework.

4. Настройте строку подключения в файле `appsettings.json`:
   - Откройте файл `appsettings.json` в корне проекта.
   - Найдите раздел `ConnectionStrings` и измените строку подключения на вашу, например:
     ```json
     "ConnectionStrings": {
         "DefaultConnection": "Server=your_server;Database=your_database;User   Id=your_username;Password=your_password;"
     }
     ```

5. Обновите базу данных:
   - Откройте консоль диспетчера пакетов (Tools > NuGet Package Manager > Package Manager Console).
   - Выполните команду для применения миграций:
     ```bash
     Update-Database
     ```

6. Запустите проект:
   - Нажмите `F5` или выберите **"Запустить"** в меню, чтобы запустить приложение.
https://github.com/Sarc-Kil/proect_5/blob/master/screnchot/Снимок5.1.PNG
https://github.com/Sarc-Kil/proect_5/blob/master/screnchot/Снимок5.2.PNG
