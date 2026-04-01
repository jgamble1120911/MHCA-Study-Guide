* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Segoe UI", sans-serif;
}

body {
  background: #000;
  color: #fff;
  overflow: hidden;
}

/* Background */
.bg {
  position: fixed;
  inset: 0;
  z-index: -1;
  overflow: hidden;
}

.gold-dust {
  position: absolute;
  inset: 0;
  background:
    radial-gradient(circle at 30% 20%, rgba(255,215,0,0.25), transparent 60%),
    radial-gradient(circle at 70% 80%, rgba(255,215,0,0.15), transparent 70%);
  filter: blur(20px);
}

.blue-glow {
  position: absolute;
  inset: 0;
  background: radial-gradient(circle at 80% 10%, rgba(0,120,255,0.25), transparent 70%);
  filter: blur(40px);
}

/* Layout */
.hud-root {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

.hud-top {
  height: 70px;
  display: flex;
  align-items: center;
  padding: 0 24px;
  border-bottom: 1px solid rgba(255,255,255,0.1);
  background: rgba(0,0,0,0.6);
  backdrop-filter: blur(10px);
}

.hud-logo {
  display: flex;
  align-items: center;
  gap: 12px;
}

.hud-logo-mark {
  font-size: 28px;
  font-weight: 700;
  color: gold;
}

.hud-logo-title {
  font-size: 20px;
  font-weight: 700;
}

.hud-logo-sub {
  font-size: 12px;
  opacity: 0.7;
}

.hud-status {
  margin-left: auto;
  display: flex;
  align-items: center;
  gap: 8px;
}

.status-dot {
  width: 10px;
  height: 10px;
  background: #00ff88;
  border-radius: 50%;
}

.hud-main {
  display: grid;
  grid-template-columns: 260px 1fr 260px;
  height: calc(100vh - 70px);
}

.hud-panel {
  padding: 20px;
  overflow-y: auto;
  background: rgba(0,0,0,0.45);
  backdrop-filter: blur(10px);
  border-right: 1px solid rgba(255,255,255,0.08);
}

.hud-center {
  border-right: none;
  border-left: none;
}

/* Panel header */
.panel-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 16px;
}

.panel-title {
  font-size: 14px;
  text-transform: uppercase;
  letter-spacing: 1px;
  opacity: 0.8;
}

.panel-accent {
  width: 40px;
  height: 2px;
  background: gold;
}

/* Sidebar */
.sidebar-list {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.sidebar-btn {
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(255,255,255,0.1);
  padding: 12px;
  border-radius: 6px;
  color: #fff;
  text-align: left;
  cursor: pointer;
  transition: 0.2s;
}

.sidebar-btn:hover,
.sidebar-btn.active {
  background: rgba(255,215,0,0.2);
  border-color: gold;
}

/* Buttons */
.btn {
  padding: 10px 16px;
  border-radius: 6px;
  cursor: pointer;
  border: none;
  font-weight: 600;
  transition: 0.2s;
}

.btn.primary {
  background: gold;
  color: #000;
}

.btn.secondary {
  background: rgba(255,255,255,0.15);
  border: 1px solid rgba(255,255,255,0.25);
}

.btn.ghost {
  background: transparent;
  border: 1px solid rgba(255,255,255,0.2);
}

.btn.tiny {
  padding: 6px 10px;
  font-size: 12px;
}

.btn.full {
  width: 100%;
}

.btn.mt-auto {
  margin-top: auto;
}

.btn.mt-16 {
  margin-top: 16px;
}

.btn:hover {
  opacity: 0.85;
}

/* Titles */
.title {
  font-size: 32px;
  font-weight: 700;
  margin-bottom: 12px;
}

.title.small {
  font-size: 24px;
}

.subtitle {
  opacity: 0.8;
  margin-bottom: 20px;
}

/* Views */
.view {
  display: none;
}

.view.active {
  display: block;
}

/* Quiz */
.quiz-top {
  margin-bottom: 10px;
}

.progress-wrap {
  width: 100%;
  height: 8px;
  background: rgba(255,255,255,0.1);
  border-radius: 4px;
  overflow: hidden;
}

.progress-bar {
  height: 100%;
  width: 0%;
  background: gold;
  transition: width 0.3s;
}

.progress-text {
  margin-top: 6px;
  font-size: 14px;
  opacity: 0.8;
}

.streak-row {
  display: flex;
  justify-content: space-between;
  margin: 12px 0;
  font-size: 14px;
}

.question-card {
  background: rgba(255,255,255,0.05);
  padding: 16px;
  border-radius: 8px;
  margin-bottom: 16px;
  border: 1px solid rgba(255,255,255,0.1);
}

.question-header {
  display: flex;
  justify-content: space-between;
  margin-bottom: 10px;
}

.question-label {
  font-size: 14px;
  opacity: 0.7;
}

.question-text {
  font-size: 20px;
  line-height: 1.4;
}

.options {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.option-btn {
  background: rgba(255,255,255,0.08);
  border: 1px solid rgba(255,255,255,0.15);
  padding: 12px;
  border-radius: 6px;
  cursor: pointer;
  text-align: left;
  transition: 0.2s;
}

.option-btn:hover {
  background: rgba(255,255,255,0.15);
}

.option-btn.selected {
  background: gold;
  color: #000;
  border-color: gold;
}

.controls-row {
  display: flex;
  gap: 10px;
  margin-top: 12px;
  flex-wrap: wrap;
}

.controls-row.bottom {
  margin-top: 20px;
}

.feedback-text {
  margin-top: 12px;
  font-size: 18px;
}

.feedback-text.correct {
  color: #00ff88;
}

.feedback-text.incorrect {
  color: #ff4444;
}

.hint-text,
.explanation-text {
  margin-top: 10px;
  opacity: 0.85;
  font-size: 14px;
}

/* Answer sheet */
.answer-overlay {
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.85);
  display: none;
  justify-content: center;
  align-items: center;
  padding: 40px;
  z-index: 20;
}

.answer-overlay.active {
  display: flex;
}

.answer-panel {
  width: 80%;
  height: 80%;
  background: rgba(0,0,0,0.6);
  border: 1px solid rgba(255,255,255,0.2);
  border-radius: 10px;
  padding: 20px;
  overflow-y: auto;
}

.answer-list {
  margin-top: 12px;
}

.answer-card {
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(255,255,255,0.1);
  padding: 12px;
  border-radius: 6px;
  margin-bottom: 12px;
}

.answer-q {
  font-weight: 600;
  margin-bottom: 6px;
}

.answer-a {
  font-size: 14px;
  opacity: 0.85;
}

/* Right panel */
.info-block {
  margin-bottom: 16px;
}

.info-label {
  font-size: 12px;
  opacity: 0.6;
}

.info-value {
  font-size: 16px;
  font-weight: 600;
}

.tip-card {
  background: rgba(255,255,255,0.05);
  padding: 12px;
  border-radius: 6px;
  border: 1px solid rgba(255,255,255,0.1);
  margin-top: 20px;
}

.tip-title {
  font-size: 14px;
  font-weight: 600;
  margin-bottom: 6px;
}

.tip-body {
  font-size: 13px;
  opacity: 0.8;
}

/* Scrollbars */
::-webkit-scrollbar {
  width: 8px;
}

::-webkit-scrollbar-thumb {
  background: rgba(255,255,255,0.2);
  border-radius: 4px;
}

::-webkit-scrollbar-thumb:hover {
  background: rgba(255,255,255,0.35);
}
