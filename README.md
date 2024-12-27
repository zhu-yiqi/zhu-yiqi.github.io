<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yiqi Zhu</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
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
        }
        main {
            max-width: none;
            margin: 0;
            padding: 2rem;
            margin-left: 25%;
            width: 75%;
            box-sizing: border-box;
        }
        h1, h2, h3 {
            color: #333;
        }
        .info, .publications {
            margin-bottom: 2rem;
        }
        .info p, .publications ul {
            margin: 0.5rem 0;
        }
        .publications ul {
            list-style: none;
            padding: 0;
        }
        .publications li {
            margin: 1rem 0;
        }
        .publications a {
            color: #007BFF;
            text-decoration: none;
        }
        .publications a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            background: #f4f4f4;
            padding: 1rem;
        }
        .left-column {
            position: fixed;
            left: 0;
            transform: none;
            width: 25%;
            padding: 2rem;
            top: 0;
            height: 100vh;
            background: white;
            box-sizing: border-box;
        }
        .info {
            text-align: left;
            max-width: 600px;
            margin: 2rem auto;
        }
        .publications {
            max-width: 100%;
            margin: 0 auto;
            text-align: left;
        }
        .profile-info {
            flex-grow: 1;
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
            margin-top: 0.5rem;
            font-size: 0.9rem;
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .contact-info p {
            margin: 0;
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
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 0.5rem;
            color: #333;
        }
    </style>
</head>
<body>
    <header>
        <!-- Remove content from here -->
    </header>
    <main>
        <div class="left-column">
            <img src="./images/image.png" alt="Yiqi Zhu">
            <div class="profile-info">
                <br>
                <div class="name">Yiqi Zhu</div>
                <p style="margin: 0; color: #666;">Undergraduate Student</p>
                <p style="margin: 0 0 1rem 0; color: #666;">Tsinghua University</p>
                <div class="contact-info">
                    <p><i class="fas fa-map-marker-alt"></i>Beijing, China</p><br>
                    <p><i class="fas fa-envelope"></i><a href="mailto:zhu-yq22@mails.tsinghua.edu.cn">Email</a></p><br>
                    <p><i class="fab fa-twitter"></i><a href="https://x.com/StephenZhu0218" target="_blank">Twitter</a></p><br>
                    <p><i class="fas fa-graduation-cap"></i><a href="https://scholar.google.com/citations?user=pVSe6agAAAAJ" target="_blank">Google Scholar</a></p><br>
                </div>
            </div>
        </div>
        <section class="info">
            <h2>About Me</h2>
            <p>I am currently an undergraduate student at Department of Computer Science and Technology, Tsinghua University. I am honored to have the opportunity to work as a research intern with Professor <a href="https://nlp.csai.tsinghua.edu.cn/~ly/">Yang Liu</a> and <a href="https://lpeng.net/">Peng Li</a> on the topic of language agents and multimodal large language models since October 2023.</p>
            <p>My research interest broadly lies in artificial intelligence. Specifically, I am curious about the following three topics: 1) <em>How to build robust language agents to finish challenging tasks (e.g. discovery of scientific knowledge)?</em> 2) <em>How to utilize the generalization ability of foundation models in embodied scenrios and tasks?</em> 3) <em>How to empower foundation models with the ability of understanding and simulating the real world?</em></p> 
        </section>
        <section class="publications">
            <h2>Publications</h2>
            <ul>
                <li>
                    <strong>CoSpace: Benchmarking Continuous Space Perception Ability for Vision-Language Models</strong><br>
                    <strong>Yiqi Zhu*</strong>, Ziyue Wang*, Can Zhang, Peng Li, Yang Liu<br>
                    [<a href="https://thunlp-mt.github.io/CoSpace/">Homepage</a>] [<a href="https://github.com/THUNLP-MT/CoSpace">Code</a>]
                </li>
                <li>
                    <strong>AIGS: Generating Science from AI-Powered Automated Falsification</strong><br>
                    Zijun Liu*, Kaiming Liu*, <strong>Yiqi Zhu*</strong>, Xuanyu Lei*, Zonghan Yang*, Zhenhe Zhang, Peng Li, Yang Liu<br>
                    [<a href="https://agent-force.github.io/AIGS/">Homepage</a>] [<a href="https://github.com/AgentForceTeamOfficial/Baby-AIGS">Code</a>] [<a href="https://arxiv.org/abs/2411.11910">Paper</a>]
                </li>
                <li>
                    <strong>Browse and Concentrate: Comprehending Multimodal Content via prior-LLM Context Fusion</strong><br>
                    Ziyue Wang*, Chi Chen*, <strong>Yiqi Zhu</strong>, Fuwen Luo, Peng Li, Ming Yan, Ji Zhang, Fei Huang, Maosong Sun, Yang Liu<br>
                    [<a href="https://thunlp-mt.github.io/Brote/">Homepage</a>] [<a href="https://github.com/THUNLP-MT/Brote">Code</a>] [<a href="https://arxiv.org/abs/2402.12195">Paper</a>]<br>
                    <strong><em>ACL 2024 (Oral)</em></strong><br>
                </li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Yiqi Zhu. All rights reserved.</p>
    </footer>
</body>
</html>