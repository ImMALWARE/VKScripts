# Скрипт для скачивания всей музыки ВК + с обложкой + с текстом MusixMatch или Genius
[VKMusicDownloader](https://github.com/ImMALWARE/VKScripts/blob/main/VKMusicDownloader/VKMusicDownloader.py)
## Заполняем конфиг:
**vk_user_agent** - User Agent, который будет использоваться при скачивании. Лучше не трогать и оставить как есть.

**vk_katemobile_token** - токен от ВК от приложения Kate Mobile. Получать тут: https://oauth.vk.com/oauth/authorize?client_id=2685278&scope=1073737727&redirect_uri=https://oauth.vk.com/blank.html&display=page&response_type=token&revoke=1&slogin_h=76221ebe206a61f572.1311d3f9b4f42b1afc&__q_hash=aec2ca6a35a6e62c117fdb16395d7df0
(нужно скопировать строку от access_token= до &expires_in)

**genius_token** - токен от сайта Genius, получать тут [URL]https://genius.com/api-clients[/URL] (сначала надо создать аккаунт)

**owner_id** - с чьего аккаунта скачивать музыку (по ID профиля)

Если скрипт не сможет найти обложку или текст песни, потребуется вставить их в теги mp3 самому. Это можно сделать через AIMP Tag Editor или Mp3tag (https://www.mp3tag.de/en/download.html)
![image](https://github.com/ImMALWARE/VKMusicDownloader/assets/53017160/fbb258f4-4513-42b6-8c41-25c653a6bb7b)