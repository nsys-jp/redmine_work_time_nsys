このフォークでは、redmine6系への対応を目的とした改修のみを実施します。
本家が対応した場合、更新を終了する予定です。
現在、[動作する]ところまで対応済み。一部背景色が正しく表示されない問題は追って対応する可能性があります。

In this fork, we will only implement modifications aimed at supporting Redmine 6.x.
If the original project provides support, we plan to discontinue updates.
Currently, it is [working] to the extent that it operates.
We may address the issue of some background colors not displaying correctly in the future.


---

WorkTime is a Redmine plugin to edit spent time by each user.

### Installation notes ###

* cd {RAILS_ROOT}/plugins
* git clone https://github.com/tkusukawa/redmine_work_time.git
* cd ../
* bundle exec rake redmine:plugins:migrate RAILS_ENV=production
* Restart Redmine
* Enable the module on the project setting page.
* Check the permissions on the Roles and permissions(Administration)

### Links ###

* http://www.redmine.org/plugins/redmine_work_time
* https://github.com/tkusukawa/redmine_work_time
* http://www.r-labs.org/projects/worktime/
