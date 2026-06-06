<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover"/>
<meta name="mobile-web-app-capable" content="yes"/>
<meta name="apple-mobile-web-app-capable" content="yes"/>
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent"/>
<title>BarberOS</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Mono:wght@400;500&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet"/>
<style>*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

:root {
  --bg: #0f0e0d;
  --bg2: #161513;
  --bg3: #1e1c1a;
  --border: #2a2826;
  --accent: #c8a96e;
  --accent2: #e8c98e;
  --text: #e8e4de;
  --text2: #9a9590;
  --text3: #5a5550;
  --danger: #c05050;
  --success: #5a9a6a;
  --info: #5a80b0;
  --font-display: 'Bebas Neue', sans-serif;
  --font-mono: 'DM Mono', monospace;
  --font-body: 'DM Sans', sans-serif;
  --bottom-nav-h: 64px;
}

html { height: 100%; }

body {
  background: var(--bg);
  color: var(--text);
  font-family: var(--font-body);
  display: flex;
  min-height: 100vh;
  overflow-x: hidden;
}

.noise {
  position: fixed; inset: 0;
  pointer-events: none; z-index: 999; opacity: 0.03;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)'/%3E%3C/svg%3E");
}

/* ─── SIDEBAR (desktop) ─────────────────────────── */
.sidebar {
  width: 240px; min-height: 100vh;
  background: var(--bg2);
  border-right: 1px solid var(--border);
  display: flex; flex-direction: column;
  position: fixed; top: 0; left: 0; bottom: 0;
  z-index: 10;
}

.brand {
  display: flex; align-items: center; gap: 12px;
  padding: 28px 20px 24px;
  border-bottom: 1px solid var(--border);
}
.brand-icon { font-size: 22px; color: var(--accent); line-height: 1; }
.brand-name { font-family: var(--font-display); font-size: 22px; letter-spacing: 2px; color: var(--accent); line-height: 1; }
.brand-sub  { font-size: 10px; color: var(--text3); font-family: var(--font-mono); letter-spacing: 1px; margin-top: 2px; }

.nav {
  padding: 16px 12px;
  display: flex; flex-direction: column; gap: 4px;
  flex: 1;
}

.nav-item {
  width: 100%; background: none; border: none;
  color: var(--text2); font-family: var(--font-mono);
  font-size: 12px; letter-spacing: 1px;
  padding: 10px 12px; text-align: left; cursor: pointer;
  border-radius: 4px; display: flex; align-items: center;
  gap: 10px; transition: all 0.15s;
}
.nav-item:hover  { background: var(--bg3); color: var(--text); }
.nav-item.active { background: var(--accent); color: #0f0e0d; font-weight: 500; }
.nav-icon { font-size: 14px; }

.sidebar-footer {
  padding: 16px;
  border-top: 1px solid var(--border);
}
.barber-status-label {
  font-size: 10px; color: var(--text3);
  font-family: var(--font-mono); letter-spacing: 1px;
  margin-bottom: 10px; text-transform: uppercase;
}
.barber-pill {
  display: flex; align-items: center; gap: 8px;
  padding: 6px 0; font-size: 12px;
  color: var(--text2); font-family: var(--font-mono);
}
.status-dot { width: 7px; height: 7px; border-radius: 50%; flex-shrink: 0; }
.dot-available { background: var(--success); box-shadow: 0 0 6px var(--success); }
.dot-busy      { background: var(--accent);  box-shadow: 0 0 6px var(--accent); }
.dot-off-duty  { background: var(--text3); }

/* ─── BOTTOM NAV (mobile only) ──────────────────── */
.bottom-nav {
  display: none;
  position: fixed; bottom: 0; left: 0; right: 0;
  height: var(--bottom-nav-h);
  background: var(--bg2);
  border-top: 1px solid var(--border);
  z-index: 50;
  padding: 0 4px;
  padding-bottom: env(safe-area-inset-bottom);
}
.bottom-nav-inner {
  display: flex; height: 100%;
  align-items: center; justify-content: space-around;
}
.bnav-item {
  flex: 1; display: flex; flex-direction: column;
  align-items: center; justify-content: center;
  gap: 3px; background: none; border: none;
  color: var(--text3); cursor: pointer;
  padding: 6px 4px; border-radius: 8px;
  transition: color 0.15s;
  -webkit-tap-highlight-color: transparent;
}
.bnav-item.active { color: var(--accent); }
.bnav-icon { font-size: 20px; line-height: 1; }
.bnav-label { font-family: var(--font-mono); font-size: 9px; letter-spacing: 0.5px; text-transform: uppercase; }

/* ─── MOBILE HEADER ─────────────────────────────── */
.mobile-header {
  display: none;
  position: fixed; top: 0; left: 0; right: 0;
  height: 52px;
  background: var(--bg2);
  border-bottom: 1px solid var(--border);
  z-index: 40;
  align-items: center;
  padding: 0 16px;
  gap: 10px;
}
.mobile-header .brand-icon { font-size: 18px; }
.mobile-header .brand-name { font-size: 18px; }

/* ─── MAIN ──────────────────────────────────────── */
.main {
  margin-left: 240px;
  flex: 1; padding: 32px;
  min-height: 100vh;
}

.page { display: none; animation: fadeIn 0.2s ease; }
.page.active { display: block; }

@keyframes fadeIn { from { opacity: 0; transform: translateY(6px); } to { opacity: 1; transform: none; } }

.page-header {
  display: flex; align-items: center;
  justify-content: space-between;
  margin-bottom: 28px;
  flex-wrap: wrap; gap: 12px;
}
.page-header h1 {
  font-family: var(--font-display); font-size: 42px;
  letter-spacing: 3px; color: var(--text); line-height: 1;
}
.date-badge {
  font-family: var(--font-mono); font-size: 12px;
  color: var(--text3); background: var(--bg3);
  border: 1px solid var(--border);
  padding: 6px 12px; border-radius: 4px;
}

/* ─── STATS ─────────────────────────────────────── */
.stats-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 16px; margin-bottom: 24px;
}
.stat-card {
  background: var(--bg2); border: 1px solid var(--border);
  border-radius: 6px; padding: 20px;
  transition: border-color 0.2s;
}
.stat-card:hover { border-color: var(--text3); }
.stat-card.accent { border-color: var(--accent); background: #1a1712; }
.stat-label {
  font-family: var(--font-mono); font-size: 11px;
  color: var(--text3); letter-spacing: 1px;
  text-transform: uppercase; margin-bottom: 8px;
}
.stat-value {
  font-family: var(--font-display); font-size: 36px;
  letter-spacing: 2px; color: var(--text); line-height: 1;
}
.stat-card.accent .stat-value { color: var(--accent); }

.two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }

/* ─── PANEL ─────────────────────────────────────── */
.panel {
  background: var(--bg2); border: 1px solid var(--border);
  border-radius: 6px; overflow: hidden; margin-bottom: 16px;
}
.panel-header {
  font-family: var(--font-mono); font-size: 11px;
  letter-spacing: 2px; text-transform: uppercase;
  color: var(--text3); padding: 14px 20px;
  border-bottom: 1px solid var(--border); background: var(--bg3);
}

/* ─── TABLE ─────────────────────────────────────── */
.table-wrap { overflow-x: auto; -webkit-overflow-scrolling: touch; }
.data-table { width: 100%; border-collapse: collapse; font-size: 13px; min-width: 520px; }
.data-table th {
  font-family: var(--font-mono); font-size: 10px;
  letter-spacing: 1px; text-transform: uppercase;
  color: var(--text3); padding: 12px 16px; text-align: left;
  background: var(--bg3); border-bottom: 1px solid var(--border);
  white-space: nowrap;
}
.data-table td {
  padding: 12px 16px; border-bottom: 1px solid var(--border);
  color: var(--text2); vertical-align: middle;
}
.data-table tr:last-child td { border-bottom: none; }
.data-table tr:hover td { background: var(--bg3); }

/* ─── MOBILE CARDS (replaces table on small screens) */
.card-list { display: none; }
.m-card {
  background: var(--bg2); border: 1px solid var(--border);
  border-radius: 8px; padding: 14px 16px;
  margin-bottom: 10px;
}
.m-card-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 6px; }
.m-card-name { color: var(--text); font-weight: 500; font-size: 14px; }
.m-card-sub  { color: var(--text3); font-size: 11px; font-family: var(--font-mono); margin-top: 3px; }
.m-card-actions { display: flex; gap: 8px; margin-top: 10px; flex-wrap: wrap; }

/* ─── DASH ITEMS ────────────────────────────────── */
.dash-item {
  padding: 12px 20px; border-bottom: 1px solid var(--border);
  display: flex; justify-content: space-between; align-items: center;
  font-size: 13px;
}
.dash-item:last-child { border-bottom: none; }
.dash-name { color: var(--text); font-weight: 500; }
.dash-sub  { color: var(--text3); font-size: 11px; font-family: var(--font-mono); margin-top: 2px; }
.dash-right { text-align: right; }

/* ─── BADGES ────────────────────────────────────── */
.badge {
  display: inline-block; font-family: var(--font-mono);
  font-size: 10px; letter-spacing: 0.5px;
  padding: 3px 8px; border-radius: 3px; text-transform: uppercase;
}
.badge-pending     { background: #2a2416; color: var(--accent);  border: 1px solid #3a3020; }
.badge-confirmed   { background: #162a1e; color: var(--success); border: 1px solid #203a28; }
.badge-completed   { background: #161e2a; color: var(--info);    border: 1px solid #202838; }
.badge-cancelled   { background: #2a1616; color: var(--danger);  border: 1px solid #3a2020; }
.badge-waiting     { background: #2a2416; color: var(--accent);  border: 1px solid #3a3020; }
.badge-in-progress { background: #1e1a2a; color: #9a80d0;        border: 1px solid #2a2038; }
.badge-cash        { background: #162a1e; color: var(--success); border: 1px solid #203a28; }
.badge-gcash       { background: #161e2a; color: var(--info);    border: 1px solid #202838; }
.badge-card        { background: #2a1e2a; color: #c080d0;        border: 1px solid #382038; }

/* ─── BUTTONS ───────────────────────────────────── */
.btn-primary {
  background: var(--accent); color: #0f0e0d; border: none;
  font-family: var(--font-mono); font-size: 12px; font-weight: 500;
  letter-spacing: 1px; padding: 10px 18px; border-radius: 4px;
  cursor: pointer; transition: background 0.15s;
  -webkit-tap-highlight-color: transparent;
  touch-action: manipulation;
}
.btn-primary:hover, .btn-primary:active { background: var(--accent2); }
.btn-primary.full { width: 100%; padding: 14px; margin-top: 8px; font-size: 13px; }

.btn-sm {
  font-family: var(--font-mono); font-size: 10px;
  letter-spacing: 0.5px; padding: 5px 12px; border-radius: 3px;
  cursor: pointer; border: 1px solid var(--border);
  background: var(--bg3); color: var(--text2);
  transition: all 0.15s; margin-right: 4px;
  -webkit-tap-highlight-color: transparent;
  touch-action: manipulation;
}
.btn-sm:hover, .btn-sm:active { border-color: var(--accent); color: var(--accent); }
.btn-sm.danger:hover, .btn-sm.danger:active { border-color: var(--danger); color: var(--danger); }

/* ─── MODAL ─────────────────────────────────────── */
.modal-overlay {
  display: none; position: fixed; inset: 0;
  background: rgba(0,0,0,0.75); z-index: 100;
  align-items: flex-end; justify-content: center;
  backdrop-filter: blur(4px);
}
.modal-overlay.open { display: flex; }

.modal {
  background: var(--bg2); border: 1px solid var(--border);
  border-radius: 12px 12px 0 0;
  width: 100%; max-width: 480px;
  padding: 24px; padding-bottom: calc(24px + env(safe-area-inset-bottom));
  animation: slideUp 0.25s ease;
  max-height: 92vh; overflow-y: auto;
}

@keyframes slideUp {
  from { transform: translateY(40px); opacity: 0; }
  to   { transform: none; opacity: 1; }
}

.modal-header {
  display: flex; justify-content: space-between; align-items: center;
  margin-bottom: 20px;
  font-family: var(--font-display); font-size: 22px;
  letter-spacing: 2px; color: var(--accent);
}
.modal-close {
  background: none; border: none; color: var(--text3);
  cursor: pointer; font-size: 20px; padding: 4px;
  transition: color 0.15s; line-height: 1;
}
.modal-close:hover { color: var(--text); }

.form-group { margin-bottom: 16px; }
.form-group label {
  display: block; font-family: var(--font-mono);
  font-size: 11px; letter-spacing: 1px; color: var(--text3);
  text-transform: uppercase; margin-bottom: 6px;
}
.form-group input,
.form-group select {
  width: 100%; background: var(--bg3);
  border: 1px solid var(--border); color: var(--text);
  font-family: var(--font-body); font-size: 16px;
  padding: 12px 14px; border-radius: 6px; outline: none;
  transition: border-color 0.15s;
  -webkit-appearance: none;
}
.form-group input:focus,
.form-group select:focus { border-color: var(--accent); }
.form-group select option { background: var(--bg3); }

.pay-summary {
  background: var(--bg3); border: 1px solid var(--border);
  border-radius: 6px; padding: 14px; margin-bottom: 16px;
  font-family: var(--font-mono); font-size: 13px;
  color: var(--text2); line-height: 2; white-space: pre-line;
}

/* ─── TOAST ─────────────────────────────────────── */
.toast {
  position: fixed; bottom: calc(var(--bottom-nav-h) + 12px); right: 16px;
  background: var(--bg3); border: 1px solid var(--accent);
  color: var(--text); font-family: var(--font-mono); font-size: 12px;
  padding: 12px 18px; border-radius: 6px; z-index: 200;
  transform: translateY(80px); opacity: 0;
  transition: all 0.25s ease; pointer-events: none;
  max-width: calc(100vw - 32px);
}
.toast.show { transform: none; opacity: 1; }

/* ─── EMPTY ─────────────────────────────────────── */
.empty {
  padding: 32px; text-align: center;
  color: var(--text3); font-family: var(--font-mono);
  font-size: 12px; letter-spacing: 1px;
}

/* ─── MOBILE BREAKPOINT ─────────────────────────── */
@media (max-width: 768px) {
  .sidebar      { display: none; }
  .bottom-nav   { display: block; }
  .mobile-header { display: flex; }

  .main {
    margin-left: 0;
    padding: 16px;
    padding-top: calc(52px + 16px);
    padding-bottom: calc(var(--bottom-nav-h) + 16px);
  }

  .page-header h1 { font-size: 30px; letter-spacing: 2px; }
  .date-badge { display: none; }

  .stats-grid { grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 16px; }
  .stat-card { padding: 14px; }
  .stat-value { font-size: 28px; }
  .stat-label { font-size: 10px; }

  .two-col { grid-template-columns: 1fr; gap: 12px; }

  /* Hide tables, show cards on mobile */
  .panel .table-wrap { display: none; }
  .card-list { display: block; padding: 12px; }

  .modal { border-radius: 16px 16px 0 0; }

  .toast { bottom: calc(var(--bottom-nav-h) + env(safe-area-inset-bottom) + 12px); }
}

@media (min-width: 769px) {
  /* Ensure table wrap is visible on desktop */
  .panel .table-wrap { display: block; }
  .card-list { display: none !important; }
  .modal {
    border-radius: 12px;
    align-self: center;
  }
  .modal-overlay { align-items: center; }
}
</style>
</head>
<body>
<div class="noise"></div>

<!-- MOBILE HEADER -->
<header class="mobile-header">
  <span class="brand-icon">✦</span>
  <span class="brand-name">BarberOS</span>
</header>

<!-- SIDEBAR (desktop) -->
<aside class="sidebar">
  <div class="brand">
    <span class="brand-icon">✦</span>
    <div>
      <div class="brand-name">BarberOS</div>
      <div class="brand-sub">Management System</div>
    </div>
  </div>
  <nav class="nav">
    <button class="nav-item active" onclick="showPage('dashboard')"><span class="nav-icon">▣</span> Dashboard</button>
    <button class="nav-item" onclick="showPage('appointments')"><span class="nav-icon">◈</span> Appointments</button>
    <button class="nav-item" onclick="showPage('walkins')"><span class="nav-icon">◉</span> Walk-ins</button>
    <button class="nav-item" onclick="showPage('customers')"><span class="nav-icon">◎</span> Customers</button>
    <button class="nav-item" onclick="showPage('payments')"><span class="nav-icon">◆</span> Payments</button>
  </nav>
  <div class="sidebar-footer">
    <div class="barber-status-label">Barber Status</div>
    <div id="barber-status-list"></div>
  </div>
</aside>

<!-- BOTTOM NAV (mobile) -->
<nav class="bottom-nav">
  <div class="bottom-nav-inner">
    <button class="bnav-item active" onclick="showPage('dashboard')">
      <span class="bnav-icon">▣</span><span class="bnav-label">Home</span>
    </button>
    <button class="bnav-item" onclick="showPage('appointments')">
      <span class="bnav-icon">◈</span><span class="bnav-label">Appts</span>
    </button>
    <button class="bnav-item" onclick="showPage('walkins')">
      <span class="bnav-icon">◉</span><span class="bnav-label">Queue</span>
    </button>
    <button class="bnav-item" onclick="showPage('customers')">
      <span class="bnav-icon">◎</span><span class="bnav-label">Clients</span>
    </button>
    <button class="bnav-item" onclick="showPage('payments')">
      <span class="bnav-icon">◆</span><span class="bnav-label">Payments</span>
    </button>
  </div>
</nav>

<main class="main">

  <!-- DASHBOARD -->
  <div id="page-dashboard" class="page active">
    <div class="page-header">
      <h1>Dashboard</h1>
      <div class="date-badge" id="today-date"></div>
    </div>
    <div class="stats-grid">
      <div class="stat-card accent"><div class="stat-label">Revenue</div><div class="stat-value" id="stat-revenue">₱0</div></div>
      <div class="stat-card"><div class="stat-label">Appointments</div><div class="stat-value" id="stat-appointments">0</div></div>
      <div class="stat-card"><div class="stat-label">Walk-ins</div><div class="stat-value" id="stat-walkins">0</div></div>
      <div class="stat-card"><div class="stat-label">Queue</div><div class="stat-value" id="stat-queue">0</div></div>
    </div>
    <div class="two-col">
      <div class="panel"><div class="panel-header">Upcoming Appointments</div><div id="dash-appointments"></div></div>
      <div class="panel"><div class="panel-header">Live Queue</div><div id="dash-queue"></div></div>
    </div>
    <!-- Mobile barber status -->
    <div class="panel" id="mobile-barber-panel">
      <div class="panel-header">Barber Status</div>
      <div id="mobile-barber-list" style="padding:12px 16px"></div>
    </div>
  </div>

  <!-- APPOINTMENTS -->
  <div id="page-appointments" class="page">
    <div class="page-header">
      <h1>Appointments</h1>
      <button class="btn-primary" onclick="openModal('modal-book')">+ Book</button>
    </div>
    <div class="panel">
      <div class="table-wrap">
        <table class="data-table">
          <thead><tr><th>#</th><th>Customer</th><th>Barber</th><th>Service</th><th>Schedule</th><th>Status</th><th>Action</th></tr></thead>
          <tbody id="appt-table"></tbody>
        </table>
      </div>
      <div class="card-list" id="appt-cards"></div>
    </div>
  </div>

  <!-- WALK-INS -->
  <div id="page-walkins" class="page">
    <div class="page-header">
      <h1>Walk-in Queue</h1>
      <button class="btn-primary" onclick="openModal('modal-walkin')">+ Register</button>
    </div>
    <div class="panel">
      <div class="table-wrap">
        <table class="data-table">
          <thead><tr><th>Q#</th><th>Customer</th><th>Barber</th><th>Service</th><th>Arrived</th><th>Status</th><th>Action</th></tr></thead>
          <tbody id="walkin-table"></tbody>
        </table>
      </div>
      <div class="card-list" id="walkin-cards"></div>
    </div>
  </div>

  <!-- CUSTOMERS -->
  <div id="page-customers" class="page">
    <div class="page-header">
      <h1>Customers</h1>
      <button class="btn-primary" onclick="openModal('modal-customer')">+ Add</button>
    </div>
    <div class="panel">
      <div class="table-wrap">
        <table class="data-table">
          <thead><tr><th>ID</th><th>Name</th><th>Phone</th><th>Email</th><th>Since</th><th>Action</th></tr></thead>
          <tbody id="customer-table"></tbody>
        </table>
      </div>
      <div class="card-list" id="customer-cards"></div>
    </div>
  </div>

  <!-- PAYMENTS -->
  <div id="page-payments" class="page">
    <div class="page-header"><h1>Payments</h1></div>
    <div class="panel">
      <div class="table-wrap">
        <table class="data-table">
          <thead><tr><th>ID</th><th>Type</th><th>Source</th><th>Amount</th><th>Method</th><th>Date</th></tr></thead>
          <tbody id="payment-table"></tbody>
        </table>
      </div>
      <div class="card-list" id="payment-cards"></div>
    </div>
  </div>
</main>

<!-- MODAL: Book Appointment -->
<div class="modal-overlay" id="modal-book">
  <div class="modal">
    <div class="modal-header"><span>Book Appointment</span><button class="modal-close" onclick="closeModal('modal-book')">✕</button></div>
    <div class="form-group"><label>Customer</label><select id="book-customer"></select></div>
    <div class="form-group"><label>Barber</label><select id="book-barber"></select></div>
    <div class="form-group"><label>Service</label><select id="book-service"></select></div>
    <div class="form-group"><label>Schedule</label><input type="datetime-local" id="book-datetime"/></div>
    <button class="btn-primary full" onclick="bookAppointment()">Confirm Booking</button>
  </div>
</div>

<!-- MODAL: Register Walk-in -->
<div class="modal-overlay" id="modal-walkin">
  <div class="modal">
    <div class="modal-header"><span>Register Walk-in</span><button class="modal-close" onclick="closeModal('modal-walkin')">✕</button></div>
    <div class="form-group"><label>Customer</label><select id="wi-customer"></select></div>
    <div class="form-group"><label>Barber</label><select id="wi-barber"></select></div>
    <div class="form-group"><label>Service</label><select id="wi-service"></select></div>
    <button class="btn-primary full" onclick="registerWalkIn()">Register & Get Queue #</button>
  </div>
</div>

<!-- MODAL: Add Customer -->
<div class="modal-overlay" id="modal-customer">
  <div class="modal">
    <div class="modal-header"><span>Add Customer</span><button class="modal-close" onclick="closeModal('modal-customer')">✕</button></div>
    <div class="form-group"><label>Full Name</label><input type="text" id="cust-name" placeholder="e.g. Juan dela Cruz"/></div>
    <div class="form-group"><label>Phone</label><input type="tel" id="cust-phone" placeholder="09XXXXXXXXX"/></div>
    <div class="form-group"><label>Email (optional)</label><input type="email" id="cust-email" placeholder="email@example.com"/></div>
    <button class="btn-primary full" onclick="addCustomer()">Add Customer</button>
  </div>
</div>

<!-- MODAL: Process Payment -->
<div class="modal-overlay" id="modal-payment">
  <div class="modal">
    <div class="modal-header"><span>Process Payment</span><button class="modal-close" onclick="closeModal('modal-payment')">✕</button></div>
    <div class="pay-summary" id="pay-summary"></div>
    <div class="form-group"><label>Payment Method</label>
      <select id="pay-method">
        <option value="cash">Cash</option>
        <option value="gcash">GCash</option>
        <option value="card">Card</option>
      </select>
    </div>
    <button class="btn-primary full" onclick="processPayment()">Confirm Payment</button>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>// ============================================
// IN-MEMORY DATABASE (mirrors MySQL schema)
// ============================================

const DB = {
  customers: [
    { customer_id: 1, name: 'Juan dela Cruz',  phone: '09171234567', email: 'juan@email.com',  created_at: '2025-06-01T08:00:00' },
    { customer_id: 2, name: 'Marco Reyes',     phone: '09182345678', email: 'marco@email.com', created_at: '2025-06-02T09:00:00' },
    { customer_id: 3, name: 'Carlo Santos',    phone: '09193456789', email: 'carlo@email.com', created_at: '2025-06-03T10:00:00' },
    { customer_id: 4, name: 'Luis Garcia',     phone: '09204567890', email: 'luis@email.com',  created_at: '2025-06-04T11:00:00' },
    { customer_id: 5, name: 'Ryan Mendoza',    phone: '09215678901', email: 'ryan@email.com',  created_at: '2025-06-05T08:30:00' },
  ],
  barbers: [
    { barber_id: 1, name: 'Kuya Ben',  specialty: 'Fade & Taper', status: 'available' },
    { barber_id: 2, name: 'Kuya Dave', specialty: 'Skin Fade',    status: 'available' },
    { barber_id: 3, name: 'Kuya Mark', specialty: 'Classic Cut',  status: 'busy'      },
  ],
  services: [
    { service_id: 1, service_name: 'Haircut',          price: 120, duration_min: 30 },
    { service_id: 2, service_name: 'Skin Fade',        price: 150, duration_min: 45 },
    { service_id: 3, service_name: 'Haircut + Shave',  price: 180, duration_min: 50 },
    { service_id: 4, service_name: 'Kids Haircut',     price: 80,  duration_min: 20 },
    { service_id: 5, service_name: 'Hair Color',       price: 350, duration_min: 90 },
  ],
  appointments: [
    { appointment_id: 1, customer_id: 1, barber_id: 1, service_id: 1, scheduled_at: '2025-06-10T09:00:00', status: 'confirmed'  },
    { appointment_id: 2, customer_id: 2, barber_id: 2, service_id: 2, scheduled_at: '2025-06-10T10:00:00', status: 'confirmed'  },
    { appointment_id: 3, customer_id: 3, barber_id: 1, service_id: 3, scheduled_at: '2025-06-10T11:00:00', status: 'pending'    },
    { appointment_id: 4, customer_id: 4, barber_id: 3, service_id: 5, scheduled_at: '2025-06-11T14:00:00', status: 'pending'    },
    { appointment_id: 5, customer_id: 5, barber_id: 2, service_id: 1, scheduled_at: '2025-06-11T15:00:00', status: 'confirmed'  },
  ],
  walk_ins: [
    { walkin_id: 1, customer_id: 1, barber_id: 2, service_id: 1, arrived_at: '2025-06-09T10:15:00', queue_number: 1, status: 'completed'   },
    { walkin_id: 2, customer_id: 3, barber_id: 1, service_id: 2, arrived_at: '2025-06-09T10:30:00', queue_number: 2, status: 'completed'   },
    { walkin_id: 3, customer_id: 5, barber_id: 3, service_id: 4, arrived_at: '2025-06-09T11:00:00', queue_number: 3, status: 'completed'   },
    { walkin_id: 4, customer_id: 2, barber_id: 1, service_id: 3, arrived_at: '2025-06-09T11:20:00', queue_number: 4, status: 'in-progress' },
    { walkin_id: 5, customer_id: 4, barber_id: 2, service_id: 1, arrived_at: '2025-06-09T11:45:00', queue_number: 5, status: 'waiting'     },
  ],
  payments: [
    { payment_id: 1, appointment_id: 1, walkin_id: null, amount: 120, method: 'cash',  paid_at: '2025-06-09T09:30:00' },
    { payment_id: 2, appointment_id: 2, walkin_id: null, amount: 150, method: 'gcash', paid_at: '2025-06-09T10:30:00' },
    { payment_id: 3, appointment_id: null, walkin_id: 1, amount: 120, method: 'cash',  paid_at: '2025-06-09T10:45:00' },
    { payment_id: 4, appointment_id: null, walkin_id: 2, amount: 150, method: 'gcash', paid_at: '2025-06-09T11:15:00' },
    { payment_id: 5, appointment_id: null, walkin_id: 3, amount: 80,  method: 'cash',  paid_at: '2025-06-09T11:30:00' },
  ],
  _nextId: { customer: 6, appointment: 6, walkin: 6, payment: 6 },
};

// ============================================
// HELPER LOOKUPS
// ============================================
function getCustomer(id)    { return DB.customers.find(c => c.customer_id === id); }
function getBarber(id)      { return DB.barbers.find(b => b.barber_id === id); }
function getService(id)     { return DB.services.find(s => s.service_id === id); }
function getAppointment(id) { return DB.appointments.find(a => a.appointment_id === id); }
function getWalkIn(id)      { return DB.walk_ins.find(w => w.walkin_id === id); }

// ============================================
// STORED PROCEDURE SIMULATIONS
// ============================================

// BookAppointment
function sp_BookAppointment(customer_id, barber_id, service_id, scheduled_at) {
  const barber = getBarber(barber_id);
  if (barber.status === 'off-duty') throw new Error('Barber is off-duty. Please choose another barber.');
  const newAppt = {
    appointment_id: DB._nextId.appointment++,
    customer_id, barber_id, service_id,
    scheduled_at, status: 'pending'
  };
  DB.appointments.push(newAppt);
  return newAppt;
}

// RegisterWalkIn
function sp_RegisterWalkIn(customer_id, barber_id, service_id) {
  const today = new Date().toDateString();
  const todayWalkins = DB.walk_ins.filter(w => new Date(w.arrived_at).toDateString() === today);
  const nextQueue = todayWalkins.length > 0 ? Math.max(...todayWalkins.map(w => w.queue_number)) + 1 : 1;
  const newWI = {
    walkin_id: DB._nextId.walkin++,
    customer_id, barber_id, service_id,
    arrived_at: new Date().toISOString(),
    queue_number: nextQueue,
    status: 'waiting'
  };
  DB.walk_ins.push(newWI);
  return newWI;
}

// ProcessPayment
function sp_ProcessPayment(appointment_id, walkin_id, method) {
  let amount, source;
  if (appointment_id) {
    source = getAppointment(appointment_id);
    amount = getService(source.service_id).price;
    source.status = 'completed';
  } else {
    source = getWalkIn(walkin_id);
    amount = getService(source.service_id).price;
    source.status = 'completed';
    // TRIGGER: barber goes available
    trg_walkin_status_change(source, 'completed');
  }
  const pay = {
    payment_id: DB._nextId.payment++,
    appointment_id: appointment_id || null,
    walkin_id: walkin_id || null,
    amount, method,
    paid_at: new Date().toISOString()
  };
  DB.payments.push(pay);
  return pay;
}

// ============================================
// TRIGGER SIMULATION
// trg_walkin_status_change
// ============================================
function trg_walkin_status_change(walkin, newStatus) {
  const barber = getBarber(walkin.barber_id);
  if (newStatus === 'in-progress') {
    barber.status = 'busy';
  } else if (newStatus === 'completed' || newStatus === 'cancelled') {
    barber.status = 'available';
  }
}

// Update walk-in status (fires trigger)
function updateWalkInStatus(walkin_id, newStatus) {
  const wi = getWalkIn(walkin_id);
  if (!wi) return;
  wi.status = newStatus;
  trg_walkin_status_change(wi, newStatus);
}
</script>
<script>// ============================================
// UI HELPERS
// ============================================

function showPage(name) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
  document.querySelectorAll('.bnav-item').forEach(n => n.classList.remove('active'));

  document.getElementById('page-' + name).classList.add('active');

  // Sync sidebar nav
  document.querySelectorAll('.nav-item').forEach(n => {
    const txt = n.textContent.toLowerCase();
    if (txt.includes(name === 'walkins' ? 'walk' : name)) n.classList.add('active');
  });

  // Sync bottom nav (by index)
  const pages = ['dashboard','appointments','walkins','customers','payments'];
  const idx = pages.indexOf(name);
  const bnavItems = document.querySelectorAll('.bnav-item');
  if (idx >= 0 && bnavItems[idx]) bnavItems[idx].classList.add('active');

  render();
  window.scrollTo(0, 0);
}

function openModal(id) {
  populateSelects();
  document.getElementById(id).classList.add('open');
  document.body.style.overflow = 'hidden';
}

function closeModal(id) {
  document.getElementById(id).classList.remove('open');
  document.body.style.overflow = '';
}

function toast(msg) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  setTimeout(() => t.classList.remove('show'), 2800);
}

function badge(status) {
  return `<span class="badge badge-${status.replace(/[\s-]/g,'-')}">${status}</span>`;
}

function fmt(dt) {
  return new Date(dt).toLocaleString('en-PH', { month:'short', day:'numeric', hour:'2-digit', minute:'2-digit' });
}
function fmtDate(dt) {
  return new Date(dt).toLocaleDateString('en-PH', { month:'short', day:'numeric', year:'numeric' });
}

// ============================================
// POPULATE SELECTS
// ============================================
function populateSelects() {
  const custOpts   = DB.customers.map(c => `<option value="${c.customer_id}">${c.name}</option>`).join('');
  const barberOpts = DB.barbers.map(b => `<option value="${b.barber_id}">${b.name} (${b.status})</option>`).join('');
  const svcOpts    = DB.services.map(s => `<option value="${s.service_id}">${s.service_name} — ₱${s.price}</option>`).join('');
  ['book-customer','wi-customer'].forEach(id => document.getElementById(id).innerHTML = custOpts);
  ['book-barber','wi-barber'].forEach(id => document.getElementById(id).innerHTML = barberOpts);
  ['book-service','wi-service'].forEach(id => document.getElementById(id).innerHTML = svcOpts);
}

// ============================================
// RENDER
// ============================================
function render() {
  renderBarberStatus();
  renderDashboard();
  renderAppointments();
  renderWalkIns();
  renderCustomers();
  renderPayments();
}

function renderBarberStatus() {
  const html = DB.barbers.map(b => `
    <div class="barber-pill">
      <span class="status-dot dot-${b.status.replace(' ','-')}"></span>
      <span>${b.name}</span>
    </div>`).join('');
  const sidebar = document.getElementById('barber-status-list');
  const mobile  = document.getElementById('mobile-barber-list');
  if (sidebar) sidebar.innerHTML = html;
  if (mobile)  mobile.innerHTML  = html;
}

function renderDashboard() {
  const totalRevenue = DB.payments.reduce((s, p) => s + p.amount, 0);
  document.getElementById('stat-revenue').textContent = '₱' + totalRevenue.toLocaleString();
  document.getElementById('stat-appointments').textContent = DB.appointments.length;
  document.getElementById('stat-walkins').textContent = DB.walk_ins.length;
  const queueCount = DB.walk_ins.filter(w => w.status === 'waiting' || w.status === 'in-progress').length;
  document.getElementById('stat-queue').textContent = queueCount;
  document.getElementById('today-date').textContent = new Date().toLocaleDateString('en-PH', { weekday:'long', year:'numeric', month:'long', day:'numeric' });

  const upcoming = DB.appointments.filter(a => a.status !== 'completed' && a.status !== 'cancelled').slice(0,5);
  document.getElementById('dash-appointments').innerHTML = upcoming.length ? upcoming.map(a => {
    const c = getCustomer(a.customer_id), b = getBarber(a.barber_id), s = getService(a.service_id);
    return `<div class="dash-item">
      <div><div class="dash-name">${c.name}</div><div class="dash-sub">${b.name} · ${s.service_name}</div></div>
      <div class="dash-right">${badge(a.status)}<div class="dash-sub" style="margin-top:4px">${fmt(a.scheduled_at)}</div></div>
    </div>`;
  }).join('') : '<div class="empty">no upcoming appointments</div>';

  const queue = DB.walk_ins.filter(w => w.status !== 'completed' && w.status !== 'cancelled');
  document.getElementById('dash-queue').innerHTML = queue.length ? queue.map(w => {
    const c = getCustomer(w.customer_id), b = getBarber(w.barber_id);
    return `<div class="dash-item">
      <div><div class="dash-name">#${w.queue_number} · ${c.name}</div><div class="dash-sub">${b.name}</div></div>
      ${badge(w.status)}
    </div>`;
  }).join('') : '<div class="empty">queue is empty</div>';
}

function renderAppointments() {
  // Desktop table
  document.getElementById('appt-table').innerHTML = DB.appointments.map(a => {
    const c = getCustomer(a.customer_id), b = getBarber(a.barber_id), s = getService(a.service_id);
    const paid = DB.payments.some(p => p.appointment_id === a.appointment_id);
    return `<tr>
      <td style="font-family:var(--font-mono);color:var(--text3)">#${a.appointment_id}</td>
      <td style="color:var(--text)">${c.name}</td>
      <td>${b.name}</td>
      <td>${s.service_name}</td>
      <td style="font-family:var(--font-mono);font-size:12px">${fmt(a.scheduled_at)}</td>
      <td>${badge(a.status)}</td>
      <td>${apptActions(a, s, c, paid)}</td>
    </tr>`;
  }).join('') || '<tr><td colspan="7" class="empty">no appointments</td></tr>';

  // Mobile cards
  document.getElementById('appt-cards').innerHTML = DB.appointments.map(a => {
    const c = getCustomer(a.customer_id), b = getBarber(a.barber_id), s = getService(a.service_id);
    const paid = DB.payments.some(p => p.appointment_id === a.appointment_id);
    return `<div class="m-card">
      <div class="m-card-top">
        <div>
          <div class="m-card-name">${c.name}</div>
          <div class="m-card-sub">${b.name} · ${s.service_name} · ₱${s.price}</div>
          <div class="m-card-sub">${fmt(a.scheduled_at)}</div>
        </div>
        ${badge(a.status)}
      </div>
      <div class="m-card-actions">${apptActions(a, s, c, paid)}</div>
    </div>`;
  }).join('') || '<div class="empty">no appointments</div>';
}

function apptActions(a, s, c, paid) {
  let btns = '';
  if (a.status === 'pending')
    btns += `<button class="btn-sm" onclick="confirmAppt(${a.appointment_id})">Confirm</button>`;
  if (a.status !== 'completed' && a.status !== 'cancelled' && !paid)
    btns += `<button class="btn-sm" onclick="openPayModal(${a.appointment_id}, null, '${s.service_name}', ${s.price}, '${c.name}')">Pay</button>`;
  if (a.status !== 'completed' && a.status !== 'cancelled')
    btns += `<button class="btn-sm danger" onclick="cancelAppt(${a.appointment_id})">Cancel</button>`;
  return btns;
}

function renderWalkIns() {
  document.getElementById('walkin-table').innerHTML = DB.walk_ins.map(w => {
    const c = getCustomer(w.customer_id), b = getBarber(w.barber_id), s = getService(w.service_id);
    const paid = DB.payments.some(p => p.walkin_id === w.walkin_id);
    return `<tr>
      <td style="font-family:var(--font-mono);color:var(--accent);font-size:18px">${w.queue_number}</td>
      <td style="color:var(--text)">${c.name}</td>
      <td>${b.name}</td>
      <td>${s.service_name}</td>
      <td style="font-family:var(--font-mono);font-size:12px">${fmt(w.arrived_at)}</td>
      <td>${badge(w.status)}</td>
      <td>${walkInActions(w, s, c, paid)}</td>
    </tr>`;
  }).join('') || '<tr><td colspan="7" class="empty">no walk-ins</td></tr>';

  document.getElementById('walkin-cards').innerHTML = DB.walk_ins.map(w => {
    const c = getCustomer(w.customer_id), b = getBarber(w.barber_id), s = getService(w.service_id);
    const paid = DB.payments.some(p => p.walkin_id === w.walkin_id);
    return `<div class="m-card">
      <div class="m-card-top">
        <div>
          <div class="m-card-name" style="display:flex;align-items:center;gap:8px">
            <span style="font-family:var(--font-display);font-size:22px;color:var(--accent)">#${w.queue_number}</span>
            ${c.name}
          </div>
          <div class="m-card-sub">${b.name} · ${s.service_name} · ₱${s.price}</div>
          <div class="m-card-sub">Arrived ${fmt(w.arrived_at)}</div>
        </div>
        ${badge(w.status)}
      </div>
      <div class="m-card-actions">${walkInActions(w, s, c, paid)}</div>
    </div>`;
  }).join('') || '<div class="empty">no walk-ins</div>';
}

function walkInActions(w, s, c, paid) {
  let btns = '';
  if (w.status === 'waiting')
    btns += `<button class="btn-sm" onclick="startWalkIn(${w.walkin_id})">Start</button>`;
  if (w.status === 'in-progress' && !paid)
    btns += `<button class="btn-sm" onclick="openPayModal(null, ${w.walkin_id}, '${s.service_name}', ${s.price}, '${c.name}')">Pay & Complete</button>`;
  if (w.status !== 'completed' && w.status !== 'cancelled')
    btns += `<button class="btn-sm danger" onclick="cancelWalkIn(${w.walkin_id})">Cancel</button>`;
  return btns;
}

function renderCustomers() {
  document.getElementById('customer-table').innerHTML = DB.customers.map(c => `
    <tr>
      <td style="font-family:var(--font-mono);color:var(--text3)">#${c.customer_id}</td>
      <td style="color:var(--text)">${c.name}</td>
      <td style="font-family:var(--font-mono);font-size:12px">${c.phone}</td>
      <td style="color:var(--text3)">${c.email || '—'}</td>
      <td style="font-family:var(--font-mono);font-size:12px">${fmtDate(c.created_at)}</td>
      <td><button class="btn-sm danger" onclick="deleteCustomer(${c.customer_id})">Delete</button></td>
    </tr>`).join('');

  document.getElementById('customer-cards').innerHTML = DB.customers.map(c => `
    <div class="m-card">
      <div class="m-card-top">
        <div>
          <div class="m-card-name">${c.name}</div>
          <div class="m-card-sub">${c.phone}</div>
          <div class="m-card-sub">${c.email || '—'}</div>
        </div>
        <div style="text-align:right">
          <div class="m-card-sub">Since ${fmtDate(c.created_at)}</div>
        </div>
      </div>
      <div class="m-card-actions">
        <button class="btn-sm danger" onclick="deleteCustomer(${c.customer_id})">Delete</button>
      </div>
    </div>`).join('');
}

function renderPayments() {
  document.getElementById('payment-table').innerHTML = DB.payments.map(p => `
    <tr>
      <td style="font-family:var(--font-mono);color:var(--text3)">#${p.payment_id}</td>
      <td>${p.appointment_id ? 'Appointment' : 'Walk-in'}</td>
      <td style="font-family:var(--font-mono)">#${p.appointment_id || p.walkin_id}</td>
      <td style="color:var(--accent);font-family:var(--font-mono)">₱${p.amount}</td>
      <td>${badge(p.method)}</td>
      <td style="font-family:var(--font-mono);font-size:12px">${fmt(p.paid_at)}</td>
    </tr>`).join('');

  document.getElementById('payment-cards').innerHTML = DB.payments.map(p => `
    <div class="m-card">
      <div class="m-card-top">
        <div>
          <div class="m-card-name" style="color:var(--accent);font-family:var(--font-display);font-size:22px">₱${p.amount}</div>
          <div class="m-card-sub">${p.appointment_id ? 'Appointment' : 'Walk-in'} #${p.appointment_id || p.walkin_id}</div>
          <div class="m-card-sub">${fmt(p.paid_at)}</div>
        </div>
        ${badge(p.method)}
      </div>
    </div>`).join('');
}

// ============================================
// ACTIONS
// ============================================

function bookAppointment() {
  const customer_id  = +document.getElementById('book-customer').value;
  const barber_id    = +document.getElementById('book-barber').value;
  const service_id   = +document.getElementById('book-service').value;
  const scheduled_at = document.getElementById('book-datetime').value;
  if (!scheduled_at) { toast('Please pick a date and time.'); return; }
  try {
    sp_BookAppointment(customer_id, barber_id, service_id, scheduled_at);
    closeModal('modal-book');
    render();
    toast('✦ Appointment booked!');
  } catch(e) { toast('✕ ' + e.message); }
}

function registerWalkIn() {
  const customer_id = +document.getElementById('wi-customer').value;
  const barber_id   = +document.getElementById('wi-barber').value;
  const service_id  = +document.getElementById('wi-service').value;
  const wi = sp_RegisterWalkIn(customer_id, barber_id, service_id);
  closeModal('modal-walkin');
  render();
  toast(`✦ Queue #${wi.queue_number} assigned!`);
}

function addCustomer() {
  const name  = document.getElementById('cust-name').value.trim();
  const phone = document.getElementById('cust-phone').value.trim();
  const email = document.getElementById('cust-email').value.trim();
  if (!name || !phone) { toast('Name and phone are required.'); return; }
  if (DB.customers.some(c => c.phone === phone)) { toast('✕ Phone already exists.'); return; }
  DB.customers.push({ customer_id: DB._nextId.customer++, name, phone, email, created_at: new Date().toISOString() });
  closeModal('modal-customer');
  document.getElementById('cust-name').value = '';
  document.getElementById('cust-phone').value = '';
  document.getElementById('cust-email').value = '';
  render();
  toast('✦ Customer added!');
}

function deleteCustomer(id) {
  DB.appointments = DB.appointments.filter(a => a.customer_id !== id);
  DB.walk_ins     = DB.walk_ins.filter(w => w.customer_id !== id);
  DB.customers    = DB.customers.filter(c => c.customer_id !== id);
  render();
  toast('Customer deleted.');
}

function confirmAppt(id)  { getAppointment(id).status = 'confirmed'; render(); toast('✦ Appointment confirmed.'); }
function cancelAppt(id)   { getAppointment(id).status = 'cancelled'; render(); toast('Appointment cancelled.'); }

function startWalkIn(id)  { updateWalkInStatus(id, 'in-progress'); render(); toast('✦ Walk-in started. Barber is now busy.'); }
function cancelWalkIn(id) { updateWalkInStatus(id, 'cancelled'); render(); toast('Walk-in cancelled.'); }

let _paySource = {};
function openPayModal(appointment_id, walkin_id, service_name, price, customer_name) {
  _paySource = { appointment_id, walkin_id };
  document.getElementById('pay-summary').textContent =
    `Customer: ${customer_name}\nService: ${service_name}\nAmount: ₱${price}`;
  openModal('modal-payment');
}

function processPayment() {
  const method = document.getElementById('pay-method').value;
  const pay = sp_ProcessPayment(_paySource.appointment_id, _paySource.walkin_id, method);
  if (_paySource.walkin_id) trg_walkin_status_change(getWalkIn(_paySource.walkin_id), 'completed');
  closeModal('modal-payment');
  render();
  toast(`✦ ₱${pay.amount} received via ${method}.`);
}

// ============================================
// INIT
// ============================================
document.addEventListener('DOMContentLoaded', () => {
  render();
  document.querySelectorAll('.modal-overlay').forEach(overlay => {
    overlay.addEventListener('click', e => {
      if (e.target === overlay) {
        overlay.classList.remove('open');
        document.body.style.overflow = '';
      }
    });
  });
});
</script>
</body>
</html>
