# DecibelBridge

Minecraft Server에서 플레이어의 마이크 입력을 실시간으로 분석하여 dB(데시벨)와 Pitch(음높이)를 측정하고 표시하는 프로젝트입니다.

## 목표

웹 브라우저에서 사용자의 마이크 입력을 실시간으로 분석합니다.

* 음성 데이터는 저장하지 않습니다.
* 음성 데이터는 서버로 전송하지 않습니다.
* dB와 Pitch 같은 분석 결과값만 Minecraft Server로 전달합니다.

플레이어별 음량과 음높이 정보를 서버에서 처리하여 HUD, Scoreboard, 사운드 기반 퍼즐, 공포 게임 기믹 등에 활용하는 것을 목표로 합니다.

## 구조

HTML → DecibelBridge.jar → Minecraft Plugin → Minecraft Server


## 개인정보 보호

DecibelBridge는 사용자의 음성을 절대로! 녹음하거나 저장하지 않습니다.

마이크 입력은 사용자의 브라우저 내부에서 실시간 분석 후 즉시 폐기되며, 서버에는 dB와 Pitch 같은 분석 결과값만 전달됩니다.
