# HowToUseBackupRoR

* Pre-requisites

backup
whenever
slack

* It is for generate backup file using backup gem.

backup generate:model --trigger gerenciadorSala_backup --databases="mysql" \
 --storages="local" --compressors="gzip" --notifiers='slack'
