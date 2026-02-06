# ubiquitous-octo-broccoli

https://disk.yandex.ru/d/2o8dqaXOVwInbQ

# Отключить все эффекты анимации
kwriteconfig6 --file kwinrc --group Plugins --key kwin4_effect_blur false
kwriteconfig6 --file kwinrc --group Plugins --key kwin4_effect_fade false
# ... и аналогично для других эффектов


kwriteconfig6 --file kwinrc --group Compositing --key Enabled false
kwin_x11 --replace &  # или kwin_wayland --replace для Wayland
