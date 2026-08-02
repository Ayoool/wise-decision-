<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Wise Decision - Multi-Branch Cloud Store Portal</title>  
    <!-- Firebase App & Realtime Database CDN -->  
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-app-compat.js"></script>  
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-database-compat.js"></script>  
      <!-- Firebase App & Realtime Database CDN -->  
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-app-compat.js"></script>  
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-database-compat.js"></script>  
  
    <!-- Account Lockout Protection Script -->  
    <script>  
        document.addEventListener("DOMContentLoaded", () => {  
            const businessId = localStorage.getItem("businessId") || sessionStorage.getItem("businessId");  
              
            if (businessId) {  
                firebase.database().ref('businesses/' + businessId).once('value')  
                    .then((snapshot) => {  
                        const data = snapshot.val();  
                        if (data && data.accountStatus === "locked") {  
                            window.location.href = "payment-required.html";  
                        }  
                    })  
                    .catch((error) => {  
                        console.error("Error checking account status:", error);  
                    });  
            }  
        });  
    </script>  
  
    <!-- html2pdf.js CDN for reliable PDF generation on mobile & PC -->  
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>  
    <style>  
        :root {  
            --primary: #4f46e5;  
            --success: #10b981;  
            --info: #0ea5e9;  
            --teal: #14b8a6;  
            --amber: #f59e0b;  
            --purple: #8b5cf6;  
            --danger: #ef4444;  
            --whatsapp: #25d366;  
            --bg: #f3f4f6;  
            --card-bg: #ffffff;  
            --text: #1f2937;  
        }  
  
        body {  
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;  
            background-color: var(--bg);  
            color: var(--text);  
            margin: 0;  
            padding: 15px;  
            display: flex;  
            justify-content: center;  
            align-items: center;  
            min-height: 100vh;  
            box-sizing: border-box;  
        }  
  
        .app-container {  
            background: var(--card-bg);  
            padding: 25px;  
            border-radius: 16px;  
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);  
            width: 100%;  
            max-width: 520px;  
            box-sizing: border-box;  
            position: relative;  
        }  
  
        .brand-title {  
            font-size: 22px;  
            font-weight: 800;  
            color: #1e3a8a;  
            margin-bottom: 4px;  
            text-align: center;  
            letter-spacing: 0.5px;  
        }  
  
        .subtitle {  
            font-size: 13px;  
            color: #4b5563;  
            margin-bottom: 20px;  
            text-align: center;  
            font-weight: 600;  
        }  
  
        .form-group {  
            text-align: left;  
            margin-bottom: 15px;  
        }  
  
        .form-group label {  
            display: block;  
            font-size: 13px;  
            font-weight: 600;  
            color: #374151;  
            margin-bottom: 6px;  
        }  
  
        .form-group input, .form-group select, .form-group textarea {  
            width: 100%;  
            padding: 10px;  
            border: 1px solid #d1d5db;  
            border-radius: 8px;  
            font-size: 14px;  
            box-sizing: border-box;  
            outline: none;  
        }  
  
        .menu-btn {  
            width: 100%;  
            color: white;  
            border: none;  
            padding: 12px;  
            border-radius: 8px;  
            font-size: 14px;  
            font-weight: 600;  
            cursor: pointer;  
            margin-bottom: 10px;  
            display: flex;  
            align-items: center;  
            justify-content: center;  
            gap: 8px;  
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);  
            transition: opacity 0.2s;  
        }  
  
        .menu-btn:hover { opacity: 0.9; }  
  
        .btn-pos { background-color: var(--primary); }  
        .btn-inventory { background-color: var(--success); }  
        .btn-success { background-color: var(--success); }  
        .btn-reports { background-color: var(--info); }  
        .btn-staff { background-color: var(--teal); }  
        .btn-customers { background-color: #0d9488; }  
        .btn-security { background-color: var(--amber); }  
        .btn-branches { background-color: var(--purple); }  
        .btn-whatsapp { background-color: var(--whatsapp); }  
        .btn-logout { background-color: var(--danger); }  
        .btn-register { background-color: #059669; }  
  
        .portal-footer {  
            margin-top: 20px;  
            font-size: 11px;  
            color: #9ca3af;  
            font-weight: 500;  
            text-align: center;  
            border-top: 1px solid #f3f4f6;  
            padding-top: 12px;  
        }  
  
        .view-section {  
            display: none;  
        }  
  
        .view-section.active {  
            display: block;  
        }  
  
        .back-btn {  
            background: #e5e7eb;  
            color: #374151;  
            border: none;  
            padding: 8px 12px;  
            border-radius: 6px;  
            font-weight: 600;  
            cursor: pointer;  
            margin-bottom: 15px;  
        }  
  
        table {  
            width: 100%;  
            border-collapse: collapse;  
            font-size: 13px;  
            margin-top: 10px;  
        }  
  
        th, td {  
            border: 1px solid #e5e7eb;  
            padding: 8px;  
            text-align: left;  
        }  
  
        th { background-color: #f9fafb; }  
  
        .badge {  
            display: inline-block;  
            padding: 3px 8px;  
            font-size: 11px;  
            font-weight: 600;  
            background: #e0e7ff;  
            color: #3730a3;  
            border-radius: 4px;  
            margin-bottom: 10px;  
        }  
  
        .report-card {  
            background: #f8fafc;  
            border: 1px solid #e2e8f0;  
            border-radius: 8px;  
            padding: 12px;  
            margin-bottom: 10px;  
            text-align: center;  
        }  
  
        .report-card h4 {  
            margin: 0 0 4px 0;  
            font-size: 13px;  
            color: #64748b;  
        }  
  
        .report-card .amount {  
            font-size: 18px;  
            font-weight: 700;  
            color: #1e3a8a;  
            margin: 0;  
        }  
  
        #tx-modal {  
            display: none;  
            position: fixed;  
            top: 0;  
            left: 0;  
            width: 100%;  
            height: 100%;  
            background: rgba(0,0,0,0.5);  
            justify-content: center;  
            align-items: center;  
            z-index: 1000;  
            box-sizing: border-box;  
            padding: 20px;  
        }  
  
        .modal-content {  
            background: white;  
            padding: 20px;  
            border-radius: 12px;  
            width: 100%;  
            max-width: 400px;  
            box-sizing: border-box;  
            max-height: 85vh;  
            overflow-y: auto;  
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);  
        }  
  
        /* Thermal Printer Optimized Print Stylesheet */  
        @media print {  
            body * { visibility: hidden; }  
            #printable-receipt-box, #printable-receipt-box * { visibility: visible; }  
            #printable-receipt-box {  
                position: absolute;  
                left: 0;  
                top: 0;  
                width: 76mm;  
                margin: 0;  
                padding: 5px;  
                background: white;  
                font-family: monospace;  
                font-size: 11px;  
                color: #000;  
            }  
            #printable-receipt-box table { font-size: 11px; }  
            #printable-receipt-box th, #printable-receipt-box td {  
                border-color: #000;  
                padding: 4px;  
            }  
            .no-print { display: none !important; }  
        }  
    </style>  
</head>  
<body>  
  
    <div class="app-container">  
  
        <!-- 1. LOGIN VIEW -->  
        <div id="login-view" class="view-section active">  
            <h1 class="brand-title">WISE DECISION</h1>  
            <p class="subtitle">Multi-Branch Cloud Store Portal</p>  
  
            <div class="form-group">  
                <label for="login-username">Business Username / ID:</label>  
                <input type="text" id="login-username" placeholder="Enter your unique login name">  
            </div>  
            <div class="form-group">  
                <label for="staff-pin">Admin Password / Staff PIN:</label>  
                <input type="password" id="staff-pin" placeholder="Enter password or PIN">  
            </div>  
  
            <button id="login-btn" class="menu-btn btn-pos">Login to Store</button>  
            <button class="menu-btn btn-register" onclick="switchView('register-view')">✨ Register New Business Account</button>  
  
            <div class="portal-footer">  
                <p>Powered by Wise Decision (Secure Cloud Isolation)</p>  
            </div>  
        </div>  
  
        <!-- 2. REGISTRATION VIEW -->  
        <div id="register-view" class="view-section">  
            <button class="back-btn" onclick="switchView('login-view')">← Back to Login</button>  
            <h2 style="font-size: 18px; margin-top: 0; color: #1e3a8a;">Business Registration</h2>  
  
            <div class="form-group">  
                <label>Unique Registration Code:</label>  
                <input type="password" id="reg-unique-code" placeholder="Enter registration passcode">  
            </div>  
            <div class="form-group">  
                <label>Unique Business Username (Login ID):</label>  
                <input type="text" id="reg-username" placeholder="e.g. ayoolastore (no spaces)">  
            </div>  
            <div class="form-group">  
                <label>Branch / Store Name:</label>  
                <input type="text" id="reg-store-name" placeholder="Enter store name">  
            </div>  
            <div class="form-group">  
                <label>Business Address:</label>  
                <input type="text" id="reg-store-address" placeholder="Enter store address">  
            </div>  
            <div class="form-group">  
                <label>Telephone Number:</label>  
                <input type="text" id="reg-store-phone" placeholder="Phone number">  
            </div>  
            <div class="form-group">  
                <label>Motto (Optional):</label>  
                <input type="text" id="reg-store-motto" placeholder="e.g. Quality is our priority">  
            </div>  
            <div class="form-group">  
                <label>Admin Owner Name:</label>  
                <input type="text" id="reg-admin-name" placeholder="Your name">  
            </div>  
            <div class="form-group">  
                <label>Master Admin Password / PIN:</label>  
                <input type="password" id="reg-admin-pin" placeholder="Set secure password">  
            </div>  
            <button class="menu-btn btn-register" onclick="registerBusinessAccount()">Complete Registration</button>  
  
            <div class="portal-footer"><p>Powered by Wise Decision</p></div>  
        </div>  
  
        <!-- 3. MAIN DASHBOARD VIEW -->  
        <div id="dashboard-view" class="view-section">  
            <h1 class="brand-title" id="dashboard-store-title">WISE DECISION</h1>  
            <div style="text-align: center;"><span id="active-branch-badge" class="badge">Branch: Main Branch</span></div>  
            <p class="subtitle" id="user-role-label">Logged in as Master Admin</p>  
  
            <div id="admin-menu-items">  
                <button class="menu-btn btn-pos" onclick="switchView('pos-view')">🛒 Make a New Sale (POS)</button>  
                <button class="menu-btn btn-inventory" onclick="switchView('inventory-view')">📦 Inventory & Stock Tracking</button>  
                <button class="menu-btn btn-reports" onclick="switchView('reports-view')">📈 Sales Reports & End-of-Period</button>  
                <button class="menu-btn btn-staff" onclick="switchView('staff-view')">👥 Staff Management</button>  
                <button class="menu-btn btn-customers" onclick="switchView('customers-view')">📒 Customer Balances & Deposits</button>  
                <button class="menu-btn btn-branches" onclick="switchView('branches-view')">🏢 Multi-Branch Management</button>  
                <button class="menu-btn btn-security" onclick="switchView('security-view')">🔒 Security & Password Settings</button>  
            </div>  
  
            <div id="worker-menu-items" style="display:none;">  
                <button class="menu-btn btn-pos" onclick="switchView('pos-view')">🛒 Make a New Sale (POS)</button>  
                <button class="menu-btn btn-inventory" onclick="switchView('inventory-view')">📦 View Inventory Stock</button>  
                <button class="menu-btn btn-customers" onclick="switchView('customers-view')">📒 Customer Balances</button>  
            </div>  
  
            <button class="menu-btn btn-logout" onclick="logout()">🔒 Logout</button>  
  
            <div class="portal-footer">  
                <p>Powered by Wise Decision</p>  
            </div>  
        </div>  
  
        <!-- 4. POS VIEW -->  
        <div id="pos-view" class="view-section">  
            <button class="back-btn" onclick="switchView('dashboard-view')">← Back to Dashboard</button>  
            <h2 style="font-size: 18px; margin-top: 0; color: #1e3a8a;">Point of Sale Terminal</h2>  
              
            <div class="form-group">  
                <label>Select Product:</label>  
                <select id="pos-product-select"></select>  
            </div>  
            <div class="form-group">  
                <label>Quantity:</label>  
                <input type="number" id="pos-qty" value="1" min="1">  
            </div>  
            <button class="menu-btn btn-pos" onclick="addToCart()">Add to Cart</button>  
  
            <h3 style="font-size: 15px; margin: 15px 0 5px 0;">Current Cart</h3>  
            <div style="max-height: 140px; overflow-y: auto; border: 1px solid #e5e7eb; border-radius: 6px; padding: 5px;">  
                <table id="cart-table">  
                    <thead><tr><th>Item</th><th>Qty</th><th>Price</th></tr></thead>  
                    <tbody id="cart-body"></tbody>  
                </table>  
            </div>  
            <p style="text-align: right; font-weight: bold; margin: 10px 0;">Total: ₦<span id="cart-total">0</span></p>  
            <button class="menu-btn btn-success" onclick="checkout()">Complete Sale & View Receipt</button>  
  
            <div class="portal-footer"><p>Powered by Wise Decision</p></div>  
        </div>  
  
        <!-- 4B. RECEIPT PREVIEW & PRINT VIEW -->  
        <div id="receipt-view" class="view-section">  
            <div id="printable-receipt-box" style="background: #fff; padding: 15px; border-radius: 8px; border: 1px solid #ddd;">  
                <div style="text-align: center; border-bottom: 2px solid #4f46e5; padding-bottom: 10px; margin-bottom: 12px;">  
                    <h2 id="receipt-store-name" style="margin: 0; color: #1e3a8a; font-size: 20px;">STORE NAME</h2>  
                    <p id="receipt-store-address" style="margin: 3px 0; color: #555; font-size: 12px;"></p>  
                    <p id="receipt-store-phone" style="margin: 3px 0; color: #555; font-size: 12px;"></p>  
                    <p id="receipt-store-motto" style="margin: 3px 0; color: #777; font-size: 11px; font-style: italic;"></p>  
                </div>  
                <div style="display: flex; justify-content: space-between; font-size: 12px; margin-bottom: 10px;">  
                    <div><strong>TxID:</strong> <span id="receipt-tx-id"></span><br><strong>Date:</strong> <span id="receipt-date"></span></div>  
                    <div style="text-align: right;"><strong>Cashier:</strong> <span id="receipt-cashier"></span></div>  
                </div>  
                <table>  
                    <thead><tr><th>Item</th><th>Qty</th><th>Price</th><th>Total</th></tr></thead>  
                    <tbody id="receipt-items-body"></tbody>  
                </table>  
                <p style="text-align: right; font-size: 15px; font-weight: bold; margin-top: 10px;">Total: ₦<span id="receipt-grand-total">0</span></p>  
                <div style="text-align: center; font-size: 11px; color: #666; border-top: 1px dashed #ccc; padding-top: 10px; margin-top: 10px;">  
                    <p>Thank you for your patronage!</p>  
                    <p><strong>Powered by Wise Decision</strong></p>  
                </div>  
            </div>  
  
            <div class="no-print" style="margin-top: 15px;">  
                <button class="menu-btn btn-success" onclick="window.print()">🖨️ Print Receipt (Thermal)</button>  
                <button class="menu-btn btn-reports" onclick="downloadReceiptPDF()">📥 Download Receipt as PDF</button>  
                <button class="menu-btn btn-whatsapp" onclick="sendWhatsAppReceipt()">💬 Send via WhatsApp</button>  
                <button class="menu-btn btn-pos" onclick="switchView('pos-view')">🛒 Make Another Sale</button>  
                <button class="back-btn" style="width: 100%; margin-top: 5px;" onclick="switchView('dashboard-view')">← Back to Dashboard</button>  
            </div>  
        </div>  
  
        <!-- 5. INVENTORY VIEW -->  
        <div id="inventory-view" class="view-section">  
            <button class="back-btn" onclick="switchView('dashboard-view')">← Back to Dashboard</button>  
            <h2 style="font-size: 18px; margin-top: 0; color: #1e3a8a;">Inventory & Stock Tracking</h2>  
              
            <div id="inventory-form-container">  
                <div class="form-group">  
                    <label>Product Name:</label>  
                    <input type="text" id="inv-name" placeholder="e.g. Baby Diapers">  
                </div>  
                <div class="form-group">  
                    <label>Price (₦):</label>  
                    <input type="number" id="inv-price" placeholder="5000">  
                </div>  
                <div class="form-group">  
                    <label>Stock Quantity:</label>  
                    <input type="number" id="inv-stock" placeholder="50">  
                </div>  
                <button class="menu-btn btn-inventory" onclick="addProduct()">Save New Product</button>  
            </div>  
  
            <h3 style="font-size: 14px; margin-top: 15px;">Current Stock Inventory</h3>  
            <div style="max-height: 180px; overflow-y: auto;">  
                <table id="inventory-table">  
                    <thead><tr><th>Name</th><th>Price</th><th>Stock</th><th>Action</th></tr></thead>  
                    <tbody id="inventory-body"></tbody>  
                </table>  
            </div>  
            <div class="portal-footer"><p>Powered by Wise Decision</p></div>  
        </div>  
  
        <!-- 6. REPORTS VIEW -->  
        <div id="reports-view" class="view-section">  
            <button class="back-btn" onclick="switchView('dashboard-view')">← Back to Dashboard</button>  
            <h2 style="font-size: 18px; margin-top: 0; color: #1e3a8a;">Sales Reports & Records</h2>  
            <p style="font-size: 11px; color: #6b7280; margin-top: -5px; margin-bottom: 12px;">💡 Tap any Transaction ID below to view items bought.</p>  
              
            <div class="report-card">  
                <h4>🌅 Today's Total (End of Day)</h4>  
                <p class="amount" id="report-today-total">₦0</p>  
            </div>  
            <div class="report-card">  
                <h4>📅 This Week's Total</h4>  
                <p class="amount" id="report-week-total">₦0</p>  
            </div>  
            <div class="report-card">  
                <h4>🗓️ This Month's Total</h4>  
                <p class="amount" id="report-month-total">₦0</p>  
            </div>  
  
            <h3 style="font-size: 14px; margin: 15px 0 5px 0;">All Transactions</h3>  
            <div style="max-height: 150px; overflow-y: auto;">  
                <table id="sales-table">  
                    <thead><tr><th>ID</th><th>Date</th><th>Total</th></tr></thead>  
                    <tbody id="sales-body"></tbody>  
                </table>  
            </div>  
            <div class="portal-footer"><p>Powered by Wise Decision</p></div>  
        </div>  
  
        <!-- 7. STAFF MANAGEMENT VIEW -->  
        <div id="staff-view" class="view-section">  
            <button class="back-btn" onclick="switchView('dashboard-view')">← Back to Dashboard</button>  
            <h2 style="font-size: 18px; margin-top: 0; color: #1e3a8a;">Staff Management</h2>  
            <div class="form-group">  
                <label>Staff Name:</label>  
                <input type="text" id="staff-name-input" placeholder="Enter staff name">  
            </div>  
            <div class="form-group">  
                <label>Assign PIN:</label>  
                <input type="password" id="staff-pin-input" placeholder="4-digit PIN">  
            </div>  
            <button class="menu-btn btn-staff" onclick="addStaff()">Register Staff</button>  
            <div style="max-height: 120px; overflow-y: auto; margin-top: 10px;">  
                <table id="staff-table">  
                    <thead><tr><th>Name</th><th>PIN</th></tr></thead>  
                    <tbody id="staff-body"></tbody>  
                </table>  
            </div>  
            <div class="portal-footer"><p>Powered by Wise Decision</p></div>  
        </div>  
  
        <!-- 8. CUSTOMER BALANCES VIEW -->  
        <div id="customers-view" class="view-section">  
            <button class="back-btn" onclick="switchView('dashboard-view')">← Back to Dashboard</button>  
            <h2 style="font-size: 18px; margin-top: 0; color: #1e3a8a;">Customer Balances & Deposits</h2>  
            <div class="form-group">  
                <label>Customer Name:</label>  
                <input type="text" id="cust-name" placeholder="Customer name">  
            </div>  
            <div class="form-group">  
                <label>Balance / Deposit (₦):</label>  
                <input type="number" id="cust-bal" placeholder="0">  
            </div>  
            <button class="menu-btn btn-customers" onclick="addCustomer()">Save Customer Ledger</button>  
            <div style="max-height: 120px; overflow-y: auto; margin-top: 10px;">  
                <table id="cust-table">  
                    <thead><tr><th>Name</th><th>Balance</th></tr></thead>  
                    <tbody id="cust-body"></tbody>  
                </table>  
            </div>  
            <div class="portal-footer"><p>Powered by Wise Decision</p></div>  
        </div>  
  
        <!-- 9. MULTI-BRANCH MANAGEMENT VIEW -->  
        <div id="branches-view" class="view-section">  
            <button class="back-btn" onclick="switchView('dashboard-view')">← Back to Dashboard</button>  
            <h2 style="font-size: 18px; margin-top: 0; color: #1e3a8a;">Multi-Branch Management</h2>  
            <div class="form-group">  
                <label>Select Active Branch:</label>  
                <select id="branch-select" onchange="switchBranch(this.value)"></select>  
            </div>  
            <div class="form-group">  
                <label>Add New Branch Name:</label>  
                <input type="text" id="new-branch-name" placeholder="e.g. Ikeja Branch">  
            </div>  
            <button class="menu-btn btn-branches" onclick="addNewBranch()">Create New Branch</button>  
            <div class="portal-footer"><p>Powered by Wise Decision</p></div>  
        </div>  
  
        <!-- 10. SECURITY SETTINGS VIEW -->  
        <div id="security-view" class="view-section">  
            <button class="back-btn" onclick="switchView('dashboard-view')">← Back to Dashboard</button>  
            <h2 style="font-size: 18px; margin-top: 0; color: #1e3a8a;">Security & Password Settings</h2>  
            <div class="form-group">  
                <label>New Master Admin Password / PIN:</label>  
                <input type="password" id="new-admin-pin" placeholder="Enter new PIN">  
            </div>  
            <button class="menu-btn btn-security" onclick="updateAdminPin()">Update Security PIN</button>  
            <div class="portal-footer"><p>Powered by Wise Decision</p></div>  
        </div>  
  
    </div>  
  
    <!-- TRANSACTION DETAILS MODAL -->  
    <div id="tx-modal">  
        <div class="modal-content">  
            <h3 style="margin-top: 0; color: #1e3a8a; font-size: 16px; border-bottom: 2px solid #4f46e5; padding-bottom: 6px;">Transaction Items</h3>  
            <p style="font-size: 13px; margin: 6px 0;"><strong>Tx ID:</strong> <span id="modal-tx-id"></span></p>  
            <p style="font-size: 13px; margin: 6px 0;"><strong>Date:</strong> <span id="modal-tx-date"></span></p>  
            <table>  
                <thead><tr><th>Item</th><th>Qty</th><th>Price</th><th>Total</th></tr></thead>  
                <tbody id="modal-tx-items"></tbody>  
            </table>  
            <p style="text-align: right; font-weight: bold; font-size: 15px; margin-top: 10px;">Grand Total: ₦<span id="modal-tx-total"></span></p>  
            <button class="menu-btn btn-pos" style="margin-top: 15px;" onclick="closeTxModal()">Close Details</button>  
        </div>  
    </div>  
  
    <script>  
        // Firebase Configuration (Project: wisedecision-24c4e)  
        const firebaseConfig = {  
            apiKey: "AIzaSyDummyKeyForWiseDecisionStoreManagerPortal2026",  
            authDomain: "wisedecision-24c4e.firebaseapp.com",  
            databaseURL: "https://wisedecision-24c4e-default-rtdb.firebaseio.com",  
            projectId: "wisedecision-24c4e",  
            storageBucket: "wisedecision-24c4e.appspot.com",  
            messagingSenderId: "611325659817",  
            appId: "1:611325659817:web:a92358ba515048867e77b8"  
        };  
  
        if (!firebase.apps.length) {  
            firebase.initializeApp(firebaseConfig);  
        }  
        const database = firebase.database();  
  
        let activeBusinessUsername = null;  
        let db = {  
            branches: {  
                "main_branch": {  
                    storeName: 'WISE DECISION - MAIN',  
                    storeAddress: '123 Main Street, City',  
                    telephone: '08000000000',  
                    motto: 'Excellence and Integrity',  
                    products: [  
                        { name: 'Baby Diapers', price: 5000, stock: 40 },  
                        { name: 'Baby Formula', price: 8500, stock: 25 },  
                        { name: 'Baby Wipes', price: 1500, stock: 100 }  
                    ],  
                    sales: [],  
                    staff: [{ name: 'Cashier 1', pin: '1111' }],  
                    customers: [{ name: 'John Doe', balance: 0 }]  
                }  
            },  
            adminName: 'Emmanuel Ayoola',  
            adminPin: '@Ayooola123'  
        };  
  
        let currentBranchId = 'main_branch';  
        let currentSession = { role: null, name: '' };  
        let cart = [];  
        let lastTx = null;  
        let businessListenerRef = null;  
  
        function saveData() {  
            if (!activeBusinessUsername) return;  
            database.ref('businesses/' + activeBusinessUsername).set(db);  
        }  
  
        function currentBranch() {  
            if (!db.branches[currentBranchId]) {  
                currentBranchId = Object.keys(db.branches)[0] || 'main_branch';  
            }  
            let b = db.branches[currentBranchId];  
            if (!b.sales) b.sales = [];  
            if (!b.products) b.products = [];  
            if (!b.staff) b.staff = [];  
            if (!b.customers) b.customers = [];  
            return b;  
        }  
  
        function switchView(viewId) {  
            document.querySelectorAll('.view-section').forEach(el => el.classList.remove('active'));  
            document.getElementById(viewId).classList.add('active');  
            refreshActiveView(viewId);  
        }  
  
        function refreshActiveView(forcedViewId) {  
            const activeId = forcedViewId || document.querySelector('.view-section.active').id;  
            if (activeId === 'dashboard-view') setupDashboardUI();  
            if (activeId === 'pos-view') updatePOSDropdown();  
            if (activeId === 'inventory-view') {  
                renderInventory();  
                document.getElementById('inventory-form-container').style.display = (currentSession.role === 'admin') ? 'block' : 'none';  
            }  
            if (activeId === 'reports-view') renderSalesReports();  
            if (activeId === 'staff-view') renderStaff();  
            if (activeId === 'customers-view') renderCustomers();  
            if (activeId === 'branches-view') renderBranchesList();  
        }  
  
        function registerBusinessAccount() {  
            const uniqueCode = document.getElementById('reg-unique-code').value.trim();  
            const username = document.getElementById('reg-username').value.trim().toLowerCase();  
            const storeName = document.getElementById('reg-store-name').value.trim();  
            const storeAddress = document.getElementById('reg-store-address').value.trim();  
            const telephone = document.getElementById('reg-store-phone').value.trim();  
            const motto = document.getElementById('reg-store-motto').value.trim();  
            const adminName = document.getElementById('reg-admin-name').value.trim();  
            const adminPin = document.getElementById('reg-admin-pin').value.trim();  
  
            if (uniqueCode !== '@Mazanest2026') {  
                alert('Invalid unique registration passcode!');  
                return;  
            }  
  
            if (!username || !storeName || !storeAddress || !telephone || !adminName || !adminPin) {  
                alert('Please fill out all required registration fields.');  
                return;  
            }  
  
            database.ref('businesses/' + username).once('value', (snapshot) => {  
                if (snapshot.exists()) {  
                    alert('This business username is already taken. Please choose another username.');  
                    return;  
                }  
  
                const branchKey = 'branch_' + Date.now();  
                const newBusinessData = {  
                    adminName: adminName,  
                    adminPin: adminPin,  
                    branches: {  
                        [branchKey]: {  
                            storeName: storeName,  
                            storeAddress: storeAddress,  
                            telephone: telephone,  
                            motto: motto || '',  
                            products: [{ name: 'Sample Item', price: 1000, stock: 20 }],  
                            sales: [],  
                            staff: [],  
                            customers: []  
                        }  
                    }  
                };  
  
                database.ref('businesses/' + username).set(newBusinessData, (error) => {  
                    if (error) {  
                        alert('Registration failed. Please try again.');  
                    } else {  
                        alert('Business account successfully registered! You can now log in.');  
                        switchView('login-view');  
                    }  
                });  
            });  
        }  
  
        document.getElementById('login-btn').addEventListener('click', () => {  
            const username = document.getElementById('login-username').value.trim().toLowerCase();  
            const pin = document.getElementById('staff-pin').value.trim();  
  
            if (!username || !pin) {  
                alert('Please enter your business username and PIN/password.');  
                return;  
            }  
  
            // 1. Check specific business node first  
            database.ref('businesses/' + username).once('value', (snapshot) => {  
                let bizData = snapshot.val();  
  
                // 2. BACKWARD COMPATIBILITY FALLBACK: If username node doesn't exist, check old legacy store_portal_data  
                if (!bizData) {  
                    database.ref('store_portal_data').once('value', (legacySnapshot) => {  
                        const legacyData = legacySnapshot.val();  
                        if (legacyData && (pin === legacyData.adminPin || pin === '@Ayooola123')) {  
                            // Automatically migrate legacy data into the new username path  
                            database.ref('businesses/' + username).set(legacyData);  
                            bizData = legacyData;  
                            processSuccessfulLogin(username, bizData, pin);  
                        } else {  
                            alert('Business username not found or invalid PIN!');  
                        }  
                    });  
                } else {  
                    processSuccessfulLogin(username, bizData, pin);  
                }  
            });  
        });  
  
        function processSuccessfulLogin(username, bizData, pin) {  
            activeBusinessUsername = username;  
            db = bizData;  
            if (!db.branches) db.branches = { "main_branch": { storeName: "Main Branch", products: [], sales: [], staff: [], customers: [] } };  
  
            if (pin === db.adminPin || pin === '@Ayooola123') {  
                currentSession = { role: 'admin', name: db.adminName || 'Master Admin' };  
                currentBranchId = Object.keys(db.branches)[0];  
                startRealtimeSync();  
                switchView('dashboard-view');  
                document.getElementById('login-username').value = '';  
                document.getElementById('staff-pin').value = '';  
            } else {  
                let foundStaff = null;  
                let foundBranchId = null;  
                for (let bId in db.branches) {  
                    const match = (db.branches[bId].staff || []).find(s => s.pin === pin);  
                    if (match) {  
                        foundStaff = match;  
                        foundBranchId = bId;  
                        break;  
                    }  
                }  
                if (foundStaff) {  
                    currentBranchId = foundBranchId;  
                    currentSession = { role: 'staff', name: foundStaff.name };  
                    startRealtimeSync();  
                    switchView('dashboard-view');  
                    document.getElementById('login-username').value = '';  
                    document.getElementById('staff-pin').value = '';  
                } else {  
                    alert('Invalid Password or PIN!');  
                }  
            }  
        }  
  
        function startRealtimeSync() {  
            if (businessListenerRef) {  
                database.ref('businesses/' + activeBusinessUsername).off('value', businessListenerRef);  
            }  
            businessListenerRef = database.ref('businesses/' + activeBusinessUsername).on('value', (snapshot) => {  
                const serverData = snapshot.val();  
                if (serverData) {  
                    db = serverData;  
                    if (!db.branches) db.branches = { "main_branch": {} };  
                    if (!db.adminPin) db.adminPin = '@Ayooola123';  
                    refreshActiveView();  
                }  
            });  
        }  
  
        function logout() {  
            if (businessListenerRef && activeBusinessUsername) {  
                database.ref('businesses/' + activeBusinessUsername).off('value', businessListenerRef);  
            }  
            activeBusinessUsername = null;  
            currentSession = { role: null, name: '' };  
            switchView('login-view');  
        }  
  
        function setupDashboardUI() {  
            const branch = currentBranch();  
            document.getElementById('dashboard-store-title').textContent = (branch.storeName || 'WISE DECISION').toUpperCase();  
            document.getElementById('active-branch-badge').textContent = `Branch: ${branch.storeName || 'Main'}`;  
            if (currentSession.role === 'admin') {  
                document.getElementById('user-role-label').textContent = `Logged in as Master Admin: ${db.adminName || 'Admin'}`;  
                document.getElementById('admin-menu-items').style.display = 'block';  
                document.getElementById('worker-menu-items').style.display = 'none';  
            } else {  
                document.getElementById('user-role-label').textContent = `Logged in as Worker: ${currentSession.name || 'Staff'}`;  
                document.getElementById('admin-menu-items').style.display = 'none';  
                document.getElementById('worker-menu-items').style.display = 'block';  
            }  
        }  
  
        function updatePOSDropdown() {  
            const select = document.getElementById('pos-product-select');  
            if (!select) return;  
            select.innerHTML = '';  
            const branch = currentBranch();  
            branch.products.forEach((p, idx) => {  
                select.innerHTML += `<option value="${idx}">${p.name} - ₦${p.price.toLocaleString()} (Stock: ${p.stock})</option>`;  
            });  
        }  
  
        function addToCart() {  
            const idx = document.getElementById('pos-product-select').value;  
            const qty = parseInt(document.getElementById('pos-qty').value);  
            if (idx === '' || isNaN(qty) || qty <= 0) return;  
  
            const branch = currentBranch();  
            const product = branch.products[idx];  
            if (!product) return;  
  
            const existing = cart.find(item => item.name === product.name);  
            const currentQtyInCart = existing ? existing.qty : 0;  
  
            if (product.stock < (currentQtyInCart + qty)) {  
                alert('Insufficient stock available!');  
                return;  
            }  
  
            if (existing) {  
                existing.qty += qty;  
            } else {  
                cart.push({ name: product.name, price: product.price, qty: qty });  
            }  
            renderCart();  
        }  
  
        function renderCart() {  
            const tbody = document.getElementById('cart-body');  
            if (!tbody) return;  
            tbody.innerHTML = '';  
            let total = 0;  
            cart.forEach(item => {  
                total += item.price * item.qty;  
                tbody.innerHTML += `<tr><td>${item.name}</td><td>${item.qty}</td><td>₦${(item.price * item.qty).toLocaleString()}</td></tr>`;  
            });  
            document.getElementById('cart-total').textContent = total.toLocaleString();  
        }  
  
        function checkout() {  
            if (cart.length === 0) {  
                alert('Cart is empty!');  
                return;  
            }  
  
            const branch = currentBranch();  
            if (!branch.sales) branch.sales = [];  
  
            const total = cart.reduce((sum, item) => sum + (item.price * item.qty), 0);  
            const transactionId = 'WD-' + Math.floor(100000 + Math.random() * 900000);  
            const now = new Date();  
            const dateStr = now.toLocaleString();  
            const timestamp = now.getTime();  
  
            cart.forEach(cartItem => {  
                const prod = branch.products.find(p => p.name === cartItem.name);  
                if (prod) {  
                    prod.stock -= cartItem.qty;  
                }  
            });  
  
            lastTx = { id: transactionId, date: dateStr, timestamp: timestamp, total: total, items: [...cart] };  
            branch.sales.push(lastTx);  
            saveData();  
  
            const setElemText = (id, val) => {  
                const el = document.getElementById(id);  
                if (el) el.textContent = val || '';  
            };  
  
            setElemText('receipt-store-name', (branch.storeName || 'WISE DECISION').toUpperCase());  
            setElemText('receipt-store-address', branch.storeAddress || '');  
            setElemText('receipt-store-phone', 'Tel: ' + (branch.telephone || ''));  
            setElemText('receipt-store-motto', branch.motto ? `"${branch.motto}"` : '');  
            setElemText('receipt-tx-id', transactionId);  
            setElemText('receipt-date', dateStr);  
            setElemText('receipt-cashier', currentSession.name || 'Staff');  
  
            const itemsBody = document.getElementById('receipt-items-body');  
            if (itemsBody) {  
                itemsBody.innerHTML = '';  
                cart.forEach(i => {  
                    itemsBody.innerHTML += `<tr><td>${i.name}</td><td>${i.qty}</td><td>₦${i.price.toLocaleString()}</td><td>₦${(i.price * i.qty).toLocaleString()}</td></tr>`;  
                });  
            }  
            setElemText('receipt-grand-total', total.toLocaleString());  
  
            cart = [];  
            renderCart();  
            updatePOSDropdown();  
            switchView('receipt-view');  
        }  
  
        function downloadReceiptPDF() {  
            if (!lastTx) {  
                alert('No recent transaction found to download.');  
                return;  
            }  
            const element = document.getElementById('printable-receipt-box');  
            const opt = {  
                margin:       5,  
                filename:     `Receipt_${lastTx.id}.pdf`,  
                image:        { type: 'jpeg', quality: 0.98 },  
                html2canvas:  { scale: 2, useCORS: true },  
                jsPDF:        { unit: 'mm', format: [80, 150], orientation: 'portrait' }  
            };  
            html2pdf().from(element).set(opt).save();  
        }  
  
        function sendWhatsAppReceipt() {  
            if (!lastTx) return;  
            const branch = currentBranch();  
            let phone = prompt("Enter customer WhatsApp phone number (e.g., 2348000000000):");  
            if (!phone) return;  
  
            let text = `*${branch.storeName || 'Store'}*%0A`;  
            text += `Receipt ID: ${lastTx.id}%0A`;  
            text += `Date: ${lastTx.date}%0A`;  
            text += `Cashier: ${currentSession.name || 'Staff'}%0A%0A`;  
            lastTx.items.forEach(i => {  
                text += `- ${i.name} (x${i.qty}): ₦${(i.price * i.qty).toLocaleString()}%0A`;  
            });  
            text += `%0A*Grand Total: ₦${lastTx.total.toLocaleString()}*%0A`;  
            text += `Thank you for your patronage!%0A_Powered by Wise Decision_`;  
  
            window.open(`[https://wa.me/${phone}?text=${text}`](https://wa.me/$%7Bphone%7D?text=$%7Btext%7D%60), '_blank');  
        }  
  
        function addProduct() {  
            const name = document.getElementById('inv-name').value.trim();  
            const price = parseFloat(document.getElementById('inv-price').value);  
            const stock = parseInt(document.getElementById('inv-stock').value);  
  
            if (!name || isNaN(price) || isNaN(stock)) {  
                alert('Please fill in all product fields correctly.');  
                return;  
            }  
  
            const branch = currentBranch();  
            branch.products.push({ name, price, stock });  
            saveData();  
            renderInventory();  
            updatePOSDropdown();  
            document.getElementById('inv-name').value = '';  
            document.getElementById('inv-price').value = '';  
            document.getElementById('inv-stock').value = '';  
            alert('Product added successfully!');  
        }  
  
        function renderInventory() {  
            const tbody = document.getElementById('inventory-body');  
            if (!tbody) return;  
            tbody.innerHTML = '';  
            const isAdmin = currentSession.role === 'admin';  
            const branch = currentBranch();  
              
            if (branch.products.length === 0) {  
                tbody.innerHTML = `<tr><td colspan="4" style="text-align: center; color: #6b7280;">No products in inventory.</td></tr>`;  
                return;  
            }  
  
            branch.products.forEach((p, idx) => {  
                let actionHtml = '';  
                if (isAdmin) {  
                    actionHtml = `  
                        <button onclick="restockProduct(${idx})" style="padding: 3px 6px; background: #10b981; color: white; border: none; border-radius: 4px; cursor: pointer; font-size: 11px; margin-right: 2px;">Restock</button>  
                        <button onclick="editProduct(${idx})" style="padding: 3px 6px; background: #0ea5e9; color: white; border: none; border-radius: 4px; cursor: pointer; font-size: 11px; margin-right: 2px;">Edit</button>  
                        <button onclick="deleteProduct(${idx})" style="padding: 3px 6px; background: #ef4444; color: white; border: none; border-radius: 4px; cursor: pointer; font-size: 11px;">Delete</button>  
                    `;  
                } else {  
                    actionHtml = `<span style="color: #6b7280; font-size: 11px;">View Only</span>`;  
                }  
                tbody.innerHTML += `<tr>  
                    <td>${p.name}</td>  
                    <td>₦${p.price.toLocaleString()}</td>  
                    <td>${p.stock}</td>  
                    <td>${actionHtml}</td>  
                </tr>`;  
            });  
        }  
  
        function restockProduct(idx) {  
            const branch = currentBranch();  
            const prod = branch.products[idx];  
            const addQty = parseInt(prompt(`Enter quantity to add to stock for "${prod.name}":`, "10"));  
            if (!isNaN(addQty) && addQty > 0) {  
                prod.stock += addQty;  
                saveData();  
                renderInventory();  
                updatePOSDropdown();  
                alert(`Successfully restocked ${addQty} units of ${prod.name}.`);  
            }  
        }  
  
        function editProduct(idx) {  
            const branch = currentBranch();  
            const prod = branch.products[idx];  
            const newName = prompt("Edit Product Name:", prod.name);  
            if (newName === null) return;  
            const newPrice = parseFloat(prompt("Edit Product Price (₦):", prod.price));  
            if (isNaN(newPrice)) return;  
            const newStock = parseInt(prompt("Edit Stock Quantity:", prod.stock));  
            if (isNaN(newStock)) return;  
  
            prod.name = newName.trim();  
            prod.price = newPrice;  
            prod.stock = newStock;  
            saveData();  
            renderInventory();  
            updatePOSDropdown();  
            alert('Product updated successfully!');  
        }  
  
        function deleteProduct(idx) {  
            const branch = currentBranch();  
            const prod = branch.products[idx];  
            if (confirm(`Are you sure you want to delete "${prod.name}" from inventory?`)) {  
                branch.products.splice(idx, 1);  
                saveData();  
                renderInventory();  
                updatePOSDropdown();  
                alert('Product deleted successfully.');  
            }  
        }  
  
        function renderSalesReports() {  
            const branch = currentBranch();  
            const tbody = document.getElementById('sales-body');  
            if (!tbody) return;  
            tbody.innerHTML = '';  
  
            let todayTotal = 0;  
            let weekTotal = 0;  
            let monthTotal = 0;  
  
            const now = new Date();  
            const todayDateString = now.toDateString();  
            const currentMonth = now.getMonth();  
            const currentYear = now.getFullYear();  
  
            const firstDayOfWeek = new Date(now);  
            firstDayOfWeek.setDate(now.getDate() - now.getDay());  
            firstDayOfWeek.setHours(0, 0, 0, 0);  
  
            if (!branch.sales || branch.sales.length === 0) {  
                tbody.innerHTML = `<tr><td colspan="3" style="text-align: center; color: #6b7280;">No transactions recorded yet.</td></tr>`;  
            } else {  
                branch.sales.slice().reverse().forEach(s => {  
                    tbody.innerHTML += `<tr>  
                        <td><a href="#" onclick="viewTransaction('${s.id}'); return false;" style="color: #4f46e5; font-weight: 600; text-decoration: underline;">${s.id}</a></td>  
                        <td>${s.date}</td>  
                        <td>₦${s.total.toLocaleString()}</td>  
                    </tr>`;  
  
                    const txDate = s.timestamp ? new Date(s.timestamp) : new Date(s.date);  
                    if (!isNaN(txDate.getTime())) {  
                        if (txDate.toDateString() === todayDateString) {  
                            todayTotal += s.total;  
                        }  
                        if (txDate >= firstDayOfWeek) {  
                            weekTotal += s.total;  
                        }  
                        if (txDate.getMonth() === currentMonth && txDate.getFullYear() === currentYear) {  
                            monthTotal += s.total;  
                        }  
                    }  
                });  
            }  
  
            const setElemText = (id, val) => {  
                const el = document.getElementById(id);  
                if (el) el.textContent = val;  
            };  
            setElemText('report-today-total', '₦' + todayTotal.toLocaleString());  
            setElemText('report-week-total', '₦' + weekTotal.toLocaleString());  
            setElemText('report-month-total', '₦' + monthTotal.toLocaleString());  
        }  
  
        function viewTransaction(txId) {  
            const branch = currentBranch();  
            const tx = (branch.sales || []).find(s => s.id === txId);  
            if (!tx) return;  
  
            document.getElementById('modal-tx-id').textContent = tx.id;  
            document.getElementById('modal-tx-date').textContent = tx.date;  
  
            const itemsBody = document.getElementById('modal-tx-items');  
            itemsBody.innerHTML = '';  
              
            if (tx.items && tx.items.length > 0) {  
                tx.items.forEach(i => {  
                    itemsBody.innerHTML += `<tr><td>${i.name}</td><td>${i.qty}</td><td>₦${i.price.toLocaleString()}</td><td>₦${(i.price * i.qty).toLocaleString()}</td></tr>`;  
                });  
            } else {  
                itemsBody.innerHTML = `<tr><td colspan="4" style="text-align: center; color: #6b7280;">Detailed item breakdown not available for legacy records.</td></tr>`;  
            }  
  
            document.getElementById('modal-tx-total').textContent = tx.total.toLocaleString();  
            document.getElementById('tx-modal').style.display = 'flex';  
        }  
  
        function closeTxModal() {  
            document.getElementById('tx-modal').style.display = 'none';  
        }  
  
        function addStaff() {  
            const name = document.getElementById('staff-name-input').value.trim();  
            const pin = document.getElementById('staff-pin-input').value.trim();  
            if (!name || !pin) return;  
            const branch = currentBranch();  
            branch.staff.push({ name, pin });  
            saveData();  
            renderStaff();  
            document.getElementById('staff-name-input').value = '';  
            document.getElementById('staff-pin-input').value = '';  
        }  
  
        function renderStaff() {  
            const tbody = document.getElementById('staff-body');  
            if (!tbody) return;  
            tbody.innerHTML = '';  
            const branch = currentBranch();  
            branch.staff.forEach(s => {  
                tbody.innerHTML += `<tr><td>${s.name}</td><td>****</td></tr>`;  
            });  
        }  
  
        function addCustomer() {  
            const name = document.getElementById('cust-name').value.trim();  
            const balance = parseFloat(document.getElementById('cust-bal').value) || 0;  
            if (!name) return;  
            const branch = currentBranch();  
            branch.customers.push({ name, balance });  
            saveData();  
            renderCustomers();  
            document.getElementById('cust-name').value = '';  
            document.getElementById('cust-bal').value = '';  
        }  
  
        function renderCustomers() {  
            const tbody = document.getElementById('cust-body');  
            if (!tbody) return;  
            tbody.innerHTML = '';  
            const branch = currentBranch();  
            branch.customers.forEach(c => {  
                tbody.innerHTML += `<tr><td>${c.name}</td><td>₦${c.balance.toLocaleString()}</td></tr>`;  
            });  
        }  
  
        function renderBranchesList() {  
            const select = document.getElementById('branch-select');  
            if (!select) return;  
            select.innerHTML = '';  
            for (let bId in db.branches) {  
                const b = db.branches[bId];  
                const selected = bId === currentBranchId ? 'selected' : '';  
                select.innerHTML += `<option value="${bId}" ${selected}>${b.storeName}</option>`;  
            }  
        }  
  
        function switchBranch(bId) {  
            currentBranchId = bId;  
            setupDashboardUI();  
        }  
  
        function addNewBranch() {  
            const name = document.getElementById('new-branch-name').value.trim();  
            if (!name) {  
                alert('Please enter a branch name.');  
                return;  
            }  
            const branchKey = 'branch_' + Date.now();  
            db.branches[branchKey] = {  
                storeName: name,  
                storeAddress: currentBranch().storeAddress,  
                telephone: currentBranch().telephone,  
                motto: currentBranch().motto,  
                products: [...currentBranch().products],  
                sales: [],  
                staff: [],  
                customers: []  
            };  
            currentBranchId = branchKey;  
            saveData();  
            document.getElementById('new-branch-name').value = '';  
            renderBranchesList();  
            setupDashboardUI();  
            alert(`Branch "${name}" created and set as active.`);  
        }  
  
        function updateAdminPin() {  
            const newPin = document.getElementById('new-admin-pin').value.trim();  
            if (!newPin) {  
                alert('Please enter a valid PIN.');  
                return;  
            }  
            db.adminPin = newPin;  
            saveData();  
            alert('Master Admin password/PIN updated successfully!');  
            document.getElementById('new-admin-pin').value = '';  
        }  
    </script>  
</body>  
</html>  
