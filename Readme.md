##计划任务监听网络状态，断网重启网卡
解决网络出现黄色叹号问题
当出现黄色叹号（Internet不可用）时重启网卡。并记录日志
使用方式：
    windows计划任务中新建任务，常规设置运行任务使用Administrators用户，勾选使用最高权限运行，触发器填入tigger.xml，新建操作，powershell 启动 restart-netadpter.ps1。 
