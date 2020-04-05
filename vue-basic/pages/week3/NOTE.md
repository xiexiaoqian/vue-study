# 第二周的文件导航

## date_format 格式化时间

- 插值表达式，函数，过滤器，计算属性简单使用（文本域还能输入x个字）

## score 足球比赛demo

- 计时器简单使用
  - 一个等号、两个等号与三个等号

    - ```
        //一个等号，界面数字从0直接变5
        data:{
            time: 0,
        }

        let time = setInterval(() => {
                this.time += 1
                if (this.time = 5) {
                    clearInterval(time)
                }
            }, 1000)
      ```

    - 后两个正常，但区别。。。
- 计时器结合计算属性
- 计时器结合进度条
- 注意
  - ```<dody></dody>```里面,不用写this去调用变量，即使是```@click=""```里面也不用
