# DecibelBridge

Minecraft 서버에서 플레이어의 마이크 음량(dB)을 실시간으로 측정하고 표시하는 프로젝트입니다.

## 목표

웹 브라우저에서 사용자의 마이크 입력을 측정하여
음성 데이터는 저장하거나 전송하지 않고 dB 값만 Minecraft 서버로 전달합니다.

플레이어별 음량 정보를 서버에서 처리하여
HUD, Scoreboard 등의 형태로 표시하는 것을 목표로 합니다.

## 구조

HTML → GitHub Pages → cloudflared → WSS → Minecraft Plugin → Server
