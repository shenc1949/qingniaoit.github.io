<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>极简倒数日 | 高感知动态流淌背景</title>
    <style>
        :root {
            --radius: 12px;
            --small-radius: 8px;
            --bg-card: #ffffff;
            --bg-modal: rgba(0, 0, 0, 0.5);
            --text-main: #1e293b;
            --text-secondary: #64748b;
            --text-light: #94a3b8;
            --border-color: #e2e8f0;
            --danger: #ef4444;
            --success: #10b981;
            --primary: #6366f1;
            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            --flow-duration: 20s;
        }

        body.dawn {
            --bg-gradient-1: #0a192f;
            --bg-gradient-2: #112240;
            --bg-gradient-3: #233554;
            --text-main: #f8fafc;
            --text-secondary: #e2e8f0;
            --bg-card: rgba(255, 255, 255, 0.1);
            --border-color: rgba(255, 255, 255, 0.2);
        }

        body.morning {
            --bg-gradient-1: #ffd166;
            --bg-gradient-2: #feb47b;
            --bg-gradient-3: #ffd166;
        }

        body.forenoon {
            --bg-gradient-1: #e0f7fa;
            --bg-gradient-2: #b2ebf2;
            --bg-gradient-3: #80deea;
        }

        body.noon {
            --bg-gradient-1: #ffecd2;
            --bg-gradient-2: #fcb69f;
            --bg-gradient-3: #a8edea;
        }

        body.afternoon {
            --bg-gradient-1: #6a11cb;
            --bg-gradient-2: #2575fc;
            --bg-gradient-3: #00c9ff;
        }

        body.night {
            --bg-gradient-1: #0f2027;
            --bg-gradient-2: #2c3e50;
            --bg-gradient-3: #4ca1af;
            --text-main: #f8fafc;
            --text-secondary: #e2e8f0;
            --bg-card: rgba(255, 255, 255, 0.1);
            --border-color: rgba(255, 255, 255, 0.2);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', 'Segoe UI', 'Microsoft YaHei', sans-serif;
        }

        body {
            min-height: 100vh;
            padding: 2rem 1rem;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            transition: color 0.5s ease;
            background: linear-gradient(
                -45deg,
                var(--bg-gradient-1),
                var(--bg-gradient-2),
                var(--bg-gradient-3),
                var(--bg-gradient-2),
                var(--bg-gradient-1)
            );
            background-size: 600% 600%;
            animation: gradientFlow var(--flow-duration) ease-in-out infinite;
            color: var(--text-main);
            position: relative;
            overflow-x: hidden;
        }

        @keyframes gradientFlow {
            0% {
                background-position: 0% 0%;
            }
            50% {
                background-position: 100% 100%;
            }
            100% {
                background-position: 0% 0%;
            }
        }

        .menu-btn {
            position: fixed;
            top: 1.5rem;
            right: 1.5rem;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid var(--border-color);
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            z-index: 1100;
            transition: var(--transition);
        }

        .menu-btn:hover {
            background-color: rgba(255, 255, 255, 0.2);
            transform: scale(1.05);
        }

        .menu-dots {
            width: 16px;
            height: 16px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .menu-dot {
            width: 4px;
            height: 4px;
            border-radius: 50%;
            background-color: white;
            margin: 0 auto;
        }

        .side-menu {
            position: fixed;
            top: 0;
            right: 0;
            width: 300px;
            height: 100vh;
            background-color: rgba(0, 0, 0, 0.8);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            z-index: 1050;
            transform: translateX(100%);
            transition: transform 0.3s ease-in-out;
            padding: 2rem 1.5rem;
            overflow-y: auto;
        }

        .side-menu.active {
            transform: translateX(0);
        }

        .menu-header {
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
        }

        .menu-title {
            font-size: 1.2rem;
            font-weight: 600;
            color: white;
            text-align: center;
        }

        .menu-content {
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }

        .menu-item {
            display: flex;
            flex-direction: column;
            gap: 0.3rem;
        }

        .menu-label {
            font-size: 0.95rem;
            font-weight: bold;
            color: white;
        }

        .menu-value {
            font-size: 0.9rem;
            font-weight: 300;
            color: white;
            padding-left: 0.5rem;
        }

        .switch-container {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .switch {
            position: relative;
            display: inline-block;
            width: 50px;
            height: 24px;
        }

        .switch input {
            opacity: 0;
            width: 0;
            height: 0;
        }

        .slider {
            position: absolute;
            cursor: pointer;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(255, 255, 255, 0.2);
            transition: .4s;
            border-radius: 24px;
        }

        .slider:before {
            position: absolute;
            content: "";
            height: 18px;
            width: 18px;
            left: 3px;
            bottom: 3px;
            background-color: white;
            transition: .4s;
            border-radius: 50%;
        }

        input:checked + .slider {
            background-color: var(--primary);
        }

        input:checked + .slider:before {
            transform: translateX(26px);
        }

        .password-modal {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: var(--bg-modal);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 2000;
            opacity: 0;
            visibility: hidden;
            transition: var(--transition);
        }

        .password-modal.active {
            opacity: 1;
            visibility: visible;
        }

        .password-modal-content {
            width: 100%;
            max-width: 350px;
            background-color: var(--bg-card);
            border-radius: var(--radius);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
            padding: 2rem;
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border: 1px solid var(--border-color);
        }

        .password-modal-title {
            font-size: 1.2rem;
            font-weight: 600;
            color: var(--text-main);
            margin-bottom: 1.5rem;
            text-align: center;
        }

        .password-input-group {
            margin-bottom: 1.5rem;
        }

        .password-input {
            width: 100%;
            padding: 1rem;
            border: 1px solid var(--border-color);
            border-radius: var(--small-radius);
            font-size: 1rem;
            outline: none;
            transition: var(--transition);
            background-color: rgba(255, 255, 255, 0.15);
            color: var(--text-main);
        }

        .password-input::placeholder {
            color: var(--text-secondary);
        }

        .password-input:focus {
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.2);
        }

        .password-modal-actions {
            display: flex;
            gap: 0.75rem;
        }

        .password-modal-btn {
            flex: 1;
            padding: 0.875rem 1rem;
            border-radius: var(--small-radius);
            font-size: 0.9rem;
            font-weight: 500;
            cursor: pointer;
            transition: var(--transition);
            border: 1px solid var(--border-color);
            background-color: transparent;
            color: var(--text-main);
        }

        .password-confirm-btn {
            background-color: var(--primary);
            color: white;
            border: none;
        }

        .password-confirm-btn:hover {
            background-color: #4f46e5;
        }

        .password-cancel-btn:hover {
            background-color: rgba(255, 255, 255, 0.15);
        }

        .password-error {
            color: var(--danger);
            font-size: 0.85rem;
            margin-top: 0.5rem;
            display: none;
        }

        .password-error.active {
            display: block;
        }

        .app-container {
            width: 100%;
            max-width: 650px;
            background-color: var(--bg-card);
            border-radius: var(--radius);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
            overflow: hidden;
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            z-index: 100;
        }

        .app-header {
            padding: 1.5rem 2rem;
            border-bottom: 1px solid var(--border-color);
            text-align: center;
        }

        .app-title {
            font-size: 1.5rem;
            font-weight: 600;
            margin-bottom: 0.5rem;
        }

        .app-date {
            font-size: 1.1rem;
            color: var(--primary);
            font-weight: 500;
        }

        .app-subtitle {
            font-size: 0.9rem;
            color: var(--text-secondary);
            margin-top: 0.3rem;
        }

        .app-content {
            padding: 2rem;
        }

        .add-form {
            display: flex;
            gap: 0.75rem;
            margin-bottom: 1.5rem;
            flex-wrap: wrap;
        }

        .form-input {
            flex: 1;
            min-width: 120px;
            padding: 0.875rem 1rem;
            border: 1px solid var(--border-color);
            border-radius: var(--small-radius);
            font-size: 0.9rem;
            outline: none;
            transition: var(--transition);
            background-color: rgba(255, 255, 255, 0.1);
            color: var(--text-main);
        }

        .form-input::placeholder {
            color: var(--text-secondary);
        }

        .form-input:focus {
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.1);
        }

        .color-picker {
            padding: 0.5rem;
            cursor: pointer;
            min-width: 60px;
            background-color: rgba(255, 255, 255, 0.1);
            border: 1px solid var(--border-color);
            border-radius: var(--small-radius);
        }

        .add-btn {
            min-width: 100px;
            padding: 0.875rem 1rem;
            background-color: var(--primary);
            color: white;
            border: none;
            border-radius: var(--small-radius);
            font-size: 0.9rem;
            font-weight: 500;
            cursor: pointer;
            transition: var(--transition);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
        }

        .add-btn:hover {
            background-color: #4f46e5;
            transform: translateY(-1px);
        }

        .shortcut-group {
            display: flex;
            gap: 0.5rem;
            margin-bottom: 2rem;
            flex-wrap: wrap;
        }

        .shortcut-btn {
            padding: 0.5rem 1rem;
            background-color: rgba(255, 255, 255, 0.1);
            border: 1px solid var(--border-color);
            border-radius: var(--small-radius);
            font-size: 0.8rem;
            cursor: pointer;
            transition: var(--transition);
            white-space: nowrap;
            color: var(--text-main);
        }

        .shortcut-btn:hover {
            background-color: rgba(255, 255, 255, 0.2);
            transform: translateY(-1px);
        }

        .event-list {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            max-height: 400px;
            overflow-y: auto;
            padding-right: 0.5rem;
            margin-bottom: 2rem;
        }

        .event-card {
            background-color: var(--bg-card);
            border-radius: var(--radius);
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
            border: 1px solid var(--border-color);
            overflow: hidden;
            cursor: pointer;
            transition: var(--transition);
            min-height: 120px;
            display: flex;
            flex-direction: column;
        }

        .event-card:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.08);
        }

        .card-header {
            padding: 1.25rem 1.5rem;
            background-color: var(--primary);
            color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 0.5rem;
        }

        .card-name {
            font-size: 1.2rem;
            font-weight: 600;
            white-space: normal;
            word-break: break-all;
            max-width: 70%;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }

        .card-days {
            font-size: 1.3rem;
            font-weight: 600;
            white-space: nowrap;
            flex-shrink: 0;
        }

        .card-body {
            padding: 1.5rem 1.5rem;
            border-top: 1px solid var(--border-color);
            background-color: rgba(255, 255, 255, 0.05);
            text-align: center;
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .card-date-label {
            font-size: 0.9rem;
            color: var(--text-secondary);
            margin-bottom: 0.3rem;
            display: block;
        }

        .card-date {
            font-size: 1.8rem;
            font-weight: 700;
            letter-spacing: 1px;
        }

        .card-footer {
            padding: 0.75rem 1.5rem;
            border-top: 1px solid var(--border-color);
            background-color: rgba(255, 255, 255, 0.05);
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 0.5rem;
        }

        .card-note-count {
            font-size: 0.9rem;
            color: var(--text-secondary);
        }

        /* 重点：删除按钮样式，确保显示 */
        .card-delete-btn {
            color: var(--danger);
            font-size: 0.9rem;
            cursor: pointer;
            transition: var(--transition);
            padding: 0.25rem 0.5rem;
            border-radius: var(--small-radius);
            background-color: rgba(239, 68, 68, 0.1);
        }

        .card-delete-btn:hover {
            color: white;
            background-color: var(--danger);
        }

        .empty-state {
            padding: 4rem 2rem;
            text-align: center;
            border: 1px dashed var(--border-color);
            border-radius: var(--radius);
            color: var(--text-secondary);
        }

        .empty-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
            opacity: 0.5;
        }

        .empty-text {
            font-size: 0.9rem;
        }

        ::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }

        ::-webkit-scrollbar-track {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 3px;
        }

        ::-webkit-scrollbar-thumb {
            background: var(--text-light);
            border-radius: 3px;
        }

        @media (max-width: 550px) {
            .app-content {
                padding: 1.5rem;
            }

            .add-form {
                flex-direction: column;
            }

            .card-date {
                font-size: 1.5rem;
            }

            .card-name {
                max-width: 100%;
            }

            .side-menu {
                width: 250px;
            }
        }

        .event-detail-page {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100vh;
            background-color: inherit;
            z-index: 1000;
            padding: 2rem 1rem;
            display: none;
            flex-direction: column;
            overflow-y: auto;
        }

        .event-detail-page.active {
            display: flex;
        }

        .close-detail-btn {
            position: absolute;
            top: 1rem;
            left: 1rem;
            font-size: 1.5rem;
            background: transparent;
            border: none;
            color: var(--text-main);
            cursor: pointer;
            transition: var(--transition);
            z-index: 1010;
        }

        .close-detail-btn:hover {
            transform: scale(1.1);
        }

        .countdown-card {
            background-color: var(--bg-card);
            border: 2px solid var(--primary);
            border-radius: var(--radius);
            padding: 2rem;
            text-align: center;
            margin-bottom: 1rem;
            position: relative;
            box-shadow: 0 4px 12px rgba(99, 102, 241, 0.15);
        }

        .countdown-card::after {
            content: '';
            position: absolute;
            top: -5px;
            left: -5px;
            right: -5px;
            bottom: -5px;
            border: 1px dashed var(--primary);
            border-radius: calc(var(--radius) + 5px);
            pointer-events: none;
            opacity: 0.6;
        }

        .countdown-top-text {
            font-size: 1rem;
            color: var(--text-secondary);
            margin-bottom: 1rem;
        }

        .countdown-days {
            font-size: 4rem;
            font-weight: bold;
            color: var(--primary);
            margin-bottom: 1rem;
        }

        .countdown-target-date {
            font-size: 1rem;
            color: var(--text-secondary);
        }

        .countdown-slogan {
            text-align: center;
            color: var(--text-secondary);
            font-size: 0.9rem;
            margin-bottom: 2rem;
        }

        .notes-section {
            background-color: var(--bg-card);
            border: 2px solid var(--text-main);
            border-radius: var(--radius);
            padding: 1rem;
            flex: 1;
            position: relative;
        }

        .notes-section::after {
            content: '';
            position: absolute;
            top: -5px;
            left: -5px;
            right: -5px;
            bottom: -5px;
            border: 1px dashed var(--text-secondary);
            border-radius: calc(var(--radius) + 5px);
            pointer-events: none;
        }

        .notes-title {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 1px solid var(--border-color);
        }

        .notes-title img {
            width: 24px;
            height: 24px;
        }

        .notes-list {
            max-height: 400px;
            overflow-y: auto;
            margin-bottom: 1rem;
        }

        .note-item {
            background-color: rgba(255, 255, 255, 0.05);
            border: 1px solid var(--border-color);
            border-radius: var(--small-radius);
            padding: 1rem;
            margin-bottom: 0.5rem;
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }

        .note-content {
            font-size: 1rem;
            line-height: 1.5;
        }

        .note-meta {
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 0.8rem;
            color: var(--text-secondary);
        }

        .note-edit-btn {
            color: var(--primary);
            cursor: pointer;
        }

        .note-delete-btn {
            color: var(--danger);
            cursor: pointer;
        }

        .new-note-input {
            width: 100%;
            min-height: 80px;
            border: 1px solid var(--border-color);
            border-radius: var(--small-radius);
            padding: 1rem;
            font-size: 1rem;
            resize: none;
            outline: none;
            transition: var(--transition);
            background-color: rgba(255, 255, 255, 0.1);
            color: var(--text-main);
            margin-bottom: 1rem;
        }

        .new-note-input::placeholder {
            color: var(--text-secondary);
        }

        .new-note-input:focus {
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.1);
        }

        .add-note-btn {
            display: block;
            width: 100%;
            padding: 1rem;
            background-color: var(--danger);
            color: white;
            border: none;
            border-radius: var(--small-radius);
            font-size: 1rem;
            font-weight: 500;
            cursor: pointer;
            transition: var(--transition);
            text-align: center;
        }

        .add-note-btn:hover {
            background-color: #dc2626;
        }
    </style>
</head>
<body>
    <div class="menu-btn" id="menuBtn">
        <div class="menu-dots">
            <div class="menu-dot"></div>
            <div class="menu-dot"></div>
            <div class="menu-dot"></div>
        </div>
    </div>

    <div class="side-menu" id="sideMenu">
        <div class="menu-header">
            <div class="menu-title">关于 X倒数日</div>
        </div>
        <div class="menu-content">
            <div class="menu-item">
                <div class="menu-label">软件开发者</div>
                <div class="menu-value">青鸟IT工作室 深城</div>
            </div>
            <div class="menu-item">
                <div class="menu-label">软件版本</div>
                <div class="menu-value">1.2.8</div>
            </div>
            <div class="menu-item">
                <div class="menu-label">QQ群</div>
                <div class="menu-value">765639552</div>
            </div>
            <div class="menu-item">
                <div class="menu-label">联系我们</div>
                <div class="menu-value">邮箱 qnroom@qq.com</div>
            </div>
            <div class="menu-item">
                <div class="menu-label">实验性功能</div>
            </div>
            <div class="menu-item switch-container">
                <div class="menu-label">是否有进入密码</div>
                <label class="switch">
                    <input type="checkbox" id="passwordSwitch">
                    <span class="slider"></span>
                </label>
            </div>
        </div>
    </div>

    <div class="password-modal" id="passwordModal">
        <div class="password-modal-content">
            <div class="password-modal-title" id="passwordModalTitle">请输入开屏密码</div>
            <div class="password-input-group">
                <input type="password" class="password-input" id="passwordInput" placeholder="请输入密码">
                <div class="password-error" id="passwordError">密码错误，请重试</div>
            </div>
            <div class="password-modal-actions">
                <button class="password-modal-btn password-cancel-btn" id="passwordCancelBtn" style="display: none;">取消</button>
                <button class="password-modal-btn password-confirm-btn" id="passwordConfirmBtn">确认</button>
            </div>
        </div>
    </div>

    <div class="app-container" id="appContainer" style="display: none;">
        <div class="app-header">
            <h1 class="app-title">极简倒数日</h1>
            <div class="app-date" id="currentDate"></div>
            <p class="app-subtitle">点击卡片管理笔记 | 支持单事件多笔记 | 点击删除按钮移除事件</p>
        </div>
        <div class="app-content">
            <div class="add-form">
                <input type="text" class="form-input event-name" placeholder="事件名称（如：生日）" required>
                <input type="date" class="form-input event-date" required>
                <input type="color" class="form-input color-picker" value="#6366f1">
                <button class="add-btn" id="addEventBtn">+ 添加</button>
            </div>

            <div class="shortcut-group">
                <button class="shortcut-btn" data-name="2026年元旦" data-date="2026-01-01" data-color="#ef4444">2026元旦</button>
                <button class="shortcut-btn" data-name="2026春节" data-date="2026-02-17" data-color="#f59e0b">2026春节</button>
                <button class="shortcut-btn" data-name="情人节" data-date="2026-02-14" data-color="#ec4899">情人节</button>
                <button class="shortcut-btn" data-name="国庆节" data-date="2026-10-01" data-color="#10b981">国庆节</button>
            </div>

            <div class="event-list" id="eventList">
                <div class="empty-state">
                    <div class="empty-icon">📅</div>
                    <div class="empty-text">暂无事件，添加一个开始记录吧</div>
                </div>
            </div>
        </div>
    </div>

    <div class="event-detail-page" id="eventDetailPage">
        <button class="close-detail-btn" id="closeDetailBtn">×</button>
        <div class="countdown-card" id="countdownCard">
            <div class="countdown-top-text">距离 <span id="detailEventName">目标日</span> <span id="detailStatus">还有</span></div>
            <div class="countdown-days" id="detailCountdownDays">N天</div>
            <div class="countdown-target-date" id="detailTargetDate">目标日: N年N月N日</div>
        </div>
        <div class="countdown-slogan">-相信所有美好都会如期而至-</div>
        <div class="notes-section">
            <div class="notes-title">
                <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEwLjk2IDE0LjA0bC0uMjktLjI5aC4wMWwtLjA1LS4wNWExLjk5IDEuOTkgMCAwIDAtMi43OSAwbC0uMDYuMDZsLS4wNS4wNWgtLjAxbC0uMjkuMjljLS43LjctLjcgMS44MiAwIDIuNTJsNC41OSA0LjU5YTEuOTkgMS45OSAwIDAgMCAyLjUxIDBsNC41OS00LjU5aC4wMWMuNzEtLjcgLjcxLTEuODIgMC0yLjUyek0xMiAyQzcuNTggMiA0IDUuNTggNCAxMGMwIDQuNDIgMy41OCA4IDggOGM0LjQyIDAgOC0zLjU4IDgtOFMyMC40MiAyIDEyIDJ6bTAgMTZjLTMuMzEgMC02LTIuNjktNi02czIuNjktNiA2LTZjMy4zMSAwIDYgMi42OSA2IDZzLTIuNjkgNi02IDZ6Ii8+PC9zdmc+" alt="笔记图标">
                笔记
            </div>
            <div class="notes-list" id="detailNotesList">
                <div class="empty-text">笔记内容</div>
            </div>
            <textarea class="new-note-input" id="detailNewNoteInput" placeholder="输入笔记内容..."></textarea>
            <button class="add-note-btn" id="detailAddNoteBtn">添加笔记</button>
        </div>
    </div>

    <script>
        let events = JSON.parse(localStorage.getItem('countdown_events')) || [];
        let currentEvent = null;
        let passwordEnabled = JSON.parse(localStorage.getItem('password_enabled')) || false;
        let appPassword = localStorage.getItem('app_password') || '';
        let isFirstSetup = false;

        const dom = {
            currentDate: document.getElementById('currentDate'),
            eventName: document.querySelector('.event-name'),
            eventDate: document.querySelector('.event-date'),
            colorPicker: document.querySelector('.color-picker'),
            addEventBtn: document.getElementById('addEventBtn'),
            shortcutBtns: document.querySelectorAll('.shortcut-btn'),
            eventList: document.getElementById('eventList'),
            menuBtn: document.getElementById('menuBtn'),
            sideMenu: document.getElementById('sideMenu'),
            passwordSwitch: document.getElementById('passwordSwitch'),
            passwordModal: document.getElementById('passwordModal'),
            passwordModalTitle: document.getElementById('passwordModalTitle'),
            passwordInput: document.getElementById('passwordInput'),
            passwordError: document.getElementById('passwordError'),
            passwordConfirmBtn: document.getElementById('passwordConfirmBtn'),
            passwordCancelBtn: document.getElementById('passwordCancelBtn'),
            appContainer: document.getElementById('appContainer'),
            eventDetailPage: document.getElementById('eventDetailPage'),
            closeDetailBtn: document.getElementById('closeDetailBtn'),
            countdownCard: document.getElementById('countdownCard'),
            detailEventName: document.getElementById('detailEventName'),
            detailStatus: document.getElementById('detailStatus'),
            detailCountdownDays: document.getElementById('detailCountdownDays'),
            detailTargetDate: document.getElementById('detailTargetDate'),
            detailNotesList: document.getElementById('detailNotesList'),
            detailNewNoteInput: document.getElementById('detailNewNoteInput'),
            detailAddNoteBtn: document.getElementById('detailAddNoteBtn')
        };

        document.addEventListener('DOMContentLoaded', init);

        function init() {
            initPasswordLogic();
            updateCurrentDate();
            setInterval(updateCurrentDate, 1000);
            updateTimeBackground();
            setInterval(updateTimeBackground, 60 * 1000);
            dom.passwordSwitch.checked = passwordEnabled;
            renderEvents();
            bindEvents();
            bindMenuEvents();
            bindDetailPageEvents();
        }

        function initPasswordLogic() {
            if (passwordEnabled) {
                if (appPassword) {
                    showPasswordModal('请输入开屏密码', false);
                } else {
                    isFirstSetup = true;
                    showPasswordModal('请设置开屏密码', true);
                }
            } else {
                showAppContainer();
            }
        }

        function showPasswordModal(title, isSetup) {
            dom.passwordModalTitle.textContent = title;
            dom.passwordInput.value = '';
            dom.passwordError.classList.remove('active');
            dom.passwordModal.classList.add('active');
            dom.passwordCancelBtn.style.display = isSetup ? 'block' : 'none';
            dom.passwordInput.focus();
        }

        function verifyPassword(password) {
            return password === appPassword;
        }

        function setNewPassword(password) {
            appPassword = password;
            localStorage.setItem('app_password', appPassword);
            passwordEnabled = true;
            dom.passwordSwitch.checked = true;
            localStorage.setItem('password_enabled', JSON.stringify(passwordEnabled));
            showAppContainer();
        }

        function showAppContainer() {
            dom.appContainer.style.display = 'block';
            dom.passwordModal.classList.remove('active');
        }

        function bindMenuEvents() {
            dom.menuBtn.addEventListener('click', () => {
                dom.sideMenu.classList.toggle('active');
            });

            document.addEventListener('click', (e) => {
                if (!dom.menuBtn.contains(e.target) && !dom.sideMenu.contains(e.target)) {
                    dom.sideMenu.classList.remove('active');
                }
            });

            dom.passwordSwitch.addEventListener('change', (e) => {
                passwordEnabled = e.target.checked;
                if (passwordEnabled) {
                    if (appPassword) {
                        localStorage.setItem('password_enabled', JSON.stringify(true));
                    } else {
                        isFirstSetup = true;
                        showPasswordModal('请设置开屏密码', true);
                    }
                } else {
                    if (appPassword) {
                        showPasswordModal('请输入当前密码以关闭保护', false);
                        dom.passwordSwitch.checked = true;
                    } else {
                        localStorage.setItem('password_enabled', JSON.stringify(false));
                    }
                }
            });

            dom.passwordConfirmBtn.addEventListener('click', () => {
                const password = dom.passwordInput.value.trim();
                if (!password) {
                    alert('密码不能为空！');
                    return;
                }

                if (isFirstSetup) {
                    setNewPassword(password);
                    isFirstSetup = false;
                } else {
                    if (dom.passwordModalTitle.textContent === '请输入当前密码以关闭保护') {
                        if (verifyPassword(password)) {
                            passwordEnabled = false;
                            appPassword = '';
                            localStorage.setItem('password_enabled', JSON.stringify(false));
                            localStorage.removeItem('app_password');
                            dom.passwordSwitch.checked = false;
                            showAppContainer();
                        } else {
                            dom.passwordError.classList.add('active');
                        }
                    } else {
                        if (verifyPassword(password)) {
                            showAppContainer();
                        } else {
                            dom.passwordError.classList.add('active');
                        }
                    }
                }
            });

            dom.passwordCancelBtn.addEventListener('click', () => {
                passwordEnabled = false;
                dom.passwordSwitch.checked = false;
                localStorage.setItem('password_enabled', JSON.stringify(false));
                dom.passwordModal.classList.remove('active');
                showAppContainer();
            });
        }

        function updateCurrentDate() {
            const now = new Date();
            const year = now.getFullYear();
            const month = String(now.getMonth() + 1).padStart(2, '0');
            const day = String(now.getDate()).padStart(2, '0');
            const weekDays = ['星期日', '星期一', '星期二', '星期三', '星期四', '星期五', '星期六'];
            const weekDay = weekDays[now.getDay()];
            const hours = String(now.getHours()).padStart(2, '0');
            const minutes = String(now.getMinutes()).padStart(2, '0');
            const seconds = String(now.getSeconds()).padStart(2, '0');
            dom.currentDate.textContent = `${year}-${month}-${day} ${weekDay} ${hours}:${minutes}:${seconds}`;
        }

        function getCurrentTimePeriod() {
            const hour = new Date().getHours();
            if (hour >= 0 && hour < 6) return 'dawn';
            if (hour >= 6 && hour < 9) return 'morning';
            if (hour >= 9 && hour < 12) return 'forenoon';
            if (hour >= 12 && hour < 14) return 'noon';
            if (hour >= 14 && hour < 18) return 'afternoon';
            return 'night';
        }

        function updateTimeBackground() {
            const currentPeriod = getCurrentTimePeriod();
            document.body.classList.remove('dawn', 'morning', 'forenoon', 'noon', 'afternoon', 'night');
            document.body.classList.add(currentPeriod);
        }

        // 核心：修改getDayDiff函数，返回天数和状态（还有/已经）
        function getDayDiff(targetDateStr) {
            const today = new Date();
            today.setHours(0, 0, 0, 0);
            const target = new Date(targetDateStr);
            target.setHours(0, 0, 0, 0);
            const diffMs = target - today;
            const diffDays = Math.ceil(diffMs / (1000 * 60 * 60 * 24));
            let status = '还有';
            if (diffDays < 0) {
                status = '已经';
            } else if (diffDays === 0) {
                status = '就是';
                return { days: '今天', status: status };
            }
            return { days: `${Math.abs(diffDays)}天`, status: status };
        }

        // 修复删除按钮显示 + 功能
        function renderEvents() {
            if (events.length === 0) {
                dom.eventList.innerHTML = `
                    <div class="empty-state">
                        <div class="empty-icon">📅</div>
                        <div class="empty-text">暂无事件，添加一个开始记录吧</div>
                    </div>
                `;
                return;
            }

            dom.eventList.innerHTML = '';
            events.forEach((event, index) => {
                const diffObj = getDayDiff(event.date);
                const card = document.createElement('div');
                card.className = 'event-card';
                card.innerHTML = `
                    <div class="card-header" style="background-color: ${event.color}">
                        <div class="card-name">${event.name}</div>
                        <div class="card-days">${diffObj.days}</div>
                    </div>
                    <div class="card-body">
                        <span class="card-date-label">目标日期</span>
                        <div class="card-date">${event.date}</div>
                    </div>
                    <div class="card-footer">
                        <span class="card-note-count">📝 ${event.notes.length} 条笔记</span>
                        <span class="card-delete-btn" data-index="${index}">删除事件</span>
                    </div>
                `;
                // 点击卡片进入详情
                card.addEventListener('click', (e) => {
                    if (!e.target.classList.contains('card-delete-btn')) {
                        currentEvent = event;
                        openEventDetailPage();
                    }
                });
                // 点击删除按钮删除事件
                const deleteBtn = card.querySelector('.card-delete-btn');
                deleteBtn.addEventListener('click', (e) => {
                    e.stopPropagation();
                    const idx = parseInt(e.target.dataset.index);
                    if (confirm('确定要删除这个事件吗？')) {
                        events.splice(idx, 1);
                        saveToLocal();
                        renderEvents();
                    }
                });
                dom.eventList.appendChild(card);
            });
        }

        function addNewEvent() {
            const name = dom.eventName.value.trim();
            const date = dom.eventDate.value.trim();
            const color = dom.colorPicker.value;
            if (!name || !date) {
                alert('请填写事件名称和选择日期！');
                return;
            }
            const newEvent = {
                id: Date.now().toString(),
                name: name,
                date: date,
                color: color,
                notes: []
            };
            events.push(newEvent);
            saveToLocal();
            renderEvents();
            dom.eventName.value = '';
            dom.eventDate.value = '';
            dom.colorPicker.value = '#6366f1';
        }

        function addShortcutEvent(btn) {
            const newEvent = {
                id: Date.now().toString(),
                name: btn.dataset.name,
                date: btn.dataset.date,
                color: btn.dataset.color,
                notes: []
            };
            events.push(newEvent);
            saveToLocal();
            renderEvents();
        }

        // 核心：动态切换“还有/已经”状态
        function openEventDetailPage() {
            if (!currentEvent) return;
            const diffObj = getDayDiff(currentEvent.date);
            dom.detailEventName.textContent = currentEvent.name;
            dom.detailStatus.textContent = diffObj.status;
            dom.detailCountdownDays.textContent = diffObj.days;
            const dateArr = currentEvent.date.split('-');
            const formatDate = `目标日: ${dateArr[0]}年${dateArr[1]}月${dateArr[2]}日`;
            dom.detailTargetDate.textContent = formatDate;
            dom.countdownCard.style.borderColor = currentEvent.color;
            dom.countdownCard.style.boxShadow = `0 4px 12px rgba(${hexToRgb(currentEvent.color).join(',')}, 0.15)`;
            renderDetailNotes();
            dom.eventDetailPage.classList.add('active');
            dom.appContainer.style.display = 'none';
        }

        function hexToRgb(hex) {
            hex = hex.replace('#', '');
            return [
                parseInt(hex.substring(0, 2), 16),
                parseInt(hex.substring(2, 4), 16),
                parseInt(hex.substring(4, 6), 16)
            ];
        }

        function closeEventDetailPage() {
            dom.eventDetailPage.classList.remove('active');
            dom.appContainer.style.display = 'block';
            currentEvent = null;
            dom.detailAddNoteBtn.textContent = '添加笔记';
            delete dom.detailAddNoteBtn.dataset.editIndex;
            dom.detailNewNoteInput.value = '';
        }

        function renderDetailNotes() {
            if (!currentEvent || currentEvent.notes.length === 0) {
                dom.detailNotesList.innerHTML = `
                    <div class="empty-text">暂无笔记，点击下方输入框添加 📝</div>
                `;
                return;
            }

            dom.detailNotesList.innerHTML = '';
            currentEvent.notes.forEach((note, noteIndex) => {
                const noteItem = document.createElement('div');
                noteItem.className = 'note-item';
                noteItem.innerHTML = `
                    <div class="note-content">${note.content}</div>
                    <div class="note-meta">
                        <span>笔记日期: ${note.createTime}</span>
                        <div>
                            <span class="note-edit-btn" data-index="${noteIndex}">修改</span>
                            <span class="note-delete-btn" data-index="${noteIndex}">删除</span>
                        </div>
                    </div>
                `;
                noteItem.querySelector('.note-delete-btn').addEventListener('click', (e) => {
                    const noteIndex = parseInt(e.target.dataset.index);
                    if (confirm('确定删除这条笔记吗？')) {
                        currentEvent.notes.splice(noteIndex, 1);
                        saveToLocal();
                        renderDetailNotes();
                        renderEvents();
                    }
                });
                noteItem.querySelector('.note-edit-btn').addEventListener('click', (e) => {
                    const noteIndex = parseInt(e.target.dataset.index);
                    const note = currentEvent.notes[noteIndex];
                    dom.detailNewNoteInput.value = note.content;
                    dom.detailAddNoteBtn.textContent = '修改笔记';
                    dom.detailAddNoteBtn.dataset.editIndex = noteIndex;
                });
                dom.detailNotesList.appendChild(noteItem);
            });
        }

        function handleAddOrEditNote() {
            if (!currentEvent) return;
            const content = dom.detailNewNoteInput.value.trim();
            if (!content) {
                alert('笔记内容不能为空！');
                return;
            }
            const editIndex = dom.detailAddNoteBtn.dataset.editIndex;
            if (editIndex !== undefined) {
                currentEvent.notes[editIndex].content = content;
                currentEvent.notes[editIndex].createTime = new Date().toLocaleString();
                dom.detailAddNoteBtn.textContent = '添加笔记';
                delete dom.detailAddNoteBtn.dataset.editIndex;
            } else {
                const newNote = {
                    id: Date.now().toString(),
                    content: content,
                    createTime: new Date().toLocaleString()
                };
                currentEvent.notes.push(newNote);
            }
            saveToLocal();
            renderDetailNotes();
            dom.detailNewNoteInput.value = '';
            renderEvents();
        }

        function bindDetailPageEvents() {
            dom.closeDetailBtn.addEventListener('click', closeEventDetailPage);
            dom.detailAddNoteBtn.addEventListener('click', handleAddOrEditNote);
        }

        function saveToLocal() {
            localStorage.setItem('countdown_events', JSON.stringify(events));
        }

        function bindEvents() {
            dom.addEventBtn.addEventListener('click', addNewEvent);
            dom.shortcutBtns.forEach(btn => {
                btn.addEventListener('click', () => addShortcutEvent(btn));
            });
        }
    </script>
</body>
</html>
