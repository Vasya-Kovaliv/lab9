Програма використовує бібліотеку cryptography для роботи з еліптичними кривими та протоколом ECDH.
Інструкції для запуску програми:
Переконайтеся, що встановлено бібліотеку cryptography. Якщо вона відсутня, встановіть її за допомогою команди pip install cryptography.
Скопіюйте код в файл з розширенням .py.
У цьому прикладі програма генерує два особистих ключа та відповідні відкриті ключі для двох учасників протоколу.
Потім вона виконує обмін відкритими ключами і генерує спільний секрет для кожного учасника за допомогою функції generate_shared_secret().
Умова if __name__ == "__main__": визначає, чи виконується код безпосередньо з файлу, чи він був імпортований в інший модуль.
Також програма порівнює отримані спільні секрети та виводить результат.
