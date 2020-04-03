
# ThinkPHP6 Valet Driver

拷贝 `ThinkPHP6ValetDriver.php` 文件到 `valet` 驱动文件夹 `~/.config/valet/Drivers` 。

**注意：如果你的系统下没在 config 目录下哪应该是在 驱动文件夹为：`~/.valet/Drivers`**

**备注：`$sitePath` 是你在执行 `valet link ` 命令时的目录地址**

关于文件中的三个方法 `serves` 、`isStaticFile` 和 `frontControllerPath` 方法的具体介绍可以通过(查看官网)[https://laravel.com/docs/5.6/valet#custom-valet-drivers]获得更多帮助。

## License
