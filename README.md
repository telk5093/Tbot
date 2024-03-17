# TKbot
TKbot은 [치지직](https://chzzk.naver.com)과 [Twitch](https://twitch.tv), [YouTube Live](https://www.youtube.com/live)를 지원하는 실시간 스트리밍 용 봇입니다.  


# 명령어
| 명령어                                          | 설명 | 기본 별칭 |
|-------------------------------------------------|------|-----|
| ``!title``                                      | 현재 방송 제목을 보여줍니다. (치지직만 지원) | ``!방제``, ``!타이틀``, ``!샤싣`` |
| ``!title <방송 제목>``                          | 방송 제목을 지정합니다. 채널 관리자만 사용 가능합니다. (치지직만 지원) | 〃 |
| ``!game``                                       | 현재 방송 주제를 보여줍니다. (치지직만 지원) | ``!게임``, ``!ㅎ믇``, ``!주제`` |
| ``!game <방송 주제>``                           | 방송 주제를 지정합니다. 채널 관리자만 사용 가능합니다. (치지직만 지원) | 〃 |
| ``!say <메시지>``                               | ``<메시지>``로 반응해줍니다 |  |
| ``!command add <추가할 명령어> <반응할 내용>``  | 명령어 별칭을 추가합니다. ``<추가할 명령어>``를 입력하면 ``<반응할 내용>``을 입력한 것과 같은 효과를 냅니다.<br />대답을 하게 하려면 ``!say`` 명령어와 조합하면 됩니다.<br />예를 들어, ``!hello`` 를 입력하면 TKbot이 ``안녕하세요``로 반응하게 하려면, ``!command add !hello !say 안녕하세요``를 입력하면 됩니다.<br /> ``!hello``의 별칭으로 ``!hi``를 등록하려면 ``!command add !hi !hello``를 입력하면 됩니다. | ``!명령어 추가`` |
| ``!command edit <수정할 명령어> <수정할 내용>`` | 명령어를 수정합니다. 형식은 ``!command add``와 동일합니다. | ``!명령어 수정`` |
| ``!command del <삭제할 명령어>``                | 명령어를 삭제합니다. | ``!command delete``, ``!command remove``, ``!명령어 삭제``, ``!명령어 제거`` |
| ``!command reload``                             | 명령어를 다시 불러옵니다. | ``!command refresh``, ``!명령어 새로고침``, ``!명령어 불러오기`` |
| ``!follow``                                     | 팔로우 기간을 보여줍니다. (치지직만 지원) | ``!팔로우`` |
* 유튜브는 명령어를 아직 지원하지 않습니다.

# 봇 관리자 권한

## 치지직
``치지직 스튜디오 > 채널/권한 관리 > 권한 관리``로 들어가서,  
``TKbot`` 또는 ``b3aabd192daea932db7b4465df5eb6a6`` 를 ``채널 관리자``로 추가해주세요.  

## Twitch
``스트리머 대시보드 > 커뮤니티 > 역할 관리자``로 들어가서,  
``telkbot``에 ``매니저, 편집자`` 역할을 추가해주세요.

# Thanks to
[kimcore/chzzk](https://github.com/kimcore/chzzk)
