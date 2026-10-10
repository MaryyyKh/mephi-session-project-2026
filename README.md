# Сессионный проект по курсу «Безопасность GNU/Linux»

Номер зачётной книжки: М265976

| Раздел | Что сделано | Файл отчёта |
|---|---|---|
| 1 | Установка РЕД ОС 8, имя хоста mephi-2026.domain.local, DHCP | ping.out |
| 2 | Обновление, установка nginx + libcap-ng-utils + tcpdump | dnf.out |
| 3 | /dev/sdb1 ext4, метка MEPHI_WEB, монтирование в /mephi-web | fstab |
| 4 | nginx запущен и в автозагрузке | journalctl.out |
| 5 | DAC/ACL на /data/mephi-2026, capabilities для tcpdump, SELinux enforcing | stat.out, getcap.out, getenforce.out |
| 6 | Запрет локального входа curator1/curator2, пароли 90 дней, minlen 12 | access.conf, pwquality.conf, login.defs |
| 7 | index.html в /mephi-web | curl.out, mephi-screenshot.png |
| 8 | Публикация | этот репозиторий |
