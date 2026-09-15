# 6 взвод 1Б42П

Шестой взвод первой роты первого батальона 42-пропаганды, созданный на базе организации ООО "Кирилл Пятерка 42", специализируется на вайбкодинге софта для распространения 42 через нейрослоп

## Проекты

### Mimic 42

[Репозиторий](https://github.com/42-Z/Mimic42) | [Проект](https://github.com/orgs/42-Z/projects/2)

Мимик42 - это сервис для быстрого создания ботов в ТГ, которые иммитируют реальных людей. Нужно только ввести номер телефона и код, остальное поставится само, а нейросеть будет отвечать на сообщения. Агенты умеют делать с телеграмом все то же самое, что и люди: писать, комментировать, ставить реакции и т.д.

### Gen 42

| gen42.vercel.app

### Twitch RAG

| 



## Инструкция

### GitHub

Весь наш код и все наши проекты хранятся на GitHub. Гитхаб позволяет разным людям работать над приложением и не мешать друг другу. 
Вся история изменений хранится в репозитории, можно откатиться в любую точку в случае ошибки, работать в ветках, а потом сливать 
изменения в основную

Репозиторий - это папка под управлением Git (программа, которая следит за изменениями). Каждый сохранение версии - это commit. 
Репозиторий лежит на GitHub, и вы можете скачать его себе на компьютер, что-то поделать и сделать push обратно в общий удаленный репозиторий

Главная ветка `main`. Это код приложения, который лежит на сайте. Чтобы сделать обновление, надо создать от нее ответвление, 
отредактироать файлы, сделать коммиты и создать pull request (запрос на слияние в main)

У каждого нашего приложения есть Проект - доска с задачами. Issue - это карточка задачи, в которой все прописано. Ты берешь Issue, переносишь его в столбик "В работе" и приступаешь к работе

### Установка приложений

Скачать **Opencode** - приложение для вайбкодинга 

https://opencode.ai/ru/download

Установить **Bun** - рантайм для Typescript

Для Linux, macOS:
```bash
curl -fsSL https://bun.sh/install | bash
```

Для Windows:
```powershell
powershell -c "irm bun.sh/install.ps1|iex"
```

Установить **uv**

Для Linux, macOs:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Для Windows:
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

И потом Python через него скачать:
```
uv python install
```

Поставить **Git**

https://git-scm.com/install/

Установить **GitHub CLI**

https://cli.github.com/

Авторизоваться в gh-cli:

```
gh login
```

Выдать нужные права:

```
gh auth refresh -h github.com -s repo,admin:repo_hook,admin:org,admin:public_key,admin:org_hook,gist,notifications,user,project,delete_repo,write:packages,read:packages,delete:packages,admin:gpg_key,codespace,workflow,admin:enterprise,read:audit_log,offline_access
```
