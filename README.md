# AI-For-Trading Project 2. Breakout Strategy

**Implementing a breakout trading strategy and use backtesting to estimate its profitability.**

이 프로젝트는 Udacity의 [AI For Trading](https://www.udacity.com/course/ai-for-trading--nd880)의 Project2 내용입니다.

## 개요
* Breakout Trading Signal을 만들고 백테스팅한다. 강력한 백테스팅 절차를 위해 이상치들을 제거한다.

* 데이터셋은 Quotemedia에서 주식 종가를 set을 활용했다.

## 내용
* 다양한 time window를 갖고 long-short breakout trading signal을 포착한다.

* 각각의 time window에서 중복되는 long-short signal을 제거한다.

* Kolmogorov-Smirnov Test를 사용하여 이상치를 확인한다.

* 발견한 모든 이상치들을 제거한 뒤 신호에 따른 수익률을 계산한다.

## Project2 - Jupyter Notebook
* [Project 2. Breakout Strategy](https://nbviewer.jupyter.org/gist/Hwanyy/2728a94a0ca067b3ae92004d71af3363)

## 사용된 라이브러리들과 version (Dependencies)
* [requirements.txt](https://github.com/Hwanyy/Ai-for-Trading-project-2-breakout-strategy/blob/main/requirements.txt)
