<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SmartOasis - Plateforme d'Irrigation Intelligente</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.9.1/chart.min.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif;
            background: #f8fafc;
            color: #1e293b;
            line-height: 1.6;
        }

        /* ===== HEADER ===== */
        .header {
            background: white;
            border-bottom: 1px solid #e2e8f0;
            padding: 0 2rem;
            height: 70px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            position: fixed !important;
            top: 0 !important;
            left: 0 !important;
            right: 0 !important;
            width: 100% !important;
            z-index: 1000 !important;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .logo-icon {
            width: 40px;
            height: 40px;
        }

        .smartoasis-logo {
            width: 100%;
            height: 100%;
        }

        .logo-text h1 {
            font-size: 1.5rem;
            color: #0f172a;
            font-weight: 600;
        }

        .logo-text p {
            font-size: 0.875rem;
            color: #64748b;
        }

        .user-section {
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .user-info {
            text-align: right;
        }

        .user-name {
            font-weight: 600;
            font-size: 0.875rem;
        }

        .user-role {
            font-size: 0.75rem;
            color: #64748b;
        }

        .user-avatar {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: linear-gradient(135deg, #22c55e, #16a34a);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: 600;
        }

        /* ===== LAYOUT ===== */
        .main-container {
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            padding-top: 70px; /* Espace pour le header fixe */
        }

        .top-navigation {
            background: white;
            border-bottom: 1px solid #e2e8f0;
            padding: 0 2rem;
            position: fixed !important;
            top: 70px !important;
            left: 0 !important;
            right: 0 !important;
            width: 100% !important;
            z-index: 999 !important;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .nav-menu {
            list-style: none !important;
            display: flex !important;
            gap: 0 !important;
            margin: 0 !important;
            padding: 0 !important;
            position: static !important;
        }

        .nav-item {
            margin: 0 !important;
            position: static !important;
        }

        .nav-link {
            display: flex !important;
            align-items: center !important;
            gap: 12px !important;
            padding: 16px 24px !important;
            color: #64748b !important;
            text-decoration: none !important;
            font-weight: 500 !important;
            transition: all 0.2s !important;
            cursor: pointer !important;
            border-bottom: 3px solid transparent !important;
            position: static !important;
        }

        .nav-link:hover {
            background: #f8fafc !important;
            color: #0f172a !important;
        }

        .nav-link.active {
            color: #22c55e !important;
            border-bottom-color: #22c55e !important;
            background: #f0fdf4 !important;
        }

        .nav-icon {
            width: 20px !important;
            height: 20px !important;
        }

        .content-wrapper {
            display: flex;
            flex: 1;
            padding-top: 60px; /* Espace pour la navigation fixe */
        }

        .sidebar {
            display: none;
        }

        .content-area {
            flex: 1;
            padding: 2rem;
            overflow-y: auto;
        }

        /* ===== DASHBOARD COMPONENTS ===== */
        .page-header {
            margin-bottom: 2rem;
        }

        .page-title {
            font-size: 1.875rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
        }

        .page-subtitle {
            color: #64748b;
        }

        .metrics-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-bottom: 2rem;
        }

        .metric-card {
            background: white;
            padding: 1.5rem;
            border-radius: 12px;
            border: 1px solid #e2e8f0;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }

        .metric-header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 1rem;
        }

        .metric-title {
            font-size: 0.875rem;
            color: #64748b;
            font-weight: 500;
        }

        .metric-icon {
            width: 24px;
            height: 24px;
            color: #22c55e;
        }

        .metric-value {
            font-size: 2rem;
            font-weight: 700;
            color: #0f172a;
        }

        .metric-change {
            font-size: 0.875rem;
            margin-top: 0.25rem;
        }

        .metric-change.positive {
            color: #22c55e;
        }

        .metric-change.negative {
            color: #ef4444;
        }

        /* ===== CONTENT SECTIONS ===== */
        .content-grid {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .card {
            background: white;
            border-radius: 12px;
            border: 1px solid #e2e8f0;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }

        .card-header {
            padding: 1.5rem 1.5rem 1rem 1.5rem;
            border-bottom: 1px solid #f1f5f9;
        }

        .card-title {
            font-size: 1.125rem;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .card-content {
            padding: 1.5rem;
        }

        .chart-container {
            position: relative;
            height: 300px;
        }

        /* ===== FARM COMPONENTS ===== */
        .farms-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 1.5rem;
        }

        .farm-card {
            background: white;
            border-radius: 12px;
            border: 1px solid #e2e8f0;
            overflow: hidden;
            transition: all 0.2s;
        }

        .farm-card:hover {
            border-color: #22c55e;
            box-shadow: 0 4px 12px rgba(34,197,94,0.15);
        }

        .farm-header {
            padding: 1.5rem;
            border-bottom: 1px solid #f1f5f9;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .farm-info {
            flex: 1;
        }

        .farm-name {
            font-size: 1.125rem;
            font-weight: 600;
            margin-bottom: 0.25rem;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .farm-details {
            font-size: 0.875rem;
            color: #64748b;
        }

        .status-badge {
            padding: 0.25rem 0.75rem;
            border-radius: 9999px;
            font-size: 0.75rem;
            font-weight: 600;
            text-transform: uppercase;
        }

        .status-optimal {
            background: #dcfce7;
            color: #166534;
        }

        .status-warning {
            background: #fef3c7;
            color: #92400e;
        }

        .status-critical {
            background: #fee2e2;
            color: #991b1b;
        }

        .sensor-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 1rem;
            padding: 1.5rem;
        }

        .sensor-item {
            text-align: center;
            padding: 1rem;
            background: #f8fafc;
            border-radius: 8px;
        }

        .sensor-value {
            font-size: 1.5rem;
            font-weight: 700;
            color: #0f172a;
        }

        .sensor-label {
            font-size: 0.75rem;
            color: #64748b;
            margin-top: 0.25rem;
        }

        .recommendation-section {
            padding: 1.5rem;
            background: #eff6ff;
            border-top: 1px solid #f1f5f9;
        }

        .recommendation-header {
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 600;
            color: #1d4ed8;
            margin-bottom: 0.75rem;
        }

        .recommendation-text {
            font-size: 0.875rem;
            color: #64748b;
            margin-bottom: 1rem;
        }

        .action-buttons {
            display: flex;
            gap: 0.75rem;
        }

        .btn {
            padding: 0.5rem 1rem;
            border-radius: 6px;
            font-size: 0.875rem;
            font-weight: 500;
            border: none;
            cursor: pointer;
            transition: all 0.2s;
            display: flex;
            align-items: center;
            gap: 6px;
        }

        .btn-primary {
            background: #22c55e;
            color: white;
        }

        .btn-primary:hover {
            background: #16a34a;
        }

        .btn-secondary {
            background: #f1f5f9;
            color: #64748b;
        }

        .btn-secondary:hover {
            background: #e2e8f0;
            color: #0f172a;
        }

        .btn-icon {
            width: 16px;
            height: 16px;
        }

        /* ===== ALERTS ===== */
        .alerts-section {
            space-y: 1rem;
        }

        .alert {
            padding: 1rem;
            border-radius: 8px;
            border-left: 4px solid;
            display: flex;
            align-items: start;
            gap: 12px;
        }

        .alert-critical {
            background: #fee2e2;
            border-color: #ef4444;
        }

        .alert-warning {
            background: #fef3c7;
            border-color: #f59e0b;
        }

        .alert-info {
            background: #dbeafe;
            border-color: #3b82f6;
        }

        .alert-icon {
            width: 20px;
            height: 20px;
            margin-top: 2px;
        }

        .alert-content {
            flex: 1;
        }

        .alert-title {
            font-weight: 600;
            margin-bottom: 0.25rem;
        }

        .alert-description {
            font-size: 0.875rem;
            color: #64748b;
        }

        /* ===== MODAL ===== */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.5);
            z-index: 1000;
            align-items: center;
            justify-content: center;
        }

        .modal.active {
            display: flex;
        }

        .modal-content {
            background: white;
            border-radius: 12px;
            max-width: 500px;
            width: 90%;
            max-height: 90vh;
            overflow-y: auto;
        }

        .modal-header {
            padding: 1.5rem;
            border-bottom: 1px solid #e2e8f0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .modal-title {
            font-size: 1.25rem;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .modal-close {
            background: none;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: #64748b;
        }

        .modal-body {
            padding: 1.5rem;
        }

        /* ===== FORM ELEMENTS ===== */
        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-label {
            display: block;
            font-weight: 500;
            margin-bottom: 0.5rem;
            color: #374151;
        }

        .form-input, .form-select {
            width: 100%;
            padding: 0.75rem;
            border: 1px solid #d1d5db;
            border-radius: 6px;
            font-size: 0.875rem;
        }

        .form-input:focus, .form-select:focus {
            outline: none;
            border-color: #22c55e;
            box-shadow: 0 0 0 3px rgba(34,197,94,0.1);
        }

        .form-range {
            width: 100%;
            margin: 0.5rem 0;
        }

        .range-value {
            text-align: center;
            font-weight: 600;
            color: #22c55e;
            margin-top: 0.5rem;
        }

        .hidden {
            display: none !important;
        }

        .text-center {
            text-align: center;
        }

        .text-success {
            color: #22c55e;
        }

        .text-warning {
            color: #f59e0b;
        }

        .text-danger {
            color: #ef4444;
        }

        .mb-4 {
            margin-bottom: 1rem;
        }

        .notification {
            position: fixed;
            top: 20px;
            right: 20px;
            background: white;
            padding: 1rem 1.5rem;
            border-radius: 8px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
            border-left: 4px solid #22c55e;
            transform: translateX(400px);
            transition: all 0.3s ease;
            z-index: 1001;
        }

        .notification.show {
            transform: translateX(0);
        }

        .notification.success {
            border-left-color: #22c55e;
        }

        .notification.error {
            border-left-color: #ef4444;
        }

        .notification.info {
            border-left-color: #3b82f6;
        }

        .notification.warning {
            border-left-color: #f59e0b;
        }

        /* ===== MANUAL IRRIGATION CONTROLS ===== */
        .manual-control-section {
            padding: 1.5rem;
            background: #f8fafc;
            border-top: 1px solid #f1f5f9;
        }

        .control-header {
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 600;
            color: #0f172a;
            margin-bottom: 1rem;
        }

        .manual-controls {
            display: grid;
            gap: 1rem;
            margin-bottom: 1.5rem;
        }

        .control-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .control-label {
            font-weight: 500;
            color: #374151;
            font-size: 0.875rem;
        }

        .control-input-group {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .control-input {
            width: 80px;
            padding: 0.5rem;
            border: 1px solid #d1d5db;
            border-radius: 6px;
            font-size: 0.875rem;
            text-align: center;
        }

        .control-input:focus {
            outline: none;
            border-color: #22c55e;
            box-shadow: 0 0 0 3px rgba(34,197,94,0.1);
        }

        .control-select {
            width: 120px;
            padding: 0.5rem;
            border: 1px solid #d1d5db;
            border-radius: 6px;
            font-size: 0.875rem;
        }

        .control-select:focus {
            outline: none;
            border-color: #22c55e;
            box-shadow: 0 0 0 3px rgba(34,197,94,0.1);
        }

        .control-unit {
            font-size: 0.75rem;
            color: #64748b;
            font-weight: 500;
        }

        .irrigation-summary {
            background: white;
            padding: 1rem;
            border-radius: 8px;
            border: 1px solid #e2e8f0;
            margin-bottom: 1rem;
        }

        .summary-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0.25rem 0;
        }

        .summary-label {
            font-size: 0.875rem;
            color: #64748b;
        }

        .summary-value {
            font-weight: 600;
            color: #0f172a;
        }

        /* ===== IRRIGATION HISTORY ===== */
        .irrigation-history-item {
            background: white;
            padding: 1rem;
            border-radius: 8px;
            border: 1px solid #e2e8f0;
        }

        .history-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 0.5rem;
        }

        .history-farm {
            font-weight: 600;
            color: #0f172a;
        }

        .history-date {
            font-size: 0.75rem;
            color: #64748b;
        }

        .history-details {
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 0.875rem;
            color: #64748b;
        }

        .history-status {
            padding: 0.25rem 0.5rem;
            border-radius: 4px;
            font-size: 0.75rem;
            font-weight: 500;
        }

        .history-status.completed {
            background: #dcfce7;
            color: #166534;
        }

        .history-status.running {
            background: #dbeafe;
            color: #1e40af;
        }

        .history-status.scheduled {
            background: #fef3c7;
            color: #92400e;
        }
        .toggle-switch {
            position: relative;
            display: inline-block;
            width: 44px;
            height: 24px;
        }

        .toggle-switch input {
            opacity: 0;
            width: 0;
            height: 0;
        }

        .toggle-slider {
            position: absolute;
            cursor: pointer;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: #e2e8f0;
            transition: .4s;
            border-radius: 24px;
        }

        .toggle-slider:before {
            position: absolute;
            content: "";
            height: 18px;
            width: 18px;
            left: 3px;
            bottom: 3px;
            background-color: white;
            transition: .4s;
            border-radius: 50%;
            box-shadow: 0 2px 4px rgba(0,0,0,0.2);
        }

        input:checked + .toggle-slider {
            background-color: #22c55e;
        }

        input:checked + .toggle-slider:before {
            transform: translateX(20px);
        }

        /* ===== RESPONSIVE ===== */
        @media (max-width: 1024px) {
            .content-grid {
                grid-template-columns: 1fr;
            }
            
            .metrics-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media (max-width: 768px) {
            .main-container {
                flex-direction: column;
            }
            
            .sidebar {
                width: 100%;
                padding: 1rem 0;
            }
            
            .nav-menu {
                display: flex;
                overflow-x: auto;
                padding: 0 1rem;
            }
            
            .nav-item {
                margin: 0 0.25rem;
                white-space: nowrap;
            }
            
            .metrics-grid {
                grid-template-columns: 1fr;
            }
            
            .farms-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="logo">
            <div class="logo-icon">
                <svg class="smartoasis-logo" viewBox="0 0 200 240" xmlns="http://www.w3.org/2000/svg">
                    <defs>
                        <linearGradient id="waterGradient" x1="0%" y1="0%" x2="0%" y2="100%">
                            <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:1" />
                            <stop offset="100%" style="stop-color:#22c55e;stop-opacity:1" />
                        </linearGradient>
                    </defs>
                    <path d="M100 20 C60 60, 40 100, 40 140 C40 180, 65 210, 100 210 C135 210, 160 180, 160 140 C160 100, 140 60, 100 20 Z" 
                          fill="url(#waterGradient)" stroke="#3b82f6" stroke-width="3"/>
                    <circle cx="100" cy="110" r="5" fill="white"/>
                    <path d="M85 100 Q100 85, 115 100" fill="none" stroke="white" stroke-width="3" stroke-linecap="round"/>
                    <path d="M75 110 Q100 75, 125 110" fill="none" stroke="white" stroke-width="2" stroke-linecap="round"/>
                    <path d="M85 140 Q70 150, 75 165 Q85 175, 95 165 Q90 150, 85 140" fill="#16a34a"/>
                    <path d="M115 140 Q130 150, 125 165 Q115 175, 105 165 Q110 150, 115 140" fill="#22c55e"/>
                    <path d="M100 165 L100 185" stroke="#22c55e" stroke-width="3" stroke-linecap="round"/>
                </svg>
            </div>
            <div class="logo-text">
                <h1>SmartOasis</h1>
                <p>Irrigation Intelligente - Errachidia, Maroc</p>
            </div>
        </div>
        <div class="user-section">
            <div class="user-info">
                <div class="user-name">Ahmed Benali</div>
                <div class="user-role">Coopérative Agricole Oasis</div>
            </div>
            <div class="user-avatar">AB</div>
        </div>
    </header>

    <!-- Navigation fixe en haut -->
    <nav class="top-navigation">
        <ul class="nav-menu">
            <li class="nav-item">
                <a class="nav-link active" onclick="showPage('dashboard')">
                    <svg class="nav-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <rect x="3" y="3" width="7" height="7"/>
                        <rect x="14" y="3" width="7" height="7"/>
                        <rect x="14" y="14" width="7" height="7"/>
                        <rect x="3" y="14" width="7" height="7"/>
                    </svg>
                    Tableau de Bord
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" onclick="showPage('farms')">
                    <svg class="nav-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="m3 21 18 0"/>
                        <path d="m5 21-2-4 9-9h5l4-4"/>
                        <path d="m9 21 0-7"/>
                        <path d="m13 21 0-7"/>
                        <path d="m17 21 0-7"/>
                    </svg>
                    Exploitations
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" onclick="showPage('analytics')">
                    <svg class="nav-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M3 3v18h18"/>
                        <path d="m19 9-5 5-4-4-3 3"/>
                    </svg>
                    Analyses
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" onclick="showPage('irrigation')">
                    <svg class="nav-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M8 16a6 6 0 0 0 6-6c0-1.655-1.122-2.904-2.432-4.362C10.254 4.176 8.75 2.503 8 0c0 0-6 5.686-6 10a6 6 0 0 0 6 6Z"/>
                        <circle cx="7" cy="20" r="1"/>
                        <circle cx="11" cy="20" r="1"/>
                        <circle cx="15" cy="20" r="1"/>
                    </svg>
                    Irrigation
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" onclick="showPage('alerts')">
                    <svg class="nav-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M6 8a6 6 0 0 1 12 0c0 7 3 9 3 9H3s3-2 3-9"/>
                        <path d="m13.73 21a2 2 0 0 1-3.46 0"/>
                    </svg>
                    Notifications
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" onclick="showPage('settings')">
                    <svg class="nav-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 20a8 8 0 1 0 0-16 8 8 0 0 0 0 16Z"/>
                        <path d="M12 14a2 2 0 1 0 0-4 2 2 0 0 0 0 4Z"/>
                        <path d="M12 2v2"/>
                        <path d="M12 20v2"/>
                        <path d="m4.93 4.93 1.41 1.41"/>
                        <path d="m17.66 17.66 1.41 1.41"/>
                        <path d="M2 12h2"/>
                        <path d="M20 12h2"/>
                        <path d="m6.34 17.66-1.41 1.41"/>
                        <path d="m19.07 4.93-1.41 1.41"/>
                    </svg>
                    Configuration
                </a>
            </li>
        </ul>
    </nav>

    <!-- Main Container -->
    <div class="main-container">
        <!-- Content Area -->
        <div class="content-wrapper">
            <main class="content-area">
                <!-- Dashboard Page -->
                <div id="dashboard-page" class="page-content">
                    <div class="page-header">
                        <h1 class="page-title">Tableau de Bord</h1>
                        <p class="page-subtitle">Vue d'ensemble de vos exploitations agricoles</p>
                    </div>

                    <!-- Metrics -->
                    <div class="metrics-grid">
                        <div class="metric-card">
                            <div class="metric-header">
                                <span class="metric-title">Eau Économisée</span>
                                <svg class="metric-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M8 16a6 6 0 0 0 6-6c0-1.655-1.122-2.904-2.432-4.362C10.254 4.176 8.75 2.503 8 0c0 0-6 5.686-6 10a6 6 0 0 0 6 6Z"/>
                                </svg>
                            </div>
                            <div class="metric-value">1,250L</div>
                            <div class="metric-change positive">+32% ce mois</div>
                        </div>

                        <div class="metric-card">
                            <div class="metric-header">
                                <span class="metric-title">Efficacité</span>
                                <svg class="metric-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M3 3v18h18"/>
                                    <path d="m19 9-5 5-4-4-3 3"/>
                                </svg>
                            </div>
                            <div class="metric-value">98%</div>
                            <div class="metric-change positive">+5% cette semaine</div>
                        </div>

                        <div class="metric-card">
                            <div class="metric-header">
                                <span class="metric-title">Alertes Actives</span>
                                <svg class="metric-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3Z"/>
                                    <path d="M12 9v4"/>
                                    <path d="M12 17h.01"/>
                                </svg>
                            </div>
                            <div class="metric-value">3</div>
                            <div class="metric-change negative">2 critiques</div>
                        </div>

                        <div class="metric-card">
                            <div class="metric-header">
                                <span class="metric-title">Irrigations</span>
                                <svg class="metric-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <circle cx="12" cy="12" r="3"/>
                                    <path d="m12 1 0 6m0 6 0 6m11-7-6 0m-6 0-6 0"/>
                                </svg>
                            </div>
                            <div class="metric-value">24</div>
                            <div class="metric-change positive">Cette semaine</div>
                        </div>
                    </div>

                    <!-- Main Content Grid -->
                    <div class="content-grid">
                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <path d="M3 3v18h18"/>
                                        <path d="m19 9-5 5-4-4-3 3"/>
                                    </svg>
                                    Tendances d'Irrigation
                                </h3>
                            </div>
                            <div class="card-content">
                                <div class="chart-container">
                                    <canvas id="trendsChart"></canvas>
                                </div>
                            </div>
                        </div>

                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3Z"/>
                                        <path d="M12 9v4"/>
                                        <path d="M12 17h.01"/>
                                    </svg>
                                    Alertes Récentes
                                </h3>
                            </div>
                            <div class="card-content">
                                <div class="alerts-section">
                                    <div class="alert alert-critical">
                                        <svg class="alert-icon" viewBox="0 0 24 24" fill="none" stroke="#ef4444" stroke-width="2">
                                            <path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3Z"/>
                                            <path d="M12 9v4"/>
                                            <path d="M12 17h.01"/>
                                        </svg>
                                        <div class="alert-content">
                                            <div class="alert-title">Humidité critique</div>
                                            <div class="alert-description">Ferme Oasis Nord - Il y a 15 min</div>
                                        </div>
                                    </div>

                                    <div class="alert alert-warning">
                                        <svg class="alert-icon" viewBox="0 0 24 24" fill="none" stroke="#f59e0b" stroke-width="2">
                                            <path d="M14 4v10.54a4 4 0 1 1-4 0V4a2 2 0 0 1 4 0Z"/>
                                            <circle cx="12" cy="17" r="1"/>
                                        </svg>
                                        <div class="alert-content">
                                            <div class="alert-title">Température élevée</div>
                                            <div class="alert-description">34°C détectée - Il y a 1h</div>
                                        </div>
                                    </div>

                                    <div class="alert alert-info">
                                        <svg class="alert-icon" viewBox="0 0 24 24" fill="none" stroke="#3b82f6" stroke-width="2">
                                            <path d="M8 2v4"/>
                                            <path d="M16 2v4"/>
                                            <rect x="3" y="4" width="18" height="18" rx="2"/>
                                            <path d="M3 10h18"/>
                                        </svg>
                                        <div class="alert-content">
                                            <div class="alert-title">Irrigation programmée</div>
                                            <div class="alert-description">Demain 06:00 - Ferme Oliviers</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Farms Page -->
                <div id="farms-page" class="page-content hidden">
                    <div class="page-header">
                        <h1 class="page-title">Exploitations Agricoles</h1>
                        <p class="page-subtitle">Gestion et surveillance de vos fermes</p>
                    </div>

                    <div class="farms-grid">
                        <div class="farm-card">
                            <div class="farm-header">
                                <div class="farm-info">
                                    <div class="farm-name">
                                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#22c55e" stroke-width="2">
                                            <path d="m3 21 18 0"/>
                                            <path d="m5 21-2-4 9-9h5l4-4"/>
                                            <path d="m9 21 0-7"/>
                                            <path d="m13 21 0-7"/>
                                            <path d="m17 21 0-7"/>
                                        </svg>
                                        Ferme Oasis Nord
                                    </div>
                                    <div class="farm-details">2.5 hectares • Palmiers Dattiers</div>
                                </div>
                                <div class="status-badge status-warning">Attention</div>
                            </div>

                            <div class="sensor-grid">
                                <div class="sensor-item">
                                    <div class="sensor-value">28%</div>
                                    <div class="sensor-label">Humidité Sol</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">31°C</div>
                                    <div class="sensor-label">Température</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">45%</div>
                                    <div class="sensor-label">Humidité Air</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">6.8</div>
                                    <div class="sensor-label">pH Sol</div>
                                </div>
                            </div>

                            <div class="recommendation-section">
                                <div class="recommendation-header">
                                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <rect x="2" y="3" width="20" height="14" rx="2" ry="2"/>
                                        <circle cx="8" cy="21" r="1"/>
                                        <circle cx="16" cy="21" r="1"/>
                                        <path d="M7 11h10"/>
                                        <path d="M7 7h4"/>
                                    </svg>
                                    Recommandation IA
                                </div>
                                <div class="recommendation-text">
                                    <strong>Irrigation recommandée</strong> - 25L/m² ce soir (18h-20h). 
                                    Température élevée détectée, palmiers dattiers nécessitent plus d'eau.
                                </div>
                                <div class="action-buttons">
                                    <button class="btn btn-primary" onclick="openIrrigationModal('farm1')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <path d="M8 16a6 6 0 0 0 6-6c0-1.655-1.122-2.904-2.432-4.362C10.254 4.176 8.75 2.503 8 0c0 0-6 5.686-6 10a6 6 0 0 0 6 6Z"/>
                                        </svg>
                                        Irriguer
                                    </button>
                                    <button class="btn btn-secondary" onclick="showFarmDetails('farm1')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <path d="M3 3v18h18"/>
                                            <path d="m19 9-5 5-4-4-3 3"/>
                                        </svg>
                                        Détails
                                    </button>
                                </div>
                            </div>
                        </div>

                        <div class="farm-card">
                            <div class="farm-header">
                                <div class="farm-info">
                                    <div class="farm-name">
                                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#22c55e" stroke-width="2">
                                            <path d="m3 21 18 0"/>
                                            <path d="m5 21-2-4 9-9h5l4-4"/>
                                            <path d="m9 21 0-7"/>
                                            <path d="m13 21 0-7"/>
                                            <path d="m17 21 0-7"/>
                                        </svg>
                                        Ferme Oliviers Sud
                                    </div>
                                    <div class="farm-details">1.7 hectares • Oliviers</div>
                                </div>
                                <div class="status-badge status-optimal">Optimal</div>
                            </div>

                            <div class="sensor-grid">
                                <div class="sensor-item">
                                    <div class="sensor-value">42%</div>
                                    <div class="sensor-label">Humidité Sol</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">29°C</div>
                                    <div class="sensor-label">Température</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">48%</div>
                                    <div class="sensor-label">Humidité Air</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">7.2</div>
                                    <div class="sensor-label">pH Sol</div>
                                </div>
                            </div>

                            <div class="recommendation-section" style="background: #f0fdf4;">
                                <div class="recommendation-header" style="color: #16a34a;">
                                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <path d="M9 12l2 2 4-4"/>
                                        <circle cx="12" cy="12" r="9"/>
                                    </svg>
                                    Conditions Optimales
                                </div>
                                <div class="recommendation-text">
                                    Aucune irrigation nécessaire. Les oliviers résistent bien à la sécheresse 
                                    et les conditions actuelles sont parfaites.
                                </div>
                                <div class="action-buttons">
                                    <button class="btn btn-secondary" onclick="showFarmDetails('farm2')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <path d="M3 3v18h18"/>
                                            <path d="m19 9-5 5-4-4-3 3"/>
                                        </svg>
                                        Voir Détails
                                    </button>
                                </div>
                            </div>
                        </div>

                        <div class="farm-card">
                            <div class="farm-header">
                                <div class="farm-info">
                                    <div class="farm-name">
                                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#22c55e" stroke-width="2">
                                            <path d="m3 21 18 0"/>
                                            <path d="m5 21-2-4 9-9h5l4-4"/>
                                            <path d="m9 21 0-7"/>
                                            <path d="m13 21 0-7"/>
                                            <path d="m17 21 0-7"/>
                                        </svg>
                                        Ferme Agrumes Est
                                    </div>
                                    <div class="farm-details">3.2 hectares • Agrumes</div>
                                </div>
                                <div class="status-badge status-optimal">Bon</div>
                            </div>

                            <div class="sensor-grid">
                                <div class="sensor-item">
                                    <div class="sensor-value">35%</div>
                                    <div class="sensor-label">Humidité Sol</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">30°C</div>
                                    <div class="sensor-label">Température</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">50%</div>
                                    <div class="sensor-label">Humidité Air</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">6.5</div>
                                    <div class="sensor-label">pH Sol</div>
                                </div>
                            </div>

                            <div class="recommendation-section">
                                <div class="recommendation-header">
                                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <circle cx="12" cy="12" r="10"/>
                                        <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"/>
                                        <path d="M12 17h.01"/>
                                    </svg>
                                    Surveillance Recommandée
                                </div>
                                <div class="recommendation-text">
                                    Irrigation dans 2-3 jours. Les conditions actuelles sont acceptables 
                                    pour les agrumes mais nécessitent une surveillance.
                                </div>
                                <div class="action-buttons">
                                    <button class="btn btn-secondary" onclick="openIrrigationModal('farm3')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <circle cx="12" cy="12" r="10"/>
                                            <polyline points="12,6 12,12 16,14"/>
                                        </svg>
                                        Programmer
                                    </button>
                                    <button class="btn btn-secondary" onclick="showFarmDetails('farm3')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <path d="M3 3v18h18"/>
                                            <path d="m19 9-5 5-4-4-3 3"/>
                                        </svg>
                                        Détails
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Analytics Page -->
                <div id="analytics-page" class="page-content hidden">
                    <div class="page-header">
                        <h1 class="page-title">Analyses & Rapports</h1>
                        <p class="page-subtitle">Performance et insights de vos exploitations</p>
                    </div>

                    <div class="content-grid">
                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <path d="M8 16a6 6 0 0 0 6-6c0-1.655-1.122-2.904-2.432-4.362C10.254 4.176 8.75 2.503 8 0c0 0-6 5.686-6 10a6 6 0 0 0 6 6Z"/>
                                    </svg>
                                    Consommation d'Eau
                                </h3>
                            </div>
                            <div class="card-content">
                                <div class="chart-container">
                                    <canvas id="waterChart"></canvas>
                                </div>
                            </div>
                        </div>

                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <path d="M14 4v10.54a4 4 0 1 1-4 0V4a2 2 0 0 1 4 0Z"/>
                                        <circle cx="12" cy="17" r="1"/>
                                    </svg>
                                    Conditions Climatiques
                                </h3>
                            </div>
                            <div class="card-content">
                                <div class="chart-container">
                                    <canvas id="climateChart"></canvas>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="card">
                        <div class="card-header">
                            <h3 class="card-title">
                                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <rect x="2" y="3" width="20" height="14" rx="2" ry="2"/>
                                    <circle cx="8" cy="21" r="1"/>
                                    <circle cx="16" cy="21" r="1"/>
                                    <path d="M7 11h10"/>
                                    <path d="M7 7h4"/>
                                </svg>
                                Insights IA SmartOasis
                            </h3>
                        </div>
                        <div class="card-content">
                            <div style="display: grid; gap: 1rem;">
                                <div style="background: #f0fdf4; padding: 1rem; border-radius: 8px; border-left: 4px solid #22c55e;">
                                    <strong>Économie d'eau</strong><br>
                                    <small>Vous avez économisé 32% d'eau ce mois-ci grâce aux recommandations IA.</small>
                                </div>
                                <div style="background: #eff6ff; padding: 1rem; border-radius: 8px; border-left: 4px solid #3b82f6;">
                                    <strong>Horaire optimal</strong><br>
                                    <small>Les irrigations entre 18h-20h montrent 25% plus d'efficacité.</small>
                                </div>
                                <div style="background: #fefce8; padding: 1rem; border-radius: 8px; border-left: 4px solid #eab308;">
                                    <strong>Optimisation cultures</strong><br>
                                    <small>Les palmiers dattiers bénéficient d'une irrigation ciblée le matin.</small>
                                </div>
                                <div style="background: #fdf4ff; padding: 1rem; border-radius: 8px; border-left: 4px solid #a855f7;">
                                    <strong>Prévision</strong><br>
                                    <small>Potentiel d'économie supplémentaire de 15% avec optimisation des horaires.</small>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Alerts Page -->
                <div id="alerts-page" class="page-content hidden">
                    <div class="page-header">
                        <h1 class="page-title">Centre de Notifications</h1>
                        <p class="page-subtitle">3 alertes actives nécessitent votre attention</p>
                    </div>

                    <div style="display: grid; gap: 2rem;">
                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title" style="color: #ef4444;">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3Z"/>
                                        <path d="M12 9v4"/>
                                        <path d="M12 17h.01"/>
                                    </svg>
                                    Alertes Critiques
                                </h3>
                            </div>
                            <div class="card-content">
                                <div class="alert alert-critical">
                                    <svg class="alert-icon" viewBox="0 0 24 24" fill="none" stroke="#ef4444" stroke-width="2">
                                        <path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3Z"/>
                                        <path d="M12 9v4"/>
                                        <path d="M12 17h.01"/>
                                    </svg>
                                    <div class="alert-content">
                                        <div class="alert-title">Humidité du sol critique</div>
                                        <div class="alert-description">
                                            Ferme Oasis Nord - Capteur S001 - Il y a 15 minutes<br>
                                            Humidité: 18% (Seuil critique: 20%)
                                        </div>
                                    </div>
                                    <div class="action-buttons">
                                        <button class="btn btn-primary" onclick="resolveAlert('alert1')">
                                            <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                                <path d="M8 16a6 6 0 0 0 6-6c0-1.655-1.122-2.904-2.432-4.362C10.254 4.176 8.75 2.503 8 0c0 0-6 5.686-6 10a6 6 0 0 0 6 6Z"/>
                                            </svg>
                                            Irriguer
                                        </button>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title" style="color: #f59e0b;">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3Z"/>
                                        <path d="M12 9v4"/>
                                        <path d="M12 17h.01"/>
                                    </svg>
                                    Alertes Moyennes
                                </h3>
                            </div>
                            <div class="card-content">
                                <div style="display: grid; gap: 1rem;">
                                    <div class="alert alert-warning">
                                        <svg class="alert-icon" viewBox="0 0 24 24" fill="none" stroke="#f59e0b" stroke-width="2">
                                            <path d="M14 4v10.54a4 4 0 1 1-4 0V4a2 2 0 0 1 4 0Z"/>
                                            <circle cx="12" cy="17" r="1"/>
                                        </svg>
                                        <div class="alert-content">
                                            <div class="alert-title">Température élevée détectée</div>
                                            <div class="alert-description">
                                                Ferme Oasis Nord - Il y a 1 heure<br>
                                                Température: 34°C (Seuil: 32°C)
                                            </div>
                                        </div>
                                        <div class="action-buttons">
                                            <button class="btn btn-secondary" onclick="resolveAlert('alert2')">
                                                <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                                    <path d="M9 12l2 2 4-4"/>
                                                    <circle cx="12" cy="12" r="9"/>
                                                </svg>
                                                Vu
                                            </button>
                                        </div>
                                    </div>

                                    <div class="alert alert-warning">
                                        <svg class="alert-icon" viewBox="0 0 24 24" fill="none" stroke="#f59e0b" stroke-width="2">
                                            <path d="M4 15s1-1 4-1 5 2 8 2 4-1 4-1V3s-1 1-4 1-5-2-8-2-4 1-4 1z"/>
                                            <line x1="4" y1="22" x2="4" y2="15"/>
                                        </svg>
                                        <div class="alert-content">
                                            <div class="alert-title">Capteur déconnecté</div>
                                            <div class="alert-description">
                                                Capteur S003 - Ferme Agrumes Est - Il y a 2 heures<br>
                                                Dernière communication: 14:30
                                            </div>
                                        </div>
                                        <div class="action-buttons">
                                            <button class="btn btn-secondary" onclick="diagnosticSensor('S003')">
                                                <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                                    <path d="M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z"/>
                                                </svg>
                                                Diagnostic
                                            </button>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title" style="color: #22c55e;">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <circle cx="12" cy="12" r="10"/>
                                        <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"/>
                                        <path d="M12 17h.01"/>
                                    </svg>
                                    Informations
                                </h3>
                            </div>
                            <div class="card-content">
                                <div style="display: grid; gap: 1rem;">
                                    <div class="alert alert-info">
                                        <svg class="alert-icon" viewBox="0 0 24 24" fill="none" stroke="#3b82f6" stroke-width="2">
                                            <path d="M5 18v-6a9 9 0 0 1 18 0v6"/>
                                            <path d="M5 18H3a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2h2"/>
                                            <path d="M19 18h2a2 2 0 0 0 2-2v-3a2 2 0 0 0-2-2h-2"/>
                                        </svg>
                                        <div class="alert-content">
                                            <div class="alert-title">Précipitations prévues</div>
                                            <div class="alert-description">
                                                Demain 15h-18h - 8mm de pluie attendue<br>
                                                Impact: Réduction automatique de l'irrigation
                                            </div>
                                        </div>
                                    </div>

                                    <div class="alert alert-info">
                                        <svg class="alert-icon" viewBox="0 0 24 24" fill="none" stroke="#3b82f6" stroke-width="2">
                                            <path d="M8 2v4"/>
                                            <path d="M16 2v4"/>
                                            <rect x="3" y="4" width="18" height="18" rx="2"/>
                                            <path d="M3 10h18"/>
                                        </svg>
                                        <div class="alert-content">
                                            <div class="alert-title">Irrigation programmée</div>
                                            <div class="alert-description">
                                                Ferme Oliviers Sud - Demain 06:00<br>
                                                Durée estimée: 35 minutes
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="action-buttons">
                        <button class="btn btn-primary" onclick="markAllAsRead()">
                            <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M9 12l2 2 4-4"/>
                                <circle cx="12" cy="12" r="9"/>
                            </svg>
                            Marquer tout comme lu
                        </button>
                        <button class="btn btn-secondary" onclick="configureAlerts()">
                            <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <circle cx="12" cy="12" r="3"/>
                                <path d="m12 1 0 6m0 6 0 6m11-7-6 0m-6 0-6 0"/>
                            </svg>
                            Configurer alertes
                        </button>
                    </div>
                </div>

                <!-- Irrigation Page -->
                <div id="irrigation-page" class="page-content hidden">
                    <div class="page-header">
                        <h1 class="page-title">Irrigation Manuelle</h1>
                        <p class="page-subtitle">Contrôle direct de l'irrigation sans recommandations IA</p>
                    </div>

                    <div class="farms-grid">
                        <div class="farm-card">
                            <div class="farm-header">
                                <div class="farm-info">
                                    <div class="farm-name">
                                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#22c55e" stroke-width="2">
                                            <path d="m3 21 18 0"/>
                                            <path d="m5 21-2-4 9-9h5l4-4"/>
                                            <path d="m9 21 0-7"/>
                                            <path d="m13 21 0-7"/>
                                            <path d="m17 21 0-7"/>
                                        </svg>
                                        Ferme Oasis Nord
                                    </div>
                                    <div class="farm-details">2.5 hectares • Palmiers Dattiers</div>
                                </div>
                                <div class="status-badge" style="background: #e0f2fe; color: #0277bd;">Manuel</div>
                            </div>

                            <div class="sensor-grid">
                                <div class="sensor-item">
                                    <div class="sensor-value">28%</div>
                                    <div class="sensor-label">Humidité Sol</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">31°C</div>
                                    <div class="sensor-label">Température</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">45%</div>
                                    <div class="sensor-label">Humidité Air</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">6.8</div>
                                    <div class="sensor-label">pH Sol</div>
                                </div>
                            </div>

                            <div class="manual-control-section">
                                <div class="control-header">
                                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <circle cx="12" cy="12" r="3"/>
                                        <path d="m12 1 0 6m0 6 0 6m11-7-6 0m-6 0-6 0"/>
                                    </svg>
                                    Contrôle Manuel
                                </div>
                                <div class="manual-controls">
                                    <div class="control-row">
                                        <label class="control-label">Durée (minutes)</label>
                                        <div class="control-input-group">
                                            <input type="number" class="control-input" value="30" min="5" max="180" id="duration1">
                                            <span class="control-unit">min</span>
                                        </div>
                                    </div>
                                    <div class="control-row">
                                        <label class="control-label">Débit (L/min)</label>
                                        <div class="control-input-group">
                                            <input type="number" class="control-input" value="15" min="5" max="50" id="flow1">
                                            <span class="control-unit">L/min</span>
                                        </div>
                                    </div>
                                    <div class="control-row">
                                        <label class="control-label">Mode</label>
                                        <select class="control-select" id="mode1">
                                            <option value="immediate">Immédiat</option>
                                            <option value="scheduled">Programmé</option>
                                        </select>
                                    </div>
                                </div>
                                <div class="irrigation-summary">
                                    <div class="summary-item">
                                        <span class="summary-label">Volume total:</span>
                                        <span class="summary-value" id="totalVolume1">450 L</span>
                                    </div>
                                    <div class="summary-item">
                                        <span class="summary-label">Coût estimé:</span>
                                        <span class="summary-value" id="totalCost1">18.00 DH</span>
                                    </div>
                                </div>
                                <div class="action-buttons">
                                    <button class="btn btn-primary" onclick="startManualIrrigation('farm1')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <polygon points="5,3 19,12 5,21 12,12"/>
                                        </svg>
                                        Démarrer
                                    </button>
                                    <button class="btn btn-secondary" onclick="testSystem('farm1')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <path d="M9 12l2 2 4-4"/>
                                            <circle cx="12" cy="12" r="9"/>
                                        </svg>
                                        Test Système
                                    </button>
                                </div>
                            </div>
                        </div>

                        <div class="farm-card">
                            <div class="farm-header">
                                <div class="farm-info">
                                    <div class="farm-name">
                                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#22c55e" stroke-width="2">
                                            <path d="m3 21 18 0"/>
                                            <path d="m5 21-2-4 9-9h5l4-4"/>
                                            <path d="m9 21 0-7"/>
                                            <path d="m13 21 0-7"/>
                                            <path d="m17 21 0-7"/>
                                        </svg>
                                        Ferme Oliviers Sud
                                    </div>
                                    <div class="farm-details">1.7 hectares • Oliviers</div>
                                </div>
                                <div class="status-badge" style="background: #e0f2fe; color: #0277bd;">Manuel</div>
                            </div>

                            <div class="sensor-grid">
                                <div class="sensor-item">
                                    <div class="sensor-value">42%</div>
                                    <div class="sensor-label">Humidité Sol</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">29°C</div>
                                    <div class="sensor-label">Température</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">48%</div>
                                    <div class="sensor-label">Humidité Air</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">7.2</div>
                                    <div class="sensor-label">pH Sol</div>
                                </div>
                            </div>

                            <div class="manual-control-section">
                                <div class="control-header">
                                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <circle cx="12" cy="12" r="3"/>
                                        <path d="m12 1 0 6m0 6 0 6m11-7-6 0m-6 0-6 0"/>
                                    </svg>
                                    Contrôle Manuel
                                </div>
                                <div class="manual-controls">
                                    <div class="control-row">
                                        <label class="control-label">Durée (minutes)</label>
                                        <div class="control-input-group">
                                            <input type="number" class="control-input" value="20" min="5" max="180" id="duration2">
                                            <span class="control-unit">min</span>
                                        </div>
                                    </div>
                                    <div class="control-row">
                                        <label class="control-label">Débit (L/min)</label>
                                        <div class="control-input-group">
                                            <input type="number" class="control-input" value="12" min="5" max="50" id="flow2">
                                            <span class="control-unit">L/min</span>
                                        </div>
                                    </div>
                                    <div class="control-row">
                                        <label class="control-label">Mode</label>
                                        <select class="control-select" id="mode2">
                                            <option value="immediate">Immédiat</option>
                                            <option value="scheduled">Programmé</option>
                                        </select>
                                    </div>
                                </div>
                                <div class="irrigation-summary">
                                    <div class="summary-item">
                                        <span class="summary-label">Volume total:</span>
                                        <span class="summary-value" id="totalVolume2">240 L</span>
                                    </div>
                                    <div class="summary-item">
                                        <span class="summary-label">Coût estimé:</span>
                                        <span class="summary-value" id="totalCost2">9.60 DH</span>
                                    </div>
                                </div>
                                <div class="action-buttons">
                                    <button class="btn btn-primary" onclick="startManualIrrigation('farm2')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <polygon points="5,3 19,12 5,21 12,12"/>
                                        </svg>
                                        Démarrer
                                    </button>
                                    <button class="btn btn-secondary" onclick="testSystem('farm2')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <path d="M9 12l2 2 4-4"/>
                                            <circle cx="12" cy="12" r="9"/>
                                        </svg>
                                        Test Système
                                    </button>
                                </div>
                            </div>
                        </div>

                        <div class="farm-card">
                            <div class="farm-header">
                                <div class="farm-info">
                                    <div class="farm-name">
                                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#22c55e" stroke-width="2">
                                            <path d="m3 21 18 0"/>
                                            <path d="m5 21-2-4 9-9h5l4-4"/>
                                            <path d="m9 21 0-7"/>
                                            <path d="m13 21 0-7"/>
                                            <path d="m17 21 0-7"/>
                                        </svg>
                                        Ferme Agrumes Est
                                    </div>
                                    <div class="farm-details">3.2 hectares • Agrumes</div>
                                </div>
                                <div class="status-badge" style="background: #e0f2fe; color: #0277bd;">Manuel</div>
                            </div>

                            <div class="sensor-grid">
                                <div class="sensor-item">
                                    <div class="sensor-value">35%</div>
                                    <div class="sensor-label">Humidité Sol</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">30°C</div>
                                    <div class="sensor-label">Température</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">50%</div>
                                    <div class="sensor-label">Humidité Air</div>
                                </div>
                                <div class="sensor-item">
                                    <div class="sensor-value">6.5</div>
                                    <div class="sensor-label">pH Sol</div>
                                </div>
                            </div>

                            <div class="manual-control-section">
                                <div class="control-header">
                                    <svg width="16" width="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <circle cx="12" cy="12" r="3"/>
                                        <path d="m12 1 0 6m0 6 0 6m11-7-6 0m-6 0-6 0"/>
                                    </svg>
                                    Contrôle Manuel
                                </div>
                                <div class="manual-controls">
                                    <div class="control-row">
                                        <label class="control-label">Durée (minutes)</label>
                                        <div class="control-input-group">
                                            <input type="number" class="control-input" value="45" min="5" max="180" id="duration3">
                                            <span class="control-unit">min</span>
                                        </div>
                                    </div>
                                    <div class="control-row">
                                        <label class="control-label">Débit (L/min)</label>
                                        <div class="control-input-group">
                                            <input type="number" class="control-input" value="18" min="5" max="50" id="flow3">
                                            <span class="control-unit">L/min</span>
                                        </div>
                                    </div>
                                    <div class="control-row">
                                        <label class="control-label">Mode</label>
                                        <select class="control-select" id="mode3">
                                            <option value="immediate">Immédiat</option>
                                            <option value="scheduled">Programmé</option>
                                        </select>
                                    </div>
                                </div>
                                <div class="irrigation-summary">
                                    <div class="summary-item">
                                        <span class="summary-label">Volume total:</span>
                                        <span class="summary-value" id="totalVolume3">810 L</span>
                                    </div>
                                    <div class="summary-item">
                                        <span class="summary-label">Coût estimé:</span>
                                        <span class="summary-value" id="totalCost3">32.40 DH</span>
                                    </div>
                                </div>
                                <div class="action-buttons">
                                    <button class="btn btn-primary" onclick="startManualIrrigation('farm3')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <polygon points="5,3 19,12 5,21 12,12"/>
                                        </svg>
                                        Démarrer
                                    </button>
                                    <button class="btn btn-secondary" onclick="testSystem('farm3')">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <path d="M9 12l2 2 4-4"/>
                                            <circle cx="12" cy="12" r="9"/>
                                        </svg>
                                        Test Système
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Section Historique d'irrigation manuelle -->
                    <div class="card" style="margin-top: 2rem;">
                        <div class="card-header">
                            <h3 class="card-title">
                                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <circle cx="12" cy="12" r="10"/>
                                    <polyline points="12,6 12,12 16,14"/>
                                </svg>
                                Historique Irrigation Manuelle
                            </h3>
                        </div>
                        <div class="card-content">
                            <div style="display: grid; gap: 1rem;">
                                <div class="irrigation-history-item">
                                    <div class="history-header">
                                        <span class="history-farm">Ferme Oasis Nord</span>
                                        <span class="history-date">Aujourd'hui, 14:30</span>
                                    </div>
                                    <div class="history-details">
                                        <span>30 min • 15 L/min • 450 L total</span>
                                        <span class="history-status completed">Terminé</span>
                                    </div>
                                </div>
                                <div class="irrigation-history-item">
                                    <div class="history-header">
                                        <span class="history-farm">Ferme Oliviers Sud</span>
                                        <span class="history-date">Hier, 06:15</span>
                                    </div>
                                    <div class="history-details">
                                        <span>25 min • 12 L/min • 300 L total</span>
                                        <span class="history-status completed">Terminé</span>
                                    </div>
                                </div>
                                <div class="irrigation-history-item">
                                    <div class="history-header">
                                        <span class="history-farm">Ferme Agrumes Est</span>
                                        <span class="history-date">Hier, 18:00</span>
                                    </div>
                                    <div class="history-details">
                                        <span>40 min • 18 L/min • 720 L total</span>
                                        <span class="history-status completed">Terminé</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Settings Page -->
                <div id="settings-page" class="page-content hidden">
                    <div class="page-header">
                        <h1 class="page-title">Configuration</h1>
                        <p class="page-subtitle">Paramètres de votre compte et préférences</p>
                    </div>

                    <div class="content-grid">
                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/>
                                        <circle cx="12" cy="7" r="4"/>
                                    </svg>
                                    Profil Agriculteur
                                </h3>
                            </div>
                            <div class="card-content">
                                <div style="text-align: center; margin-bottom: 2rem;">
                                    <div style="width: 80px; height: 80px; background: linear-gradient(135deg, #22c55e, #16a34a); border-radius: 50%; margin: 0 auto 1rem; display: flex; align-items: center; justify-content: center; color: white; font-size: 1.5rem; font-weight: 600;">
                                        AB
                                    </div>
                                    <h3>Ahmed Benali</h3>
                                    <p style="color: #64748b;">Coopérative Agricole Oasis - Errachidia</p>
                                    <p style="color: #64748b; font-size: 0.875rem;">Membre depuis Mars 2024</p>
                                </div>

                                <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1rem; margin-bottom: 2rem;">
                                    <div class="metric-card">
                                        <div class="metric-value" style="font-size: 1.5rem;">3</div>
                                        <div class="metric-title">Fermes</div>
                                    </div>
                                    <div class="metric-card">
                                        <div class="metric-value" style="font-size: 1.5rem;">7</div>
                                        <div class="metric-title">Capteurs</div>
                                    </div>
                                    <div class="metric-card">
                                        <div class="metric-value" style="font-size: 1.5rem;">7.4ha</div>
                                        <div class="metric-title">Surface totale</div>
                                    </div>
                                    <div class="metric-card">
                                        <div class="metric-value" style="font-size: 1.5rem;">-28%</div>
                                        <div class="metric-title">Économie eau</div>
                                    </div>
                                </div>

                                <div style="display: grid; gap: 1rem;">
                                    <div class="form-group">
                                        <label class="form-label">Région</label>
                                        <select class="form-select" id="region">
                                            <option value="errachidia" selected>Errachidia</option>
                                            <option value="ouarzazate">Ouarzazate</option>
                                            <option value="zagora">Zagora</option>
                                        </select>
                                    </div>
                                    <div class="form-group">
                                        <label class="form-label">Email</label>
                                        <input type="email" class="form-input" value="ahmed.benali@oasis-coop.ma" id="email">
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <path d="M6 8a6 6 0 0 1 12 0c0 7 3 9 3 9H3s3-2 3-9"/>
                                        <path d="m13.73 21a2 2 0 0 1-3.46 0"/>
                                    </svg>
                                    Notifications
                                </h3>
                            </div>
                            <div class="card-content">
                                <div style="display: grid; gap: 1rem;">
                                    <div style="display: flex; justify-content: space-between; align-items: center; padding: 0.75rem 0; border-bottom: 1px solid #f1f5f9;">
                                        <span>Rapports hebdomadaires</span>
                                        <label class="toggle-switch">
                                            <input type="checkbox" checked>
                                            <span class="toggle-slider"></span>
                                        </label>
                                    </div>
                                    <div style="display: flex; justify-content: space-between; align-items: center; padding: 0.75rem 0;">
                                        <span>Alertes météo</span>
                                        <label class="toggle-switch">
                                            <input type="checkbox" checked>
                                            <span class="toggle-slider"></span>
                                        </label>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="content-grid">
                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <rect x="2" y="3" width="20" height="14" rx="2" ry="2"/>
                                        <circle cx="8" cy="21" r="1"/>
                                        <circle cx="16" cy="21" r="1"/>
                                        <path d="M7 11h10"/>
                                        <path d="M7 7h4"/>
                                    </svg>
                                    Intelligence Artificielle
                                </h3>
                            </div>
                            <div class="card-content">
                                <div style="display: grid; gap: 1rem;">
                                    <div style="display: flex; justify-content: space-between; align-items: center; padding: 0.75rem 0; border-bottom: 1px solid #f1f5f9;">
                                        <span>Irrigation automatique</span>
                                        <label class="toggle-switch">
                                            <input type="checkbox">
                                            <span class="toggle-slider"></span>
                                        </label>
                                    </div>
                                    <div style="display: flex; justify-content: space-between; align-items: center; padding: 0.75rem 0; border-bottom: 1px solid #f1f5f9;">
                                        <span>Mode apprentissage avancé</span>
                                        <label class="toggle-switch">
                                            <input type="checkbox" checked>
                                            <span class="toggle-slider"></span>
                                        </label>
                                    </div>
                                    <div class="form-group">
                                        <label class="form-label">Seuil d'humidité critique (%)</label>
                                        <input type="number" class="form-input" value="20" min="10" max="40" id="humidityCritical">
                                    </div>
                                    <div class="form-group">
                                        <label class="form-label">Température maximale (°C)</label>
                                        <input type="number" class="form-input" value="35" min="25" max="45" id="tempMax">
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="card">
                            <div class="card-header">
                                <h3 class="card-title">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                        <path d="M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z"/>
                                    </svg>
                                    Maintenance & Support
                                </h3>
                            </div>
                            <div class="card-content">
                                <div style="display: grid; gap: 0.75rem;">
                                    <button class="btn btn-secondary" onclick="syncData()">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <path d="M21 12c0 4.97-4.03 9-9 9s-9-4.03-9-9 4.03-9 9-9c2.35 0 4.48.9 6.08 2.38"/>
                                            <path d="M17 12l4-4-4-4"/>
                                        </svg>
                                        Synchroniser données
                                    </button>
                                    <button class="btn btn-secondary" onclick="exportData()">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/>
                                            <polyline points="7,10 12,15 17,10"/>
                                            <line x1="12" y1="15" x2="12" y2="3"/>
                                        </svg>
                                        Exporter données
                                    </button>
                                    <button class="btn btn-secondary" onclick="contactSupport()">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <path d="M8 2v4"/>
                                            <path d="M16 2v4"/>
                                            <rect x="3" y="4" width="18" height="18" rx="2"/>
                                            <path d="M3 10h18"/>
                                        </svg>
                                        Support technique
                                    </button>
                                    <button class="btn btn-secondary" onclick="showHelp()">
                                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                            <circle cx="12" cy="12" r="10"/>
                                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"/>
                                            <path d="M12 17h.01"/>
                                        </svg>
                                        Guide d'utilisation
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="action-buttons">
                        <button class="btn btn-primary" onclick="saveSettings()">
                            <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M9 12l2 2 4-4"/>
                                <circle cx="12" cy="12" r="9"/>
                            </svg>
                            Sauvegarder les paramètres
                        </button>
                    </div>
                </div>
            </main>
        </div>
    </div>

    <!-- Irrigation Modal -->
    <div id="irrigationModal" class="modal">
        <div class="modal-content">
            <div class="modal-header">
                <h3 class="modal-title">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#22c55e" stroke-width="2">
                        <path d="M8 16a6 6 0 0 0 6-6c0-1.655-1.122-2.904-2.432-4.362C10.254 4.176 8.75 2.503 8 0c0 0-6 5.686-6 10a6 6 0 0 0 6 6Z"/>
                    </svg>
                    Contrôle d'Irrigation SmartOasis
                </h3>
                <button class="modal-close" onclick="closeIrrigationModal()">&times;</button>
            </div>
            <div class="modal-body">
                <div style="background: #f0fdf4; padding: 1.5rem; border-radius: 12px; text-align: center; margin-bottom: 1.5rem; border: 1px solid #bbf7d0;">
                    <div style="font-size: 3rem; margin-bottom: 0.5rem;">💧</div>
                    <h4 style="color: #16a34a; margin-bottom: 0.5rem;">Système d'irrigation SmartOasis prêt</h4>
                    <p style="color: #64748b; font-size: 0.875rem;">Pression: 2.1 bar • Débit: 15L/min • Connexion IoT active</p>
                </div>

                <div class="recommendation-section">
                    <div class="recommendation-header">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <rect x="2" y="3" width="20" height="14" rx="2" ry="2"/>
                            <circle cx="8" cy="21" r="1"/>
                            <circle cx="16" cy="21" r="1"/>
                            <path d="M7 11h10"/>
                            <path d="M7 7h4"/>
                        </svg>
                        Recommandation SmartOasis IA
                    </div>
                    <div style="display: grid; gap: 0.5rem; font-size: 0.875rem;">
                        <p><strong>Quantité suggérée:</strong> <span id="recommendedAmount">25</span> litres/m²</p>
                        <p><strong>Durée estimée:</strong> <span id="estimatedDuration">42</span> minutes</p>
                        <p><strong>Coût estimé:</strong> <span id="estimatedCost">15.50</span> DH</p>
                    </div>
                </div>

                <div style="display: grid; gap: 1.5rem; margin: 1.5rem 0;">
                    <div class="form-group">
                        <label class="form-label">Durée d'irrigation (minutes)</label>
                        <input type="range" class="form-range" id="irrigationDuration" min="10" max="120" value="42" oninput="updateIrrigationEstimate()">
                        <div class="range-value"><span id="durationDisplay">42</span> minutes</div>
                    </div>

                    <div class="form-group">
                        <label class="form-label">Intensité</label>
                        <select class="form-select" id="irrigationIntensity" onchange="updateIrrigationEstimate()">
                            <option value="1">Très Faible</option>
                            <option value="2">Faible</option>
                            <option value="3" selected>Moyenne</option>
                            <option value="4">Élevée</option>
                            <option value="5">Très Élevée</option>
                        </select>
                    </div>

                    <div class="form-group">
                        <label class="form-label">Mode d'irrigation</label>
                        <select class="form-select" id="irrigationMode" onchange="updateIrrigationEstimate()">
                            <option value="manual">Manuel</option>
                            <option value="scheduled">Programmé</option>
                            <option value="auto">Automatique IA</option>
                        </select>
                    </div>

                    <div id="scheduledOptions" class="form-group hidden">
                        <label class="form-label">Heure de début</label>
                        <input type="time" class="form-input" id="startTime" value="18:00">
                    </div>
                </div>

                <div style="background: #fefce8; padding: 1rem; border-radius: 8px; border-left: 4px solid #eab308; margin-bottom: 1.5rem;">
                    <h4 style="color: #a16207; display: flex; align-items: center; gap: 8px; margin-bottom: 0.5rem;">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <circle cx="12" cy="12" r="10"/>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"/>
                            <path d="M12 17h.01"/>
                        </svg>
                        Conseil Optimal
                    </h4>
                    <p style="color: #713f12; font-size: 0.875rem;">
                        Heure optimale: 18h-20h pour minimiser l'évaporation. Température actuelle: 31°C
                    </p>
                </div>

                <div class="action-buttons">
                    <button class="btn btn-primary" onclick="startIrrigation()" style="flex: 2;">
                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <polygon points="5,3 19,12 5,21 12,12"/>
                        </svg>
                        DÉMARRER IRRIGATION
                    </button>
                    <button class="btn btn-secondary" onclick="closeIrrigationModal()">
                        <svg class="btn-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <line x1="18" y1="6" x2="6" y2="18"/>
                            <line x1="6" y1="6" x2="18" y2="18"/>
                        </svg>
                        Annuler
                    </button>
                </div>
            </div>
        </div>
    </div>

    <!-- Notification -->
    <div id="notification" class="notification">
        <span id="notificationText"></span>
    </div>

    <script>
        // ===== NAVIGATION =====
        function showPage(pageId) {
            // Hide all pages
            document.querySelectorAll('.page-content').forEach(page => {
                page.classList.add('hidden');
            });
            
            // Show selected page
            const targetPage = document.getElementById(pageId + '-page');
            if (targetPage) {
                targetPage.classList.remove('hidden');
            }
            
            // Update navigation
            document.querySelectorAll('.nav-link').forEach(link => {
                link.classList.remove('active');
            });
            
            // Find the clicked link and activate it
            const clickedLink = event.target.closest('.nav-link');
            if (clickedLink) {
                clickedLink.classList.add('active');
            }
            
            // Load page-specific data
            loadPageData(pageId);
        }

        function loadPageData(pageId) {
            switch(pageId) {
                case 'dashboard':
                    initializeCharts();
                    break;
                case 'farms':
                    loadFarmsData();
                    break;
                case 'analytics':
                    loadAnalyticsCharts();
                    break;
                case 'irrigation':
                    loadIrrigationData();
                    break;
                case 'alerts':
                    loadAlertsData();
                    break;
                case 'settings':
                    loadSettingsData();
                    break;
            }
        }

        // ===== CHARTS =====
        // Variable globale pour stocker les instances des graphiques
        window.chartInstances = {};

        function destroyChart(chartId) {
            if (window.chartInstances[chartId]) {
                window.chartInstances[chartId].destroy();
                delete window.chartInstances[chartId];
            }
        }

        function createChart(canvasId, config) {
            const ctx = document.getElementById(canvasId);
            if (!ctx) {
                console.error(`Canvas ${canvasId} not found`);
                return null;
            }

            // Détruire l'ancien graphique s'il existe
            destroyChart(canvasId);

            try {
                window.chartInstances[canvasId] = new Chart(ctx, config);
                return window.chartInstances[canvasId];
            } catch (error) {
                console.error(`Error creating chart ${canvasId}:`, error);
                return null;
            }
        }

        function initializeCharts() {
            // Attendre que Chart.js soit chargé
            if (typeof Chart === 'undefined') {
                console.error('Chart.js not loaded');
                return;
            }

            setTimeout(() => {
                // Trends Chart pour le dashboard
                createChart('trendsChart', {
                    type: 'line',
                    data: {
                        labels: ['06h', '09h', '12h', '15h', '18h', '21h'],
                        datasets: [{
                            label: 'Humidité Sol (%)',
                            data: [35, 32, 28, 25, 30, 33],
                            borderColor: '#22c55e',
                            backgroundColor: 'rgba(34, 197, 94, 0.1)',
                            tension: 0.4,
                            fill: true,
                            borderWidth: 2
                        }, {
                            label: 'Température (°C)',
                            data: [22, 28, 32, 35, 31, 26],
                            borderColor: '#f59e0b',
                            backgroundColor: 'rgba(245, 158, 11, 0.1)',
                            tension: 0.4,
                            fill: true,
                            borderWidth: 2
                        }]
                    },
                    options: {
                        responsive: true,
                        maintainAspectRatio: false,
                        plugins: {
                            legend: {
                                position: 'top',
                                labels: {
                                    usePointStyle: true,
                                    padding: 20
                                }
                            }
                        },
                        scales: {
                            y: {
                                beginAtZero: true,
                                grid: {
                                    color: '#f1f5f9'
                                },
                                ticks: {
                                    color: '#64748b'
                                }
                            },
                            x: {
                                grid: {
                                    color: '#f1f5f9'
                                },
                                ticks: {
                                    color: '#64748b'
                                }
                            }
                        }
                    }
                });
            }, 200);
        }

        function loadAnalyticsCharts() {
            // Attendre que Chart.js soit chargé
            if (typeof Chart === 'undefined') {
                console.error('Chart.js not loaded');
                return;
            }

            setTimeout(() => {
                // Water consumption chart
                createChart('waterChart', {
                    type: 'bar',
                    data: {
                        labels: ['Semaine 1', 'Semaine 2', 'Semaine 3', 'Semaine 4'],
                        datasets: [{
                            label: 'Consommation (L)',
                            data: [1200, 950, 800, 750],
                            backgroundColor: ['#ef4444', '#f59e0b', '#eab308', '#22c55e'],
                            borderRadius: 8,
                            borderSkipped: false
                        }, {
                            label: 'Objectif (L)',
                            data: [1000, 1000, 1000, 1000],
                            type: 'line',
                            borderColor: '#3b82f6',
                            borderWidth: 3,
                            fill: false,
                            pointBackgroundColor: '#3b82f6',
                            pointBorderColor: '#ffffff',
                            pointBorderWidth: 2,
                            pointRadius: 6
                        }]
                    },
                    options: {
                        responsive: true,
                        maintainAspectRatio: false,
                        plugins: {
                            legend: {
                                position: 'top',
                                labels: {
                                    usePointStyle: true,
                                    padding: 20
                                }
                            }
                        },
                        scales: {
                            y: {
                                beginAtZero: true,
                                grid: {
                                    color: '#f1f5f9'
                                },
                                ticks: {
                                    color: '#64748b',
                                    callback: function(value) {
                                        return value + ' L';
                                    }
                                }
                            },
                            x: {
                                grid: {
                                    color: '#f1f5f9'
                                },
                                ticks: {
                                    color: '#64748b'
                                }
                            }
                        }
                    }
                });

                // Climate chart
                createChart('climateChart', {
                    type: 'line',
                    data: {
                        labels: ['Lundi', 'Mardi', 'Mercredi', 'Jeudi', 'Vendredi', 'Samedi', 'Dimanche'],
                        datasets: [{
                            label: 'Température (°C)',
                            data: [28, 31, 33, 35, 32, 29, 30],
                            borderColor: '#ef4444',
                            backgroundColor: 'rgba(239, 68, 68, 0.1)',
                            yAxisID: 'y',
                            tension: 0.4,
                            borderWidth: 3,
                            pointBackgroundColor: '#ef4444',
                            pointBorderColor: '#ffffff',
                            pointBorderWidth: 2,
                            pointRadius: 5
                        }, {
                            label: 'Humidité (%)',
                            data: [45, 42, 38, 35, 40, 48, 46],
                            borderColor: '#3b82f6',
                            backgroundColor: 'rgba(59, 130, 246, 0.1)',
                            yAxisID: 'y1',
                            tension: 0.4,
                            borderWidth: 3,
                            pointBackgroundColor: '#3b82f6',
                            pointBorderColor: '#ffffff',
                            pointBorderWidth: 2,
                            pointRadius: 5
                        }]
                    },
                    options: {
                        responsive: true,
                        maintainAspectRatio: false,
                        interaction: {
                            mode: 'index',
                            intersect: false,
                        },
                        plugins: {
                            legend: {
                                position: 'top',
                                labels: {
                                    usePointStyle: true,
                                    padding: 20
                                }
                            }
                        },
                        scales: {
                            x: {
                                display: true,
                                grid: {
                                    color: '#f1f5f9'
                                },
                                ticks: {
                                    color: '#64748b'
                                }
                            },
                            y: {
                                type: 'linear',
                                display: true,
                                position: 'left',
                                grid: {
                                    color: '#f1f5f9'
                                },
                                ticks: {
                                    color: '#64748b',
                                    callback: function(value) {
                                        return value + '°C';
                                    }
                                },
                                title: {
                                    display: true,
                                    text: 'Température (°C)',
                                    color: '#ef4444',
                                    font: {
                                        weight: 'bold'
                                    }
                                }
                            },
                            y1: {
                                type: 'linear',
                                display: true,
                                position: 'right',
                                grid: {
                                    drawOnChartArea: false,
                                },
                                ticks: {
                                    color: '#64748b',
                                    callback: function(value) {
                                        return value + '%';
                                    }
                                },
                                title: {
                                    display: true,
                                    text: 'Humidité (%)',
                                    color: '#3b82f6',
                                    font: {
                                        weight: 'bold'
                                    }
                                }
                            },
                        }
                    }
                });

                console.log('Analytics charts loaded successfully');
            }, 300);
        }

        // ===== IRRIGATION MODAL =====
        function openIrrigationModal(farmId) {
            document.getElementById('irrigationModal').classList.add('active');
            updateIrrigationEstimate();
        }

        function closeIrrigationModal() {
            document.getElementById('irrigationModal').classList.remove('active');
        }

        function updateIrrigationEstimate() {
            const duration = document.getElementById('irrigationDuration').value;
            const intensity = document.getElementById('irrigationIntensity').value;
            const mode = document.getElementById('irrigationMode').value;
            
            document.getElementById('durationDisplay').textContent = duration;
            
            const waterAmount = Math.round(duration * intensity * 0.6);
            const cost = (waterAmount * 0.8).toFixed(2);
            
            document.getElementById('recommendedAmount').textContent = waterAmount;
            document.getElementById('estimatedDuration').textContent = duration;
            document.getElementById('estimatedCost').textContent = cost;
            
            const scheduledOptions = document.getElementById('scheduledOptions');
            if (mode === 'scheduled') {
                scheduledOptions.classList.remove('hidden');
            } else {
                scheduledOptions.classList.add('hidden');
            }
        }

        function startIrrigation() {
            showNotification('Irrigation démarrée avec succès!', 'success');
            closeIrrigationModal();
        }

        // ===== MANUAL IRRIGATION FUNCTIONS =====
        function startManualIrrigation(farmId) {
            const farmName = getFarmName(farmId);
            showNotification(`Irrigation manuelle démarrée pour ${farmName}`, 'success');
            
            // Simulate irrigation process
            setTimeout(() => {
                showNotification(`Irrigation de ${farmName} en cours...`, 'info');
            }, 2000);
            
            setTimeout(() => {
                showNotification(`Irrigation de ${farmName} terminée avec succès`, 'success');
            }, 5000);
        }

        function testSystem(farmId) {
            const farmName = getFarmName(farmId);
            showNotification(`Test du système d'irrigation pour ${farmName}...`, 'info');
            
            setTimeout(() => {
                showNotification(`Système de ${farmName} : Tous les composants fonctionnent correctement`, 'success');
            }, 3000);
        }

        function getFarmName(farmId) {
            const farmNames = {
                'farm1': 'Ferme Oasis Nord',
                'farm2': 'Ferme Oliviers Sud',
                'farm3': 'Ferme Agrumes Est'
            };
            return farmNames[farmId] || 'Ferme inconnue';
        }

        function updateManualCalculations(farmNumber) {
            const duration = document.getElementById(`duration${farmNumber}`).value;
            const flow = document.getElementById(`flow${farmNumber}`).value;
            
            const totalVolume = duration * flow;
            const totalCost = (totalVolume * 0.04).toFixed(2);
            
            document.getElementById(`totalVolume${farmNumber}`).textContent = `${totalVolume} L`;
            document.getElementById(`totalCost${farmNumber}`).textContent = `${totalCost} DH`;
        }

        function loadIrrigationData() {
            console.log('Loading manual irrigation data...');
            
            // Add event listeners for real-time calculations
            for (let i = 1; i <= 3; i++) {
                const durationInput = document.getElementById(`duration${i}`);
                const flowInput = document.getElementById(`flow${i}`);
                
                if (durationInput && flowInput) {
                    durationInput.addEventListener('input', () => updateManualCalculations(i));
                    flowInput.addEventListener('input', () => updateManualCalculations(i));
                }
            }
        }
        function loadFarmsData() {
            console.log('Loading farms data...');
        }

        function loadAlertsData() {
            console.log('Loading alerts data...');
        }

        function loadSettingsData() {
            console.log('Loading settings data...');
        }

        function showFarmDetails(farmId) {
            showNotification(`Chargement des détails de la ferme ${farmId}...`, 'info');
        }

        // ===== ACTIONS =====
        function resolveAlert(alertId) {
            showNotification('Alerte résolue', 'success');
        }

        function diagnosticSensor(sensorId) {
            showNotification(`Diagnostic du capteur ${sensorId} en cours...`, 'info');
        }

        function markAllAsRead() {
            showNotification('Toutes les alertes ont été marquées comme lues', 'success');
        }

        function configureAlerts() {
            showNotification('Configuration des alertes ouverte', 'info');
        }

        function syncData() {
            showNotification('Synchronisation des données en cours...', 'info');
            setTimeout(() => {
                showNotification('Données synchronisées avec succès', 'success');
            }, 2000);
        }

        function exportData() {
            showNotification('Export des données en cours...', 'info');
            setTimeout(() => {
                showNotification('Données exportées avec succès', 'success');
            }, 1500);
        }

        function contactSupport() {
            showNotification('Redirection vers le support technique...', 'info');
        }

        function showHelp() {
            showNotification('Guide d\'utilisation ouvert', 'info');
        }

        function saveSettings() {
            showNotification('Paramètres sauvegardés avec succès', 'success');
        }

        // ===== NOTIFICATIONS =====
        function showNotification(message, type = 'info') {
            const notification = document.getElementById('notification');
            const notificationText = document.getElementById('notificationText');
            
            notificationText.textContent = message;
            notification.className = `notification ${type}`;
            notification.classList.add('show');
            
            setTimeout(() => {
                notification.classList.remove('show');
            }, 4000);
        }

        // ===== INITIALIZATION =====
        document.addEventListener('DOMContentLoaded', function() {
            console.log('DOM loaded, initializing...');
            
            // Vérifier si Chart.js est chargé
            if (typeof Chart === 'undefined') {
                console.error('Chart.js not loaded!');
                showNotification('Erreur: Graphiques non disponibles', 'error');
                return;
            } else {
                console.log('Chart.js loaded successfully');
            }
            
            // Initialize dashboard charts immédiatement
            setTimeout(() => {
                initializeCharts();
            }, 500);
            
            // Close modal when clicking outside
            document.getElementById('irrigationModal').addEventListener('click', function(e) {
                if (e.target === this) {
                    closeIrrigationModal();
                }
            });
            
            // Escape key closes modal
            document.addEventListener('keydown', function(e) {
                if (e.key === 'Escape') {
                    closeIrrigationModal();
                }
            });
            
            // Welcome message
            setTimeout(() => {
                showNotification('Bienvenue sur SmartOasis ! 🌱', 'success');
            }, 1000);
            
            // Forcer le refresh des graphiques quand on change d'onglet
            document.querySelectorAll('.nav-link').forEach(link => {
                link.addEventListener('click', function() {
                    setTimeout(() => {
                        // Re-initialiser les graphiques selon la page active
                        const activePage = document.querySelector('.page-content:not(.hidden)');
                        if (activePage) {
                            const pageId = activePage.id.replace('-page', '');
                            if (pageId === 'dashboard') {
                                initializeCharts();
                            } else if (pageId === 'analytics') {
                                loadAnalyticsCharts();
                            }
                        }
                    }, 100);
                });
            });
        });
    </script>
</body>
</html> 
