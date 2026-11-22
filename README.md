# Zn45 Scientific Reasoning Benchmark

一道中文科学推理题。模型根据单点筛选数据提出蛋白质工程候选，选取能区分假说的计算证据，再根据证据解释验证优先级。

## 公开材料

- [题目](question.md)与[提交模板](submission_template.json)
- [考生数据](input_data/data_dictionary.md)，含序列、结构、筛选结果和原始时间序列
- [来源与许可](source_manifest.md)

解压后可将本目录内容上传到 GitHub 仓库。正式评测时，候选端挂载 question.md、submission_template.json 和 input_data/。完整工具版需要评委单独运行题目服务和实验室工具服务，再按阶段提供回执及动力学拟合。纸面版可由评委按题意主持，候选用文字申请计算，评委给出事先准备并清楚标注的假定结果。公开仓库用于浏览题目和考生数据。
