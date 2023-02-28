
<h1 align="center">
  <img width="300" s alt="ChatGPT">
  
</h1>
<p align="center">
  <p align="center">ChatGPT에 대한 모든 기술이다</p>
</p>

<h4 align="center">
  <a href=" ">GPT</a> |
  <a href="https:csdn">CSDN中文版</a> |
  <a href="https://www.github.com/zhanglina94">MyWebsite</a>
</h4>


GPT (Generative Pre-trained Transformer) 란 Generative (생성하는) Pre-trained (사전 학습된) Transformer (트랜스포머) 이다.
GPT를 공부하기 전에 꼭 알아야한은 것:
- Transformer의 구조,QKV이론 몇 계산
- NLP 기초:word embedding
- Language Modeling(LM):언어모델이란 단어 시퀀스에 대한 확률분포(probability distribution)를 가리킵니다. 

그래서 구체적으로 보시면 BERT는 Transformer의 Encoder를 이용하며 GPT는 Transformer의 Decoder를 이용했습니다.
![image](https://user-images.githubusercontent.com/43246784/218370731-86e958bc-9218-4cd9-8b67-48b7e7510fd8.png)

ChatGPT에 관련논문을 정리하자면 다음과 같습니다:
![image](https://user-images.githubusercontent.com/43246784/218370224-f5506d31-d9d3-41ee-a543-b304271657ec.png)

한논문씩 알아보도록 합니다~

## 🔥 GPT
논문 제목:Improving Language Understanding by Generative Pre-Training
- [GPT 논문 보기](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)
- [GPT 코딩 보기](https://github.com/karpathy/minGPT)

GPT는 주로 2까지 제안했고 Unsupervised Pre-training 와 Supervised Fine-tuning 있고요.
![image](https://user-images.githubusercontent.com/43246784/218371596-2a006b7b-f219-4a33-bea3-7ff2ce403b1a.png)


![image](https://user-images.githubusercontent.com/43246784/218372027-2b306706-1370-4524-b24c-586ebec0741b.png)



## 🔥 GPT2
논문 제목:Language Models are Unsupervised Multitask Learners
- [GPT2 논문 보기](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
- [GPT2 코딩 보기](https://github.com/openai/gpt-2)

![image](https://user-images.githubusercontent.com/43246784/218372222-8cccc45b-1412-4f49-b699-167a4e93742c.png)

## 🔥 GPT3
논문 제목:Language Models are Few-Shot Learners
- [GPT3 논문 보기](https://arxiv.org/pdf/2005.14165.pdf)
- [GPT3 코딩 보기](https://github.com/openai/gpt-3)

  GPT-3 대규모 언어 모델들은 그 능력으로 시작했습니다. 대부분의 비즈니스에서 고객용으로 사용하기에 충분히 신뢰성(reliable)이 있다고 할 수는 없지만, 이 모델들은 자동화(automation)로의 꾸준한 전환과 지능형 컴퓨터 시스템의 가능성을 가속화할 영리함의 번뜩이는 순간들을 보여주고 있습니다.

- 훈련된 모델은 텍스트를 생성합니다(A trained language model generates text).
- 선택적으로 일부 텍스트를 입력으로 넣을 수 있으며, 출력에 영향을 줍니다.
- 대량의 텍스트를 읽는(scan하는) 훈련 기간동안 “학습된” 모델로 부터 출력이 생성됩니다.

GPT-3 Training Dataset
![image](https://user-images.githubusercontent.com/43246784/218372507-0232715c-b887-48d7-98b2-aeccb3ece2ac.png)

![image](https://user-images.githubusercontent.com/43246784/218372939-685db260-cc1d-47e0-8194-f08362c32a27.png)


## 🔥 InstructGPT
논문 제목:Training language models to follow instructions with human feedback
- [InstructGPT 논문 보기](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
- InstructGPT 코딩 보기:2023.02.13까지 없음


![image](https://github.com/zhanglina94/gpt_explain_ko/blob/main/img/igpt.png)

![image](https://user-images.githubusercontent.com/43246784/218373275-fa7285f2-d020-4f7d-9d41-576d1a6a738a.png)


## 🔥 GPT3.5(ChatGPT)

![image](https://user-images.githubusercontent.com/43246784/218373426-7ec783bf-2dcb-4418-a10b-b05c534bcb35.png)

![image](https://user-images.githubusercontent.com/43246784/218373849-d829d50a-0b45-4f99-9559-c1c9d021c5c4.png)

![image](https://user-images.githubusercontent.com/43246784/218373872-c1e5b1d4-09d8-412d-8995-5f45be49e4b9.png)

![image](https://user-images.githubusercontent.com/43246784/218373880-ab1e81b0-9139-4aea-a1a2-dd933cfffbc1.png)

![image](https://user-images.githubusercontent.com/43246784/218373906-7782303e-5860-49b2-9afd-3a4d42be12db.png)

![image](https://user-images.githubusercontent.com/43246784/218373921-4a2a9404-e2d7-42a2-89db-31fd7abba13b.png)

![image](https://user-images.githubusercontent.com/43246784/218373961-3cd892d6-37e3-4883-a814-a15d3dcdc910.png)

![image](https://user-images.githubusercontent.com/43246784/218373991-d6aac029-4772-44e7-806b-f980965ed8c4.png)

-----

![image](https://user-images.githubusercontent.com/43246784/218373470-30b8aa26-675e-4560-96d0-e6a2c5cd98d9.png)

![image](https://user-images.githubusercontent.com/43246784/218374057-2adce878-38ac-4252-9950-14582c051547.png)

-----
#### Keypoint
##### RLHF:
-  논문 제목:Proximal Policy Optimization Algorithms

RLHF 이용한 Dialog Agents

  <p> Meta -> BlenderBot  [1] </p>
  <p> Google -> LaMDA [2] </p>
  <p> DeepMind -> Sparrow [3] </p>
  <p> Anthropic -> Assistant [4] </p>

RLHF의 과정:
<p>Step 1.Pretraining a language model (LM)</p>
<p>Step 2.Gathering data and training a reward model<p>
<p>Step 3.Fine-tuning the LM with reinforcement learning</p>



##### PPO

-  논문 제목:Proximal Policy Optimization Algorithms
![image](https://github.com/zhanglina94/gpt_explain_ko/blob/main/img/ppo.png)

##### Prompt
Prompt engineering is used to better understand the LLMs.

## References
[1] [2022_BlenderBot 3: a deployed conversational agent that continually∗ learns to responsibly engage](https://arxiv.org/abs/2208.03188) </p>
[2] [2022_LaMDA: Language Models for Dialog Applications!](https://arxiv.org/abs/2201.08239) </p>
[3] [2022_Improving alignment of dialogue agents via targeted human judgements](https://arxiv.org/abs/2209.14375) </p>
[4] [2022_Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2204.05862) </p>
[5] [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)</p>

## 🦸 Contributors

<a href="https://github.com/zhanglina94"><img src="https://avatars.githubusercontent.com/u/43246784?s=40&v=4" width="50" height="50" alt=""/></a>
