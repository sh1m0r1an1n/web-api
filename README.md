# Обрезка ссылок с помощью VK

Программа может укоротить любую длинную ссылку или посчитать клики по короткой, если эта короткая ссылка была сформирована через сервис VK.

### Как установить

Для работы программы нужен API VK. Где и как его получить, написано тут:
- [Сервисный токен приложения](https://id.vk.com/about/business/go/docs/ru/vkid/latest/vk-id/connection/tokens/service-token)
- [Создание приложения](https://id.vk.com/about/business/go/docs/ru/vkid/latest/vk-id/connection/create-application). Тип приложения - Web. Базовый домен - example.com. Доверенный Redirect URL - https://example.com.

Выглядит ключ так: 82a02da882a02da882a02da8a981b7f3cc882a082a02da8e4af9c41e8551329276dde72. Ключ нужно вставить в файл .env.

Python3 должен быть уже установлен. 
Затем используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).
 
