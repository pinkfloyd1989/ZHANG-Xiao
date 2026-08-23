<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>张骁 - 个人主页</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 30px;
            background-color: #fafafa;
        }
        h1 {
            font-size: 2.2em;
            color: #1a1a1a;
            margin-bottom: 8px;
        }
        h2 {
            font-size: 1.5em;
            color: #0047ab;
            border-bottom: 2px solid #e6ecf5;
            padding-bottom: 6px;
            margin-top: 35px;
            margin-bottom: 15px;
        }
        .profile-header {
            display: flex;
            align-items: center;
            gap: 50px;
            margin-bottom: 20px;
        }
        .avatar {
            border-radius: 50%;
            width: 180px;
            height: 180px;
            object-fit: cover;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        .profile-info p {
            font-size: 1.2em;
            margin: 6px 0;
            color: #444;
        }
        ul {
            padding-left: 22px;
            margin: 10px 0;
        }
        li {
            margin-bottom: 8px;
        }
        .paper-item {
            margin-bottom: 12px;
            text-align: justify;
        }
        details {
            margin-top: 15px;
        }
        summary {
            list-style: none;
            display: inline-block;
            padding: 12px 30px;
            background: linear-gradient(135deg, #1677ff 0%, #0047ab 100%);
            color: #ffffff;
            border-radius: 10px;
            cursor: pointer;
            font-weight: 900;
            font-size: 18px;
            box-shadow: 0 4px 15px rgba(0, 71, 171, 0.4), inset 0 1px 0 rgba(255,255,255,0.2);
            border: 1px solid #1677ff;
            text-shadow: 0 1px 2px rgba(0,0,0,0.3);
            transition: all 0.2s ease;
        }
        summary:hover {
            transform: translateY(-1px);
            box-shadow: 0 6px 20px rgba(0, 71, 171, 0.5);
        }
        summary::before {
            content: "▶ ";
            font-size: 16px;
        }
        details[open] summary::before {
            content: "▼ ";
        }
        .detail-content {
            margin-top: 18px;
            padding-left: 10px;
        }
        .highlight {
            color: #d90000;
            font-weight: 600;
        }
        a {
            color: #0047ab;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="profile-header">
        <img src="https://raw.githubusercontent.com/pinkfloyd1989/ZHANG-Xiao/master/zx-1.jpg" class="avatar" alt="张骁">
        <div class="profile-info">
            <h1>张骁</h1>
            <p><b>中国人民大学，高瓴人工智能学院，副教授，博导</b></p>
            <p>电子邮箱：zhangx89@ruc.edu.cn</p>
        </div>
    </div>

    <h2>研究兴趣</h2>
    <ul>
        <li>流式机器学习：强化学习及在线学习的理论分析与算法设计、面向大模型的流式持续学习算法研究</li>
        <li>可信可控人工智能：可控机器学习、因果学习、公平机器学习方法研究</li>
        <li>大模型与信息检索应用：大模型赋能的信息获取智能体、个性化推荐、搜索排序算法与应用研究</li>
    </ul>

    <h2>个人简介</h2>
    <p>张骁，中国人民大学高瓴人工智能学院副教授，博导，中国人民大学杰出学者青年学者，中国人民大学人工智能治理研究院研究员，北京中关村学院兼职导师，中国人民大学智慧治理学院兼职导师。已在本领域相关的国内外学术期刊和会议上发表论文七十余篇，涵盖 TPAMI、ICML、NeurIPS、ICLR、KDD、SIGIR、ACL、TOIS、TKDE、WWW 等 CCF A 类期刊会议，并获得吴文俊人工智能科技进步一等奖、CCIR 2026最佳论文奖、SIGIR 2024 最佳短文提名奖、VLDB 2024 最佳论文提名奖、SIGIR-AP 2024 最佳论文奖, WWW 2023 最佳论文提名奖、SIGIR-AP 2023 最佳论文奖、ICPR 2018 最佳论文奖、CCFAI 2017 最佳论文提名奖、CCDM 2016 最佳论文奖。受邀担任 ICLR、ACL、SIGIR、NeurIPS、CCL 等多个国际国内会议的领域主席。主持科研基金项目十余项，包括：国家自然科学基金（面上项目、青年基金项目）、科技部人工智能重大专项子课题、中国科协高端科技创新智库青年项目、中国博士后科学基金特别资助、以及校企合作项目（腾讯、阿里、字节跳动、联想、华为、快手等）。研究成果坚持理论创新与工程落地双向赋能，多项成果在电子商务、信息流推荐、军事交互增强等场景获得正向提升。</p>

    <h2>工作经历</h2>
    <ul>
        <li>2024-至今，中国人民大学，高瓴人工智能学院，副教授</li>
        <li>2022-2024，中国人民大学，高瓴人工智能学院，助理教授</li>
        <li>2020-2022, 中国人民大学，高瓴人工智能学院，博士后研究员，合作导师：文继荣 教授</li>
    </ul>

    <h2>教授课程</h2>
    <ul>
        <li>强化学习（本科生课程，2026年）</li>
        <li>高级强化学习（研究生课程，2026年秋）</li>
        <li>智能信息检索（研究生课程，2026年秋，with 徐君老师）</li>
        <li>人工智能伦理与安全（本科生课程，2026年春）</li>
        <li>人工智能概论（本科生课程, 2026年春）</li>
        <li>人工智能治理导论（本科生课程, 2026年春，任课教师之一）</li>
        <li>人工智能前沿技术与创新应用（研究生课程, 2026年春，任课教师之一）</li>
    </ul>

    <details>
        <summary>点击此处展开查看更多课程</summary>
        <div class="detail-content">
            <ul>
                <li>强化学习（本科生课程，2025年）</li>
                <li>高级强化学习（研究生课程，2025年秋）</li>
                <li>智能信息检索（研究生课程，2025年秋，with 徐君老师）</li>
                <li>人工智能伦理与安全（本科生课程，2025年春）</li>
                <li>人工智能概论（本科生课程, 2025年春）</li>
                <li>强化学习（本科生课程，2024年）</li>
                <li>高级强化学习（研究生课程，2024年秋）</li>
                <li>智能信息检索（研究生课程，2024年秋，with 徐君老师）</li>
                <li>人工智能伦理与安全（本科生课程，2024年春）</li>
                <li>人工智能概论（本科生课程, 2024年春）</li>
                <li>高级强化学习（研究生课程，2023年秋）</li>
                <li>高级强化学习（研究生课程，2022年秋）</li>
                <li>海量数据挖掘（研究生课程，2021年秋，with 刘勇老师）</li>
            </ul>
        </div>
    </details>

    <h2>代表英文论文</h2>
    <div class="paper-item">Haoyu Wang, Yifan Shang, Zhongxiang Sun, Weijie Yu, <strong>Xiao Zhang***</strong>, Jun Xu. Towards understanding continual factual knowledge acquisition of language models: From theory to algorithm. Proceedings of the 43rd International Conference on Machine Learning (ICML 2026).</div>
    <div class="paper-item">Yuan Wang, Zhiyu Li, Ang Gao, Changshuo Zhang, <strong>Xiao Zhang***</strong>, Jun Xu, Quan Lin. Large-scale online learning for generative list recommendation in E-commerce: An environment policy optimization approach. Proceedings of the 54th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2026).</div>
    <div class="paper-item">Chenglei Shen, Teng Shi, Weijie Yu, <strong>Xiao Zhang***</strong>, Jun Xu. GenRecEdit: Adapting model editing for generative recommendation with cold-start items. Proceedings of the 54th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2026).</div>
    <div class="paper-item">Changshuo Zhang, Teng Shi, <strong>Xiao Zhang***</strong>, Yanping Zheng, Ruobing Xie, Qi Liu, Jun Xu. Disentangling from collaborative and semantic biews: Graph collaborative filtering for Q&A recommendation. Proceedings of the 54th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2026).</div>
    <div class="paper-item">Changle Qu, Sunhao Dai, Ke Guo, <strong>Xiao Zhang***</strong>, Liqin Zhao, Shijun Wang, Yannan Niu, Lantao Hu, Han Li, Jun Xu. KuaiLive: A real-time interactive dataset for live streaming recommendation. Proceedings of the 54th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2026 Resource Paper).</div>
    <div class="paper-item">Chenglei Shen, Zhongxiang Sun, Teng Shi, <strong>Xiao Zhang***</strong>, Jun Xu. StyliTruth: Unlocking stylized yet truthful LLM generation via disentangled steering. Proceedings of the 14th International Conference on Learning Representations (ICLR 2026).</div>
    <div class="paper-item">Ke Guo, Changle Qu, <strong>Xiao Zhang***</strong>, Liqin Zhao, Shijun Wang, Yanan Niu and Jun Xu. Room matters: Dynamic room-level collaboration information modeling for live streaming recommendation. Proceedings of the Web Conference 2026 (WWW 2026).</div>
    <div class="paper-item">Chenglei Shen, Yi Zhan, Weijie Yu, <strong>Xiao Zhang***</strong>, Jun Xu. Enhancing bandit algorithms with LLMs for time-varying user preferences in streaming recommendations. ACM Transactions on Information Systems (TOIS), 2026.</div>
    <div class="paper-item">Yi Xu, Weiran Shen, Jun Xu, <strong>Xiao Zhang***</strong>, Ji-Rong Wen. IBCB: Efficient inverse batched contextual bandit for behavioral evolution history. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2026.</div>
    <div class="paper-item">Chenglei Shen, <strong>Xiao Zhang***</strong>, Teng Shi, Changshuo Zhang, Guofu Xie, Jun Xu, Ming He, Jianping Fan. A survey of controllable learning: Methods and applications in information retrieval. Frontiers of Computer Science (FCS), 2026, 20(10): 2010619. <a href="https://journal.hep.com.cn/fcs/EN/10.1007/s11704-025-41366-5" target="_blank">https://journal.hep.com.cn/fcs/EN/10.1007/s11704-025-41366-5</a>. <span class="highlight">可控学习（Controllable Learning）综述，入选 FCS Excellent Young Computer Scientists Forum</span></div>

    <details>
        <summary>点击此处展开查看更多英文论文</summary>
        <div class="detail-content">
            <div class="paper-item">Changshuo Zhang, <strong>Xiao Zhang***</strong>, Teng Shi, Jun Xu and Ji-Rong Wen. Test-time alignment with state space model for tracking user interest shifts in sequential recommendation. Proceedings of the 19th ACM Recommender Systems Conference (RecSys 2025).</div>
            <div class="paper-item">Chenglei Shen, Jiahao Zhao, <strong>Xiao Zhang***</strong>, Weijie Yu, Ming He and Jianping Fan. Paragon: Parameter generation for controllable multi-task recommendation. Proceedings of the 19th ACM Recommender Systems Conference (RecSys 2025).</div>
            <div class="paper-item">Guofu Xie, <strong>Xiao Zhang***</strong>, Ting Yao, Yunsheng Shi. Bone Soups: A seek-and-soup model merging approach for controllable multi-objective generation. Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025 main conference).</div>
            <div class="paper-item">Weicong Qin, Yi Xu, Weijie Yu, Chenglei Shen, Ming He, Jianping Fan, <strong>Xiao Zhang**</strong>, Jun Xu. MAPS: Motivation-aware personalized search via LLM-driven consultation alignment. Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025 main conference).</div>
            <div class="paper-item">Changshuo Zhang, Ang Gao, <strong>Xiao Zhang***</strong>, Yong Liu, Deyang Li, Fangchao Liu, Xinyu Zhang. Reward Mixology: Crafting Hybrid Signals for Reinforcement Learning Driven In-Context Learning. Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP 2025 findings).</div>
            <div class="paper-item">Xiang Cheng, Chengyan Pan, Minjun Zhao, Deyang Li, Fangchao Liu, Xinyu Zhang, <strong>Xiao Zhang**</strong>, Yong Liu. Revisiting Chain-of-Thought Prompting: Zero-shot Can Be Stronger than Few-shot. Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP 2025 findings).</div>
            <div class="paper-item">Weicong Qin, Yi Xu, Weijie Yu, Teng Shi, Chenglei Shen, Ming He, Jianping Fan, <strong>Xiao Zhang**</strong>, Jun Xu. Similarity = Value? Consultation Value-Assessment and Alignment for Personalized Search. Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP 2025 main conference).</div>
            <div class="paper-item">Zhiyuan Su, Sunhao Dai, <strong>Xiao Zhang***</strong>. Revisiting clustering of neural bandits: Selective reinitialization for mitigating loss of plasticity. Proceedings of the 31st SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2025).</div>
            <div class="paper-item">Yi-Fan Zhang<sup>†</sup>, <strong>Xiao Zhang</strong><sup>†</sup>, Min-Ling Zhang. Generalization analysis for controllable learning. Proceedings of the 42nd International Conference on Machine Learning (ICML 2025).</div>
            <div class="paper-item">Dongxie Wen, <strong>Xiao Zhang***</strong>, Zhewei Wei, Chenping Hou, Shuai Li, Weinan Zhang. Fast second-order online kernel learning through incremental matrix sketching and decomposition. Proceedings of the 34th International Joint Conference on Artificial Intelligence (IJCAI 2025).</div>
            <div class="paper-item">Changle Qu, Liqin Zhao, Yanan Niu, <strong>Xiao Zhang***</strong>, and Jun Xu. Bridging short videos and streamers with multi-graph contrastive learning for live streaming recommendation. Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2025).</div>
            <div class="paper-item">Zhongxiang Sun, Qipeng Wang, Weijie Yu, Xiaoxue Zang, Kai Zheng, Jun Xu, <strong>Xiao Zhang**</strong>, Yang Song and Han Li. Trustworthy process rewarding for retrieval-augmented reasoning. Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2025).</div>
            <div class="paper-item">Teng Shi, Jun Xu, <strong>Xiao Zhang**</strong>, Xiaoxue Zang, Kai Zheng, Yang Song and Han Li. Retrieval augmented generation with collaborative filtering for personalized text generation. Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2025).</div>
            <div class="paper-item">Haoyu Wang, Sunhao Dai, Haiyuan Zhao, Liang Pang, <strong>Xiao Zhang**</strong>, Gang Wang, Zhenhua Dong, Jun Xu, Ji-Rong Wen. Perplexity trap: PLM-Based retrievers overrate low perplexity documents. Proceedings of the 13th International Conference on Learning Representations (ICLR 2025).</div>
            <div class="paper-item">ZhongXiang Sun, Xiaoxue Zang, Kai Zheng, Jun Xu, <strong>Xiao Zhang**</strong>, Weijie Yu, Yang Song, Han Li. ReDeEP: Detecting hallucination in retrieval-augmented generation via mechanistic interpretability. Proceedings of the 13th International Conference on Learning Representations (ICLR 2025).</div>
            <div class="paper-item">ZhongXiang Sun, Zihua Si, Xiaoxue Zang, Kai Zheng, Yang Song, <strong>Xiao Zhang**</strong>, Jun Xu. LargePiG for Hallucination-free query generation: Your large language model is secretly a pointer generator. Proceedings of the Web Conference 2025 (WWW 2025).</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Sunhao Dai, Jun Xu, Yong Liu, Zhenhua Dong. AdaO2B: Adaptive online to batch conversion for out-of-distribution generalization. Proceedings of the 39th Annual AAAI Conference on Artificial Intelligence (AAAI 2025).</div>
            <div class="paper-item">Kepu Zhang, Zhongxiang Sun, <strong>Xiao Zhang***</strong>, Xiaoxue Zang, Kai Zheng, Yang Song, Jun Xu. Trigger^3: Refining query correction via adaptive model selector. Proceedings of the 39th Annual AAAI Conference on Artificial Intelligence (AAAI 2025).</div>
            <div class="paper-item">Chenglei Shen, Guofu Xie, <strong>Xiao Zhang***</strong> and Jun Xu. On the decision-making abilities in role-playing using large language models. Proceedings of the 39th Annual AAAI Conference on Artificial Intelligence (AAAI 2025, CMASDL Workshop).</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Teng Shi, Jun Xu, Zhenhua Dong, Ji-Rong-Wen. Model-agnostic causal embedding learning for counterfactually group-fair recommendation. IEEE Transactions on Knowledge and Data Engineering (TKDE), doi: 10.1109/TKDE.2024.3424906.</div>
            <div class="paper-item">Yuan Wang, Zhiyu Li, Changshuo Zhang, Sirui Chen, <strong>Xiao Zhang***</strong>, Jun Xu, Quan Lin. Do not wait: Learning re-ranking model without user feedback at serving time in e-commerce. Proceedings of the 18th ACM Conference on Recommender Systems (RecSys 2024), short paper.</div>
            <div class="paper-item">Kepu Zhang, Teng Shi, Sunhao Dai, <strong>Xiao Zhang***</strong>, Yinfeng Li, Jing Lu, Xiaoxue Zang, Yang Song, Jun Xu. SAQRec: Aligning recommender systems to user satisfaction via questionnaire feedback. Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM 2024).</div>
            <div class="paper-item">Zhongxiang Sun, Zihua Si, Xiaoxue Zang, Kai Zheng, Yang Song, <strong>Xiao Zhang**</strong>, Jun Xu. Large language models enhanced collaborative filtering. Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM 2024).</div>
            <div class="paper-item">Sunhao Dai, Yuqi Zhou, Liang Pang, Weihao Liu, Xiaolin Hu, Yong Liu, <strong>Xiao Zhang**</strong>, Gang Wang, Jun Xu. Neural retrievers are biased towards LLM-generated content. Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2024).</div>
            <div class="paper-item">Hanyan Yin, Dongxie Wen, Jiajun Li, Zhewei Wei, <strong>Xiao Zhang**</strong>, Zengfeng Huang, Feifei Li. Optimal matrix sketching over sliding windows. Proceedings of the 50th International Conference on Very Large Databases (VLDB 2024). <span class="highlight">最佳论文提名, Best Research Paper Nominations</span></div>
            <div class="paper-item">Chen Xu, Xiaopeng Ye, Jun Xu, <strong>Xiao Zhang**</strong>, Weiran Shen, Ji-Rong Wen. LTP-MMF: Toward long-term provider max-min fairness under recommendation feedback loops. ACM Transactions on Information Systems (TOIS), 43(1): 1-29.</div>
            <div class="paper-item">ZhongXiang Sun, Kepu Zhang, Haoyu Wang, <strong>Xiao Zhang**</strong>, Jun Xu. Effective in-context example selection through data compression. ACL Findings (2024).</div>
            <div class="paper-item">Changshuo Zhang, Sirui Chen, <strong>Xiao Zhang***</strong>, Sunhao Dai, Weijie Yu and Jun Xu. Reinforcing long-term performance in recommender systems with user-oriented exploration policy. Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2024).</div>
            <div class="paper-item">Zhongxiang Sun, Zihua Si, Xiaoxue Zang, Kai Zheng, Yang Song, <strong>Xiao Zhang**</strong>, Jun Xu. To search or to recommend: Predicting open-app motivation with neural Hawkes process. Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2024).</div>
            <div class="paper-item">Teng Shi, Zihua Si, Jun Xu, <strong>Xiao Zhang**</strong>, Xiaoxue Zang, Kai Zheng, Dewei Leng, Yanan Niu and Yang Song. UniSAR: Modeling user transition behaviors between search and recommendation. Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2024).</div>
            <div class="paper-item">Sunhao Dai, Changle Qu, Sirui Chen, <strong>Xiao Zhang**</strong> and Jun Xu. ReCODE: Modeling repeat consumption with neural ODE. Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2024), short paper. <span class="highlight">最佳短文提名, Best Short Paper Nominee</span></div>
            <div class="paper-item">Zihua Si, Zhongxiang Sun, Jiale Chen, Guozhang Chen, Xiaoxue Zang, Kai Zheng, Yang Song, <strong>Xiao Zhang**</strong>, Jun Xu and Kun Gai. Generative retrieval with semantic tree-structured identifiers and contrastive learning. Proceedings of the 2nd International ACM SIGIR Conference on Information Retrieval in the Asia Pacific (SIGIR-AP 2024). <span class="highlight">最佳论文奖, Best Paper Reward</span></div>
            <div class="paper-item">Peiyu Liu, Ze-Feng Gao, <strong>Xiao Zhang**</strong>, Wayne Xin Zhao, Ji-Rong Wen. Enhancing parameter-efficient fine-tuning with simple calibration based on stable rank. Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024).</div>
            <div class="paper-item">Chen Xu, Jun Xu, Yiming Ding, <strong>Xiao Zhang**</strong>, Qi Qi. FairSync: Ensuring amortized group exposure in distributed recommendation retrieval. Proceedings of the 2024 ACM Web Conference (WWW 2024).</div>
            <div class="paper-item">Jianwen Yang, <strong>Xiao Zhang***</strong>, Jun Xu. Smooth start: a unified approach for gradual transition from cold to old in recommender systems. Proceedings of the 49th IEEE International Conference on Acoustics, Speech, & Signal Processing (ICASSP 2024).</div>
            <div class="paper-item">Sunhao Dai, Ninglu Shao, Jieming Zhu, <strong>Xiao Zhang**</strong>, Zhenhua Dong, Jun Xu, Quanyu Dai, Ji-Rong Wen. Modeling user attention in music recommendation. Proceedings of the 40th IEEE International Conference on Data Engineering (ICDE 2024).</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Ninglu Shao, Zihua Si, Jun Xu, Wenhan Wang, Hanjing Su, Ji-Rong Wen. Reward imputation with sketching for contextual batched bandits. Advances in Neural Information Processing Systems 35 (NeurIPS 2023), 64577-64588, 2023.</div>
            <div class="paper-item">Chuhao Jin, Yutao Zhu, Lingzhen Kong, Shijie Li, <strong>Xiao Zhang**</strong>, Ruihua Song, Xu Chen, Yuchong Sun, Yu Chen, Jun Xu. Joint semantic and strategy matching for persuasive dialogue. Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing (Findings of EMNLP).</div>
            <div class="paper-item">Chenglei Shen, <strong>Xiao Zhang***</strong>, Wei Wei, Jun Xu. HyperBandit: Contextual bandit with hypernewtork for time-varying user preferences in streaming recommendation. Proceedings of the 32nd ACM International Conference on Information and Knowledge Management (CIKM 2023), 2239–2248, 2023.</div>
            <div class="paper-item">Zhongxiang Sun, Zihua Si, Xiaoxue Zang, Dewei Leng, Yanan Niu, Yang Song, <strong>Xiao Zhang**</strong>, Jun Xu. KuaiSAR: A unified search and recommendation dataset, Proceedings of the 32nd ACM International Conference on Information and Knowledge Management (CIKM 2023 Resource Paper).</div>
            <div class="paper-item">Sirui Chen, Yuan Wang, Zijing Wen, Zhiyu Li, Changshuo Zhang, <strong>Xiao Zhang***</strong>, Quan Lin, Cheng Zhu, Jun Xu. Controllable multi-objective re-ranking with policy hypernetworks. Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2023).</div>
            <div class="paper-item">Zhongxiang Sun, Jun Xu, <strong>Xiao Zhang**</strong>, Zhenhua Dong and Ji-Rong Wen. Law article-enhanced legal case matching: A causal learning approach. Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2023).</div>
            <div class="paper-item">Zihua Si, Zhongxiang Sun, <strong>Xiao Zhang***</strong>, Jun Xu, Xiaoxue Zang, Yang Song, Kun Gai and Ji-Rong Wen. When search meets recommendation: Learning disentangled search representation for recommendation. Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2023), 1313-1323, 2023.</div>
            <div class="paper-item">Sunhao Dai, Ninglu Shao, Haiyuan Zhao, Weijie Yu, Zihua Si, Chen Xu, Zhongxiang Sun, <strong>Xiao Zhang**</strong> and Jun Xu. Uncovering ChatGPT's capabilities in recommender systems. RecSys 2023 Late Breaking Results (LBR) track, 2023.</div>
            <div class="paper-item">Sirui Chen, <strong>Xiao Zhang**</strong>, Xu Chen, Zhiyu Li, Yuan Wang, Quan Lin and Jun Xu. Reinforcement re-ranking with 2D grid-based recommendation panels. Proceedings of the 1st International ACM SIGIR Conference on Information Retrieval in the Asia Pacific, 2023.</div>
            <div class="paper-item">Haiyuan Zhao, Jun Xu, <strong>Xiao Zhang**</strong>, Guohao Cai, Zhenhua Dong and Ji-Rong Wen. Unbiased top-$k$ learning to rank with causal likelihood decomposition. Proceedings of the 1st International ACM SIGIR Conference on Information Retrieval in the Asia Pacific, 2023. <span class="highlight">最佳论文奖, Best Paper Reward</span></div>
            <div class="paper-item">Chen Xu, Sirui Chen, Jun Xu, Weiran Shen, <strong>Xiao Zhang**</strong>, Gang Wang, Zhenhua Dong. P-MMF: Provider max-min fairness re-ranking in recommender system. Proceedings of the Web Conference 2023 (WWW 2023), 2023. <span class="highlight">Spotlight-最佳论文提名奖</span></div>
            <div class="paper-item">Zihua Si, Zhongxiang Sun, <strong>Xiao Zhang**</strong>, Jun Xu, Yang Song, Xiaoxue Zang, Ji-Rong Wen. Enhancing recommendation with search data in a causal learning manner. ACM Transactions on Information Systems (TOIS), 2023.</div>
            <div class="paper-item">Haiyuan Zhao, Jun Xu, <strong>Xiao Zhang**</strong>, Guohao Cai, Zhenhua Dong, Ji-Rong Wen. Separating examination and trust bias from click predictions for unbiased relevance ranking. Proceedings of the 16th ACM International Conference on Web Search and Data Mining (WSDM 2023).</div>
            <div class="paper-item">Haonan Jia, <strong>Xiao Zhang**</strong>, Jun Xu, Wei Zeng, Hao Jiang, Xiaohui Yan. Variance reduction for deep Q-Learning using stochastic recursive gradient, Proceedings of the 29th International Conference on Neural Information Processing (ICONIP 2022).</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Sunhao Dai, Jun Xu, Zhenhua Dong, Quanyu Dai, Ji-Rong Wen. Counteracting user attention bias in music streaming recommendation via reward modification. Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2022), 2504–2514, 2022.</div>
            <div class="paper-item">Zihua Si, Xueran Han, <strong>Xiao Zhang**</strong>, Jun Xu, Yue Yin, Yang Song, Ji-Rong Wen. A model-agnostic causal learning framework for recommendation using search data. Proceedings of the Web Conference 2022 (WWW 2022), 224–233, 2022.</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Haonan Jia, Hanjing Su, Wenhan Wang, Jun Xu, Ji-Rong Wen. Counterfactual reward modification for streaming recommendation with delayed feedback. Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2021), 41-50, 2021.</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Shizhong Liao, Jun Xu, Ji-Rong Wen. Regret bounds for online kernel selection in continuous kernel space. Proceedings of the 35th AAAI Conference on Artificial Intelligence (AAAI 2021), 10931-10938, 2021.</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Shizhong Liao. Hypothesis sketching for online kernel selection in continuous kernel space. Proceedings of the 29th International Joint Conference on Artificial Intelligence (IJCAI 2020), 2498–2504, 2020.</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Shizhong Liao. Incremental randomized sketching for online kernel learning. Proceedings of the 36th International Conference on Machine Learning (ICML 2019), 7394–7403, 2019.</div>
            <div class="paper-item">Shizhong Liao, <strong>Xiao Zhang***</strong>. Online kernel selection via tensor sketching. Proceedings of the 28th ACM International Conference on Information and Knowledge Management (CIKM 2019), 801–810, 2019.</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Shizhong Liao. Online kernel selection via incremental sketched kernel alignment. Proceedings of the 27th International Joint Conference on Artificial Intelligence (IJCAI 2018), 3118–3124, 2018.</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Shizhong Liao. Tensor completion via multi-shared-modes canonical correlation analysis. Neurocomputing, 205: 106–115, 2016.</div>
            <div class="paper-item"><strong>Xiao Zhang**</strong>, Yun Liao, Shizhong Liao. A survey on online kernel selection for online kernel learning. WIREs Data Mining and Knowledge Discovery, 9(2): e1295, 2019.</div>
            <div class="paper-item">Shan Xu, <strong>Xiao Zhang**</strong>, Shizhong Liao. New online kernel ridge regression via incremental predictive sampling. Proceedings of the 28th ACM International Conference on Information and Knowledge Management (CIKM 2019), 791–800, 2019.</div>
            <div class="paper-item">Shan Xu, <strong>Xiao Zhang**</strong>, Shizhong Liao. A linear incremental Nystrom method for online kernel learning. Proceedings of the 24th International Conference on Pattern Recognition (ICPR 2018), 2256–2261, 2018. <span class="highlight">Best Student Paper</span></div>
            
            <p style="margin-top: 15px; font-size: 0.9em; color: #666;">*: Corresponding author.<br>†: Equal contribution.</p>
        </div>
    </details>

    <h2>代表中文论文</h2>
    <div class="paper-item"><strong>张骁</strong>, 廖士中. 基于局部后悔的在线核选择. 计算机学报, 42(1): 61–72, 2019.</div>
    <div class="paper-item"><strong>张骁</strong>, 胡清华, 廖士中. 基于多源共享因子的多张量填充. 中国科学 : 信息科学, 46(7): 819–833, 2016. (CCDM 最佳学生论文)</div>
    <div class="paper-item">廖芸, <strong>张骁</strong>, 廖士中. 统一框架下在线核选择的竞争性分析. 计算机科学与探索, 2019, DOI:10.3778/j.issn.1673-9418.1905092.</div>

    <h2>主要主持科研项目（部分）</h2>
    <ul>
        <li>受限反馈下的可信在线学习, 国家自然科学基金——面上项目, 2024.01-2027.12, <strong>主持</strong></li>
        <li>在线模型选择的增量素描方法, 国家自然科学基金——青年科学基金项目, 2021.01-2022.12, <strong>主持</strong></li>
        <li>智能社会治理算法设计的风险及应对, 中国科协高端科技创新智库青年项目, 2020.08-2021.06, <strong>主持</strong></li>
        <li>中国博士后科学基金第 14 批特别资助（站中）, 2021.07-2022.09, <strong>主持</strong></li>
        <li>面向多场景、多任务、转化延迟场景的推荐算法研究, 腾讯微信犀牛鸟专项研究计划, 2020.05-2021.05, <strong>主持</strong></li>
        <li>基于因果推断的推荐系统归因与可控推荐模型研究, 腾讯微信犀牛鸟专项研究计划, 2023.07-2024.07, <strong>主持</strong></li>
        <li>面向信息流生成式广告推荐的动态对齐方法研究, 腾讯广告犀牛鸟专项研究计划, 2025.08-2026.08, <strong>主持</strong></li>
        <li>基于用户搜索和浏览行为的推荐系统研究, 快手合作项目, 2021.05-2023.06, <strong>主持</strong></li>
    </ul>
    <p>其他主持横向项目：腾讯、阿里、字节跳动、联想、华为、快手等校企合作项目，研究方向覆盖：大模型、智能体、强化学习、智能信息检索与推荐系统等。</p>

    <h2>主要获奖</h2>
    <ul>
        <li>2026.08 CCIR 2026 最佳论文奖</li>
        <li>2025.07 可控学习综述论文入选期刊 Frontiers of Computer Science 优秀青年科学家论坛</li>
        <li>2024.12 SIGIR-AP 2024 最佳论文奖</li>
        <li>2024.08 VLDB 最佳论文提名奖</li>
        <li>2024.07 SIGIR 2024 最佳短文提名奖</li>
        <li>2023.11 SIGIR-AP 2023 最佳论文奖</li>
        <li>2023.04 WWW 2023 最佳论文提名奖</li>
        <li>2018.11 ICPR 2018 (第 24 届国际模式识别大会) 最佳论文奖</li>
        <li>2017.08 CCFAI 2017 (2017 中国计算机学会人工智能会议) 最佳论文提名奖</li>
        <li>2016.05 CCDM 2016 (2016 中国数据挖掘会议) 最佳论文奖</li>
        <li>2011.11 全国大学生数学建模竞赛国家一等奖</li>
        <li>2010.11 全国大学生数学建模竞赛国家一等奖</li>
    </ul>

    <p style="margin-top: 30px;">毕业生去向及更多相关信息可参见实验室主页：<a href="https://ruc-iir-lab.github.io/team/" target="_blank">https://ruc-iir-lab.github.io/team/</a></p>

</body>
</html>
