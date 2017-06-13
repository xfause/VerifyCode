# VerifyCode

使用javascript编写的原生图形验证码插件。

文件目录如所示即可，使用方式见 index.html。

支持四种类型的图形验证码 ：纯数字number、纯字母letter、字母数字混合blend、算式equation。

创建div容器时自定义需要的类型即可。

P.S:算式类型验证码验证结果是算式计算的结果。

    使用equation类型验证码时 html页面中的js代码中的验证部分

    “var res = verifyCode.validate(document.getElementById("code_input").value);”

    改为

    “var res = verifyCode.validate4Equation(document.getElementById("code_input").value);”

    使用validate4Equation计算算式结果。
