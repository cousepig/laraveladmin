"# laraveladmin" 

###环境

requires PHP 7+ and Laravel 5.5

###首先安装 laravel 5.5, 配置数据库连接.

<code>composer create-project --prefer-dist laravel/laravel blog</code>

###发布assets和config：

<code>php artisan vendor:publish --provider="Encore\Admin\AdminServiceProvider"</code>

###完成安装.

<code>php artisan admin:install</code>

###登录方式

<code>http://localhost/admin/</code><br />
<code>username:admin</code><br />
<code>password:admin</code>

###安装文档：

http://laravel-admin.org/docs/#/zh/installation

###中文化：

在config/app.php 中设置 locale 为zh-CN

###集成富文本编辑器wangEditor

<code>git clone https://github.com/wangfupeng1988/wangEditor.git</code><br /><br />
<code>composer require intervention/image -vvv</code><br />
<code>composer require laravel-admin-ext/config -vvv</code><br />
<code>composer require laravel-admin-ext/helpers -vvv</code><br />
<code>composer require laravel-admin-ext/log-viewer -vvv</code><br />
<code>composer require laravel-admin-ext/media-manager -vvv</code><br />
<code>composer require laravel-admin-ext/scheduling -vvv</code><br />
<code>composer require spatie/eloquent-sortable -vvv</code><br />