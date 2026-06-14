# 🌿 Git

Git — A version control system accessible on every developer's computer. It makes it easy to branch and merge changes. At the same time, GitHub makes it much easier for both individuals and teams to use Git for version control and collaboration. 🤝


Here are some Git commands I used to create my portfolio on GitHub.

## task 1

##### Create, clone, push, and pull repositories.

```git
git init dmitriyskachkov                                    # Создайте репозиторий с тем же именем, что и ваше имя пользователя.
git clone git@github.com:skachkovdmitriy/skachkovdmitriy.git      # Cкопируйте репозиторий на свой компьютер в отдельную папку.
git clone git@github.com:testrusau/testrusau.git            # Скопируйте папку github.com/testrusau/testrusau на свой компьютер в отдельную папку
cd testrusau                                                
git push git@github.com:skachkovdmitriy/testrusau.git main:main    # Перенесите данные из репазитория testrusau в свой собственный
git commit -m "commited change description"                 # Откройте файл README.md и замените каждый блок отдельным коммитом: "git push"
git push 

```
## task 2

##### Creating and adding remote repositories

```git
git init sql                                                # Создайте отдельный репазиторий для портфолио.
git remote add sql https://github.com/skachkovdmitriy/skachkovdmitriy.git  # Подключить удаленный репазиторий к локальному
README.md edited manually                                   # Добавить ссылки на ваш репазиторий в файл README.md
git commit -m "commited change description"                 # Отправить изменения на удаленный репазиторий
git push                                                     



```