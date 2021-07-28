# kuber-14.1

# задача1
установлен миникуб выполены команды из задания

root@ubuntu2004:/home/user# kubectl get secrets
NAME                  TYPE                                  DATA   AGE
default-token-9r5k8   kubernetes.io/service-account-token   3      5h56m
domain-cert           kubernetes.io/tls                     2      5h20m


root@ubuntu2004:/home/user# kubectl get secret domain-cert
NAME          TYPE                DATA   AGE
domain-cert   kubernetes.io/tls   2      5h21m


root@ubuntu2004:~# ls
certs  domain-cert.yml  secrets.json  snap

root@ubuntu2004:~# ls certs/
cert.crt  cert.key

# задача2

Был создан деплоймент с примонтированым секретом файл 14122.yml

Был создан секрет из файла 14124.yml и под с этим секретом заданый через перемнные окружения файл 14123.yml

В файле 14125.jpg скрины вополнения команд
