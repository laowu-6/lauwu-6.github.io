<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>脚重民愤 - 欢迎您</title>
    <style>
  
        /* 全局样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft YaHei", sans-serif;
        }
        
        body {
            background-color: #912020;
            color: #333;
            line-height: 1.6;
        }
        
        a {
            text-decoration: none;
            color: #912020;
        }
              
        /* 导航栏 */
        header {
            

            background-color: #912020;
            color: white;
            padding: 1rem 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 1.5rem;
        }
        
        nav ul li a {
            color: white;
            font-weight: 500;
            padding: 0.5rem 0;
            position: relative;
        }
        
        nav ul li a:hover {
            color: #757575;
        }
        

        /* 横幅 */
        .banner {
            
            height: 400px;
            background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url('school-banner.jpg');
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        .banner-content h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        /* 主要内容区 */
        .main-content {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 2rem;
            margin-bottom: 3rem;
        }
        
        /* 校园风采 */
        .campus-showcase {
            background: white;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        
        .section-title {
            font-size: 1.5rem;
            color: #912020;
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #666666;
        }
        
        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1rem;
            margin-bottom: 1.5rem;
        }
        
        .gallery-item {
            height: 180px;
            overflow: hidden;
            border-radius: 5px;
        }
        
        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s;
        }
        
        .gallery-item:hover img {
            transform: scale(1.05);
        }
        
        /* 最新动态 */
        .news-section {
            background: white;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        
        .news-list {
            list-style: none;
        }
        
        .news-item {
            padding: 1rem 0;
            border-bottom: 1px solid #eee;
        }
        
        .news-item:last-child {
            border-bottom: none;
        }
        
        .news-date {
            font-size: 0.9rem;
            color: #666;
        }
        
        .news-title {
            font-weight: bold;
            margin: 0.5rem 0;
            display: block;
        }
        
        /* 招生政策 */
        .admission-policy {
            background: white;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            margin-bottom: 2rem;
        }
        
        .policy-list {
            list-style-position: inside;
            padding-left: 1rem;
        }
        
        .policy-list li {
            margin-bottom: 0.8rem;
        }
        
        /* 报考指导 */
        .application-guide {
            background: white;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        
        .guide-item {
            margin-bottom: 1.5rem;
        }
        
        .guide-title {
            font-weight: bold;
            margin-bottom: 0.5rem;
            color: #912020;
        }
        
        /* 页脚 */
        footer {
            background-color: #333;
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        .footer-content {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        
        .footer-section {
            flex: 1;
            min-width: 250px;
            margin-bottom: 1rem;
        }
        
        .footer-section h3 {
            margin-bottom: 1rem;
            color: #912020;
        }
        
        .copyright {
            margin-top: 2rem;
            padding-top: 1rem;
            border-top: 1px solid #555;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
            }
            
            .gallery {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 1rem;
                justify-content: center;
            }
            
            nav ul li {
                margin: 0 0.5rem;
            }
        }
        
        @media (max-width: 480px) {
            .gallery {
                grid-template-columns: 1fr;
            }
            
            .banner {
                height: 300px;
            }
            
            .banner-content h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <!-- 导航栏 -->
    <header>
        <div class="container header-content">
             <img border="0" src="picture1.jpg" alt="picture1" width="1000" height="150">
            <nav>
                <ul>
                   
                    <li><a href="#campus">校园风采</a></li>
                    <li><a href="#news">最新动态</a></li>
                    <li><a href="#policy">招生政策</a></li>
                    <li><a href="#guide">报考指导</a></li>
                    <li><a href="#">联系我们</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <!-- 横幅 -->
    <section class="banner">
        <div class="banner-content">
            <h1>欢迎来到脚重民愤</h1>
            <p>饮水思源 爱国荣校 | 创办于2025年</p>
        </div>
    </section>
    
    <!-- 主要内容区 -->
    <div class="container">
        <div class="main-content">
            <!-- 左侧内容 -->
            <div class="left-content">
                <!-- 校园风采 -->
                <section id="campus" class="campus-showcase">
                    <h2 class="section-title">校园风采</h2>
                    <p>XX学校坐落于风景秀丽的XX区，占地面积200亩，拥有现代化的教学设施和优美的校园环境。学校秉承"厚德博学，求实创新"的校训，致力于培养德智体美劳全面发展的优秀人才。</p>
                    
                    <div class="gallery">
                        <div class="gallery-item">
                            <img src="campus1.jpg" alt="校园全景">
                        </div>
                        <div class="gallery-item">
                            <img src="campus2.png" alt="教学楼">
                        </div>
                        <div class="gallery-item">
                            <img src="campus3.png" alt="校长办公室">
                        </div>
                        <div class="gallery-item">
                            <img src="campus4.jpg" alt="学生宿舍">
                        </div>
                        <div class="gallery-item">
                            <img src="campus5.jpg" alt="体育场">
                        </div>
                        <div class="gallery-item">
                            <img src="campus6.jpg" alt="学生活动">
                        </div>
                    </div>
                    
                    <p>学校拥有先进的教学设备，包括多媒体教室，已超过全上海1%的学校</p>
                </section>
                
                <!-- 招生政策 -->
                <section id="policy" class="admission-policy">
                    <h2 class="section-title">招生政策</h2>
                    <p>XX学校2023年招生工作已全面启动，现将招生政策公布如下：</p>
                    
                    <ul class="policy-list">
                        <li><strong>招生对象：</strong>面向全市招收初生</li>
                        <li><strong>招生计划：</strong>计划招收高一新生人数不限</li>
                        <li><strong>报名时间：</strong>永久</li>
                        <li><strong>录取方式：</strong>在初生竞赛中获得优异成绩</li>
                
                        <li><strong>收费标准：</strong>按照校长的经济需求执行</li>
                        <li><strong>奖学金政策：</strong>设立优秀新生奖学金，奖金为-1000元</li>
                    </ul>
                    
                    <p>更多详情请咨询招生办公室：13391282939</p>
                </section>
                
                <!-- 报考指导 -->
                <section id="guide" class="application-guide">
                    <h2 class="section-title">报考指导</h2>
                    
                    <div class="guide-item">
                        <h3 class="guide-title">如何填报志愿</h3>
                        <p>接头地点德宏路114514号，只收现金。</p>
                    </div>
                
                    
                    <div class="guide-item">
                        <h3 class="guide-title">常见问题解答</h3>
                        <p><strong>Q: 学校提供住宿吗？</strong><br>
                        A: 我校为远道学生提供住宿，1000人大通铺，不配备空调、卫生间。</p>
                        
                        <p><strong>Q: 学校有实验班吗？</strong><br>
                        A: 没有。我校不拿学生做实验。</p>
                    </div>
                </section>
            </div>
            
            <!-- 右侧内容 - 最新动态 -->
            <aside id="news" class="news-section">
                <h2 class="section-title">最新动态</h2>
                
                <ul class="news-list">
                    <li class="news-item">
                        <span class="news-date">2025-08-15</span>
                        <a href="#" class="news-title">我校学生获IMO金牌</a>
                        <p>在刚刚结束的国际数学奥林匹克竞赛中，我校高一(9)班刘伊同学荣获金牌...</p>
                    </li>
                    
                    <li class="news-item">
                        <span class="news-date">2025-08-10</span>
                        <a href="#" class="news-title">新校长上任</a>
                        <p>上海脚痛大学任命老吴担任上脚重民愤校长！...</p>
                    </li>
                    
                    <li class="news-item">
                        <span class="news-date">2025-08-05</span>
                        <a href="#" class="news-title">王健校长肛门受伤事件</a>
                        <p>2025年8月9日，王校长解手解了半天，大概觉得肛门不适，就命令王健飞副校长，拿甘油球为他润一润肛门...</p>
                    </li>
                    
                    <li class="news-item">
                        <span class="news-date">2025-08-28</span>
                        <a href="#" class="news-title">王健三难吴校长</a>
                        <p>海鳖曾欺井内蛙，大鹏张翅绕天涯。强中更有强中手，莫向人前满自夸。...</p>
                    </li>
                    
                    <li class="news-item">
                        <span class="news-date">2025-08-20</span>
                        <a href="#" class="news-title">王健校长见义勇为</a>
                        <p>脚重民愤一同学被困荒岛，朝天大喊“不要衡水模式！”后，王健校长立即骑着北极熊前来营救...</p>
                    </li>
                </ul>
                
                <div style="text-align: right; margin-top: 1rem;">
                    <a href="#">更多动态 &raquo;</a>
                </div>
            </aside>
        </div>
    </div>
    
    <!-- 页脚 -->
    <footer>
        <div class="container footer-content">
            <div class="footer-section">
                <h3>关于我们</h3>
                <p>脚重民愤创立于2025年8月，属于非法办学。</p>
            </div>
            
            <div class="footer-section">
                <h3>联系方式</h3>
                <p>地址：德宏路114514号</p>
                <p>电话：13391282939</p>
                <p>邮箱：y13391282939@163.com</p>
            </div>
            
            <div class="footer-section">
                <h3>快速链接</h3>
                <p><a href="#">学校官网</a></p>
                <p><a href="#">教学评价</a></p>
            
            </div>
        </div>
        
        <div class="container copyright">
            <p>&copy; 2025 脚重民愤 版权所有 | 设计制作：老吴</p>
        </div>
    </footer>
</body>
</html>
