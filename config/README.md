### 远程配置版本停用信息



#### 参数说明

  #### stop

    - deprecatedVersion - 要废弃的版本号，等于这个或者低于这个的都会被强制停用。

    - saveVersion - 要保留的版本号，若不想让某个低版本的停用，可以将对应的版本号加入这个列表里来。

    - info - 配置对话框的信息

    - button - 配置按钮的信息，这个地方可以是null，其中
            - text - 按钮文字
            - url  - 点击按钮后打开的网页 

  #### notice

    - id- 某一次通知的唯一标识，通知一次后可以以后不通知

    - alwaysShow- 是否每次进来都显示该通知

    - targetActivity- 只要名字相同的Activity都算，必须是继承于BaseActivity才行。

    - show- 作为远程配置是否显示通知的开关，打开后一律不显示

    - buttons - 按钮顺序按照 posi, negi, nutr排序


  #### log

    - enableUploadLog - 是否启用远程日志上报


  ### 关于按钮的url

- finish  - 关闭当前栈顶Activity

- backToHome - 退回到桌面

 - 添加QQ群  -
    mqqopensdkapi://bizAgent/qm/qr?url=http%3A%2F%2Fqm.qq.com%2Fcgi-bin%2Fqm%2Fqr%3Ffrom%3Dapp%26p%3Dandroid%26k%3D   +   官网生成的key

 