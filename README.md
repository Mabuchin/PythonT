PythonT：学習覚書		
=======

This repository is Python tutorials
自分用覚書

Django Settingsで大体の場合やっておく設定
-----

1.Project作成
	django-admin.py startproject PROJECT_NAME

2.DBセットアップ
	python manage.py syncdb

3.App作成
	python manage.py startapp APP_NAME

4.Model定義
	PROJECT_NAME/models.py

5.モデルの有効化
	settings.pyのINSTALLED_APPに
	APPNAMEを追加
	
	TIMEZONE = 'Asia/Tokyo'
	タイムゾーン日本設定

	LANGUEGE_MODE = 'ja'
	言語設定

6.migrationファイルの作成
	Modelの定義を使って作成する
	python manage.py makemigrations APP_NAME

	


