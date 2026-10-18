<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>相思 - 王维</title>
    <style>
        /* 全局样式，营造古风氛围 */
        body {
            background-color: #f7f4ed; /* 宣纸底色 */
            font-family: "KaiTi", "楷体", "STKaiti", serif; /* 优先使用楷体，更符合古诗韵味 */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            color: #3e3a36; /* 墨色 */
        }

        /* 诗歌卡片主体 */
        .poem-container {
            background-color: #ffffff;
            padding: 60px 80px;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08), inset 0 0 0 1px #e6ded1;
            text-align: center;
            max-width: 600px;
            width: 90%;
            position: relative;
        }

        /* 添加一个红色的印章效果装饰 */
        .poem-container::after {
            content: "诗";
            position: absolute;
            bottom: 30px;
            right: 40px;
            width: 40px;
            height: 40px;
            border: 2px solid #b33939;
            color: #b33939;
            font-size: 24px;
            line-height: 38px;
            border-radius: 4px;
            opacity: 0.7;
        }

        /* 标题样式 */
        h1 {
            font-size: 2.2rem;
            margin-bottom: 10px;
            letter-spacing: 5px;
        }

        /* 作者样式 */
        .author {
            font-size: 1.1rem;
            color: #7a7368;
            margin-bottom: 40px;
            letter-spacing: 2px;
        }

        /* 诗句样式 */
        .poem-content {
            font-size: 1.6rem;
            line-height: 2.2;
            letter-spacing: 3px;
            margin-bottom: 40px;
        }

        /* 翻译/解析样式 */
        .translation {
            font-family: "Microsoft YaHei", "微软雅黑", sans-serif; /* 翻译用黑体，方便阅读 */
            font-size: 1rem;
            line-height: 1.8;
            color: #666;
            text-align: left;
            background-color: #faf9f6;
            padding: 20px;
            border-left: 4px solid #d1c7b7;
            border-radius: 0 8px 8px 0;
            letter-spacing: 1px;
        }

        .translation-title {
            font-weight: bold;
            color: #3e3a36;
            margin-bottom: 10px;
            font-size: 1.1rem;
        }
    </style>
</head>
<body>

    <div class="poem-container">
        <h1>相思</h1>
        <div class="author">[唐] 王维</div>
        
        <div class="poem-content">
            红豆生南国，<br>
            春来发几枝。<br>
            愿君多采撷，<br>
            此物最相思。
        </div>

        <div class="translation">
            <div class="translation-title">【译文】</div>
            鲜红浑圆的红豆，生长在阳光明媚的南方，春暖花开的季节，不知又生出多少？<br>
            希望思念的人儿多多采集，小小红豆最能惹人相思。
        </div>
    </div>

</body>
</html>
