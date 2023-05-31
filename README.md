# prompt-programming
Prompt编程，用于结构化的、深度的定制ChatGPT的能力，可以简单高效的构建专业的AI应用，
先来看一个利用Prompt编程构建的AI应用：育儿师。育儿师用于面向0-18岁的父母咨询育儿中遇到的问题，我们来看看它的特色：

1. 育儿师先上来自我介绍、规定了用户必填输入的信息（孩子年龄段、性别）、规定了用户选填输入的信息（出生日期、所在省份）、并且可以通过“指令”与系统进行特定交互
![image](https://github.com/daijun4you/prompt-programming/assets/6802327/859db77a-dbbb-4e3b-ad9f-cc66c6cfd351)

2. 当用户输入了年龄与出生日期不匹配后，系统会进行提示并以出生日期对年龄进行修正，并且如果孩子的年龄大于18岁则系统不提供咨询服务（育儿师只专注于0-18岁的孩子）
![image](https://github.com/daijun4you/prompt-programming/assets/6802327/f6573f3c-6d4b-4d3b-af9a-c273b107933d)

3. 询问育儿问题时候，系统会判定用户给出的细节不够，进一步对用户进行更详细的询问
![image](https://github.com/daijun4you/prompt-programming/assets/6802327/f65e3768-a946-41b1-828b-5d1d738d1119)

4. 得到所需信息后，系统会给出具体的、可落地执行的解决方案
![image](https://github.com/daijun4you/prompt-programming/assets/6802327/3b92ef7d-1360-4300-a37b-d75e15444ecf)

5. 最后再来看看系统的指令能力
![image](https://github.com/daijun4you/prompt-programming/assets/6802327/2a64a0f5-85de-4867-939a-1d839ce0a3e8)



