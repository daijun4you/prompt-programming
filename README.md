# prompt-programming
## Prompt编程 是什么
Prompt编程 是指利用结构化的数据格式（如json）来定义Prompt，从而可以深度定制化ChatGPT的能力。Prompt编程可以简单高效的构建功能丰富的AI应用。
<br><br>

## Prompt编程 例子
来看一个利用Prompt编程构建的AI应用：育儿师。育儿师用于面向0-18岁孩子的父母，咨询育儿中遇到的问题，我们来看看几个AI应用的功能特色：

1. 育儿师首先会进行自我介绍、规定了用户必填输入的信息（孩子年龄段、性别）、规定了用户选填输入的信息（出生日期、所在省份）、并且可以通过“指令”与系统进行特定交互
<img src='https://github.com/daijun4you/prompt-programming/assets/6802327/859db77a-dbbb-4e3b-ad9f-cc66c6cfd351' width='60%' height='60%'/>

2. 当用户输入了年龄与出生日期不匹配后，系统会进行提示并以出生日期对年龄进行修正，并且如果孩子的年龄大于18岁则系统不提供咨询服务（育儿师只专注于0-18岁的孩子）
<img src='https://github.com/daijun4you/prompt-programming/assets/6802327/f6573f3c-6d4b-4d3b-af9a-c273b107933d' width='60%' height='60%'/>

3. 询问育儿问题时候，系统会判定用户给出的细节不够，进一步对用户进行更详细的询问
<img src='https://github.com/daijun4you/prompt-programming/assets/6802327/f65e3768-a946-41b1-828b-5d1d738d1119' width='60%' height='60%'/>

4. 得到所需信息后，系统会给出具体的、可落地执行的解决方案
<img src='https://github.com/daijun4you/prompt-programming/assets/6802327/3b92ef7d-1360-4300-a37b-d75e15444ecf' width='60%' height='60%'/>

5. 最后再来看看系统的指令能力
<img src='https://github.com/daijun4you/prompt-programming/assets/6802327/2a64a0f5-85de-4867-939a-1d839ce0a3e8' width='60%' height='60%'/>

## Prompt编程 的原理
Prompt编程主要用到了json的格式来定义Prompt，看一下json数据格式的思维导图：
<img src='https://github.com/daijun4you/prompt-programming/assets/6802327/89d769c4-ee78-43aa-ac49-77d3c083ce37' width='60%' height='60%'/>
<br/>**AI应用**，用于定义你的应用，其中又细分为三个模块：简介、用户、系统。
  <br/>**简介**，主要用于介绍你的AI应用。
  <br/>**用户**，主要用于定义需要用户输入的**必填信息**以及**选填信息**
  <br/>**系统**，主要用于定义**指令**以及**规则**（其中规则是系统最最核心的运行逻辑）
<br/>运行AI应用，用于运行你的 AI应用





