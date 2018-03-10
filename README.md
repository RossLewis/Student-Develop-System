# Student-Develop-System
*This is a system that can guide students to learn and to promote the development of students.*

-----------------------------------------------------------------------------------------------
## 功能简介

- 添加学生信息
- 删除学生信息
- 检查学生信息
- 统计学生信息
- 保存学生信息
- 读取学生信息
-----------------------------------------------------------------------------------------------
## 流程图及其解释

![](https://github.com/JohnHillRoss/Student-Develop-System/blob/master/StuDevSystem.png)

>1. MenuList:*主菜单*
>
>2. CreatStudent:*创建学生信息*
>
>3. AddStudent:*添加学生信息（1.按学生ID顺序自小到大添加/2.按学生score顺序自小到大添加）*
>
>4. DelStudent:*删除学生信息（通过输入学生ID来删除包含该ID的学生信息）*
>
>5. CheckStudent:*检查学生信息（输入端）（1.按学生name查找/2.按学生ID查找）*
>
>6. CheckStudent_1:*检查学生信息（输出端）（1.1.按学生name输出/2.按学生ID输出/3.按学生major输出/4.按学生score输出/5.按学生career输出）*
>
>7. StaStudent:*统计学生信息（1.统计录进系统学生人数/2.统计成绩合格学生人数）*
>
>8. SaveStudent:*保存学生信息（保存在与源文件同文件夹的StuDevInformation.txt文件中）*
>
>9. ReadStudent:*读取学生信息（读取StuDevInformation.txt文件中学生信息)*

-----------------------------------------------------------------------------------------------
## 界面显示
- 主菜单界面

![](https://github.com/JohnHillRoss/Student-Develop-System/blob/master/menulist.png)


- StuDevINformation.txt 文件界面

![](https://github.com/JohnHillRoss/Student-Develop-System/blob/master/StuDevInformation.png)

-----------------------------------------------------------------------------------------------
## 注意事项及BUG
-若要实现读取功能学生信息功能，要在进入系统后先执行输入序号5（若在中途读取学生信息会产生BUG）

-----------------------------------------------------------------------------------------------
## Change Log

### v1.2.0 (2018/1/28)
- 添加保存学生信息功能
- 添加读取学生信息功能
- 修复删除学生信息后不能再次添加已删除学生信息的BUG
### v1.2.5 (2018/2/1)
- 添加检查学生信息功能
- 添加统计学生信息功能
- 修复不能正确读取学生信息的BUG

-----------------------------------------------------------------------------------------------
## 讨论与交流
- 目的：该系统旨在引导学生学习方向，促进学生发展。
- 方法：
1. 收集学生的信息包括（学习专业、学科成绩、考取的证书、理想职业......)
2. 收集用人单位的信息包括（所提供的职位、所需的学历、所需的证书、所提供的月薪......)
3. 通过比较两者信息为学生提供正确的学习路线，从而促进学生发展。

- 交流：假如你对我的系统或是理念感兴趣，请私信我。（本人还在学习阶段，所以每次系统更新都会遇到困难，希望各位体谅以及指导）
 ----------------------------------------------------------------------------------------------
                                                                                                                  2018/2/1
