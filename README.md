Фиксим тормоза в Discord и YouTube — умелец написал инструкцию по обходу любых замедлений. 

Делаем с помощью клиента AmneziaWG и конфига WARP. Так как само приложение  Wireaguard не работает в России, мы воспользуемся его улучшенной версией, защищенной от обнаружения системами DPI.

### Ловите способ:

  1. Для начала вырубаем GoodbyeDPI и другие софты, такие как VPN, которые могут помешать нормальной работе приложения;

  2. Заходим в консоль Google по этой [ссылке](https://shell.cloud.google.com/?pli=1&show=ide%2Cterminal)

  3. Вставляем следующую команду в консоль и ждем:

`curl -sSL https://raw.githubusercontent.com/ImMALWARE/bash-warp-generator/main/warp_generator.sh | bash`

  4. В конце получаем ссылку, по которой нужно перейти и скачать уже готовый конфиг **WARP**;

  5. Теперь качаем клиент AmneziaWG с официального репозитория GitHub, в котором мы будем использовать этот конфиг - [здесь](https://github.com/amnezia-vpn/amneziawg-windows-client/releases/download/1.0.0/amneziawg-amd64-1.0.0.msi)

  6. Как только загрузка будет завершена - запускаем прогу, жмем кнопку **«Добавить туннель»** в левом нижнем углу и выбираем наш файл WARP.conf;

  7 После проделанных действий выбираем сверху наш туннель и нажимаем **«Подключить»**.

**В течение короткого времени всё должно заработать. Может потребоваться перезапустить Discord.**
