
@import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap');

:root {
  --bg: #080a0c;
  --panel: #101518;
  --line: #344348;
  --green: #9cf7b1;
  --dim: #6d8580;
  --red: #ff4545;
  --cream: #d6e4d9;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  background: radial-gradient(ellipse at top, #182024 0, #080a0c 65%);
  color: var(--cream);
  font-family: 'Share Tech Mono', Consolas, monospace;
  min-height: 100vh;
}

.scanlines {
  position: fixed;
  inset: 0;
  pointer-events: none;
  z-index: 20;
  background: repeating-linear-gradient(0deg, transparent 0 3px, #0005 4px);
  opacity: .23;
}

.topbar {
  height: 38px;
  border-bottom: 1px solid #344348;
  background: #0c1114;
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 0 16px;
  color: var(--green);
  font-size: 12px;
  letter-spacing: 1px;
}

.led {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #68ff91;
  box-shadow: 0 0 8px #68ff91;
}

.top-status {
  margin-left: auto;
  color: #83a59b;
}

.topbar time {
  color: #dce8df;
  margin-left: 15px;
}

.layout {
  max-width: 1250px;
  margin: 24px auto;
  padding: 0 16px;
  display: grid;
  grid-template-columns: minmax(320px, .92fr) minmax(320px, 1.08fr);
  gap: 18px;
  align-items: start;
}

.window {
  background: #0e1316;
  border: 1px solid var(--line);
  box-shadow: 0 12px 38px #0008;
  min-width: 0;
}

.window-title {
  height: 36px;
  background: linear-gradient(90deg, #1c2a2c, #101719);
  border-bottom: 1px solid var(--line);
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 10px;
  color: #d2e8da;
  font-size: 12px;
}

.window-title button {
  background: #192326;
  border: 1px solid #4b5c5f;
  color: #c6d9cf;
  width: 24px;
  height: 23px;
  cursor: pointer;
}

.profile {
  padding: 12px;
  display: flex;
  align-items: center;
  gap: 10px;
  border-bottom: 1px solid #283638;
}

.avatar {
  display: grid;
  place-items: center;
  width: 36px;
  height: 36px;
  background: #1e2c30;
  border: 1px solid #526468;
  color: var(--green);
  font-size: 20px;
}

.profile strong {
  color: var(--green);
  font-size: 14px;
}

.muted {
  color: #78908a;
  font-size: 11px;
  margin-top: 4px;
}

.encrypted {
  margin-left: auto;
  font-size: 10px;
  color: #8d9b8f;
}

.chat {
  height: 405px;
  overflow-y: auto;
  padding: 14px 13px 5px;
  scroll-behavior: smooth;
  background:
    linear-gradient(#0b1012e8, #0b1012e8),
    repeating-linear-gradient(0deg, transparent 0 24px, #1b2a2a 25px);
}

.line {
  font-size: 13px;
  line-height: 1.6;
  margin: 0 0 10px;
  overflow-wrap: anywhere;
  animation: appear .2s ease;
}

.line .who {
  color: #a1f4b1;
}

.line.player .who {
  color: #8cbaff;
}

.line.system .who {
  color: #e5bd75;
}

.line.glitch {
  color: #ff7777;
  text-shadow: 1px 0 #f00;
}

.line .stamp {
  color: #52645f;
  font-size: 10px;
  margin-right: 5px;
}

.chat-choices {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  gap: 7px;
  margin: 12px 0 17px;
  padding-left: 12px;
  border-left: 1px solid #3b5c4d;
}

.choice {
  background: #111c1b;
  border: 1px solid #3a5a4c;
  color: #c5e7d0;
  text-align: left;
  padding: 9px 11px;
  font: inherit;
  font-size: 12px;
  cursor: pointer;
  transition: .15s;
}

.choice:hover:not(:disabled) {
  background: #1d342a;
  border-color: var(--green);
  transform: translateX(2px);
}

button:disabled {
  opacity: .45;
  cursor: default;
}

.typing {
  padding: 5px 13px;
  color: #7ca38e;
  font-size: 11px;
  background: #0b1012;
}

.hidden {
  display: none !important;
}

.dots {
  animation: blink 1s steps(2, start) infinite;
}

.composer {
  display: flex;
  padding: 10px;
  gap: 7px;
  border-top: 1px solid #283638;
}

.composer input {
  flex: 1;
  min-width: 0;
  background: #080d0f;
  border: 1px solid #334744;
  color: #d8eee0;
  padding: 10px;
  font: inherit;
  font-size: 12px;
  outline: none;
}

.composer input:focus {
  border-color: #83cda0;
}

.composer button,
.ending button {
  background: #1d3b2b;
  border: 1px solid #6eaa80;
  color: #c9f6d5;
  padding: 0 13px;
  font: inherit;
  font-size: 11px;
  cursor: pointer;
}

.hint {
  font-size: 9px;
  color: #52645f;
  margin: 0;
  padding: 0 12px 10px;
}

.game-inner {
  padding: 12px;
}

.game-status,
.game-footer {
  display: flex;
  justify-content: space-between;
  gap: 8px;
  color: #6f9585;
  font-size: 10px;
  padding: 2px 1px 10px;
}

.game-status span:last-child {
  color: #d6c38a;
}

.scene {
  min-height: 455px;
  position: relative;
  overflow: hidden;
  background: linear-gradient(#b8e9c4 0 58%, #6caa7c 58% 100%);
  color: #193522;
  text-align: center;
  padding: 40px 18px 22px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  border: 3px ridge #d6e8d7;
  transition: background .3s, color .3s;
}

.scene h2 {
  font-size: clamp(20px, 3vw, 29px);
  letter-spacing: 2px;
  margin: 10px 0;
}

.scene p {
  max-width: 390px;
  font-size: 13px;
  line-height: 1.7;
  margin: 5px auto 16px;
}

.bunny {
  font-size: 76px;
  filter: drop-shadow(3px 5px 0 #294c3440);
  transition: transform .2s;
}

.actions {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 8px;
  margin-top: 12px;
  z-index: 2;
}

.actions button {
  font: inherit;
  font-size: 11px;
  padding: 10px 12px;
  background: #edf8e9;
  border: 2px outset #fff;
  color: #23452e;
  cursor: pointer;
}

.actions button:hover {
  filter: brightness(.9);
}

.room-objects {
  display: flex;
  gap: 7px;
  flex-wrap: wrap;
  justify-content: center;
  z-index: 2;
}

.room-objects button {
  background: #1a2424;
  color: #d4e8d8;
  border: 1px solid #718b7a;
  padding: 8px;
  font: inherit;
  font-size: 11px;
  cursor: pointer;
}

.scene.dark {
  background: radial-gradient(ellipse at center, #252b2d 0, #0b0d0e 75%);
  color: #d1d8d2;
  border-color: #5a6262;
}

.scene.dark .bunny {
  filter: grayscale(1) brightness(.65);
  transform: scale(1.1);
}

.scene.dark .actions button {
  background: #131819;
  color: #c7d4cc;
  border: 1px solid #687271;
}

.scene.dark h2 {
  color: #f36d6d;
  text-shadow: 0 0 12px #f00;
}

.scene.corrupt {
  animation: corrupt .15s infinite;
}

.scene-noise {
  position: absolute;
  inset: 0;
  pointer-events: none;
  opacity: 0;
  background: repeating-linear-gradient(0deg, transparent 0 7px, #fff2 8px);
  z-index: 1;
}

.scene.dark .scene-noise {
  opacity: .35;
}

.game-footer {
  padding: 10px 1px 0;
}

.ending {
  position: fixed;
  inset: 0;
  background: #000e;
  z-index: 30;
  display: grid;
  place-items: center;
  padding: 20px;
}

.ending-card {
  max-width: 520px;
  width: 100%;
  border: 1px solid #46534e;
  background: #0b1011;
  padding: 30px;
  box-shadow: 0 0 80px #ff00001a;
}

.eyebrow {
  font-size: 10px;
  letter-spacing: 3px;
  color: #8d9d95;
}

.ending h1 {
  font-size: clamp(28px, 6vw, 48px);
  color: #f05e5e;
  letter-spacing: 4px;
}

.ending-card p {
  line-height: 1.7;
}

.ending button {
  padding: 12px;
  margin-top: 14px;
}

.jumpscare {
  position: fixed;
  inset: 0;
  background: #000;
  z-index: 40;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  overflow: hidden;
}

.jumpscare.show {
  display: flex !important;
  animation: flash .12s steps(2, end) infinite;
}

.scare-face {
  font-family: Arial, sans-serif;
  font-size: min(55vw, 420px);
  line-height: .9;
  color: #f2eee8;
  text-shadow: 10px 0 #f00, -10px 0 #00f;
  transform: scaleY(1.2);
  animation: face .16s infinite alternate;
}

.scare-text {
  color: #ff2222;
  font-size: clamp(18px, 4vw, 42px);
  font-weight: bold;
  letter-spacing: 5px;
  text-align: center;
  margin-top: 20px;
  text-shadow: 0 0 12px red;
}

.shake {
  animation: shake .1s infinite;
}

.offline {
  color: #e66 !important;
}

.minimized .chat,
.minimized .profile,
.minimized .composer,
.minimized .hint,
.minimized .typing {
  display: none;
}

.minimized .window-title {
  border-bottom: 0;
}

@keyframes appear {
  from {
    opacity: 0;
    transform: translateY(4px);
  }
  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes blink {
  to {
    visibility: hidden;
  }
}

@keyframes flash {
  0% { background: #000; }
  50% { background: #1a0000; }
  100% { background: #000; }
}

@keyframes face {
  to {
    transform: scale(1.12, 1.35) translateX(8px);
  }
}

@keyframes shake {
  0% { transform: translate(4px, -2px); }
  50% { transform: translate(-4px, 2px); }
  100% { transform: translate(2px, 3px); }
}

@keyframes corrupt {
  0% { filter: hue-rotate(0); }
  50% { filter: hue-rotate(90deg) invert(.2); }
  100% { filter: hue-rotate(-30deg); }
}

@media (max-width: 820px) {
  .layout {
    grid-template-columns: 1fr;
    max-width: 650px;
    margin: 14px auto;
  }

  .chat {
    height: 320px;
  }

  .scene {
    min-height: 390px;
  }

  .game-window {
    grid-row: 1;
  }

  .encrypted {
    display: none;
  }
}

@media (max-width: 420px) {
  .layout {
    padding: 0 8px;
    gap: 10px;
  }

  .scene {
    padding: 25px 10px;
    min-height: 360px;
  }

  .bunny {
    font-size: 60px;
  }

  .chat {
    height: 300px;
  }

  .composer button {
    padding: 0 8px;
  }

  .window-title {
    font-size: 10px;
  }
}
