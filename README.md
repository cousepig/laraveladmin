"# laraveladmin" 

环境
This package requires PHP 7+ and Laravel 5.5

首先安装 laravel 5.5, 配置数据库连接.
composer create-project --prefer-dist laravel/laravel blog

Then run these commands to publish assets and config：
php artisan vendor:publish --provider="Encore\Admin\AdminServiceProvider"

At last run following command to finish install.
php artisan admin:install

Open http://localhost/admin/ in browser,use username admin and password admin to login.

安装文档：
http://laravel-admin.org/docs/#/zh/installation

在config/app.php 中设置 locale 为zh-CN


集成富文本编辑器wangEditor
git clone https://github.com/wangfupeng1988/wangEditor.git

composer require intervention/image -vvv
composer require laravel-admin-ext/config -vvv
composer require laravel-admin-ext/helpers -vvv
composer require laravel-admin-ext/log-viewer -vvv
composer require laravel-admin-ext/media-manager -vvv
composer require laravel-admin-ext/scheduling -vvv
composer require spatie/eloquent-sortable -vvv