# HiK: Hi Korea

Group Project - Team GoT(Gang of Three)


| **Name**          | **Student ID** | **Email**              | **Part**  |
| :---------------- | :------------- | :--------------------- | :---------|
| Minki Kang        | 20201980       | bbx8216@gmail.com      | Backend   |
| Gyeongbin Bak     | 20206024       | tarabin49@gmail.com    | Frontend  |
| Doyeon Lim        | 20206802       | yeons010420@gmail.com  | AI        | 

## Contents
- [HiK: Hi Korea](#HiK:-Hi-Korea)
  - [Contents](#contents)
  - [Introduction](#introduction)
    - [Project Topic](#project-topic)
    - [Proposal Background](#proposal-background)
    - [Main Features](#main-features)
    - [Project Goal & Contribution](#project-goal--contribution)
  - [Representative Screenshots](#representative-screenshots)
  - [Implementation Details](#implementation-details)
    - [Service Architecture](#service-architecture)
    - [Technology Used](#technology-used) 
    - [Code](#code)
- [In Korean](#in-korean)
  
## Introduction
### Project Topic
Language translation/learning application for foreigners staying in Korea by situation   

**Key-words**: Foreigners staying, contextual language translation, language learning   
**Field of the topic**: Translation and learning applications

### Proposal Background
- According to the Statistics Korea, 61.3 percent of the most difficult issues in studying in Korea are language problems.
- Among them, the most difficult language functions to feel are first-priority speaking (46.8%) and second-priority writing (34.2%), making it difficult to acquire language functions related to creation.
- The use of Korean culture's politeness method adds to the difficulty in conversation in everyday life.
- Education is needed to acquire politeness expressions that can appear in various situations in various dialogue situations.
- When an awkward sentence is used, such as an incorrect or inappropriate formality, the speaker's confidence in the conversation may decrease depending on the reaction of the interlocutor.
- Even in the photos below, such as "Carrot Foreign Transactions," it can be seen that foreigners staying in Korea have difficulty using proper language in daily conversations in Korean.
- <img width="200" alt="image" src="https://github.com/HiK-Hi-Korea/HiK-Server/assets/81232059/02c10485-3fcb-4283-9b78-d3b4db03bf37">
- It is intended to provide language translation appropriate to the situation and to help foreigners who have difficulty using Korean live a confident language life and a high-satisfaction Korean life by proposing an application that allows them to learn language and characteristics in various situations.

### Main Features
- When users enter or speak English sentences they want to translate aloud, and select the translation situation they want, they provide Korean sentences with language appropriate to the situation
- Pronunciation listening function that allows you to check the pronunciation of translated Korean sentences
- Location recognition function that determines where the conversation is based on the user's location (minimizes user manipulation in translation)
- Provide multi-layered learning services by providing examples of situations other than those selected by the user for sentence translation
- The ability to tell you what factors changed the translated sentence as a situation was applied
- User Login

### Project Goal & Contribution
- Helping foreigners to communicate and live in Korean naturally.
- The language learning function can help users improve their essential Korean skills.
- A business model that contributes to the promotion of communication and understanding in a multicultural society and aligns with sustainable development goals and ESG (environmental, social, and governance) values.
- Through realization conversation data, a Korean language language data set has been established, and a foundation for establishing a dedicated Korean language translation model may be laid.
- After user consent, conversation history data can be collected and analyzed to determine in which conversation situations foreigners experience discomfort and to use the data on a commercial or national level to quickly solve the inconvenience of using the facility.
- For example, from a national perspective, services such as checking frequently asked questions and producing response manuals can be provided through conversation data generated when using cultural properties or public facilities.
- On the commercial side, while existing applications provide formal, simple, and unsuitable content for real-life use, realistic learning content can be created and provided based on the advantage of being able to know sentences that are most difficult for foreigners staying in the country.

## Representative Screenshots
| <img src="https://github.com/HiK-Hi-Korea/.github/assets/81232059/6513aa67-43d1-4f60-b07e-f8889de62889" width="250px"/> | <img src="https://github.com/HiK-Hi-Korea/.github/assets/81232059/8d014f73-1fcb-4ee2-a12c-955d33631325"  width="250px"/> | <img src="https://github.com/HiK-Hi-Korea/.github/assets/81232059/4c5a33f2-ce9a-449c-967a-3f1a01835e44"  width="250px"/> | 
| :--------------------------------------------------------------------- | :--------------------------------------------------------------------- | :-------------------------------------------------------------------------- |
| <img src="https://github.com/HiK-Hi-Korea/.github/assets/81232059/012e378c-858f-446d-b93c-df4aa416d745" width="250px"/> | <img src="https://github.com/HiK-Hi-Korea/.github/assets/81232059/67cbab79-4852-4ad0-8b0b-dc91bdbc8d0d"  width="250px"/> | <img src="https://github.com/HiK-Hi-Korea/.github/assets/81232059/b7e60f3b-5748-4c8a-8b95-19e5eb35d083"  width="250px"/> |

## Implementation Details

### Service Architecture
![image](https://github.com/HiK-Hi-Korea/.github/assets/81232059/1ceffa69-a346-4b07-939b-353ec8654f61)

### Technology Used
- Spring boot
- Amazon EC2, RDS, S3
- MySQL
- Chat GPT api
- Prompt Engineering
- Google Map, TTS api
- react-native-voice STT

### Code
- [BE](https://github.com/HiK-Hi-Korea/HiK-Server)
- [FE](https://github.com/HiK-Hi-Korea/HiK-Client)
- [AI](https://github.com/HiK-Hi-Korea/Hik-Model)
  

## In Korean

### 1. 프로젝트 주제
체류 외국인 대상 한국어 상황별 어체 번역/학습 어플리케이션   

**Key-words**: 체류 외국인, 상황별 어체 번역, 어체 학습   
**Field of the topic**: 번역 및 학습 어플리케이션   

### 2. 제안배경
- 통계청에 따르면 한국 유학 생활 중 어려운 사항 1순위가 61.3%로 언어문제임.
- 이 중에서도 가장 어렵게 느끼는 언어기능은 1순위 말하기(46.8%), 2순위 쓰기(34.2%)로 생성과 관련된 언어기능을 습득하기 어려워함.
- 한국문화읭 높임법 사용은 일상생활에서 대화하는데 있어서 어려움을 가중시킴.
- 여러가지 상황에서 나타날 수 있는 높임표현을 다양한 대화상황에서 습득하는 교육이 필요함.
- 높임표현이 올바르지 않거나 적절하지 않은 격식체 등 어색한 문장을 구사했을 때 대화상대의 반응에 따라 발화자의 대화자신감이 하락할 수 있음.
- "당근 외국인 거래" 와 같은 아래 사진에서도 체류 외국인이 한국어 일상대화에서 적절한 어체 사용에 어려움을 겪는다는 것을 확인할 수 있음.
- <img width="200" alt="image" src="https://github.com/HiK-Hi-Korea/HiK-Server/assets/81232059/02c10485-3fcb-4283-9b78-d3b4db03bf37">
- 상황에 적절한 어체 번역을 제공하고 다양한 상황에서의 어체와 특징들을 학습할 수 있는 어플리케이션을 제안하여 한국어 사용에 어려움을 겪는 체류외국인들이 자신감 있는 언어생활과 만족도 높은 한국 생활을 할 수 있도록 보조하고자 함.


### 3. 프로젝트 소개
**주요 기능**
- 사용자가 번역을 원하는 영어문장을 입력하거나 소리내어 말하고, 원하는 번역 상황을 선택하면 상황에 알맞은 어체를 적용한 한국어 문장 제공
- 어체 번역된 한국어 문장의 발음을 확인할 수 있는 발음 듣기 기능
- 사용자의 위치를 통해 대화 장소가 어디인지 판단하는 장소 인식 기능(번역 시 사용자 조작 최소화)
- 사용자가 문장 번역에 선택했던 상황 이외의 다른 상황에 대한 예시 제공을 통해 다층적 학습 서비스 제공
- 상황이 적용되어 번역된 문장이 어떤 요소에 의해 바뀌었는지 알려주는 기능
- 사용자 로그인/회원가입

### 4. 목표(기여)
- 체류 외국인의 한국어 소통과 언어생활이 자연스럽게 이루어지도록 보조함.
- 어체 학습 기능을 통해 사용자의 본질적인 한국어 실력 향상에 도움을 줄 수 있음.
- 다문화 사회에서의 소통과 이해 증진에 기여하고 지속 가능한 발전 목표와 ESG(환경, 사회, 지배구조)가치에 부합하는 비즈니스 모델.
- 실생화 대화 데이터를 통해 한국어 어체 데이터셋을 구축하였고, 전용 한국어 어체 번역 모델을 구축할 수 있는 토대를 마련할 수 있음.
- 사용자 동의 후 대화 기록 데이터를 수집, 분석하여 체류 외국인이 어떤 대화 상황에서 불편함을 겪는지 확인하고 해당 데이터를 상업적 혹은 국가적 측면에서 사용하여 시설이용의 불편함을 빠르게 해결할 수 있는 솔루션을 도출할 수 있음.
- 예를 들어, 국가적 측면에서 문화재나 공공시설을 이용할 때 발생한 대화 데이터를 통해 자주 하는 질문 등을 체크하고, 대응 매뉴얼을 제작하는 등의 서비스를 제공할 수 있음.
- 상업적 측면에서는 기존 어플리케이션들이 형식적이고 단순한, 실생활에 이용하기에 적합하지 않은 콘텐츠를 제공하는 반면에 해당 데이터를 통해 체류 외국인들이 대부분 어려워하는 문장들을 알 수 있다는 장점을 토대로 현실적인 학습 콘텐츠를 만들어 제공할 수 있음.

### 5. 차별성
- 사용자가 원하는 상황에 적절한 어체 번역을 서비스로 제공.
- 실제 대화를 저장하고 직접적인 학습 컨텐츠로 제공.

<img width="671" alt="image" src="https://github.com/HiK-Hi-Korea/HiK-Server/assets/81232059/c8574451-aa26-407b-abc4-4239fd38deb1">

### 6. 개발 및 구현
**주요 기술**
- Spring boot
- Amazon EC2, RDS, S3
- MySQL
- Chat GPT api
- Prompt Engineering
- Google Map, TTS api
- react-native-voice STT
