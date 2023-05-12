<div align="center">
<h1>php:fpm Sample</h1>
</div>

***

# Motivation

---
# Features

---
# Installation

```
├── README.md 				// This.
├── docker-compose.yml 		// 全体構成
├── docker_php				// PHP周り　
├── html 					// HTML/PHPコンテンツ
├── mysql 					// mysqlデータベースファイルマウントポイント
│     └── data 				// mysqlデータベースファイル
├── mysql_config 			// mysql設定マウントポイント
│     └── my.cnf 			// mysql設定ファイル
├── nginx_config 			// nginx設定マウントポイント
│     └── default.conf 		// nginx設定ファイル
├── php_config 				// php設定マウントポイント
│     └── php.ini 			// php設定ファイル
└── up.command 				// 起動スクリプト(MacOS)
```
```shell
docker-compose exec php composer install
```

---
# Usage

---
# Tips

---
# Note

---
# Author




