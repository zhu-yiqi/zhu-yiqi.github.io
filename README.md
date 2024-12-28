<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yiqi Zhu's Homepage</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.7;
        }
        header {
            text-align: center;
            background: #f4f4f4;
            padding: 2rem;
            display: none;
        }
        .left-column img {
            width: 150px;
            margin: 0;
            display: inline-block;
        }
        main {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
            width: 100%;
            margin-left: 0;
            margin-top: 0;
            padding-left: 0;
        }
        h1, h2, h3 {
            color: #333;
        }
        .info, .publications {
            margin-bottom: 2rem;
            max-width: 1200px;
        }
        .info p, .publications ul {
            margin: 0.5rem 0;
        }
        .publications ul {
            list-style: none;
            padding: 0;
        }
        .publications li {
            margin: 2rem 0;
        }
        .publications a {
            color: #666;
            margin-right: 1rem;
            text-decoration: none;
        }
        .publications a:hover {
            color: #007BFF;
        }
        footer {
            text-align: center;
            background: #f4f4f4;
            padding: 1rem;
        }
        .left-column {
            position: relative;
            width: 100%;
            padding: 2rem;
            padding-left: 0;
            height: auto;
            text-align: left;
            display: flex;
            align-items: start;
            gap: 4rem;
        }
        .info {
            text-align: left;
            max-width: 100%;
            margin: 2rem auto;
        }
        .publications {
            max-width: 100%;
            margin: 0 auto;
            text-align: left;
        }
        .profile-info {
            text-align: left;
        }
        .social-links {
            margin-top: 0.5rem;
        }
        .social-links a {
            color: #666;
            text-decoration: none;
            margin-right: 1rem;
        }
        .social-links a:hover {
            color: #007BFF;
        }
        .contact-info {
            display: inline-block;
            text-align: left;
        }
        .contact-info p {
            margin: 0.5rem 0;
            display: block;
            width: 100%;
        }
        .contact-info i {
            width: 20px;
            margin-right: 0.5rem;
            color: #666;
        }
        .contact-info a {
            color: #333;
            text-decoration: none;
        }
        .contact-info a:hover {
            color: #007BFF;
        }
        .name {
            font-size: 28px;
            font-weight: 500;
            margin-bottom: 0.75rem;
            color: #333;
        }
        h2 {
            font-size: 32px;
            margin-bottom: 1.5rem;
            font-weight: 500;
        }
        p {
            font-size: 16px;
            line-height: 1.7;
            color: #24292f;
        }
        .publications strong {
            font-size: 18px;
            display: block;
            margin-bottom: 0.5rem;
        }
        .info p {
            margin: 0.5rem 0;
            max-width: 100%;
        }
        .header-content {
            display: none;
        }
    </style>
</head>
<body>
    <main>
        <div class="left-column">
            <img src="./images/image.png" alt="Yiqi Zhu">
            <div class="profile-info">
                <div class="name">Yiqi Zhu</div>
                <p style="margin: 0; color: #666;">Undergraduate Student, Tsinghua University</p>
                <p style="margin: 0; color: #666;">Email: zhu-yq22@mails.tsinghua.edu.cn</p>
                <div class="contact-info" style="display: flex; flex-wrap: nowrap; gap: 1.5rem; margin-top: 1rem; white-space: nowrap;">
                    <p><i class="fas fa-map-marker-alt"></i>Beijing, China</p>
                    <p><i class="fab fa-twitter"></i><a href="https://x.com/StephenZhu0218" target="_blank">Twitter</a></p>
                    <p><i class="fas fa-graduation-cap"></i><a href="https://scholar.google.com/citations?user=pVSe6agAAAAJ" target="_blank">Google Scholar</a></p>
                    <p><i class="fas fa-file-pdf"></i><a href="./CV.pdf" target="_blank">CV</a></p>
                </div>
                <p style="margin: 0; color: #666;">Last updated on Dec 29, 2024</p>
            </div>
        </div>
        <section class="info">
            <h2>About Me</h2>
            <p>I am currently an undergraduate student at Department of Computer Science and Technology, Tsinghua University. I enjoy great honor to work with Prof. <a href="https://nlp.csai.tsinghua.edu.cn/~ly/">Yang Liu</a> and <a href="https://lpeng.net/">Peng Li</a> on language agents and multimodal large language models since October 2023. I also work closely with Dr. Ziyue Wang and <a href="https://minicheshire.github.io">Zonghan Yang</a>.</p>
            <p>My research interest broadly lies in artificial intelligence. Specifically, I am curious about the following three topics: 1) <em>How to build robust language agents to finish challenging tasks (e.g. discover scientific knowledge)?</em> 2) <em>How to utilize the generalization ability of foundation models in embodied scenarios and tasks?</em> 3) <em>How to empower foundation models with the ability of understanding and simulating the real world (a.k.a. World Modeling)?</em></p> 
        </section>
        <section class="publications">
            <h2>Publications</h2>
            <ul>
                <li>
                    <strong>CoSpace: Benchmarking Continuous Space Perception Ability for Vision-Language Models</strong>
                    <b>Yiqi Zhu</b>*, Ziyue Wang*, Can Zhang, Peng Li, Yang Liu<br>
                    <span style="font-size: 1.2em;">
                        <a href="https://thunlp-mt.github.io/CoSpace/"><i class="fas fa-home"></i> Homepage</a> 
                        <a href="https://github.com/THUNLP-MT/CoSpace"><i class="fab fa-github"></i> Code</a>
                    </span>
                </li>
                <li>
                    <strong>AIGS: Generating Science from AI-Powered Automated Falsification</strong>
                    Zijun Liu*, Kaiming Liu*, <b>Yiqi Zhu</b>*, Xuanyu Lei*, Zonghan Yang*, Zhenhe Zhang, Peng Li, Yang Liu<br>
                    <span style="font-size: 1.2em;">
                        <a href="https://agent-force.github.io/AIGS/"><i class="fas fa-home"></i> Homepage</a>
                        <a href="https://github.com/AgentForceTeamOfficial/Baby-AIGS"><i class="fab fa-github"></i> Code</a>
                        <a href="https://arxiv.org/abs/2411.11910"><i class="fas fa-file-alt"></i> Paper</a>
                    </span>
                </li>
                <li>
                    <strong>Browse and Concentrate: Comprehending Multimodal Content via prior-LLM Context Fusion</strong>
                    Ziyue Wang*, Chi Chen*, <b>Yiqi Zhu</b>, Fuwen Luo, Peng Li, Ming Yan, Ji Zhang, Fei Huang, Maosong Sun, Yang Liu<br>
                    <span style="font-size: 1.2em;">
                        <a href="https://thunlp-mt.github.io/Brote/"><i class="fas fa-home"></i> Homepage</a>
                        <a href="https://github.com/THUNLP-MT/Brote"><i class="fab fa-github"></i> Code</a>
                        <a href="https://arxiv.org/abs/2402.12195"><i class="fas fa-file-alt"></i> Paper</a>
                    </span><br>
                    <strong><em>ACL 2024 Oral</em></strong>
                </li>
            </ul>
        </section>
    </main>
</body>
</html>