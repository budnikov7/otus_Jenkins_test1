## Инициализация гитсинха (один раз)

// Основной хран
gitsync init -u DeployGit tcp://KyralesGun/Storage/storage.1ccr/StorageOtus f:\1C\Projects\otus_JenkinsExample\src\cf\
gitsync init -u DeployGit E:\1CBases\OTUS\Demo1_Storage C:\GIT\otus_Jenkins_test1\src\cf

// Хран Yaxunit
gitsync init -u DeployGit -e YAXUNIT tcp://KyralesGun/Storage/storage.1ccr/StorageOtus_yaxunit f:\1C\Projects\otus_JenkinsExample\src\cfe\yaxunit\
gitsync init -u DeployGit -e YAXUNIT E:\1CBases\OTUS\Demo1YaxStorage C:\GIT\otus_Jenkins_test1\src\cfe\yaxunit\

## Синхронизация с хранилищем

gitsync sync -u DeployGit tcp://KyralesGun/Storage/storage.1ccr/StorageOtus f:\1C\Projects\otus_JenkinsExample\src\cf\