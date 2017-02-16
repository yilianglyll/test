## 如何学习一个框架

  1. 弄清楚框架大概目录结构

      app目录  应用目录(我们MC层都在这里，以后代码大部分写到这里)

        app/Http目录   mc层在这里

        app/Http/routes.php  路由文件

      bootstrap目录  引导程序

      config目录   配置文件目录

      database目录  与数据库有关配置(数据迁移)

      public目录    入口文件目录

      resources目录  资源文件目录(V层在这里)

      vendor目录     composer安装包所在目录

      .env文件      坏境配置文件(修改数据库配置只能修改这里的)


  2.  搞清楚MVC目录分别在哪里

       




## Laravel路由

    路由： 指路。

    如果不配置路由，永远访问不了控制的方法。

	//app/Http/routes.php  路由文件


    // 当用户访问   域名/aa   访问test这个模板
    Route::get('/aa', function () {
      return view('test');
    });


## 控制器

   1. 创建控制器
