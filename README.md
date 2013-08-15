Fork Volley.

Основной репозиторий - https://android.googlesource.com/platform/frameworks/volley


Для поднятие upstream с google code

	$ git remote add upstream https://android.googlesource.com/platform/frameworks/volley
	$ git remote -v

для синхронизации с google code:

	$ git fetch upstream
	$ git merge upstream/master
