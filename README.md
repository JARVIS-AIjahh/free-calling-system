# 📞 Free Calling System

Internet se **free** voice aur video call — WhatsApp call jaisa. Koi server, koi card, koi paisa nahi.

## Kya hai isme
- **index.html** — Free Call: har user ko 6 digit ID milti hai. Dost ki ID daalo → Voice ya Video call. Mute, camera on/off, call timer, ringtone.
- **ai.html** — AI Call: AI se bina button dabaye lagatar Hinglish me baat (Google AI Studio ki free key se).

## Kaise chalta hai
- Calls **WebRTC** se direct ek phone se dusre phone jaati hain (peer-to-peer).
- Dono ko milaane ke liye **PeerJS** ka free public server use hota hai.
- Hosting: **GitHub Pages** (free).

## Use kaise karein
1. Site kholo (Chrome best hai): `https://jarvis-aijahh.github.io/free-calling-system/`
2. Apni ID dost ko bhejo (📤 Share ID).
3. Dost bhi same link khole, tumhari ID daale → call!

## Limits (sach)
- Normal phone number (SIM) pe call **nahi** hoti — uske liye number aur per-minute paisa lagta hai.
- Dono ke paas page khula hona chahiye (app jaisa background me ring nahi hota).
- Kuch strict networks pe connect na ho to TURN server chahiye (free options: Metered / OpenRelay).

## Aage kya bana sakte ho
- Contacts list, call history
- Group call
- Push notification se background ring (Firebase, free tier)

Made with Tab 🤖
