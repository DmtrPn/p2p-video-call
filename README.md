# P2P Video Chat (WebRTC demo)

Простейший пример p2p-видеозвонка на WebRTC **без собственного бэкенда**.  
Соединение устанавливается вручную: пользователи обмениваются `offer` и `answer` через копи-паст.

## Возможности
- Подключение камеры и микрофона (getUserMedia).
- P2P соединение между двумя браузерами.
- Отображение локального и удалённого видео.

## Ограничения
- Только 2 участника (one-to-one).
- Нет автоматического сигналинга — обмен SDP делается вручную.
- Используется публичный STUN-сервер Google (для демонстрации).
- Подходит **только для учебных целей**.

## Как использовать
1. Скачайте `p2p.html` и откройте его в двух браузерах.
2. В первом окне нажмите **Создать OFFER** и скопируйте JSON в буфер.
3. Вставьте его во второе окно и нажмите **Установить удалённое описание**.
4. Скопируйте сгенерированный **ANSWER** обратно в первое окно и тоже нажмите **Установить удалённое описание**.
5. Видео и звук должны подключиться напрямую.

## Назначение
Этот проект создан для демонстрации работы **WebRTC** и не предназначен для использования в продакшене.

---

# P2P Video Chat (WebRTC demo)

A minimal example of a peer-to-peer video call using WebRTC **without a custom backend**.  
The connection is established manually: users exchange `offer` and `answer` by copy-paste.

## Features
- Camera and microphone access (getUserMedia).
- P2P connection between two browsers.
- Local and remote video display.

## Limitations
- Only 2 participants (one-to-one).
- No automatic signaling — SDP exchange is manual.
- Uses Google’s public STUN server (for demo purposes).
- Intended **for educational purposes only**.

## Usage
1. Download `p2p-video-call.html` and open it in two browsers.
2. In the first window, click **Create OFFER** and copy the JSON.
3. Paste it into the second window and click **Set Remote Description**.
4. Copy the generated **ANSWER** back into the first window and also click **Set Remote Description**.
5. Video and audio should connect directly.

## Purpose
This project is for demonstrating **WebRTC basics** and is **not production ready**.
