## telegram_upbit
* 개인 문서 보관용
* 실행 결과랑 참고한 문서만 올릴 예정

### 참고한 문서
1. [telegram.ext.updater](https://python-telegram-bot.readthedocs.io/en/stable/telegram.ext.updater.html#telegram.ext.Updater.bot)
    * Its purpose is to receive the updates from Telegram and to deliver them to said dispatcher.

2. [python-telegram-bot_guide](https://github.com/python-telegram-bot/python-telegram-bot/wiki/Transition-guide-to-Version-12.0)
    * Handler

3. [telegram bot 2. 업비트 코인 가격을 메시지로 전송](https://apt-info.github.io/%EA%B0%9C%EB%B0%9C/telegram-command/)

4. [텔레그램 봇 간단 예제](https://idlecomputer.tistory.com/122)

5. [telegram bot api doc](https://core.telegram.org/bots/api)

6. [upbit api doc](https://docs.upbit.com/reference#%EC%9B%90%ED%99%94-%EC%9E%85%EA%B8%88%ED%95%98%EA%B8%B0)

7. [upbit error code doc](https://docs.upbit.com/docs/api-%EC%A3%BC%EC%9A%94-%EC%97%90%EB%9F%AC-%EC%BD%94%EB%93%9C-%EB%AA%A9%EB%A1%9D)


### 사용한 버전
* Python 3.8.3
* python-telegram-bot==13.3
* PyJWT==2.0.1
* pyupbit==0.2.8


### 남은 작업
# 채널로 할 지, 구독형 봇으로 할 지 선택
# 1. 1분마다 변화 체크
# 1-1. API로 데이터 읽어오기
# 1-2. 새 데이터, 이전 데이터 업데이트
# 2. 변화 체크 new state 기준으로 string 만들기
# 3. ID 저장되어있는 
