# serverless-webrtc-rust

Minimal Rust serverless WebRTC demo

![image](https://user-images.githubusercontent.com/60191958/99572387-98cdd880-29a2-11eb-87cd-0f0e12d85642.png)

Built with:
- rust
- actix-web
- actix-web-static-files
- webrtc-unreliable

Notes:
- WebRTC will not work with Firefox on 127.0.0.1
- Kill with killall -9 webrtc-serverless-rust
- Removes STUN and TURN servers by sending SDP data directly to WebRTC servers via AJAX