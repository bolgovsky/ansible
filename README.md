# Самоконтроль выполненения задания

---

В данном файле приведены **только ответы** ! Т.е. можно искать по **Ответ:**

---

Ход выполнения ДЗ изложен в выгрузке ``history``
[Step-by-step](https://github.com/bolgovsky/ansible/blob/main/step-by-step.txt)

---

1. Где расположен файл с `some_fact` из второго пункта задания?

**Ответ:** `./group_vars/all/examp.yml`

2. Какая команда нужна для запуска вашего `playbook` на окружении `test.yml`?

**Ответ:** `ansible-playbook -i inventory/test.yml site.yml`

3. Какой командой можно зашифровать файл?

**Ответ:** `ansible-vault encrypt group_vars/deb/examp.yml`

4. Какой командой можно расшифровать файл?

**Ответ:**  `ansible-vault decrypt group_vars/deb/examp.yml`

5. Можно ли посмотреть содержимое зашифрованного файла без команды расшифровки файла? Если можно, то как?

**Ответ:** да. `ansible-vault view  group_vars/el/examp.yml`

6. Как выглядит команда запуска `playbook`, если переменные зашифрованы?

**Ответ:** `ansible-playbook -i inventory/prod.yml site.yml --ask-vault-pass` 

9. Как называется модуль подключения к host на windows?

**Ответ:** `winrm`

10. Приведите полный текст команды для поиска информации в документации ansible для модуля подключений ssh

**Ответ:** `ansible-doc -t connection ssh`

11. Какой параметр из модуля подключения `ssh` необходим для того, чтобы определить пользователя, под которым необходимо совершать подключение?

**Ответ:** `remote_user`
