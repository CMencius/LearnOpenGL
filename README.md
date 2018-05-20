# LearnOpenGL
編譯器版本 VS2015

環境安裝
1、安裝 nupengl.core
工具 -> NuGet包管理器 -> 程序包管理器控制臺 ->  控制臺裏輸入 Install-Package nupengl.core

2、设置GLAD  (GLAD is a popular and up-to-date library)

http://glad.dav1d.de/ 
 api gl 選 gl的版本 我這裏選擇的是跟我書本一樣的4.5  profile  選擇 Core   -----> 點擊Crete 會得到一個 .zip包

 解壓出來的include文件夾 覆蓋到 項目工程目錄下  packages\nupengl.core.0.1.0.1\build\native
 src 裏的glad.c 項目根目錄下  拉到項目中就可以了 


3、添加 opengl32.lib添加进连接器(windows 平台一般自帶)
 右擊項目 屬性->連接器->輸入 在附加項目依賴中寫上  ;opengl32.lib




