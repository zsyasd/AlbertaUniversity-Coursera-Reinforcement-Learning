![image](https://user-images.githubusercontent.com/55370336/107505954-5bab6800-6bd8-11eb-9b86-6ba44912f1ee.png)

价值函数是**状态**（或状态与动作二元组）的函数，用来评估当前 `agent` 在给定状态（或者给定状态与动作）下回报的期望值。

**策略** `policy` 是从状态到每个动作的选择概率之间的映射。

![image](https://user-images.githubusercontent.com/55370336/107506379-f7d56f00-6bd8-11eb-8155-835e4197ac08.png)
![image](https://user-images.githubusercontent.com/55370336/107506412-015ed700-6bd9-11eb-9b33-dd4996c849d8.png)
![image](https://user-images.githubusercontent.com/55370336/107537410-c8852900-6bfd-11eb-978b-3ab89bfca856.png)

注意这个添加常数`reward`在episode任务和持续性任务的区别。episode任务中添加常数有可能会另奖励的正负直接反过来，所以会影响最终结果。但是持续性任务的reward添加之后不会影响总体排名

![image](https://user-images.githubusercontent.com/55370336/107537460-d76bdb80-6bfd-11eb-9fe6-5a89b9d43814.png)
![image](https://user-images.githubusercontent.com/55370336/107537704-27e33900-6bfe-11eb-8477-02903b5d697a.png)
