html

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>FitTrack — Diet & Fitness Tracker</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500;600;700&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>

<style>
/* ============================================================
   CSS VARIABLES & RESET
   ============================================================ */
:root {
  --bg: #080d1a;
  --bg2: #0f172a;
  --card: #111827;
  --card2: #1a2332;
  --border: rgba(99,102,241,0.15);
  --primary: #6366f1;
  --primary-light: #818cf8;
  --primary-dim: rgba(99,102,241,0.15);
  --secondary: #10b981;
  --secondary-dim: rgba(16,185,129,0.15);
  --accent: #f59e0b;
  --accent-dim: rgba(245,158,11,0.15);
  --danger: #ef4444;
  --danger-dim: rgba(239,68,68,0.15);
  --text: #f1f5f9;
  --text-muted: #64748b;
  --text-soft: #94a3b8;
  --radius: 18px;
  --radius-sm: 10px;
  --shadow: 0 8px 32px rgba(0,0,0,0.4);
  --shadow-lg: 0 20px 60px rgba(0,0,0,0.5);
  --nav-h: 70px;
  --glass: rgba(255,255,255,0.04);
  --glass-border: rgba(255,255,255,0.08);
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { height: 100%; }

body {
  font-family: 'DM Sans', sans-serif;
  background: var(--bg);
  color: var(--text);
  min-height: 100vh;
  overflow-x: hidden;
  position: relative;
  -webkit-tap-highlight-color: transparent;
}

/* ============================================================
   ANIMATED BACKGROUND
   ============================================================ */
.bg-orbs {
  position: fixed;
  inset: 0;
  pointer-events: none;
  z-index: 0;
  overflow: hidden;
}

.orb {
  position: absolute;
  border-radius: 50%;
  filter: blur(80px);
  animation: orbFloat 20s ease-in-out infinite;
  opacity: 0.25;
}

.orb-1 {
  width: 500px; height: 500px;
  background: radial-gradient(circle, #6366f1, transparent 70%);
  top: -150px; left: -150px;
  animation-delay: 0s; animation-duration: 25s;
}

.orb-2 {
  width: 400px; height: 400px;
  background: radial-gradient(circle, #10b981, transparent 70%);
  bottom: 100px; right: -100px;
  animation-delay: -10s; animation-duration: 20s;
}

.orb-3 {
  width: 300px; height: 300px;
  background: radial-gradient(circle, #f59e0b, transparent 70%);
  top: 50%; left: 50%;
  transform: translate(-50%, -50%);
  animation-delay: -5s; animation-duration: 30s;
  opacity: 0.12;
}

@keyframes orbFloat {
  0%, 100% { transform: translate(0, 0) scale(1); }
  25% { transform: translate(40px, -30px) scale(1.05); }
  50% { transform: translate(-20px, 40px) scale(0.95); }
  75% { transform: translate(30px, 20px) scale(1.02); }
}

/* ============================================================
   LAYOUT
   ============================================================ */
#app {
  position: relative;
  z-index: 1;
  max-width: 480px;
  margin: 0 auto;
  min-height: 100vh;
  padding-bottom: calc(var(--nav-h) + 16px);
}

.page {
  display: none;
  padding: 20px 16px;
  animation: pageIn 0.35s cubic-bezier(0.34, 1.4, 0.64, 1) both;
}

.page.active { display: block; }

@keyframes pageIn {
  from { opacity: 0; transform: translateY(18px); }
  to { opacity: 1; transform: translateY(0); }
}

/* ============================================================
   TOP HEADER
   ============================================================ */
.top-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px 16px 10px;
  position: sticky;
  top: 0;
  z-index: 50;
  background: linear-gradient(to bottom, var(--bg) 70%, transparent);
}

.logo {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 22px;
  font-weight: 700;
  background: linear-gradient(135deg, var(--primary-light), var(--secondary));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  letter-spacing: -0.5px;
}

.header-date {
  font-size: 12px;
  color: var(--text-muted);
  font-weight: 500;
}

/* ============================================================
   CARD BASE
   ============================================================ */
.card {
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  margin-bottom: 14px;
  overflow: hidden;
  transition: transform 0.2s, box-shadow 0.2s;
}

.card:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow);
}

.card-body { padding: 16px; }
.card-header { padding: 14px 16px 0; }
.card-title {
  font-size: 11px;
  font-weight: 600;
  letter-spacing: 1.2px;
  text-transform: uppercase;
  color: var(--text-muted);
  margin-bottom: 12px;
  display: flex;
  align-items: center;
  gap: 6px;
}
.card-title i { font-size: 12px; color: var(--primary-light); }

/* ============================================================
   IF TIMER CARD
   ============================================================ */
.if-card {
  background: linear-gradient(135deg, #1e1060 0%, #0f172a 50%, #0c1a2e 100%);
  border: 1px solid rgba(99,102,241,0.3);
  border-radius: var(--radius);
  padding: 22px 20px;
  margin-bottom: 14px;
  position: relative;
  overflow: hidden;
}

.if-card::before {
  content: '';
  position: absolute;
  inset: 0;
  background: radial-gradient(ellipse at top left, rgba(99,102,241,0.2), transparent 60%);
  pointer-events: none;
}

.if-card::after {
  content: '';
  position: absolute;
  top: -40px; right: -40px;
  width: 180px; height: 180px;
  border-radius: 50%;
  background: rgba(99,102,241,0.06);
  border: 1px solid rgba(99,102,241,0.1);
  pointer-events: none;
}

.if-status-badge {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 4px 12px;
  border-radius: 100px;
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  margin-bottom: 12px;
}

.if-status-badge.fasting {
  background: rgba(239,68,68,0.15);
  border: 1px solid rgba(239,68,68,0.3);
  color: #fca5a5;
}

.if-status-badge.eating {
  background: rgba(16,185,129,0.15);
  border: 1px solid rgba(16,185,129,0.3);
  color: #6ee7b7;
}

.pulse-dot {
  width: 6px; height: 6px;
  border-radius: 50%;
  animation: pulseDot 2s ease-in-out infinite;
}

.fasting .pulse-dot { background: #ef4444; }
.eating .pulse-dot { background: #10b981; }

@keyframes pulseDot {
  0%, 100% { transform: scale(1); opacity: 1; }
  50% { transform: scale(1.5); opacity: 0.5; }
}

.if-timer {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 52px;
  font-weight: 700;
  letter-spacing: -2px;
  line-height: 1;
  margin-bottom: 6px;
  background: linear-gradient(135deg, #fff 40%, #818cf8);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.if-subtitle {
  font-size: 13px;
  color: var(--text-soft);
  margin-bottom: 18px;
}

.if-buttons { display: flex; gap: 10px; }

.btn-if {
  flex: 1;
  padding: 12px;
  border-radius: 12px;
  border: none;
  font-family: 'DM Sans', sans-serif;
  font-size: 13px;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.2s;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 6px;
}

.btn-if:active { transform: scale(0.96); }

.btn-open {
  background: linear-gradient(135deg, #10b981, #059669);
  color: white;
  box-shadow: 0 4px 15px rgba(16,185,129,0.3);
}

.btn-close {
  background: linear-gradient(135deg, #ef4444, #dc2626);
  color: white;
  box-shadow: 0 4px 15px rgba(239,68,68,0.3);
}

.btn-if:hover { filter: brightness(1.1); transform: translateY(-1px); }

/* ============================================================
   QUICK STATS GRID
   ============================================================ */
.stats-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 10px;
  margin-bottom: 14px;
}

.stat-box {
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius);
  padding: 14px;
  transition: transform 0.2s, box-shadow 0.2s;
  cursor: default;
}

.stat-box:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow);
}

.stat-icon {
  width: 36px; height: 36px;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 16px;
  margin-bottom: 10px;
}

.stat-icon.purple { background: var(--primary-dim); color: var(--primary-light); }
.stat-icon.green { background: var(--secondary-dim); color: var(--secondary); }
.stat-icon.amber { background: var(--accent-dim); color: var(--accent); }
.stat-icon.red { background: var(--danger-dim); color: var(--danger); }

.stat-value {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 22px;
  font-weight: 700;
  line-height: 1;
  margin-bottom: 3px;
}

.stat-label {
  font-size: 11px;
  color: var(--text-muted);
  font-weight: 500;
}

.stat-sub {
  font-size: 10px;
  color: var(--text-muted);
  margin-top: 4px;
}

/* ============================================================
   PROGRESS BARS
   ============================================================ */
.progress-section { margin-bottom: 14px; }

.progress-item {
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius);
  padding: 14px 16px;
  margin-bottom: 10px;
}

.progress-top {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 8px;
}

.progress-name {
  display: flex;
  align-items: center;
  gap: 8px;
  font-size: 13px;
  font-weight: 600;
}

.progress-name i { font-size: 13px; }

.progress-val {
  font-size: 12px;
  color: var(--text-soft);
  font-family: 'Space Grotesk', sans-serif;
}

.progress-track {
  height: 8px;
  background: rgba(255,255,255,0.06);
  border-radius: 100px;
  overflow: hidden;
  position: relative;
}

.progress-fill {
  height: 100%;
  border-radius: 100px;
  position: relative;
  transition: width 0.8s cubic-bezier(0.34, 1.2, 0.64, 1);
  min-width: 0;
  max-width: 100%;
}

.progress-fill::after {
  content: '';
  position: absolute;
  top: 0; left: -100%;
  width: 60%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
  animation: shimmer 2.5s ease-in-out infinite;
}

@keyframes shimmer {
  0% { left: -60%; }
  100% { left: 160%; }
}

.fill-purple { background: linear-gradient(90deg, #6366f1, #818cf8); }
.fill-green { background: linear-gradient(90deg, #059669, #10b981); }
.fill-amber { background: linear-gradient(90deg, #d97706, #f59e0b); }
.fill-red { background: linear-gradient(90deg, #dc2626, #ef4444); }
.fill-over { background: linear-gradient(90deg, #ef4444, #f87171) !important; }

/* ============================================================
   WATER TRACKER
   ============================================================ */
.water-control {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  margin-top: 10px;
}

.btn-round {
  width: 44px; height: 44px;
  border-radius: 50%;
  border: 1px solid var(--glass-border);
  background: var(--glass);
  color: var(--text);
  font-size: 18px;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: all 0.2s;
  flex-shrink: 0;
}

.btn-round:active { transform: scale(0.9); }
.btn-round:hover { background: var(--primary-dim); border-color: var(--primary); color: var(--primary-light); }

.water-display {
  text-align: center;
  flex: 1;
}

.water-amount {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 28px;
  font-weight: 700;
  color: var(--text);
  line-height: 1;
}

.water-unit {
  font-size: 12px;
  color: var(--text-muted);
  margin-top: 2px;
}

/* ============================================================
   MOOD SLIDER
   ============================================================ */
.mood-section {
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius);
  padding: 16px;
  margin-bottom: 14px;
}

.mood-emoji {
  text-align: center;
  font-size: 42px;
  margin-bottom: 8px;
  line-height: 1;
  transition: all 0.3s;
  filter: drop-shadow(0 0 12px rgba(99,102,241,0.4));
}

.mood-label {
  text-align: center;
  font-size: 13px;
  color: var(--text-soft);
  margin-bottom: 12px;
  font-weight: 500;
}

input[type=range] {
  -webkit-appearance: none;
  appearance: none;
  width: 100%;
  height: 6px;
  border-radius: 100px;
  background: linear-gradient(90deg, var(--primary) var(--val, 50%), rgba(255,255,255,0.08) var(--val, 50%));
  outline: none;
  cursor: pointer;
}

input[type=range]::-webkit-slider-thumb {
  -webkit-appearance: none;
  width: 22px; height: 22px;
  border-radius: 50%;
  background: var(--primary);
  box-shadow: 0 0 0 4px rgba(99,102,241,0.25), 0 2px 8px rgba(0,0,0,0.4);
  transition: transform 0.15s;
  cursor: grab;
}

input[type=range]:active::-webkit-slider-thumb {
  transform: scale(1.15);
  cursor: grabbing;
}

.mood-labels {
  display: flex;
  justify-content: space-between;
  font-size: 10px;
  color: var(--text-muted);
  margin-top: 6px;
}

/* ============================================================
   FOOD TRACKER
   ============================================================ */
.form-card {
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius);
  padding: 16px;
  margin-bottom: 14px;
}

.form-row {
  display: flex;
  gap: 10px;
  margin-bottom: 10px;
}

.form-group {
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 5px;
}

label {
  font-size: 11px;
  font-weight: 600;
  color: var(--text-muted);
  letter-spacing: 0.5px;
  text-transform: uppercase;
}

input[type=text],
input[type=number],
input[type=time],
input[type=date],
select,
textarea {
  background: rgba(255,255,255,0.05);
  border: 1px solid var(--glass-border);
  border-radius: 10px;
  padding: 10px 12px;
  color: var(--text);
  font-family: 'DM Sans', sans-serif;
  font-size: 14px;
  width: 100%;
  outline: none;
  transition: border-color 0.2s, box-shadow 0.2s;
  -webkit-appearance: none;
}

input:focus,
select:focus,
textarea:focus {
  border-color: var(--primary);
  box-shadow: 0 0 0 3px rgba(99,102,241,0.15);
}

select {
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='12' viewBox='0 0 12 12'%3E%3Cpath fill='%2364748b' d='M6 8L1 3h10z'/%3E%3C/svg%3E");
  background-repeat: no-repeat;
  background-position: right 12px center;
  padding-right: 32px;
  cursor: pointer;
}

select option { background: #1a2332; color: var(--text); }

textarea {
  resize: vertical;
  min-height: 72px;
}

input[type=time]::-webkit-calendar-picker-indicator,
input[type=date]::-webkit-calendar-picker-indicator {
  filter: invert(0.6);
  cursor: pointer;
}

.btn-primary {
  width: 100%;
  padding: 13px;
  border-radius: 12px;
  border: none;
  background: linear-gradient(135deg, var(--primary), #4f46e5);
  color: white;
  font-family: 'DM Sans', sans-serif;
  font-size: 14px;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.2s;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  box-shadow: 0 4px 15px rgba(99,102,241,0.3);
}

.btn-primary:hover { filter: brightness(1.1); transform: translateY(-1px); box-shadow: 0 6px 20px rgba(99,102,241,0.4); }
.btn-primary:active { transform: scale(0.98) translateY(0); }

.btn-green {
  background: linear-gradient(135deg, var(--secondary), #059669);
  box-shadow: 0 4px 15px rgba(16,185,129,0.3);
}
.btn-green:hover { box-shadow: 0 6px 20px rgba(16,185,129,0.4); }

/* ============================================================
   FOOD LIST ITEMS
   ============================================================ */
.food-item {
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius-sm);
  padding: 12px 14px;
  margin-bottom: 8px;
  display: flex;
  align-items: center;
  gap: 12px;
  transition: transform 0.2s, box-shadow 0.2s;
}

.food-item:hover {
  transform: translateX(4px);
  box-shadow: var(--shadow);
}

.food-info { flex: 1; min-width: 0; }

.food-name {
  font-size: 14px;
  font-weight: 600;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  margin-bottom: 3px;
}

.food-meta {
  font-size: 11px;
  color: var(--text-muted);
  display: flex;
  gap: 10px;
}

.food-badge {
  padding: 2px 8px;
  border-radius: 100px;
  font-size: 10px;
  font-weight: 600;
  flex-shrink: 0;
}

.badge-cal { background: var(--primary-dim); color: var(--primary-light); }
.badge-prot { background: var(--secondary-dim); color: var(--secondary); }

.btn-delete {
  width: 32px; height: 32px;
  border-radius: 8px;
  border: 1px solid rgba(239,68,68,0.2);
  background: rgba(239,68,68,0.08);
  color: #f87171;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 12px;
  transition: all 0.2s;
  flex-shrink: 0;
}

.btn-delete:hover { background: var(--danger); color: white; }
.btn-delete:active { transform: scale(0.9); }

.total-bar {
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius-sm);
  padding: 12px 14px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 4px;
}

.warning-msg {
  background: rgba(239,68,68,0.1);
  border: 1px solid rgba(239,68,68,0.3);
  border-radius: var(--radius-sm);
  padding: 10px 14px;
  font-size: 12px;
  color: #fca5a5;
  display: flex;
  align-items: center;
  gap: 8px;
  margin-top: 8px;
}

.empty-state {
  text-align: center;
  padding: 30px 20px;
  color: var(--text-muted);
}

.empty-state i {
  font-size: 36px;
  margin-bottom: 10px;
  opacity: 0.3;
  display: block;
}

.empty-state p { font-size: 13px; }

/* ============================================================
   WORKOUT BADGES
   ============================================================ */
.workout-badge {
  display: inline-block;
  padding: 3px 10px;
  border-radius: 100px;
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 0.5px;
}

.badge-fullbody { background: rgba(99,102,241,0.2); color: #818cf8; }
.badge-cardio { background: rgba(239,68,68,0.2); color: #f87171; }
.badge-lower { background: rgba(245,158,11,0.2); color: #fbbf24; }
.badge-upper { background: rgba(16,185,129,0.2); color: #34d399; }
.badge-hiit { background: rgba(236,72,153,0.2); color: #f472b6; }
.badge-rest { background: rgba(100,116,139,0.2); color: #94a3b8; }

.workout-item {
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius-sm);
  padding: 12px 14px;
  margin-bottom: 8px;
  transition: transform 0.2s;
}

.workout-item:hover { transform: translateX(4px); }

.workout-top {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 6px;
}

.workout-detail {
  font-size: 12px;
  color: var(--text-soft);
  line-height: 1.5;
  margin-top: 6px;
}

/* ============================================================
   WEIGHT TRACKER
   ============================================================ */
.weight-item {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 10px 14px;
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius-sm);
  margin-bottom: 8px;
}

.weight-val {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 20px;
  font-weight: 700;
}

.weight-change {
  display: flex;
  align-items: center;
  gap: 4px;
  font-size: 12px;
  font-weight: 600;
}

.weight-change.down { color: var(--secondary); }
.weight-change.up { color: var(--danger); }
.weight-change.same { color: var(--text-muted); }

.weight-date { font-size: 11px; color: var(--text-muted); }

/* ============================================================
   CHART CONTAINER
   ============================================================ */
.chart-wrap {
  position: relative;
  height: 180px;
  padding: 8px 4px;
}

/* ============================================================
   PROGRESS PAGE
   ============================================================ */
.progress-meta {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 10px;
}

.meta-item {
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius-sm);
  padding: 14px;
  text-align: center;
}

.meta-val {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 22px;
  font-weight: 700;
  margin-bottom: 3px;
}

.meta-lbl {
  font-size: 11px;
  color: var(--text-muted);
  font-weight: 500;
}

.overall-progress {
  background: var(--glass);
  border: 1px solid var(--glass-border);
  border-radius: var(--radius);
  padding: 18px;
  margin-bottom: 14px;
  position: relative;
  overflow: hidden;
}

.overall-progress::before {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, rgba(99,102,241,0.05), transparent);
  pointer-events: none;
}

.progress-pct {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 48px;
  font-weight: 700;
  background: linear-gradient(135deg, var(--primary-light), var(--secondary));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  line-height: 1;
  margin-bottom: 4px;
}

/* ============================================================
   BOTTOM NAVIGATION
   ============================================================ */
.bottom-nav {
  position: fixed;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 100%;
  max-width: 480px;
  height: var(--nav-h);
  background: rgba(8,13,26,0.85);
  backdrop-filter: blur(24px);
  -webkit-backdrop-filter: blur(24px);
  border-top: 1px solid var(--glass-border);
  display: flex;
  align-items: center;
  z-index: 100;
  padding: 0 8px;
}

.nav-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 4px;
  padding: 8px 4px;
  cursor: pointer;
  border-radius: 12px;
  transition: all 0.25s cubic-bezier(0.34, 1.4, 0.64, 1);
  border: none;
  background: none;
  color: var(--text-muted);
  -webkit-tap-highlight-color: transparent;
}

.nav-item i { font-size: 18px; transition: all 0.25s; }
.nav-item span { font-size: 9px; font-weight: 600; letter-spacing: 0.3px; }

.nav-item.active {
  color: var(--primary-light);
  transform: translateY(-2px);
}

.nav-item.active i {
  text-shadow: 0 0 16px rgba(129,140,248,0.6);
  transform: scale(1.1);
}

/* ============================================================
   TOAST NOTIFICATION
   ============================================================ */
#toast-container {
  position: fixed;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  z-index: 9999;
  width: 100%;
  max-width: 460px;
  padding: 12px 16px 0;
  pointer-events: none;
}

.toast {
  background: rgba(30,40,60,0.95);
  border: 1px solid var(--glass-border);
  backdrop-filter: blur(20px);
  border-radius: 12px;
  padding: 12px 16px;
  margin-bottom: 8px;
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 13px;
  font-weight: 500;
  pointer-events: auto;
  animation: toastIn 0.4s cubic-bezier(0.34, 1.4, 0.64, 1) both;
  box-shadow: 0 8px 30px rgba(0,0,0,0.4);
}

.toast.removing { animation: toastOut 0.3s ease-in both; }

@keyframes toastIn {
  from { opacity: 0; transform: translateY(-20px) scale(0.95); }
  to { opacity: 1; transform: translateY(0) scale(1); }
}

@keyframes toastOut {
  from { opacity: 1; transform: translateY(0) scale(1); max-height: 60px; }
  to { opacity: 0; transform: translateY(-10px) scale(0.95); max-height: 0; padding: 0; margin: 0; }
}

.toast-icon { font-size: 16px; flex-shrink: 0; }
.toast.success .toast-icon { color: var(--secondary); }
.toast.error .toast-icon { color: var(--danger); }
.toast.info .toast-icon { color: var(--primary-light); }

/* ============================================================
   SECTION TITLE
   ============================================================ */
.section-title {
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  color: var(--text-muted);
  margin-bottom: 10px;
  display: flex;
  align-items: center;
  gap: 8px;
}

.section-title::after {
  content: '';
  flex: 1;
  height: 1px;
  background: var(--glass-border);
}

/* ============================================================
   EXPORT/BACKUP SECTION
   ============================================================ */
.btn-sm {
  padding: 9px 16px;
  border-radius: 10px;
  border: 1px solid var(--glass-border);
  background: var(--glass);
  color: var(--text-soft);
  font-family: 'DM Sans', sans-serif;
  font-size: 12px;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.2s;
  display: inline-flex;
  align-items: center;
  gap: 6px;
}

.btn-sm:hover { border-color: var(--primary); color: var(--primary-light); background: var(--primary-dim); }
.btn-sm:active { transform: scale(0.97); }

.btn-row { display: flex; gap: 8px; flex-wrap: wrap; }

/* ============================================================
   SCROLLBAR
   ============================================================ */
::-webkit-scrollbar { width: 4px; }
::-webkit-scrollbar-track { background: transparent; }
::-webkit-scrollbar-thumb { background: rgba(99,102,241,0.3); border-radius: 100px; }

/* ============================================================
   RESPONSIVE DESKTOP
   ============================================================ */
@media (min-width: 480px) {
  .bottom-nav { border-radius: 16px 16px 0 0; }
}
</style>
</head>

<body>
<div class="bg-orbs">
  <div class="orb orb-1"></div>
  <div class="orb orb-2"></div>
  <div class="orb orb-3"></div>
</div>

<div id="toast-container"></div>

<div id="app">
  <!-- TOP HEADER -->
  <div class="top-header">
    <div class="logo"><i class="fa-solid fa-bolt" style="font-size:16px"></i> FitTrack</div>
    <div class="header-date" id="header-date"></div>
  </div>

  <!-- ========== PAGE: HARI INI ========== -->
  <div class="page active" id="page-today">

    <!-- IF TIMER -->
    <div class="if-card" id="if-card">
      <div class="if-status-badge fasting" id="if-badge">
        <span class="pulse-dot"></span>
        <span id="if-badge-text">SEDANG PUASA</span>
      </div>
      <div class="if-timer" id="if-timer">00:00:00</div>
      <div class="if-subtitle" id="if-subtitle">Memuat...</div>
      <div class="if-buttons" id="if-buttons">
        <button class="btn-if btn-open" id="btn-open-fast" onclick="openFastingWindow()">
          <i class="fa-solid fa-utensils"></i> Buka Puasa
        </button>
        <button class="btn-if btn-close" id="btn-close-fast" onclick="closeFastingWindow()">
          <i class="fa-solid fa-moon"></i> Tutup Puasa
        </button>
      </div>
    </div>

    <!-- QUICK STATS -->
    <div class="stats-grid">
      <div class="stat-box">
        <div class="stat-icon purple"><i class="fa-solid fa-weight-scale"></i></div>
        <div class="stat-value" id="stat-weight">–</div>
        <div class="stat-label">Berat Hari Ini</div>
        <div class="stat-sub">Target: 80 kg</div>
      </div>
      <div class="stat-box">
        <div class="stat-icon green"><i class="fa-solid fa-fire"></i></div>
        <div class="stat-value" id="stat-cal">0</div>
        <div class="stat-label">Kalori (kcal)</div>
        <div class="stat-sub">Target: 1.800–2.000</div>
      </div>
      <div class="stat-box">
        <div class="stat-icon amber"><i class="fa-solid fa-drumstick-bite"></i></div>
        <div class="stat-value" id="stat-prot">0</div>
        <div class="stat-label">Protein (g)</div>
        <div class="stat-sub">Target: 150–180g</div>
      </div>
      <div class="stat-box">
        <div class="stat-icon red"><i class="fa-solid fa-droplet"></i></div>
        <div class="stat-value" id="stat-water-val">0</div>
        <div class="stat-label">Air (ml)</div>
        <div class="stat-sub">Target: 2.500 ml</div>
      </div>
    </div>

    <!-- PROGRESS BARS -->
    <div class="section-title"><i class="fa-solid fa-chart-bar"></i> Progress Hari Ini</div>
    <div class="progress-section">
      <div class="progress-item">
        <div class="progress-top">
          <div class="progress-name" style="color:#818cf8"><i class="fa-solid fa-fire" style="color:#818cf8"></i> Kalori</div>
          <div class="progress-val"><span id="pb-cal-val">0</span> / 1.900 kcal</div>
        </div>
        <div class="progress-track">
          <div class="progress-fill fill-purple" id="pb-cal" style="width:0%"></div>
        </div>
      </div>
      <div class="progress-item">
        <div class="progress-top">
          <div class="progress-name" style="color:#34d399"><i class="fa-solid fa-drumstick-bite" style="color:#34d399"></i> Protein</div>
          <div class="progress-val"><span id="pb-prot-val">0</span> / 165g</div>
        </div>
        <div class="progress-track">
          <div class="progress-fill fill-green" id="pb-prot" style="width:0%"></div>
        </div>
      </div>
      <div class="progress-item">
        <div class="progress-top">
          <div class="progress-name" style="color:#fbbf24"><i class="fa-solid fa-droplet" style="color:#fbbf24"></i> Air Minum</div>
          <div class="progress-val"><span id="pb-water-val">0</span> / 2.500 ml</div>
        </div>
        <div class="progress-track">
          <div class="progress-fill fill-amber" id="pb-water" style="width:0%"></div>
        </div>
      </div>
    </div>

    <!-- WATER TRACKER -->
    <div class="card">
      <div class="card-header">
        <div class="card-title"><i class="fa-solid fa-droplet"></i> Tracker Air Minum</div>
      </div>
      <div class="card-body">
        <div class="water-control">
          <button class="btn-round" onclick="changeWater(-250)"><i class="fa-solid fa-minus"></i></button>
          <div class="water-display">
            <div class="water-amount" id="water-display">0</div>
            <div class="water-unit">ml dari 2.500 ml</div>
          </div>
          <button class="btn-round" onclick="changeWater(250)"><i class="fa-solid fa-plus"></i></button>
        </div>
      </div>
    </div>

    <!-- MOOD SLIDER -->
    <div class="mood-section">
      <div class="card-title" style="margin-bottom:12px"><i class="fa-solid fa-face-smile"></i> Mood Hari Ini</div>
      <div class="mood-emoji" id="mood-emoji">😐</div>
      <div class="mood-label" id="mood-label">Biasa Aja</div>
      <input type="range" min="1" max="5" value="3" id="mood-slider" oninput="updateMood(this.value)">
      <div class="mood-labels">
        <span>😫 Lemas</span>
        <span>😕</span>
        <span>😐</span>
        <span>🙂</span>
        <span>🤩 Semangat!</span>
      </div>
    </div>

  </div><!-- /page-today -->

  <!-- ========== PAGE: MAKANAN ========== -->
  <div class="page" id="page-food">
    <div class="section-title"><i class="fa-solid fa-plus-circle"></i> Tambah Makanan</div>
    <div class="form-card">
      <div class="form-row">
        <div class="form-group" style="max-width:110px">
          <label>Jam</label>
          <input type="time" id="food-time" value="12:00">
        </div>
        <div class="form-group">
          <label>Nama Makanan</label>
          <input type="text" id="food-name" placeholder="Contoh: Nasi putih...">
        </div>
      </div>
      <div class="form-row">
        <div class="form-group">
          <label>Kalori (kcal)</label>
          <input type="number" id="food-cal" placeholder="0" min="0">
        </div>
        <div class="form-group">
          <label>Protein (g)</label>
          <input type="number" id="food-prot" placeholder="0" min="0" step="0.1">
        </div>
      </div>
      <button class="btn-primary btn-green" onclick="addFood()">
        <i class="fa-solid fa-plus"></i> Tambah Makanan
      </button>
    </div>

    <div class="section-title"><i class="fa-solid fa-list"></i> Daftar Makanan Hari Ini</div>
    <div id="food-list"></div>
    <div id="food-total-bar"></div>
    <div id="food-warning"></div>
  </div><!-- /page-food -->

  <!-- ========== PAGE: OLAHRAGA ========== -->
  <div class="page" id="page-workout">
    <div class="section-title"><i class="fa-solid fa-plus-circle"></i> Catat Olahraga</div>
    <div class="form-card">
      <div class="form-row">
        <div class="form-group">
          <label>Jenis Latihan</label>
          <select id="workout-type">
            <option value="fullbody">💪 Full Body</option>
            <option value="cardio">🏃 Cardio</option>
            <option value="lower">🦵 Lower Body</option>
            <option value="upper">🤸 Upper Body</option>
            <option value="hiit">⚡ HIIT</option>
            <option value="rest">😴 Rest Day</option>
          </select>
        </div>
        <div class="form-group" style="max-width:90px">
          <label>Durasi (mnt)</label>
          <input type="number" id="workout-dur" placeholder="30" min="0">
        </div>
      </div>
      <div class="form-group" style="margin-bottom:10px">
        <label>Tanggal</label>
        <input type="date" id="workout-date">
      </div>
      <div class="form-group" style="margin-bottom:12px">
        <label>Detail Gerakan / Set / Reps</label>
        <textarea id="workout-detail" placeholder="Contoh: Squat 3x15, Push-up 3x12, Plank 3x30s..."></textarea>
      </div>
      <button class="btn-primary" onclick="addWorkout()">
        <i class="fa-solid fa-floppy-disk"></i> Simpan Latihan
      </button>
    </div>

    <div class="section-title"><i class="fa-solid fa-clock-rotate-left"></i> Riwayat Minggu Ini</div>
    <div id="workout-list"></div>
  </div><!-- /page-workout -->

  <!-- ========== PAGE: BERAT ========== -->
  <div class="page" id="page-weight">
    <div class="section-title"><i class="fa-solid fa-plus-circle"></i> Input Berat Badan</div>
    <div class="form-card">
      <div class="form-row">
        <div class="form-group">
          <label>Berat (kg)</label>
          <input type="number" id="weight-input" placeholder="92.0" min="30" max="200" step="0.1">
        </div>
        <div class="form-group">
          <label>Tanggal</label>
          <input type="date" id="weight-date">
        </div>
      </div>
      <button class="btn-primary btn-green" onclick="saveWeight()">
        <i class="fa-solid fa-floppy-disk"></i> Simpan Berat
      </button>
    </div>

    <div class="section-title"><i class="fa-solid fa-chart-line"></i> Grafik Berat Badan</div>
    <div class="card">
      <div class="card-body">
        <div class="chart-wrap" id="weight-chart-wrap">
          <canvas id="weight-chart"></canvas>
        </div>
        <div id="weight-chart-msg" style="display:none" class="empty-state">
          <i class="fa-solid fa-chart-line"></i>
          <p>Butuh minimal 2 data untuk menampilkan grafik</p>
        </div>
      </div>
    </div>

    <div class="section-title"><i class="fa-solid fa-list"></i> Riwayat Berat</div>
    <div id="weight-list"></div>
  </div><!-- /page-weight -->

  <!-- ========== PAGE: PROGRESS ========== -->
  <div class="page" id="page-progress">

    <!-- Overall Progress -->
    <div class="section-title"><i class="fa-solid fa-trophy"></i> Progress Keseluruhan</div>
    <div class="overall-progress">
      <div style="font-size:12px;color:var(--text-muted);margin-bottom:4px;text-transform:uppercase;letter-spacing:1px;font-weight:600">Menuju Target</div>
      <div class="progress-pct" id="prog-pct">0%</div>
      <div style="font-size:13px;color:var(--text-soft);margin-bottom:14px" id="prog-sub">Mulai perjalananmu!</div>
      <div class="progress-track" style="height:10px;margin-bottom:14px">
        <div class="progress-fill fill-purple" id="prog-bar" style="width:0%"></div>
      </div>
      <div class="progress-meta">
        <div class="meta-item">
          <div class="meta-val" style="color:var(--danger)" id="prog-start">92 kg</div>
          <div class="meta-lbl">Berat Awal</div>
        </div>
        <div class="meta-item">
          <div class="meta-val" style="color:var(--primary-light)" id="prog-current">– kg</div>
          <div class="meta-lbl">Berat Sekarang</div>
        </div>
        <div class="meta-item">
          <div class="meta-val" style="color:var(--secondary)" id="prog-lost">0 kg</div>
          <div class="meta-lbl">Sudah Turun</div>
        </div>
        <div class="meta-item">
          <div class="meta-val" style="color:var(--accent)" id="prog-left">12 kg</div>
          <div class="meta-lbl">Sisa ke Target</div>
        </div>
      </div>
    </div>

    <!-- Kalori 7 Hari -->
    <div class="section-title"><i class="fa-solid fa-fire"></i> Kalori 7 Hari Terakhir</div>
    <div class="card">
      <div class="card-body">
        <div class="chart-wrap" id="cal-chart-wrap">
          <canvas id="cal-chart"></canvas>
        </div>
        <div id="cal-chart-msg" class="empty-state" style="display:none">
          <i class="fa-solid fa-fire"></i>
          <p>Belum ada data kalori minggu ini</p>
        </div>
      </div>
    </div>

    <!-- Protein 7 Hari -->
    <div class="section-title"><i class="fa-solid fa-drumstick-bite"></i> Protein 7 Hari Terakhir</div>
    <div class="card">
      <div class="card-body">
        <div class="chart-wrap" id="prot-chart-wrap">
          <canvas id="prot-chart"></canvas>
        </div>
        <div id="prot-chart-msg" class="empty-state" style="display:none">
          <i class="fa-solid fa-drumstick-bite"></i>
          <p>Belum ada data protein minggu ini</p>
        </div>
      </div>
    </div>

    <!-- Export & Backup -->
    <div class="section-title"><i class="fa-solid fa-gear"></i> Data & Backup</div>
    <div class="form-card">
      <div class="btn-row">
        <button class="btn-sm" onclick="exportCSV()"><i class="fa-solid fa-file-csv"></i> Export CSV</button>
        <button class="btn-sm" onclick="backupData()"><i class="fa-solid fa-copy"></i> Backup JSON</button>
        <button class="btn-sm" onclick="showRestore()"><i class="fa-solid fa-upload"></i> Restore</button>
      </div>
      <div id="restore-area" style="display:none;margin-top:12px">
        <textarea id="restore-input" placeholder="Paste JSON backup di sini..." style="margin-bottom:8px;height:80px"></textarea>
        <button class="btn-primary" onclick="restoreData()">
          <i class="fa-solid fa-rotate-left"></i> Restore Data
        </button>
      </div>
    </div>

  </div><!-- /page-progress -->

</div><!-- /app -->

<!-- BOTTOM NAVIGATION -->
<nav class="bottom-nav">
  <button class="nav-item active" onclick="switchTab('today',this)" id="nav-today">
    <i class="fa-solid fa-house"></i>
    <span>Hari Ini</span>
  </button>
  <button class="nav-item" onclick="switchTab('food',this)" id="nav-food">
    <i class="fa-solid fa-utensils"></i>
    <span>Makanan</span>
  </button>
  <button class="nav-item" onclick="switchTab('workout',this)" id="nav-workout">
    <i class="fa-solid fa-dumbbell"></i>
    <span>Olahraga</span>
  </button>
  <button class="nav-item" onclick="switchTab('weight',this)" id="nav-weight">
    <i class="fa-solid fa-weight-scale"></i>
    <span>Berat</span>
  </button>
  <button class="nav-item" onclick="switchTab('progress',this)" id="nav-progress">
    <i class="fa-solid fa-chart-line"></i>
    <span>Progress</span>
  </button>
</nav>

<script>
/* ============================================================
   DATA MANAGEMENT
   ============================================================ */
const STORAGE_KEY = 'fittrack_data_v1';
const PROFILE = {
  startWeight: 92,
  targetWeight: 80,
  height: 165,
  targetCalories: 1900,
  targetProtein: 165,
  targetWater: 2500,
  ifOpen: '11:00',
  ifClose: '19:00'
};

let data = loadData();

function loadData() {
  try {
    const raw = localStorage.getItem(STORAGE_KEY);
    if (!raw) return freshData();
    const parsed = JSON.parse(raw);
    // Auto-reset if new day
    const today = getDateStr();
    if (parsed.today && parsed.today.date !== today) {
      archiveToHistory(parsed);
      parsed.today = freshToday();
    }
    return parsed;
  } catch(e) {
    return freshData();
  }
}

function freshData() {
  return {
    today: freshToday(),
    history: {
      weights: [],
      foods: {},
      workouts: [],
      water: {},
      moods: {}
    }
  };
}

function freshToday() {
  return {
    date: getDateStr(),
    weight: null,
    foods: [],
    water: 0,
    mood: 3,
    workout: null
  };
}

function archiveToHistory(d) {
  const t = d.today;
  if (!t) return;
  // Archive foods
  d.history.foods[t.date] = t.foods || [];
  // Archive water
  if (t.water > 0) d.history.water[t.date] = t.water;
  // Archive mood
  if (t.mood) d.history.moods[t.date] = t.mood;
  // Archive weight
  if (t.weight) {
    d.history.weights = d.history.weights || [];
    // Avoid duplicates
    const exists = d.history.weights.find(w => w.date === t.date);
    if (!exists) d.history.weights.push({ date: t.date, weight: t.weight });
  }
}

function saveData() {
  localStorage.setItem(STORAGE_KEY, JSON.stringify(data));
}

function getDateStr(d) {
  const date = d || new Date();
  return date.toISOString().split('T')[0];
}

function formatDate(str) {
  const d = new Date(str + 'T00:00:00');
  return d.toLocaleDateString('id-ID', { day: 'numeric', month: 'short', year: 'numeric' });
}

/* ============================================================
   TAB SWITCHING
   ============================================================ */
function switchTab(tab, el) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
  document.getElementById('page-' + tab).classList.add('active');
  el.classList.add('active');
  // Re-render page-specific content
  if (tab === 'food') renderFoodList();
  if (tab === 'workout') { renderWorkoutList(); setDefaultWorkoutDate(); }
  if (tab === 'weight') { renderWeightList(); renderWeightChart(); setDefaultWeightDate(); }
  if (tab === 'progress') renderProgress();
}

/* ============================================================
   HEADER DATE
   ============================================================ */
function renderHeaderDate() {
  const now = new Date();
  const label = now.toLocaleDateString('id-ID', { weekday: 'long', day: 'numeric', month: 'long' });
  document.getElementById('header-date').textContent = label;
}

/* ============================================================
   IF TIMER
   ============================================================ */
let ifInterval;
const MOODS = {
  1: { emoji: '😫', label: 'Lemas Banget' },
  2: { emoji: '😕', label: 'Kurang Enak' },
  3: { emoji: '😐', label: 'Biasa Aja' },
  4: { emoji: '🙂', label: 'Lumayan Baik' },
  5: { emoji: '🤩', label: 'Semangat!' }
};

function getIFStatus() {
  const now = new Date();
  const [oh, om] = PROFILE.ifOpen.split(':').map(Number);
  const [ch, cm] = PROFILE.ifClose.split(':').map(Number);
  const nowMins = now.getHours() * 60 + now.getMinutes();
  const openMins = oh * 60 + om;
  const closeMins = ch * 60 + cm;
  return nowMins >= openMins && nowMins < closeMins ? 'eating' : 'fasting';
}

function getIFCountdown() {
  const now = new Date();
  const [oh, om] = PROFILE.ifOpen.split(':').map(Number);
  const [ch, cm] = PROFILE.ifClose.split(':').map(Number);
  const status = getIFStatus();
  let target = new Date(now);

  if (status === 'fasting') {
    target.setHours(oh, om, 0, 0);
    if (target <= now) target.setDate(target.getDate() + 1);
  } else {
    target.setHours(ch, cm, 0, 0);
    if (target <= now) target.setDate(target.getDate() + 1);
  }
  return (target - now) / 1000;
}

function fmtSeconds(s) {
  s = Math.max(0, Math.floor(s));
  const h = Math.floor(s / 3600);
  const m = Math.floor((s % 3600) / 60);
  const sec = s % 60;
  return `${String(h).padStart(2,'0')}:${String(m).padStart(2,'0')}:${String(sec).padStart(2,'0')}`;
}

function updateIFTimer() {
  const status = getIFStatus();
  const countdown = getIFCountdown();
  const badge = document.getElementById('if-badge');
  const badgeText = document.getElementById('if-badge-text');
  const timerEl = document.getElementById('if-timer');
  const subtitleEl = document.getElementById('if-subtitle');
  const openBtn = document.getElementById('btn-open-fast');
  const closeBtn = document.getElementById('btn-close-fast');

  timerEl.textContent = fmtSeconds(countdown);

  if (status === 'eating') {
    badge.className = 'if-status-badge eating';
    badge.innerHTML = '<span class="pulse-dot"></span><span id="if-badge-text">WINDOW MAKAN AKTIF</span>';
    const remaining = Math.floor(countdown / 60);
    const h = Math.floor(remaining / 60);
    const m = remaining % 60;
    subtitleEl.textContent = `Puasa lagi dalam ${h} jam ${m} menit`;
    openBtn.style.display = 'none';
    closeBtn.style.display = 'flex';
  } else {
    badge.className = 'if-status-badge fasting';
    badge.innerHTML = '<span class="pulse-dot"></span><span id="if-badge-text">SEDANG PUASA</span>';
    const remaining = Math.floor(countdown / 60);
    const h = Math.floor(remaining / 60);
    const m = remaining % 60;
    subtitleEl.textContent = `Buka puasa dalam ${h} jam ${m} menit`;
    openBtn.style.display = 'flex';
    closeBtn.style.display = 'none';
  }
}

function openFastingWindow() {
  toast('🌟 Selamat makan! Window makan 11:00–19:00 aktif.', 'success');
}

function closeFastingWindow() {
  toast('🌙 Puasa dimulai! Semangat ya!', 'info');
}

function startIFTimer() {
  updateIFTimer();
  ifInterval = setInterval(updateIFTimer, 1000);
}

/* ============================================================
   WATER TRACKER
   ============================================================ */
function changeWater(delta) {
  data.today.water = Math.max(0, (data.today.water || 0) + delta);
  saveData();
  renderTodayStats();
  toast(delta > 0 ? `💧 +${delta}ml ditambahkan!` : `💧 -${Math.abs(delta)}ml dikurangi`, 'info');
}

/* ============================================================
   MOOD
   ============================================================ */
function updateMood(val) {
  val = parseInt(val);
  data.today.mood = val;
  const m = MOODS[val];
  document.getElementById('mood-emoji').textContent = m.emoji;
  document.getElementById('mood-label').textContent = m.label;
  // Update slider gradient
  const pct = ((val - 1) / 4) * 100;
  document.getElementById('mood-slider').style.setProperty('--val', pct + '%');
  saveData();
}

/* ============================================================
   RENDER TODAY STATS
   ============================================================ */
function renderTodayStats() {
  const foods = data.today.foods || [];
  const totalCal = foods.reduce((s, f) => s + (parseFloat(f.cal) || 0), 0);
  const totalProt = foods.reduce((s, f) => s + (parseFloat(f.prot) || 0), 0);
  const water = data.today.water || 0;
  const weight = data.today.weight;

  // Stats
  document.getElementById('stat-weight').textContent = weight ? weight + ' kg' : '–';
  document.getElementById('stat-cal').textContent = Math.round(totalCal);
  document.getElementById('stat-prot').textContent = Math.round(totalProt);
  document.getElementById('stat-water-val').textContent = water;

  // Water display
  document.getElementById('water-display').textContent = water;

  // Progress bars
  const calPct = Math.min((totalCal / PROFILE.targetCalories) * 100, 100);
  const protPct = Math.min((totalProt / PROFILE.targetProtein) * 100, 100);
  const waterPct = Math.min((water / PROFILE.targetWater) * 100, 100);

  const pbCal = document.getElementById('pb-cal');
  pbCal.style.width = calPct + '%';
  pbCal.className = 'progress-fill ' + (totalCal > 2000 ? 'fill-over' : 'fill-purple');

  document.getElementById('pb-prot').style.width = protPct + '%';
  document.getElementById('pb-water').style.width = waterPct + '%';

  document.getElementById('pb-cal-val').textContent = Math.round(totalCal);
  document.getElementById('pb-prot-val').textContent = Math.round(totalProt);
  document.getElementById('pb-water-val').textContent = water;
}

/* ============================================================
   FOOD TRACKER
   ============================================================ */
function addFood() {
  const name = document.getElementById('food-name').value.trim();
  const cal = parseFloat(document.getElementById('food-cal').value) || 0;
  const prot = parseFloat(document.getElementById('food-prot').value) || 0;
  const time = document.getElementById('food-time').value || '12:00';

  if (!name) { toast('⚠️ Nama makanan tidak boleh kosong!', 'error'); return; }
  if (cal <= 0 && prot <= 0) { toast('⚠️ Masukkan kalori atau protein!', 'error'); return; }

  data.today.foods.push({ id: Date.now(), name, cal, prot, time });
  saveData();

  // Clear form
  document.getElementById('food-name').value = '';
  document.getElementById('food-cal').value = '';
  document.getElementById('food-prot').value = '';

  renderFoodList();
  renderTodayStats();
  toast('✅ ' + name + ' berhasil ditambahkan!', 'success');
}

function deleteFood(id) {
  data.today.foods = data.today.foods.filter(f => f.id !== id);
  saveData();
  renderFoodList();
  renderTodayStats();
  toast('🗑️ Makanan dihapus', 'info');
}

function renderFoodList() {
  const list = document.getElementById('food-list');
  const totalBar = document.getElementById('food-total-bar');
  const warning = document.getElementById('food-warning');
  const foods = data.today.foods || [];

  if (foods.length === 0) {
    list.innerHTML = `<div class="empty-state"><i class="fa-solid fa-utensils"></i><p>Belum ada makanan dicatat hari ini</p></div>`;
    totalBar.innerHTML = '';
    warning.innerHTML = '';
    return;
  }

  const totalCal = foods.reduce((s, f) => s + (parseFloat(f.cal) || 0), 0);
  const totalProt = foods.reduce((s, f) => s + (parseFloat(f.prot) || 0), 0);

  list.innerHTML = foods.slice().reverse().map(f => `
    <div class="food-item">
      <div class="food-info">
        <div class="food-name">${escHtml(f.name)}</div>
        <div class="food-meta">
          <span><i class="fa-solid fa-clock" style="font-size:10px"></i> ${f.time}</span>
          <span class="food-badge badge-cal">${Math.round(f.cal)} kcal</span>
          <span class="food-badge badge-prot">${Math.round(f.prot)}g protein</span>
        </div>
      </div>
      <button class="btn-delete" onclick="deleteFood(${f.id})"><i class="fa-solid fa-trash"></i></button>
    </div>
  `).join('');

  totalBar.innerHTML = `
    <div class="total-bar">
      <span style="font-size:13px;font-weight:600;color:var(--text-soft)">Total:</span>
      <span style="font-size:13px;font-weight:700">
        <span style="color:var(--primary-light)">${Math.round(totalCal)} kcal</span>
        &nbsp;·&nbsp;
        <span style="color:var(--secondary)">${Math.round(totalProt)}g protein</span>
      </span>
    </div>
  `;

  let warn = '';
  if (totalCal > 2000) warn += `<div class="warning-msg"><i class="fa-solid fa-triangle-exclamation"></i> Kalori melebihi target maksimum 2.000 kcal!</div>`;
  if (totalProt < 150 && foods.length > 0) warn += `<div class="warning-msg"><i class="fa-solid fa-triangle-exclamation"></i> Protein masih di bawah target 150g. Tambah sumber protein!</div>`;
  warning.innerHTML = warn;
}

/* ============================================================
   WORKOUT TRACKER
   ============================================================ */
const WORKOUT_BADGE = {
  fullbody: 'badge-fullbody',
  cardio: 'badge-cardio',
  lower: 'badge-lower',
  upper: 'badge-upper',
  hiit: 'badge-hiit',
  rest: 'badge-rest'
};

const WORKOUT_LABEL = {
  fullbody: '💪 Full Body',
  cardio: '🏃 Cardio',
  lower: '🦵 Lower Body',
  upper: '🤸 Upper Body',
  hiit: '⚡ HIIT',
  rest: '😴 Rest Day'
};

function setDefaultWorkoutDate() {
  const el = document.getElementById('workout-date');
  if (!el.value) el.value = getDateStr();
}

function addWorkout() {
  const type = document.getElementById('workout-type').value;
  const dur = parseInt(document.getElementById('workout-dur').value) || 0;
  const detail = document.getElementById('workout-detail').value.trim();
  const date = document.getElementById('workout-date').value || getDateStr();

  if (!detail && type !== 'rest') {
    toast('⚠️ Isi detail gerakan terlebih dahulu!', 'error');
    return;
  }

  const entry = { id: Date.now(), type, dur, detail, date };
  data.history.workouts = data.history.workouts || [];
  data.history.workouts.push(entry);
  saveData();

  document.getElementById('workout-detail').value = '';
  document.getElementById('workout-dur').value = '';

  renderWorkoutList();
  toast('✅ Latihan berhasil dicatat!', 'success');
}

function renderWorkoutList() {
  const list = document.getElementById('workout-list');
  const workouts = (data.history.workouts || []).slice().reverse().slice(0, 7);

  if (workouts.length === 0) {
    list.innerHTML = `<div class="empty-state"><i class="fa-solid fa-dumbbell"></i><p>Belum ada latihan dicatat</p></div>`;
    return;
  }

  list.innerHTML = workouts.map(w => `
    <div class="workout-item">
      <div class="workout-top">
        <span class="workout-badge ${WORKOUT_BADGE[w.type] || 'badge-rest'}">${WORKOUT_LABEL[w.type] || w.type}</span>
        <div style="display:flex;align-items:center;gap:8px">
          ${w.dur ? `<span style="font-size:11px;color:var(--text-muted)"><i class="fa-solid fa-stopwatch" style="font-size:10px"></i> ${w.dur} mnt</span>` : ''}
          <span style="font-size:11px;color:var(--text-muted)">${formatDate(w.date)}</span>
        </div>
      </div>
      ${w.detail ? `<div class="workout-detail">${escHtml(w.detail)}</div>` : ''}
    </div>
  `).join('');
}

/* ============================================================
   WEIGHT TRACKER
   ============================================================ */
let weightChartInst = null;

function setDefaultWeightDate() {
  const el = document.getElementById('weight-date');
  if (!el.value) el.value = getDateStr();
}

function saveWeight() {
  const val = parseFloat(document.getElementById('weight-input').value);
  const date = document.getElementById('weight-date').value || getDateStr();

  if (!val || val < 30 || val > 300) {
    toast('⚠️ Masukkan berat badan yang valid!', 'error');
    return;
  }

  // If today, update today's weight
  if (date === getDateStr()) data.today.weight = val;

  // Add to history (update if same date)
  data.history.weights = data.history.weights || [];
  const idx = data.history.weights.findIndex(w => w.date === date);
  if (idx >= 0) data.history.weights[idx].weight = val;
  else data.history.weights.push({ date, weight: val });

  // Sort
  data.history.weights.sort((a, b) => a.date.localeCompare(b.date));
  saveData();

  document.getElementById('weight-input').value = '';
  renderTodayStats();
  renderWeightList();
  renderWeightChart();
  toast('⚖️ Berat badan tersimpan: ' + val + ' kg', 'success');
}

function renderWeightList() {
  const list = document.getElementById('weight-list');
  const weights = (data.history.weights || []).slice().reverse();

  if (weights.length === 0) {
    list.innerHTML = `<div class="empty-state"><i class="fa-solid fa-weight-scale"></i><p>Belum ada data berat badan</p></div>`;
    return;
  }

  list.innerHTML = weights.map((w, i) => {
    const prev = weights[i + 1];
    let changeHtml = '';
    if (prev) {
      const diff = (w.weight - prev.weight).toFixed(1);
      if (diff < 0) changeHtml = `<span class="weight-change down"><i class="fa-solid fa-arrow-down"></i>${Math.abs(diff)} kg</span>`;
      else if (diff > 0) changeHtml = `<span class="weight-change up"><i class="fa-solid fa-arrow-up"></i>+${diff} kg</span>`;
      else changeHtml = `<span class="weight-change same">–</span>`;
    }
    return `
      <div class="weight-item">
        <div>
          <div class="weight-val">${w.weight} kg</div>
          <div class="weight-date">${formatDate(w.date)}</div>
        </div>
        ${changeHtml}
      </div>
    `;
  }).join('');
}

function renderWeightChart() {
  const weights = data.history.weights || [];
  const wrap = document.getElementById('weight-chart-wrap');
  const msg = document.getElementById('weight-chart-msg');

  if (weights.length < 2) {
    wrap.style.display = 'none';
    msg.style.display = 'block';
    return;
  }

  wrap.style.display = 'block';
  msg.style.display = 'none';

  const labels = weights.map(w => {
    const d = new Date(w.date + 'T00:00:00');
    return d.toLocaleDateString('id-ID', { day: 'numeric', month: 'short' });
  });
  const vals = weights.map(w => w.weight);

  if (weightChartInst) weightChartInst.destroy();

  const ctx = document.getElementById('weight-chart').getContext('2d');
  const gradient = ctx.createLinearGradient(0, 0, 0, 180);
  gradient.addColorStop(0, 'rgba(99,102,241,0.3)');
  gradient.addColorStop(1, 'rgba(99,102,241,0.0)');

  weightChartInst = new Chart(ctx, {
    type: 'line',
    data: {
      labels,
      datasets: [{
        label: 'Berat (kg)',
        data: vals,
        borderColor: '#818cf8',
        backgroundColor: gradient,
        fill: true,
        tension: 0.4,
        pointBackgroundColor: '#818cf8',
        pointBorderColor: '#fff',
        pointBorderWidth: 2,
        pointRadius: 5,
        pointHoverRadius: 8
      }, {
        label: 'Target',
        data: Array(labels.length).fill(PROFILE.targetWeight),
        borderColor: 'rgba(16,185,129,0.5)',
        borderDash: [6, 4],
        pointRadius: 0,
        fill: false,
        tension: 0
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: { display: false },
        tooltip: {
          backgroundColor: '#1e293b',
          borderColor: 'rgba(99,102,241,0.3)',
          borderWidth: 1,
          titleColor: '#94a3b8',
          bodyColor: '#f1f5f9',
          callbacks: {
            label: ctx => ctx.dataset.label === 'Target' ? 'Target: ' + ctx.parsed.y + ' kg' : ctx.parsed.y + ' kg'
          }
        }
      },
      scales: {
        x: {
          grid: { color: 'rgba(255,255,255,0.04)' },
          ticks: { color: '#64748b', font: { size: 10 } }
        },
        y: {
          grid: { color: 'rgba(255,255,255,0.04)' },
          ticks: { color: '#64748b', font: { size: 10 }, callback: v => v + ' kg' }
        }
      }
    }
  });
}

/* ============================================================
   PROGRESS PAGE
   ============================================================ */
let calChartInst = null;
let protChartInst = null;

function renderProgress() {
  // Overall weight progress
  const weights = data.history.weights || [];
  const latest = weights.length > 0 ? weights[weights.length - 1].weight : null;
  const startW = PROFILE.startWeight;
  const targetW = PROFILE.targetWeight;
  const totalToLose = startW - targetW; // 12kg

  const pctEl = document.getElementById('prog-pct');
  const subEl = document.getElementById('prog-sub');
  const barEl = document.getElementById('prog-bar');

  document.getElementById('prog-start').textContent = startW + ' kg';
  document.getElementById('prog-current').textContent = latest ? latest + ' kg' : '– kg';

  if (latest) {
    const lost = Math.max(0, startW - latest);
    const left = Math.max(0, latest - targetW);
    const pct = Math.min(Math.round((lost / totalToLose) * 100), 100);

    document.getElementById('prog-lost').textContent = lost.toFixed(1) + ' kg';
    document.getElementById('prog-left').textContent = left.toFixed(1) + ' kg';
    pctEl.textContent = pct + '%';
    barEl.style.width = pct + '%';

    if (pct >= 100) subEl.textContent = '🎉 Target tercapai! Luar biasa!';
    else if (pct >= 50) subEl.textContent = 'Hebat! Sudah lebih dari setengah jalan!';
    else if (pct > 0) subEl.textContent = `Sudah turun ${lost.toFixed(1)} kg — terus semangat!`;
    else subEl.textContent = 'Ayo mulai! Setiap gram yang turun adalah kemenangan!';
  } else {
    document.getElementById('prog-lost').textContent = '0 kg';
    document.getElementById('prog-left').textContent = totalToLose + ' kg';
    pctEl.textContent = '0%';
    barEl.style.width = '0%';
    subEl.textContent = 'Catat berat badan untuk mulai tracking progress!';
  }

  // Charts: 7 hari kalori & protein
  render7DayCalChart();
  render7DayProtChart();
}

function getLast7Days() {
  const days = [];
  for (let i = 6; i >= 0; i--) {
    const d = new Date();
    d.setDate(d.getDate() - i);
    days.push(getDateStr(d));
  }
  return days;
}

function render7DayCalChart() {
  const days = getLast7Days();
  const histFoods = data.history.foods || {};
  const todayFoods = data.today.foods || [];
  const todayStr = getDateStr();

  const vals = days.map(day => {
    const foods = day === todayStr ? todayFoods : (histFoods[day] || []);
    return Math.round(foods.reduce((s, f) => s + (parseFloat(f.cal) || 0), 0));
  });

  const hasData = vals.some(v => v > 0);
  const wrap = document.getElementById('cal-chart-wrap');
  const msg = document.getElementById('cal-chart-msg');

  if (!hasData) {
    wrap.style.display = 'none';
    msg.style.display = 'block';
    return;
  }

  wrap.style.display = 'block';
  msg.style.display = 'none';

  const labels = days.map(d => {
    const dt = new Date(d + 'T00:00:00');
    return dt.toLocaleDateString('id-ID', { day: 'numeric', month: 'short' });
  });

  const colors = vals.map(v => v > 2000 ? '#ef4444' : '#6366f1');
  const borders = vals.map(v => v > 2000 ? '#f87171' : '#818cf8');

  if (calChartInst) calChartInst.destroy();
  const ctx = document.getElementById('cal-chart').getContext('2d');
  calChartInst = new Chart(ctx, {
    type: 'bar',
    data: {
      labels,
      datasets: [{
        data: vals,
        backgroundColor: colors,
        borderColor: borders,
        borderWidth: 1,
        borderRadius: 8,
        borderSkipped: false
      }, {
        type: 'line',
        data: Array(7).fill(PROFILE.targetCalories),
        borderColor: 'rgba(16,185,129,0.5)',
        borderDash: [6, 4],
        pointRadius: 0,
        fill: false
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: { legend: { display: false }, tooltip: {
        backgroundColor: '#1e293b',
        borderColor: 'rgba(99,102,241,0.3)',
        borderWidth: 1,
        titleColor: '#94a3b8',
        bodyColor: '#f1f5f9',
        callbacks: { label: ctx => ctx.parsed.y + ' kcal' }
      }},
      scales: {
        x: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#64748b', font: { size: 10 } } },
        y: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#64748b', font: { size: 10 }, callback: v => v + ' kcal' } }
      }
    }
  });
}

function render7DayProtChart() {
  const days = getLast7Days();
  const histFoods = data.history.foods || {};
  const todayFoods = data.today.foods || [];
  const todayStr = getDateStr();

  const vals = days.map(day => {
    const foods = day === todayStr ? todayFoods : (histFoods[day] || []);
    return Math.round(foods.reduce((s, f) => s + (parseFloat(f.prot) || 0), 0));
  });

  const hasData = vals.some(v => v > 0);
  const wrap = document.getElementById('prot-chart-wrap');
  const msg = document.getElementById('prot-chart-msg');

  if (!hasData) {
    wrap.style.display = 'none';
    msg.style.display = 'block';
    return;
  }

  wrap.style.display = 'block';
  msg.style.display = 'none';

  const labels = days.map(d => {
    const dt = new Date(d + 'T00:00:00');
    return dt.toLocaleDateString('id-ID', { day: 'numeric', month: 'short' });
  });

  const colors = vals.map(v => v >= 150 ? '#10b981' : '#f59e0b');

  if (protChartInst) protChartInst.destroy();
  const ctx = document.getElementById('prot-chart').getContext('2d');
  protChartInst = new Chart(ctx, {
    type: 'bar',
    data: {
      labels,
      datasets: [{
        data: vals,
        backgroundColor: colors,
        borderRadius: 8,
        borderSkipped: false
      }, {
        type: 'line',
        data: Array(7).fill(150),
        borderColor: 'rgba(16,185,129,0.5)',
        borderDash: [6, 4],
        pointRadius: 0,
        fill: false
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: { legend: { display: false }, tooltip: {
        backgroundColor: '#1e293b',
        borderColor: 'rgba(16,185,129,0.3)',
        borderWidth: 1,
        titleColor: '#94a3b8',
        bodyColor: '#f1f5f9',
        callbacks: { label: ctx => ctx.parsed.y + 'g protein' }
      }},
      scales: {
        x: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#64748b', font: { size: 10 } } },
        y: { grid: { color: 'rgba(255,255,255,0.04)' }, ticks: { color: '#64748b', font: { size: 10 }, callback: v => v + 'g' } }
      }
    }
  });
}

/* ============================================================
   EXPORT & BACKUP
   ============================================================ */
function exportCSV() {
  const rows = [['Tanggal', 'Nama Makanan', 'Kalori (kcal)', 'Protein (g)', 'Air (ml)', 'Berat (kg)']];
  const todayStr = getDateStr();
  const histFoods = data.history.foods || {};
  const histWater = data.history.water || {};
  const weights = {};
  (data.history.weights || []).forEach(w => weights[w.date] = w.weight);

  const allDates = new Set([...Object.keys(histFoods), todayStr]);
  allDates.forEach(date => {
    const foods = date === todayStr ? (data.today.foods || []) : (histFoods[date] || []);
    const water = date === todayStr ? data.today.water : (histWater[date] || '');
    const weight = date === todayStr ? (data.today.weight || '') : (weights[date] || '');
    if (foods.length === 0) {
      rows.push([date, '', '', '', water, weight]);
    } else {
      foods.forEach((f, i) => {
        rows.push([date, f.name, f.cal, f.prot, i === 0 ? water : '', i === 0 ? weight : '']);
      });
    }
  });

  const csv = rows.map(r => r.map(c => `"${c}"`).join(',')).join('\n');
  const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a');
  a.href = url;
  a.download = `fittrack_export_${getDateStr()}.csv`;
  a.click();
  URL.revokeObjectURL(url);
  toast('📊 Data berhasil diekspor ke CSV!', 'success');
}

function backupData() {
  const json = JSON.stringify(data, null, 2);
  navigator.clipboard.writeText(json).then(() => {
    toast('📋 Backup JSON berhasil disalin ke clipboard!', 'success');
  }).catch(() => {
    // Fallback
    const el = document.getElementById('restore-input');
    const area = document.getElementById('restore-area');
    area.style.display = 'block';
    el.value = json;
    toast('📋 JSON tersedia di kotak teks di bawah!', 'info');
  });
}

function showRestore() {
  const area = document.getElementById('restore-area');
  area.style.display = area.style.display === 'none' ? 'block' : 'none';
}

function restoreData() {
  try {
    const input = document.getElementById('restore-input').value.trim();
    if (!input) { toast('⚠️ Paste JSON backup terlebih dahulu!', 'error'); return; }
    const parsed = JSON.parse(input);
    data = parsed;
    saveData();
    renderTodayStats();
    renderFoodList();
    toast('✅ Data berhasil di-restore!', 'success');
    document.getElementById('restore-area').style.display = 'none';
    document.getElementById('restore-input').value = '';
  } catch(e) {
    toast('❌ Format JSON tidak valid!', 'error');
  }
}

/* ============================================================
   TOAST NOTIFICATIONS
   ============================================================ */
function toast(msg, type = 'info') {
  const icons = { success: 'fa-circle-check', error: 'fa-circle-exclamation', info: 'fa-circle-info' };
  const container = document.getElementById('toast-container');
  const el = document.createElement('div');
  el.className = `toast ${type}`;
  el.innerHTML = `<i class="fa-solid ${icons[type]} toast-icon"></i><span>${msg}</span>`;
  container.appendChild(el);
  setTimeout(() => {
    el.classList.add('removing');
    setTimeout(() => el.remove(), 400);
  }, 2800);
}

/* ============================================================
   UTILS
   ============================================================ */
function escHtml(str) {
  return String(str).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;');
}

/* ============================================================
   INIT
   ============================================================ */
function init() {
  renderHeaderDate();

  // Init mood slider
  const mood = data.today.mood || 3;
  const slider = document.getElementById('mood-slider');
  slider.value = mood;
  updateMood(mood);

  renderTodayStats();
  renderFoodList();

  startIFTimer();

  // Pre-populate today's weight in stat if available
  const todayWeight = data.today.weight;
  if (!todayWeight) {
    // Try to get latest from history
    const wts = data.history.weights || [];
    if (wts.length > 0) {
      document.getElementById('stat-weight').textContent = wts[wts.length - 1].weight + ' kg';
    }
  }
}

document.addEventListener('DOMContentLoaded', init);
</script>
</body>
</html>
