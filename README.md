## 1.
>1.
>> Я считаю что при в данном проекте лучше всего использовать неизменяему инфраструктуру, она позволит производить более быстрое масштабирование и обновление компонентов сервисов

>> мне кажется что использование центрального сервера позволит обспечить более лучший контроль, на центральном сервере можно разместить систему контроля версии, куда разработчики будут выкладывать свой код, так же с данного сервера будет удобней запускать неободимые инструменты для развертывания сервисов.

>> я думаю что при кроме как агентов terraform на конечных VM запускать не понадобиться

>> на первых этапах разработки при созданни нужных образов без инструментов управления конфигурации не обойтись, после того как необходимые образы будут собраны packer думаю что можно обойтись только terraform

>2.
>> я считаю что все инструменты которые использовась до этого проекта в нашей команде жизненно необходимы, так как каждый из выполняет свою роль, от создания образов до управления кластерами нового сервиса.

>3.
>> думаю имеет смысл развернуть свой сервер котороля версии

>На совещании имеет смысл задать следующие вопросы:

>> необходимо дополнительно подумать на счет преобретения серверых моoностей, так как возможен новый приток клиентов. и еще не совсем понятно какие мощности будут необходимы даже для разворачивания сервиса на одного клиента

>> Уточнить когда будет представлен конечное техническое задание

>> Если набросок технического задания уже существует то необходимо опредиться с командами для выполнения его этапов.


## 2.

```
pugachevvv@debian-vlad:~$ terraform --version
Terraform v1.1.6
on linux_amd64


```
