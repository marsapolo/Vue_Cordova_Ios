# Vue_Cordova_Ios
Vue + Cordova + Ios 打包尝试 
 
工作需要，之前尝试使用过Cordova环境，分别打包IOS和Android安装包。 
最近学习使用了VUE框架，试想将VUE框架build后的页面，通过Cordova打包成移动端的安装文件。 
在网上查找了一些资料，尝试可行。在参考别人文章的基础上，进行了再次整理。 
第一步 准备Cordova环境
第二步 准备VUE环境
第三步 修改VUE项目里面的配置
                  编译的时候遇到的问题，如果添加了<meta>标签后，会有白屏，就陆续删除<meta>语句，直到不会白屏。
                  Main.js文件中的语句，目前还没尝试出来有何区别。
                  Config文件夹下的index.js文件中，注意要修改的是build节点下的代码。
                  建议修改的时候，修改一个地方就npm run dev 一下，步步为营。
将编译后的文件，拷贝到Cordova目录下的www文件夹。（编译后的文件，双击index.html文件，应该可以看到内容）
在Cordova目录下，运行程序，应该可以成功看到反应了。
第四部 真机调试
                  更新MAC OS ，更新手机端的IOS系统，更新Xcode版本。
                  生成一个本机的证书，安装到手机的时候，记得要点击信任。
 
 
Cordova环境搭建
参考文章 http://cordova.axuer.com/#getstarted
 
VUE环境搭建
参考文件 https://segmentfault.com/a/1190000011275993
 
教你用Cordova打包Vue项目
参考文章 https://www.jianshu.com/p/25d797b983cd
 
Xcode9 无证书真机调试
参考文章  https://blog.csdn.net/zhenggaoxing/article/details/79042382
 

