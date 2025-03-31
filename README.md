# cassandra-auto-install

Cassandra Auto Install playbook
- Установка CassandraDB
- Настройка кластера Cassandra
- Установка и настройка Cassandra экспортера (так же добавление конфигурации для consul)
- Понодный рестарт (мягкий drain и stop start ноды с health check)


# Плейбуки для конфигурации:
   # Установка однонодовой Cassandra
 - https://jenkins.emias.ru/jenkins/job/cassandra_install_and_configuration_node/ 

   # Сборка в кластер
 - https://jenkins.emias.ru/jenkins/job/cassandra_configure_cluster/

   # Установка экспортера
 - https://jenkins.emias.ru/jenkins/job/cassandra-install-exporter/

   # Понодный рестарт
 - https://jenkins.emias.ru/jenkins/job/cassandra_restart_nodes/

