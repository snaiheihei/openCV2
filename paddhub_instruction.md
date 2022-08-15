
paddlehub modules: https://github.com/PaddlePaddle/PaddleHub
---
hub 加载mode 预测示例：https://www.paddlepaddle.org.cn/hubdetail?name=realsr&en_category=ImageEditing
    -   import paddlehub as hub
        model = hub.Module(name='realsr')
        odel.predict('/PATH/TO/IMAGE/OR/VIDEO')
    - 启动hub serving: $ hub serving start -m realsr(xxxmode)
---

