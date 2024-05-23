<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>汪茹的个人网页</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@400;700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans SC', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #2f4f4f; /* 高级灰背景 */
            color: #f4f4f4; /* 浅色文字 */
            padding: 0 1em;
        }
        header {
            background-color: #3d5f5f; /* 深灰色 */
            color: white;
            padding: 2em 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        header h1 {
            font-family: 'Roboto', sans-serif;
            font-size: 2.5em;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 2em;
            background-color: #ffffff; /* 白色背景 */
            color: #333; /* 深色文字 */
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        section {
            margin-bottom: 2em;
        }
        h2 {
            font-family: 'Roboto', sans-serif;
            color: #3d5f5f; /* 深灰色 */
            border-bottom: 2px solid #3d5f5f;
            padding-bottom: 0.5em;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin-bottom: 1em;
        }
        .contact-info a {
            color: #3d5f5f; /* 深灰色 */
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        .profile-img {
            max-width: 150px;
            border-radius: 50%;
            display: block;
            margin: 0 auto 1em;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .content {
            line-height: 1.6;
        }
        .skills, .education, .experience, .projects {
            background-color: #f9f9f9;
            padding: 1em;
            border-radius: 8px;
            margin-bottom: 1.5em;
        }
        .experience-item {
            margin-bottom: 2em;
        }
        .experience-item h3 {
            color: #3d5f5f;
            margin-bottom: 0.5em;
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #3d5f5f; /* 深灰色 */
            color: white;
            margin-top: 2em;
            box-shadow: 0 -2px 4px rgba(0,0,0,0.1);
        }
        .projects a {
            color: #3d5f5f; /* 深灰色 */
            text-decoration: none;
        }
        .projects a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>汪茹的个人网页</h1>
    </header>
    <div class="container">
        <section id="about">
            <h2>个人简介</h2>
            <img src="一寸照-黑头发.JPG" alt="汪茹的照片" class="profile-img">
            <div class="content">
                <p>汪茹，23 岁，2025 届毕业生，现就读于北京师范大学，攻读汉语国际教育硕士学位。她具备丰富的实习经历，涵盖汉语教学、市场推广和内容运营。</p>
            </div>
        </section>
        <section id="contact">
            <h2>联系方式</h2>
            <ul class="contact-info">
                <li>电话: 13248280201</li>
                <li>邮箱: <a href="mailto:rue0109@gmail.com">rue0109@gmail.com</a></li>
            </ul>
        </section>
        <section id="education" class="education">
            <h2>教育背景</h2>
            <ul>
                <li>
                    <strong>北京师范大学</strong> - 汉语国际教育 硕士 (2022 年 09 月 – 2025 年 06 月)<br>
                    荣誉成就：学业一等奖学金
                </li>
                <li>
                    <strong>天津外国语大学</strong> - 汉语国际教育 本科 (2018 年 09 月 – 2022 年 06 月)<br>
                    荣誉成就：优秀毕业生、专业成绩前 2%、获保送名额
                </li>
            </ul>
        </section>
        <section id="experience" class="experience">
            <h2>实习经历</h2>
            <div class="experience-item">
                <h3>曼彻斯特大学孔子学院 - 汉语老师 (2023 年 09 月 – 2024 年 08 月)</h3>
                <ul>
                    <li><strong>汉语教学：</strong>教授初级成人汉语课程，负责Lowry Academy School汉语课程，HSK考试通过率达100%。</li>
                    <li><strong>活动策划：</strong>负责新年工作坊活动策划，协调活动时间及人员安排，新年活动预定数量增长30%。设计并组织“汉语角”跨文化交际活动，首次采用Padlet发布活动安排，与参与者及时互动，参与人数增长150%。</li>
                    <li><strong>官媒运营：</strong>运营孔院官方微信、微博、Instagram账号，撰写宣传及活动文案，策划及剪辑相关视频，粉丝数从200增长至400人。撰写年度成就回顾及规划新闻稿。</li>
                    <li><strong>市场推广：</strong>协助推广公共讲座、演出、音乐会等活动，制作宣传海报，与曼大其他学院、博物馆等单位沟通，确保活动顺利进行，累计参与人数1000+人。活动后输出高质量总结报告，优化推广流程，提升参与度30%。</li>
                </ul>
            </div>
            <div class="experience-item">
                <h3>光大证券 - 并购融资部实习生 (2022 年 12 月 – 2023 年 02 月)</h3>
                <ul>
                    <li><strong>制作底稿：</strong>按照最新进展修改招股书内容、更新底稿信息、审核表格数据的正确性。</li>
                    <li><strong>企业访谈：</strong>联系企业供应商，与负责人访谈，并抽取凭证，确保交易符合规范。</li>
                    <li><strong>撰写分析报告：</strong>根据行业上市公司招股书、年报等信息，分析行业发展趋势，提出投资建议，生成行业分析报告。</li>
                    <li><strong>拉取账户流水：</strong>拉取拟上市公司重要人员报告期内流水，规划路线并拍照取证，确保流水真实有效。</li>
                </ul>
            </div>
            <div class="experience-item">
                <h3>上海识装信息科技有限公司（识货app） - 中台运营实习生 (2022 年 01 月 – 2022 年 03 月)</h3>
                <ul>
                    <li><strong>活动策划：</strong>参与“年货节”“春节不打烊”“情人节”“三八女王节”等活动的策划、素材汇总、会场配置及数据回收工作，各活动成交额和日活跃用户均有所增长。</li>
                    <li><strong>内容运营：</strong>设计资源位配置路径及推荐策略，优化推送时机、文案及标签，提升用户参与度10%、成交额5%。</li>
                    <li><strong>数据监控：</strong>进行日常资源位排期、配置、数据统计和维护，实时监控PV、UV、GMV、ROI等数据，根据数据资源配置，优化SOP文档，制作运营周报。</li>
                </ul>
            </div>
        </section>
        <section id="projects" class="projects">
            <h2>项目经历</h2>
            <ul>
                <li>
                    <strong>自媒体账号运营</strong> (教育、生活 IP) - <a href="https://www.xiaohongshu.com/user/profile/5bbd5d1a18d7e30001987324?xhsshare=CopyLink&appuid=5bbd5d1a18d7e30001987324&apptime=1716471922">小红书账号 (“汪汪历险记”)</a> (2021 年 10 月 – 至今)<br>
                    <ul>
                        <li><strong>背景&定位：</strong>分析小红书同类优质图文，结合个人故事&成就，从0到1搭建个人账号，主要发布保研经验、出国教学实习经验及生活日常。</li>
                        <li><strong>内容运营：</strong>结合小红书用户属性、粉丝心理及账号定位，贴合平台调性制作图文内容并撰写文案，添加关键词和标签，增加曝光度。</li>
                        <li><strong>账号数据：</strong>总阅读量破120万，粉丝数1700+，点赞&收藏数2万+。生活类爆款图文单篇阅读量110万+，教育类爆款图文单篇阅读量3万+。</li>
                    </ul>
                </li>
            </ul>
        </section>
        <section id="skills" class="skills">
            <h2>专业技能</h2>
            <ul>
                <li>办公技能：熟练使用MS Office(Word, Excel, Powerpoint)、Xmind、PS、AU、Canva、ChatGPT</li>
                <li>语言技能：大学英语六级(530+)、大学日语四级、普通话一级乙等</li>
                <li>沟通能力：善于沟通、具备良好的口头和书面表达能力</li>
                <li>学习能力：执行力强，有领导力，能够快速熟悉新领域并学习相关知识</li>
            </ul>
        </section>
    </div>
    <footer>
        <p>汪茹的个人网页 © 2024</p>
    </footer>
</body>
</html>
