本项目参照博客http://www.jianshu.com/p/789edb49f3d5实现了登录界面，欢迎界面，创建账户界面。
已解决的问题：1.开启欢迎界面后的闪屏问题，配置主题透明属性。
              2.登录后，销毁返回栈的activity
存在问题：1.登录账户的后端验证
          2.密码以及账户的保存
          3.登录界面activity会重复建立，如果改变加载方式的话依然存在界面闪屏问题
          4.登录后返回栈的activity虽然被销毁但是还未及时执行destroy方法
