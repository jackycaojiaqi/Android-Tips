Mac 上彻底删除AndroidStudio的方法：

1／执行这些命令在命令行

rm -Rf /Applications/Android\ Studio.app
rm -Rf ~/Library/Preferences/AndroidStudio*
rm ~/Library/Preferences/com.google.android.studio.plist
rm -Rf ~/Library/Application\ Support/AndroidStudio*
rm -Rf ~/Library/Logs/AndroidStudio*
rm -Rf ~/Library/Caches/AndroidStudio*
2／如果你想删除全部项目

rm -Rf ~/AndroidStudioProjects
3／删除gradle关联文件 (caches & wrapper)

rm -Rf ~/.gradle
4／删除模拟器

rm -Rf ~/.android
5／删除android 工具

rm -Rf ~/Library/Android*
如果你想要完全清除的话，除了4，全部敲一下。
