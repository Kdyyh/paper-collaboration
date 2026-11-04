# 论文阅读与分享

所有论文的链接统一收录在本页的“论文总目录”中。每位成员在自己的目录下，为读过的每篇论文建立独立文件夹，保存这篇论文的阅读 PPT、笔记和其他相关资料。

## 论文总目录

按领域分类汇总，点击论文题目即可打开论文。

### AI + 教育

| 论文题目（论文链接） | 官方代码 / 项目 | 领域 |
| --- | --- | --- |
| P001 · [AgentTutor: Empowering Personalized Learning with Multi-Turn Interactive Teaching in Intelligent Education Systems](https://arxiv.org/abs/2601.04219) | 暂未找到官方公开代码 | AI + 教育 |
| P002 · [From MOOC to MAIC: Reshaping Online Teaching and Learning through LLM-driven Agents](https://arxiv.org/abs/2409.03512) | [OpenMAIC（官方项目）](https://github.com/THU-MAIC/OpenMAIC) | AI + 教育 |
| P003 · [EduAgent: Generative Student Agents in Learning](https://arxiv.org/abs/2404.07963) | [GitHub](https://github.com/EduAgent/EduAgent) | AI + 教育 |
| P004 · [Are Agents Ready to Teach? A Multi-Stage Benchmark for Real-World Teaching Workflows](https://arxiv.org/abs/2605.14322) | [TeachArena（代码与数据）](https://huggingface.co/datasets/CinderD/TeachArena) | AI + 教育 |

### AI + 工业

| 论文题目（论文链接） | 官方代码 / 项目 | 领域 |
| --- | --- | --- |
| P005 · [Towards autonomous system: flexible modular production system enhanced with large language model agents](https://arxiv.org/abs/2304.14721) | [GitHub](https://github.com/YuchenXia/GPT4IndustrialAutomation) | AI + 工业 |
| P006 · [From Detection to Action: Using LLM Agents for Fault-Tolerant Control](https://arxiv.org/abs/2606.28011) | [GitHub](https://github.com/AISL-at-Imperial-College-London/ctrl-alt-recover) | AI + 工业 |
| P007 · [An open-weight Large Language Model agent for condition monitoring and predictive maintenance in wind energy systems](https://doi.org/10.1016/j.egyai.2026.100828) | [GitHub](https://github.com/agushasan/LLM_Wind) | AI + 工业 |

### AI + 旅游

| 论文题目（论文链接） | 官方代码 / 项目 | 领域 |
| --- | --- | --- |
| P008 · [TravelPlanner: A Benchmark for Real-World Planning with Language Agents](https://proceedings.mlr.press/v235/xie24j.html) | [GitHub](https://github.com/OSU-NLP-Group/TravelPlanner) | AI + 旅游 |
| P009 · [TravelAgent: An AI Assistant for Personalized Travel Planning](https://arxiv.org/abs/2409.08069) | 暂未找到官方公开代码 | AI + 旅游 |
| P010 · [TRIP-PAL: Travel Planning with Guarantees by Combining Large Language Models and Automated Planners](https://arxiv.org/abs/2406.10196) | 暂未找到官方公开代码 | AI + 旅游 |
| P011 · [HiMAP-Travel: Hierarchical Multi-Agent Planning for Long-Horizon Constrained Travel](https://proceedings.mlr.press/v306/bui26b.html) | 暂未找到官方公开代码 | AI + 旅游 |

代码 / 项目链接核对日期：2026-11-04。论文编号用于对应成员各自的阅读资料文件夹。

## 成员阅读资料

| 成员 | 个人阅读目录 |
| --- | --- |
| [Kdyyh](https://github.com/Kdyyh) | [阅读记录与资料](members/Kdyyh/README.md) |

目录按“成员 → 读过的论文 → 这篇论文的资料”组织：

```text
paper-collaboration/
├── README.md                         # 所有论文链接的总目录
├── members/
│   ├── Kdyyh/
│   │   ├── README.md                  # 个人已读论文与资料夹索引
│   │   ├── P001_论文简称/
│   │   │   ├── README.md              # 阅读记录或笔记
│   │   │   ├── 阅读汇报.pptx           # 这篇论文的阅读 PPT
│   │   │   ├── 笔记.md                # 这篇论文的详细笔记（也可用 PDF 等格式）
│   │   │   └── images/                # 这篇论文相关的图片等附件
│   │   └── P002_另一篇论文/
│   │       └── ...
│   └── 其他成员的GitHub用户名/
│       ├── README.md
│       └── P001_论文简称/              # 同一论文可由不同成员分别整理
│           └── ...
└── templates/
    └── paper-reading/
        └── README.md                  # 单篇论文资料夹的阅读记录模板
```

上面的论文名称和文件名仅说明目录结构；上传时按实际论文及已有资料填写，不要求每篇论文都有全部文件。

## 使用流程

1. **添加论文链接**：编辑本页，在“论文总目录”的对应领域表格中登记论文编号、题目、论文链接和官方代码链接。
2. **创建个人目录**：首次加入时，用 **Add file → Create new file** 创建 `members/你的GitHub用户名/README.md`，并将个人目录加入本页的成员表。
3. **按论文建文件夹**：例如新建 `members/你的GitHub用户名/P001_论文简称/README.md`，可复制[单篇论文阅读记录模板](templates/paper-reading/README.md)。
4. **上传阅读资料**：进入这篇论文的文件夹，通过 **Add file → Upload files** 上传对应的 PPT、笔记和附件。
5. **记录已读情况**：阅读完成后更新自己的成员 README，记录论文编号及对应的 PPT、笔记资料夹链接。

## 协作约定

- 所有受邀协作者均可维护论文总目录、创建个人文件夹和上传阅读资料；仓库所有者额外管理成员及仓库设置。
- 每位成员维护自己的阅读资料。同一篇论文的不同成员资料分别保存在各自目录中。
- 仓库公开可见；个人文件夹用于区分资料归属，协作者拥有编辑权限。
