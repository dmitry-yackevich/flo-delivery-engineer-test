# flo-delivery-engineer-test
Тестовое задание для delivery engineer

Цель тестового — проверить знания python, terraform, k8s, aws api и общее понимание архитектуры приложения.

Нужно написать плагин для Sentry, который позволяет посылать sms алерты через AWS SNS

AWS Keys передавать через env vars. Sentry с плагином упаковать в docker container

Задачи со звездочкой, для тех, кому слишком легко

1*) Terraform модуль, который создает AWS SNS и настраивает доставку SMS

2*) Собрать плагин в python пакет

3*) Реализовать sms throttling с настраиваемыми значениями, по умолчанию 10 sms в минуту

4*) Собрать helm chart для деплоя всего решения

Useful links:
https://github.com/getsentry/docker-sentry/blob/master/git/Dockerfile

https://github.com/getsentry/sentry-plugins/tree/master/src/sentry_plugins
