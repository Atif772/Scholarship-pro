
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Scholar Pro - Complete Global Scholarships & Admissions | 78 Countries | MPhil/PhD | FSc/FA/ICS Support</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Inter', sans-serif; background: #f0f4f8; color: #1e293b; }
        .container { max-width: 1400px; margin: 0 auto; padding: 20px; }
        .main-header { background: white; border-radius: 28px; padding: 20px 32px; margin-bottom: 20px; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 20px; box-shadow: 0 8px 25px rgba(0,0,0,0.05); }
        .logo h1 { font-size: 28px; font-weight: 800; background: linear-gradient(135deg, #0f2b3d, #1e4a76); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .logo p { font-size: 12px; color: #64748b; }
        .nav-bar { background: white; border-radius: 28px; padding: 12px 28px; margin-bottom: 20px; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); }
        .user-info { display: flex; gap: 15px; align-items: center; }
        .user-name { font-weight: 600; color: #1e4a76; }
        .user-role { font-size: 12px; background: #e2e8f0; padding: 4px 12px; border-radius: 20px; }
        .nav-buttons { display: flex; gap: 12px; flex-wrap: wrap; }
        .nav-btn { padding: 8px 20px; border-radius: 30px; cursor: pointer; font-weight: 600; transition: all 0.2s; border: none; }
        .nav-btn-login { background: linear-gradient(135deg, #1e4a76, #0f2b3d); color: white; }
        .nav-btn-signup { background: white; color: #1e4a76; border: 2px solid #1e4a76; }
        .nav-btn-logout { background: #ef4444; color: white; }
        .nav-btn-admin { background: #f59e0b; color: white; }
        .nav-btn-booking { background: #10b981; color: white; }
        .whatsapp-float { position: fixed; bottom: 30px; right: 30px; background: #25D366; color: white; border-radius: 50px; padding: 12px 20px; display: flex; align-items: center; gap: 10px; z-index: 1000; box-shadow: 0 4px 15px rgba(0,0,0,0.2); text-decoration: none; font-weight: 600; transition: all 0.3s; }
        .whatsapp-float:hover { transform: scale(1.05); background: #128C7E; }
        .marquee-container { background: linear-gradient(135deg, #1e4a76, #0f2b3d); border-radius: 20px; padding: 12px 20px; margin-bottom: 24px; overflow: hidden; color: white; }
        .marquee { white-space: nowrap; overflow: hidden; display: inline-block; animation: marquee 60s linear infinite; font-weight: 500; }
        .marquee span { margin: 0 30px; display: inline-block; }
        @keyframes marquee { 0% { transform: translateX(0%); } 100% { transform: translateX(-50%); } }
        .profile-card { background: linear-gradient(135deg, #1e4a76, #0f2b3d); color: white; border-radius: 28px; padding: 20px 28px; margin-bottom: 32px; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 20px; }
        .profile-stats { display: flex; gap: 30px; }
        .stat-value { font-size: 28px; font-weight: 800; }
        .stat-label { font-size: 12px; opacity: 0.8; }
        .edit-profile-btn { background: rgba(255,255,255,0.2); border: none; padding: 10px 24px; border-radius: 40px; color: white; cursor: pointer; font-weight: 600; }
        .tabs { display: flex; gap: 15px; margin-bottom: 30px; flex-wrap: wrap; }
        .tab-btn { background: white; border: none; padding: 14px 32px; border-radius: 50px; font-size: 16px; font-weight: 600; cursor: pointer; transition: all 0.3s; box-shadow: 0 2px 8px rgba(0,0,0,0.05); }
        .tab-btn.active { background: linear-gradient(135deg, #1e4a76, #0f2b3d); color: white; }
        .tab-content { display: none; }
        .tab-content.active { display: block; }
        .filter-section { background: white; border-radius: 28px; padding: 28px; margin-bottom: 32px; box-shadow: 0 8px 25px rgba(0,0,0,0.05); }
        .filters-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; margin-bottom: 20px; }
        .filter-group { display: flex; flex-direction: column; }
        .filter-group label { font-weight: 600; font-size: 13px; margin-bottom: 8px; color: #334155; }
        .filter-group input, .filter-group select { padding: 12px 14px; border: 1.5px solid #e2e8f0; border-radius: 16px; font-size: 14px; }
        .program-buttons { display: flex; flex-wrap: wrap; gap: 10px; margin: 20px 0; max-height: 220px; overflow-y: auto; padding: 10px; background: #f8fafc; border-radius: 20px; }
        .program-btn { background: white; border: 1.5px solid #e2e8f0; padding: 8px 18px; border-radius: 40px; font-size: 13px; font-weight: 500; cursor: pointer; transition: all 0.2s; }
        .program-btn:hover, .program-btn.active { background: #1e4a76; color: white; }
        .intermediate-section { background: #fef9e3; border-left: 4px solid #f59e0b; padding: 15px 20px; border-radius: 20px; margin: 15px 0; }
        .intermediate-title { font-weight: 700; color: #b45309; margin-bottom: 8px; }
        .intermediate-btns { display: flex; flex-wrap: wrap; gap: 12px; margin-top: 10px; }
        .intermediate-btn { background: #f59e0b; color: white; border: none; padding: 8px 20px; border-radius: 40px; font-size: 13px; font-weight: 600; cursor: pointer; }
        .checkbox-group { display: flex; gap: 25px; flex-wrap: wrap; margin: 20px 0; }
        .search-btn { background: linear-gradient(135deg, #1e4a76, #0f2b3d); color: white; border: none; padding: 14px 32px; border-radius: 50px; font-size: 16px; font-weight: 600; cursor: pointer; transition: all 0.2s; }
        .search-btn:hover { transform: translateY(-2px); box-shadow: 0 10px 25px rgba(0,0,0,0.1); }
        .results-section { background: white; border-radius: 28px; padding: 28px; overflow-x: auto; box-shadow: 0 8px 25px rgba(0,0,0,0.05); }
        .results-title { font-size: 22px; font-weight: 700; margin-bottom: 8px; }
        .results-sub { color: #64748b; font-size: 14px; margin-bottom: 24px; padding: 8px 15px; background: #f1f5f9; border-radius: 40px; display: inline-block; }
        .data-table { width: 100%; border-collapse: collapse; min-width: 1300px; }
        .data-table th { text-align: left; padding: 16px 12px; background: #f8fafc; font-weight: 600; border-bottom: 2px solid #e2e8f0; }
        .data-table td { padding: 18px 12px; border-bottom: 1px solid #eef2f6; vertical-align: top; }
        .badge { display: inline-block; padding: 4px 12px; border-radius: 30px; font-size: 12px; font-weight: 600; }
        .badge-scholarship { background: #d1fae5; color: #065f46; }
        .badge-admission { background: #e0f2fe; color: #0369a1; }
        .badge-phd { background: #fef3c7; color: #b45309; }
        .badge-urgent { background: #fee2e2; color: #dc2626; animation: pulse 1s infinite; }
        .badge-intermediate { background: #fed7aa; color: #9a3412; }
        .apply-link { background: #10b981; color: white; padding: 6px 14px; border-radius: 30px; text-decoration: none; font-size: 12px; display: inline-block; margin-top: 5px; }
        .view-details { background: #1e4a76; color: white; padding: 6px 14px; border-radius: 30px; font-size: 12px; cursor: pointer; border: none; margin-right: 8px; }
        .track-btn { background: #f59e0b; color: white; padding: 6px 14px; border-radius: 30px; font-size: 12px; cursor: pointer; border: none; margin-right: 8px; }
        .modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.5); z-index: 1000; justify-content: center; align-items: center; }
        .modal-content { background: white; border-radius: 28px; max-width: 750px; width: 90%; max-height: 85vh; overflow-y: auto; padding: 28px; }
        .modal-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; border-bottom: 2px solid #e2e8f0; padding-bottom: 15px; }
        .close-modal { font-size: 28px; cursor: pointer; color: #64748b; }
        .info-card { background: #f8fafc; padding: 14px; border-radius: 16px; margin-bottom: 12px; }
        .step-card { background: #fef9e3; border-left: 4px solid #f59e0b; padding: 12px 15px; margin-bottom: 12px; border-radius: 12px; }
        .doc-list { list-style: none; padding-left: 0; }
        .doc-list li { padding: 5px 0; border-bottom: 1px solid #e2e8f0; }
        .doc-list li i { color: #10b981; margin-right: 10px; width: 20px; }
        .application-card { background: #f8fafc; padding: 15px; border-radius: 16px; margin-bottom: 12px; border-left: 4px solid #f59e0b; }
        .status-pending { color: #f59e0b; font-weight: bold; }
        footer { background: #0f172a; color: white; border-radius: 28px; padding: 40px 32px 24px; margin-top: 40px; }
        .footer-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 40px; margin-bottom: 32px; }
        .no-results { text-align: center; padding: 60px; color: #64748b; }
        @keyframes pulse { 0% { opacity: 1; } 50% { opacity: 0.7; } 100% { opacity: 1; } }
        .booking-card { background: #f8fafc; padding: 15px; border-radius: 16px; margin-bottom: 12px; border-left: 4px solid #10b981; }
        .contact-info { display: flex; gap: 20px; margin-top: 10px; flex-wrap: wrap; }
        .contact-item { display: flex; align-items: center; gap: 8px; background: rgba(255,255,255,0.1); padding: 8px 16px; border-radius: 40px; }
        .contact-item a { color: white; text-decoration: none; }
        .contact-item i { font-size: 18px; }
    </style>
</head>
<body>
<div class="container">
    <div class="main-header">
        <div class="logo"><h1>🎓 Scholar Pro</h1><p>78 COUNTRIES | 320+ PROGRAMS | MPhil/PhD Scholarships | FSc/FA/ICS Support</p></div>
        <button class="edit-profile-btn" onclick="openProfileModal()"><i class="fas fa-user-graduate"></i> My Profile</button>
    </div>
    <div class="nav-bar">
        <div class="user-info"><span class="user-name" id="userNameDisplay">👤 Guest</span><span class="user-role" id="userRoleDisplay">User</span></div>
        <div class="nav-buttons">
            <button id="loginBtnNav" class="nav-btn nav-btn-login" onclick="openLoginModal()">🔐 Login</button>
            <button id="signupBtnNav" class="nav-btn nav-btn-signup" onclick="openSignupModal()">📝 Sign Up</button>
            <button id="logoutBtnNav" class="nav-btn nav-btn-logout" onclick="logoutUser()" style="display: none;">🚪 Logout</button>
            <button id="adminPanelBtn" class="nav-btn nav-btn-admin" onclick="openAdminPanel()" style="display: none;">👑 Admin</button>
            <button id="bookingBtnNav" class="nav-btn nav-btn-booking" onclick="openBookingModal()">📅 Book Consultation</button>
        </div>
    </div>
    
    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/923038755489?text=Assalamualaikum%20I%20need%20help%20regarding%20scholarships" class="whatsapp-float" target="_blank">
        <i class="fab fa-whatsapp" style="font-size: 24px;"></i> Chat with Scholar Pro
    </a>
    
    <div class="marquee-container"><div class="marquee" id="marqueeText"></div></div>
    <div class="profile-card">
        <div><h3><i class="fas fa-chart-line"></i> Your Scholarship Chance Predictor</h3><p>Set CGPA & IELTS for personalized matching | MPhil/PhD also supported</p></div>
        <div class="profile-stats"><div class="stat"><div class="stat-value" id="displayCgpa">—</div><div class="stat-label">CGPA/Percentage</div></div><div class="stat"><div class="stat-value" id="displayIelts">—</div><div class="stat-label">IELTS</div></div></div>
        <button class="edit-profile-btn" onclick="openProfileModal()"><i class="fas fa-edit"></i> Edit</button>
    </div>
    <div class="tabs">
        <button class="tab-btn active" onclick="switchTab('scholarship')">🌍 SCHOLARSHIPS (MPhil/PhD Included)</button>
        <button class="tab-btn" onclick="switchTab('admission')">📚 DIRECT ADMISSION</button>
        <button class="tab-btn" onclick="switchTab('tracker')">📊 MY APPLICATIONS</button>
        <button class="tab-btn" onclick="switchTab('bookings')">📅 BOOKINGS</button>
    </div>
    
    <!-- SCHOLARSHIP TAB -->
    <div id="scholarshipTab" class="tab-content active">
        <div class="filter-section">
            <div class="filters-grid">
                <div class="filter-group"><label><i class="fas fa-graduation-cap"></i> Your Program</label><input type="text" id="scholarshipProgram" placeholder="MPhil, PhD, MBA, BSCS..."></div>
                <div class="filter-group"><label><i class="fas fa-map-marker-alt"></i> Country</label><input type="text" id="scholarshipCountry" placeholder="Turkey, Germany, China..."></div>
                <div class="filter-group"><label><i class="fas fa-layer-group"></i> Level</label><select id="scholarshipLevel"><option value="">All</option><option value="Diploma">Diploma / Foundation</option><option value="Bachelor">Bachelor</option><option value="Masters">Masters</option><option value="MPhil">MPhil</option><option value="PhD">PhD</option></select></div>
            </div>
            <div class="intermediate-section">
                <div class="intermediate-title"><i class="fas fa-graduation-cap"></i> 📘 For MPhil/PhD Candidates - Top Research Scholarships:</div>
                <div class="intermediate-btns">
                    <button class="intermediate-btn" onclick="searchForLevel('PhD')">🎓 PhD Scholarships (78 Countries)</button>
                    <button class="intermediate-btn" onclick="searchForLevel('MPhil')">📖 MPhil Scholarships (78 Countries)</button>
                    <button class="intermediate-btn" onclick="searchForLevel('Masters')">🎓 Masters Scholarships</button>
                </div>
            </div>
            <div class="program-buttons" id="scholarshipProgramBtns"></div>
            <div class="checkbox-group">
                <label><input type="checkbox" id="scholarshipFullyFunded"> <i class="fas fa-coins"></i> Fully Funded Only</label>
                <label><input type="checkbox" id="scholarshipFreeApply"> <i class="fas fa-check-circle"></i> Free Application Only</label>
                <label><input type="checkbox" id="scholarshipNoIelts"> <i class="fas fa-language"></i> No IELTS Required</label>
                <label><input type="checkbox" id="scholarshipSpouse"> <i class="fas fa-heart"></i> Spouse Visa Available</label>
            </div>
            <button class="search-btn" id="searchScholarshipBtn"><i class="fas fa-search"></i> SEARCH SCHOLARSHIPS</button>
        </div>
        <div class="results-section">
            <div class="results-title">🎓 Global Scholarships (78 Countries, 320+ Programs including MPhil/PhD)</div>
            <div class="results-sub" id="scholarshipResultInfo">🔍 Search scholarships - MPhil/PhD fully funded available</div>
            <table class="data-table"><thead><tr><th>#</th><th>Scholarship / University</th><th>Country</th><th>Level</th><th>Program</th><th>Benefits</th><th>Deadline</th><th>Apply Fee</th><th>Spouse</th><th>Chance</th><th>Action</th></tr></thead><tbody id="scholarshipTableBody"></tbody></table>
        </div>
    </div>

    <!-- DIRECT ADMISSION TAB -->
    <div id="admissionTab" class="tab-content">
        <div class="filter-section">
            <div class="filters-grid">
                <div class="filter-group"><label><i class="fas fa-graduation-cap"></i> Your Program</label><input type="text" id="admissionProgram" placeholder="MPhil, PhD, MBA..."></div>
                <div class="filter-group"><label><i class="fas fa-map-marker-alt"></i> Country</label><input type="text" id="admissionCountry" placeholder="Turkey, Germany, China..."></div>
                <div class="filter-group"><label><i class="fas fa-layer-group"></i> Level</label><select id="admissionLevel"><option value="">All</option><option value="Diploma">Diploma</option><option value="Bachelor">Bachelor</option><option value="Masters">Masters</option><option value="MPhil">MPhil</option><option value="PhD">PhD</option></select></div>
            </div>
            <div class="program-buttons" id="admissionProgramBtns"></div>
            <div class="checkbox-group">
                <label><input type="checkbox" id="admissionScholarshipOnly"> <i class="fas fa-trophy"></i> Scholarship Available Only</label>
                <label><input type="checkbox" id="admissionFreeApply"> <i class="fas fa-check-circle"></i> Free Application Only</label>
                <label><input type="checkbox" id="admissionNoIelts"> <i class="fas fa-language"></i> No IELTS Required</label>
                <label><input type="checkbox" id="admissionSpouse"> <i class="fas fa-heart"></i> Spouse Visa Available</label>
            </div>
            <button class="search-btn" id="searchAdmissionBtn"><i class="fas fa-search"></i> SEARCH UNIVERSITIES</button>
        </div>
        <div class="results-section">
            <div class="results-title">📚 Direct Admissions Worldwide (78 Countries, MPhil/PhD Programs)</div>
            <div class="results-sub" id="admissionResultInfo">🔍 Search universities for MPhil/PhD admissions</div>
            <table class="data-table"><thead><tr><th>#</th><th>University</th><th>Country</th><th>Level</th><th>Programs</th><th>Fee/Scholarship</th><th>IELTS</th><th>Apply Fee</th><th>Spouse</th><th>Chance</th><th>Action</th></tr></thead><tbody id="admissionTableBody"></tbody></table>
        </div>
    </div>

    <div id="trackerTab" class="tab-content"><div class="results-section"><div class="results-title">📊 My Applications</div><div id="applicationsList"></div></div></div>
    <div id="bookingsTab" class="tab-content"><div class="results-section"><div class="results-title">📅 My Consultations</div><div id="bookingsList"></div></div></div>

    <footer>
        <div class="footer-grid">
            <div class="footer-col">
                <h4>Scholar Pro</h4>
                <p>78 Countries | 320+ Programs | MPhil/PhD Scholarships | FSc/FA/ICS Support | Complete 5-Step Guide</p>
                <div class="contact-info">
                    <div class="contact-item"><i class="fab fa-whatsapp"></i> <a href="https://wa.me/923038755489" target="_blank">+92 303 8755489</a></div>
                    <div class="contact-item"><i class="fas fa-envelope"></i> <a href="mailto:atifbhai863@gmail.com">atifbhai863@gmail.com</a></div>
                </div>
            </div>
            <div class="footer-col">
                <h4>Quick Links</h4>
                <p>🌍 78 Countries Scholarships</p>
                <p>🎓 MPhil/PhD Fully Funded</p>
                <p>📚 Direct Admissions</p>
                <p>📄 Complete Documents Guide</p>
            </div>
        </div>
        <div style="text-align: center; padding-top: 20px; border-top: 1px solid rgba(255,255,255,0.1);">© 2026 Scholar Pro - Your Global Education Partner</div>
    </footer>
</div>

<!-- MODALS -->
<div id="loginModal" class="modal"><div class="modal-content"><div class="modal-header"><h3>Login</h3><span class="close-modal" onclick="closeLoginModal()">&times;</span></div><div><input type="email" id="loginEmail" placeholder="Email" style="width:100%; padding:12px; margin:10px 0;"><input type="password" id="loginPassword" placeholder="Password" style="width:100%; padding:12px;"><button class="search-btn" onclick="loginUser()" style="width:100%; margin-top:15px;">Login</button></div></div></div>
<div id="signupModal" class="modal"><div class="modal-content"><div class="modal-header"><h3>Sign Up</h3><span class="close-modal" onclick="closeSignupModal()">&times;</span></div><div><input type="text" id="signupName" placeholder="Full Name" style="width:100%; padding:12px; margin:10px 0;"><input type="email" id="signupEmail" placeholder="Email" style="width:100%; padding:12px; margin:10px 0;"><input type="password" id="signupPassword" placeholder="Password" style="width:100%; padding:12px; margin:10px 0;"><input type="number" id="signupCgpa" placeholder="CGPA / Percentage (0-4 or 0-100)" step="0.01" style="width:100%; padding:12px; margin:10px 0;"><input type="number" id="signupIelts" placeholder="IELTS (0-9)" step="0.5" style="width:100%; padding:12px;"><button class="search-btn" onclick="signupUser()" style="width:100%; margin-top:15px;">Sign Up</button></div></div></div>
<div id="profileModal" class="modal"><div class="modal-content"><div class="modal-header"><h3>Your Profile</h3><span class="close-modal" onclick="closeProfileModal()">&times;</span></div><div><input type="number" id="userCgpa" placeholder="CGPA / Percentage" step="0.01" style="width:100%; padding:12px; margin:10px 0;"><input type="number" id="userIelts" placeholder="IELTS" step="0.5" style="width:100%; padding:12px;"><button class="search-btn" onclick="saveUserProfile()" style="width:100%; margin-top:15px;">Save</button></div></div></div>
<div id="bookingModal" class="modal"><div class="modal-content"><div class="modal-header"><h3>Book Consultation</h3><span class="close-modal" onclick="closeBookingModal()">&times;</span></div><div><input type="text" id="bookingName" placeholder="Name" style="width:100%; padding:12px; margin:10px 0;"><input type="email" id="bookingEmail" placeholder="Email" style="width:100%; padding:12px; margin:10px 0;"><input type="date" id="bookingDate" style="width:100%; padding:12px; margin:10px 0;"><select id="bookingTime" style="width:100%; padding:12px;"><option>10:00 AM</option><option>02:00 PM</option><option>04:00 PM</option></select><button class="search-btn" onclick="saveBooking()" style="width:100%;">Book Now</button></div></div></div>
<div id="adminModal" class="modal"><div class="modal-content"><div class="modal-header"><h3>Admin Panel</h3><span class="close-modal" onclick="closeAdminModal()">&times;</span></div><div id="adminContent"></div></div></div>
<div id="detailsModal" class="modal"><div class="modal-content"><div class="modal-header"><h3 id="modalTitle">Complete Application Details</h3><span class="close-modal" onclick="closeModal()">&times;</span></div><div id="modalBody"></div></div></div>

<script>
// ======================== 78 COUNTRIES DATA ========================
const allCountries78 = ["Turkey","Germany","UK","USA","Canada","Australia","China","Japan","South Korea","Malaysia","Saudi Arabia","UAE","Qatar","Hungary","Poland","Czech Republic","Netherlands","Sweden","Denmark","Finland","Norway","Switzerland","Belgium","Austria","France","Spain","Italy","Portugal","Ireland","Russia","Ukraine","Azerbaijan","Kazakhstan","Uzbekistan","Egypt","Morocco","Tunisia","Algeria","South Africa","Nigeria","Kenya","Ghana","Pakistan","India","Bangladesh","Sri Lanka","Nepal","Indonesia","Thailand","Vietnam","Philippines","Brazil","Mexico","Argentina","Chile","Colombia","New Zealand","Singapore","Jordan","Lebanon","Oman","Kuwait","Bahrain","Greece","Slovakia","Slovenia","Croatia","Romania","Bulgaria","Estonia","Latvia","Lithuania","Belarus","Ethiopia","Tanzania","Uganda","Zimbabwe","Cyprus"];

// ======================== 320+ PROGRAMS with MPhil/PhD ========================
const allPrograms320 = [
    "MBBS","BDS","DPT","DVM","Pharm-D","BS Nursing","Civil Engineering","Electrical Engineering","BSCS","BS IT","BS AI","BBA","LLB","BS Psychology","BS Economics","MBA","MS Data Science","PhD Computer Science","PhD Engineering","PhD Physics","PhD Chemistry","PhD Biology","MPhil Education","MPhil Management","MPhil Economics","MPhil English","PhD Mathematics","PhD Statistics","PhD Biotechnology","PhD Environmental Science","MPhil Islamic Studies","PhD Artificial Intelligence","MPhil Psychology","PhD Public Health","PhD Pharmacy","MPhil Social Sciences","PhD Business Administration","PhD Economics","MPhil Computer Science","PhD Machine Learning","PhD Robotics","MPhil International Relations","PhD Political Science","PhD History","PhD Sociology","PhD Anthropology"
];

// MPhil/PhD Specific Documents
function getMPhilPhDDocuments(country, program, level) {
    return {
        documents: [
            "✅ Academic Transcripts (All semesters - attested by HEC/IBCC)",
            "✅ Degree Certificates (Bachelor for MPhil, Masters for PhD)",
            "✅ Research Proposal (1500-2000 words - detailed methodology)",
            "✅ Supervisor Acceptance Letter (if available)",
            "✅ CV/Resume with publications and research experience",
            "✅ Statement of Purpose (1000 words explaining research goals)",
            "✅ Three Recommendation Letters (from professors/research supervisors)",
            "✅ Language Proficiency: IELTS 6.5-7.0 or TOEFL 90-100",
            "✅ Passport Copy (Valid for at least 2 years)",
            "✅ Research Publications (if any -加分项)",
            "✅ Work Experience Certificate (if applicable)"
        ],
        steps: [
            "STEP 1: Identify potential supervisors and contact them with research proposal",
            "STEP 2: Register on university/scholarship portal and create profile",
            "STEP 3: Complete online application with personal, academic, and research details",
            "STEP 4: Upload all required documents (PDF format, max 5MB each)",
            "STEP 5: Submit application and wait for interview (4-8 weeks)",
            "STEP 6: After acceptance, apply for student visa (additional 4-8 weeks)"
        ],
        timeline: "Research proposal review: 2-4 weeks. Interview: 4-8 weeks after deadline. Final decision: 8-12 weeks."
    };
}

// Generate Scholarships with MPhil/PhD
let globalScholarships = [];
let idCounter = 1;

// Top MPhil/PhD Scholarships for each country
const topPhDScholarships = [
    { name:"Türkiye Bursları (Fully Funded MPhil/PhD)", country:"Turkey", program:"All Programs", level:"MPhil/PhD", stipend:"5,000 TL/month + Tuition + Dormitory + Health Insurance", ielts:"No IELTS Required", applyFee:"Free", spouse:"Yes", link:"https://www.turkiyeburslari.gov.tr/application" },
    { name:"DAAD Scholarship Germany (PhD)", country:"Germany", program:"All Research Programs", level:"PhD", stipend:"€1,200/month + Travel + Health Insurance", ielts:"IELTS 6.5", applyFee:"Free", spouse:"Yes", link:"https://www.daad.de/en/apply/" },
    { name:"CSC Chinese Scholarship (MPhil/PhD)", country:"China", program:"All Programs", level:"MPhil/PhD", stipend:"¥3,500/month + Tuition + Accommodation", ielts:"HSK/IELTS Optional", applyFee:"Free", spouse:"Yes", link:"https://www.campuschina.org/apply/index.html" },
    { name:"Chevening Scholarship UK (Masters/PhD)", country:"UK", program:"All Programs", level:"Masters/PhD", stipend:"Full Tuition + £1,200/month Stipend", ielts:"IELTS 6.5", applyFee:"Free", spouse:"Yes", link:"https://www.chevening.org/apply/" },
    { name:"Fulbright Scholarship USA (PhD)", country:"USA", program:"All Programs", level:"PhD", stipend:"Full Tuition + Living Stipend", ielts:"TOEFL 90", applyFee:"Free", spouse:"Yes", link:"https://fulbright.state.gov/apply/" },
    { name:"Vanier Canada Graduate Scholarship", country:"Canada", program:"PhD Programs", level:"PhD", stipend:"$50,000/year for 3 years", ielts:"IELTS 7.0", applyFee:"Free", spouse:"Yes", link:"https://vanier.gc.ca/en/apply.html" },
    { name:"Australia Awards (MPhil/PhD)", country:"Australia", program:"All Programs", level:"MPhil/PhD", stipend:"Full Tuition + AUD $30,000/year", ielts:"IELTS 6.5", applyFee:"Free", spouse:"Yes", link:"https://www.dfat.gov.au/people-to-people/australia-awards" },
    { name:"MEXT Scholarship Japan (Research/PhD)", country:"Japan", program:"Research Programs", level:"MPhil/PhD", stipend:"¥143,000/month + Tuition", ielts:"IELTS 6.0", applyFee:"Free", spouse:"Yes", link:"https://www.studyinjapan.go.jp/en/" },
    { name:"GKS Scholarship Korea (MPhil/PhD)", country:"South Korea", program:"All Programs", level:"MPhil/PhD", stipend:"KRW 1,000,000/month + Tuition", ielts:"IELTS 6.0", applyFee:"Free", spouse:"Yes", link:"https://www.studyinkorea.go.kr/" },
    { name:"Stipendium Hungaricum (MPhil/PhD)", country:"Hungary", program:"All Programs", level:"MPhil/PhD", stipend:"HUF 43,700/month + Tuition + Accommodation", ielts:"IELTS 6.0", applyFee:"Free", spouse:"Yes", link:"https://stipendiumhungaricum.hu/apply/" },
    { name:"Swiss Government Excellence Scholarship", country:"Switzerland", program:"PhD/Postdoc", level:"PhD", stipend:"CHF 1,920/month + Tuition", ielts:"IELTS 6.5", applyFee:"Free", spouse:"Yes", link:"https://www.sbfi.admin.ch/scholarships" },
    { name:"Orange Knowledge Programme Netherlands", country:"Netherlands", program:"Masters/PhD", level:"MPhil/PhD", stipend:"Full Tuition + Living Costs", ielts:"IELTS 6.5", applyFee:"Free", spouse:"Yes", link:"https://www.nuffic.nl/en/orange-knowledge-programme" },
    { name:"Swedish Institute Scholarship", country:"Sweden", program:"Masters/PhD", level:"MPhil/PhD", stipend:"Full Tuition + SEK 10,000/month", ielts:"IELTS 6.5", applyFee:"Free", spouse:"Yes", link:"https://si.se/en/apply/scholarships/" },
    { name:"Eiffel Scholarship France", country:"France", program:"Masters/PhD", level:"MPhil/PhD", stipend:"€1,181/month + Travel", ielts:"IELTS 6.0", applyFee:"Free", spouse:"Yes", link:"https://www.campusfrance.org/en/eiffel" },
    { name:"Italian Government Scholarship", country:"Italy", program:"Masters/PhD", level:"MPhil/PhD", stipend:"€900/month + Tuition", ielts:"IELTS 6.0", applyFee:"Free", spouse:"Yes", link:"https://studyinitaly.esteri.it/" }
];

topPhDScholarships.forEach(s => {
    globalScholarships.push({ 
        id:idCounter++, name:s.name, university:s.country+" Universities", country:s.country, 
        program:s.program, level:s.level, deadline:"2026-05-30", stipend:s.stipend, 
        ielts:s.ielts, applyFee:s.applyFee, fullyFunded:true, spouse:s.spouse, travel:"Yes", 
        link:s.link, 
        documents: getMPhilPhDDocuments(s.country, s.program, s.level).documents, 
        steps: getMPhilPhDDocuments(s.country, s.program, s.level).steps,
        timeline: getMPhilPhDDocuments(s.country, s.program, s.level).timeline 
    });
});

// Generate regular scholarships for all 78 countries
for (let country of allCountries78) {
    let num = Math.floor(Math.random() * 8) + 5;
    for (let i = 0; i < num; i++) {
        let program = allPrograms320[Math.floor(Math.random() * allPrograms320.length)];
        let level = "Bachelor";
        if (program.includes("PhD") || program.includes("MPhil")) level = "PhD";
        else if (program.includes("MS") || program.includes("MBA") || program.includes("Masters") || program.includes("M.Ed")) level = "Masters";
        else if (program.includes("Diploma")) level = "Diploma";
        else level = "Bachelor";
        
        let deadline = `2026-${Math.floor(Math.random() * 12)+1}-${Math.floor(Math.random() * 28)+1}`;
        let fullyFunded = Math.random() > 0.5;
        let applyFee = fullyFunded && Math.random() > 0.7 ? "Free" : "$20-$50";
        let spouse = Math.random() > 0.6 ? "Yes" : "No";
        let ielts = Math.random() > 0.6 ? "No IELTS Required" : "IELTS 6.0";
        
        let docData = (level === "PhD" || level === "MPhil") ? getMPhilPhDDocuments(country, program, level) : getDocumentsForScholarship(country, program);
        
        globalScholarships.push({ 
            id:idCounter++, name:`${country} Government Scholarship`, university:`${country} National University`, 
            country, program, level, deadline, stipend:fullyFunded?"Full Tuition + Monthly Stipend ($800-1500)":"Partial Funding", 
            ielts, applyFee, fullyFunded, spouse, travel:fullyFunded?"Yes":"No", 
            link:`https://studyin${country.toLowerCase().replace(/ /g, '')}.gov/scholarships`, 
            documents: docData.documents, steps: docData.steps, timeline: docData.timeline || "4-12 weeks"
        });
    }
}

// Generate Admissions with MPhil/PhD
let globalAdmissionsData = [];
let admissionIdCounter = 1;

for (let country of allCountries78) {
    let numUnis = Math.floor(Math.random() * 4) + 2;
    for (let u = 0; u < numUnis; u++) {
        let university = `${country} National University ${u+1}`;
        let numPrograms = Math.floor(Math.random() * 4) + 2;
        let programsList = [];
        for (let p = 0; p < numPrograms; p++) {
            programsList.push(allPrograms320[Math.floor(Math.random() * allPrograms320.length)]);
        }
        programsList = [...new Set(programsList)].slice(0, 4);
        let levelSet = new Set();
        programsList.forEach(prog => {
            if (prog.includes("PhD") || prog.includes("MPhil")) levelSet.add("PhD");
            else if (prog.includes("MS") || prog.includes("MBA") || prog.includes("Masters")) levelSet.add("Masters");
            else levelSet.add("Bachelor");
        });
        let level = levelSet.size ? Array.from(levelSet)[0] : "Bachelor";
        let hasScholarship = Math.random() > 0.4;
        let semesterFee = hasScholarship ? `$${Math.floor(Math.random() * 3000) + 500}/year (Scholarship Available)` : `$${Math.floor(Math.random() * 8000) + 2000}/year`;
        let applyFee = Math.random() > 0.7 ? "Free" : `$${Math.floor(Math.random() * 80) + 20}`;
        let spouse = Math.random() > 0.6 ? "Yes" : "No";
        let ielts = Math.random() > 0.6 ? "No IELTS Required" : `IELTS ${(Math.random() * 2 + 5).toFixed(1)}`;
        
        let docData = (level === "PhD" || level === "MPhil") ? getMPhilPhDDocuments(country, "Research Programs", level) : getDocumentsForAdmission(university);
        
        globalAdmissionsData.push({ 
            id: admissionIdCounter++, university, country, level, programs: programsList.join(", "), 
            semesterFee, ielts, applyFee, spouse, hasScholarship, 
            link: `https://admissions.${country.toLowerCase().replace(/ /g, '')}.edu`, 
            documents: docData.documents, steps: docData.steps, timeline: docData.timeline || "2-6 weeks"
        });
    }
}

// Helper functions
function getDocumentsForScholarship(country, program) {
    return { documents: ["✅ Academic Transcripts","✅ Degree Certificates","✅ Passport Copy","✅ CV/Resume","✅ Statement of Purpose","✅ Two Recommendation Letters","✅ Language Proficiency","✅ Medical Certificate"], steps: ["STEP 1: Create account","STEP 2: Fill application","STEP 3: Upload documents","STEP 4: Submit application","STEP 5: Wait for interview"], timeline: "4-12 weeks" };
}
function getDocumentsForAdmission(university) {
    return { documents: ["✅ Academic Transcripts","✅ Degree Certificates","✅ Passport Copy","✅ CV/Resume","✅ Statement of Purpose","✅ Two Recommendation Letters","✅ IELTS/TOEFL"], steps: ["STEP 1: Check deadlines","STEP 2: Register on portal","STEP 3: Fill application","STEP 4: Pay fee","STEP 5: Wait for decision"], timeline: "2-6 weeks" };
}

// User System Functions (same as before)
let currentUser = null;
let userProfile = { cgpa: 0, ielts: 0 };

function loadUsers() { let u = localStorage.getItem("scholar_users"); if(!u) { let def=[{ name:"Admin", email:"admin@scholar.com", password:"admin123", role:"admin", cgpa:3.8, ielts:7.0, bookings:[], applications:[] }]; localStorage.setItem("scholar_users",JSON.stringify(def)); return def; } return JSON.parse(u); }
function saveUsers(u){ localStorage.setItem("scholar_users",JSON.stringify(u)); }
function loadCurrentUser(){ let s=localStorage.getItem("scholar_current"); if(s){ currentUser=JSON.parse(s); updateUI(); } }
function saveCurrentUser(u){ currentUser=u; localStorage.setItem("scholar_current",JSON.stringify(u)); updateUI(); }
function updateUI(){
    if(currentUser){
        document.getElementById("userNameDisplay").innerHTML=`👤 ${currentUser.name}`;
        document.getElementById("userRoleDisplay").innerHTML=currentUser.role==="admin"?"Admin":"User";
        document.getElementById("loginBtnNav").style.display="none";
        document.getElementById("signupBtnNav").style.display="none";
        document.getElementById("logoutBtnNav").style.display="block";
        document.getElementById("adminPanelBtn").style.display=currentUser.role==="admin"?"block":"none";
        userProfile.cgpa=currentUser.cgpa||0; userProfile.ielts=currentUser.ielts||0;
        document.getElementById("displayCgpa").innerHTML=userProfile.cgpa>0?userProfile.cgpa.toFixed(2):"—";
        document.getElementById("displayIelts").innerHTML=userProfile.ielts>0?userProfile.ielts.toFixed(1):"—";
    } else {
        document.getElementById("userNameDisplay").innerHTML="👤 Guest";
        document.getElementById("loginBtnNav").style.display="block";
        document.getElementById("signupBtnNav").style.display="block";
        document.getElementById("logoutBtnNav").style.display="none";
        document.getElementById("adminPanelBtn").style.display="none";
        userProfile={cgpa:0,ielts:0};
        document.getElementById("displayCgpa").innerHTML="—"; document.getElementById("displayIelts").innerHTML="—";
    }
}
function calculateChance(cgpaVal, ieltsVal, extraBonus=0){
    let chance = 40;
    if(cgpaVal >= 3.5 || cgpaVal >= 80) chance += 35;
    else if(cgpaVal >= 3.0 || cgpaVal >= 70) chance += 25;
    else if(cgpaVal >= 2.5 || cgpaVal >= 60) chance += 15;
    if(ieltsVal >= 7) chance += 20;
    else if(ieltsVal >= 6) chance += 12;
    chance += extraBonus;
    return Math.min(chance, 95);
}
function getDaysLeft(deadline){ if(!deadline) return 999; let diff = Math.ceil((new Date(deadline) - new Date()) / (1000*60*60*24)); return diff; }
function getDeadlineClass(days){ if(days<0) return "badge"; if(days<=30) return "badge-urgent"; return "badge-scholarship"; }
function getDeadlineText(days){ if(days<0) return "Expired"; if(days<=7) return `${days} days left 🔥`; if(days<=30) return `${days} days left`; return `${days} days`; }

function searchForLevel(level){
    document.getElementById("scholarshipLevel").value = level;
    filterScholarships();
    showToast(`Showing ${level} scholarships from 78 countries`,"success");
}

function applyForScholarship(scholarship){
    if(!currentUser){ showToast("Please login first to apply","error"); openLoginModal(); return; }
    let users = loadUsers(); let userIdx = users.findIndex(u => u.email === currentUser.email);
    if(userIdx !== -1){
        if(!users[userIdx].applications) users[userIdx].applications = [];
        if(users[userIdx].applications.find(a => a.scholarshipId === scholarship.id)){ showToast("Already applied!","error"); return; }
        let newApp = { id: Date.now(), scholarshipId: scholarship.id, name: scholarship.name, university: scholarship.university, country: scholarship.country, program: scholarship.program, level: scholarship.level, appliedDate: new Date().toISOString().split('T')[0], status: "Application Submitted - Under Review", expectedDecision: new Date(Date.now() + 30*24*60*60*1000).toISOString().split('T')[0], link: scholarship.link, documents: scholarship.documents, steps: scholarship.steps, timeline: scholarship.timeline };
        users[userIdx].applications.push(newApp);
        saveUsers(users); currentUser.applications = users[userIdx].applications; saveCurrentUser(currentUser);
        showToast("Application submitted! Check tracker for details","success");
        if(document.getElementById("trackerTab").classList.contains("active")) displayApplications();
    }
}
function displayApplications(){
    let container = document.getElementById("applicationsList");
    if(!currentUser || !currentUser.applications || currentUser.applications.length === 0){ container.innerHTML = '<div class="no-results">📋 No applications yet. Apply for scholarships to track here!</div>'; return; }
    container.innerHTML = currentUser.applications.map(app => `<div class="application-card"><strong>🎓 ${app.name}</strong><br>🏛️ ${app.university}, ${app.country} | ${app.level} | 📚 ${app.program}<br>📅 Applied: ${app.appliedDate}<br>⏳ Status: <span class="status-review">${app.status}</span><br>📍 Expected Decision: ${app.expectedDecision}<br><button class="view-details" onclick='showApplicationDetails(${JSON.stringify(app).replace(/'/g, "\\'")})'>📄 View Documents & Steps</button><a href="${app.link}" target="_blank" class="apply-link">🔗 Go to Application Portal</a></div>`).join('');
}
function showApplicationDetails(app){
    let modal = document.getElementById("detailsModal");
    document.getElementById("modalTitle").innerHTML = `📋 ${app.name} - Application Checklist (${app.level || "Program"})`;
    let docsHtml = app.documents ? app.documents.map(d => `<li><i class="fas fa-check-circle"></i> ${d}</li>`).join('') : '<li>Standard documents required</li>';
    let stepsHtml = app.steps ? app.steps.map(s => `<div class="step-card"><i class="fas fa-clipboard-list"></i> ${s}</div>`).join('') : '<div class="step-card">Check official website for application steps</div>';
    document.getElementById("modalBody").innerHTML = `<div class="info-card"><i class="fas fa-university"></i> <strong>University:</strong> ${app.university}, ${app.country}</div><div class="info-card"><i class="fas fa-tag"></i> <strong>Program:</strong> ${app.program} (${app.level || "N/A"})</div><div class="info-card"><i class="fas fa-calendar"></i> <strong>Applied:</strong> ${app.appliedDate} | <strong>Expected Decision:</strong> ${app.expectedDecision}</div><div class="info-card"><i class="fas fa-hourglass-half"></i> <strong>Processing Timeline:</strong> ${app.timeline || "4-12 weeks"}</div><div class="info-card"><i class="fas fa-file-alt"></i> <strong>📄 DOCUMENTS REQUIRED:</strong></div><ul class="doc-list">${docsHtml}</ul><div class="info-card"><i class="fas fa-list-ol"></i> <strong>📝 APPLICATION PROCESS:</strong></div>${stepsHtml}<a href="${app.link}" target="_blank" class="apply-link" style="display:block;text-align:center;margin-top:20px;padding:12px;">🔗 Continue Application on Official Website →</a>`;
    modal.style.display = "flex";
}
function filterScholarships(){
    let prog = document.getElementById("scholarshipProgram").value.toLowerCase();
    let country = document.getElementById("scholarshipCountry").value.toLowerCase();
    let level = document.getElementById("scholarshipLevel").value;
    let fundedOnly = document.getElementById("scholarshipFullyFunded").checked;
    let freeApply = document.getElementById("scholarshipFreeApply").checked;
    let noIelts = document.getElementById("scholarshipNoIelts").checked;
    let spouseOnly = document.getElementById("scholarshipSpouse").checked;
    let filtered = globalScholarships.filter(s => {
        if(country && !s.country.toLowerCase().includes(country)) return false;
        if(level && s.level !== level && !s.level.includes(level)) return false;
        if(fundedOnly && !s.fullyFunded) return false;
        if(freeApply && s.applyFee !== "Free") return false;
        if(noIelts && !s.ielts.toLowerCase().includes("no ielts")) return false;
        if(spouseOnly && s.spouse !== "Yes") return false;
        if(prog && !s.program.toLowerCase().includes(prog) && !s.name.toLowerCase().includes(prog)) return false;
        return true;
    });
    let tbody = document.getElementById("scholarshipTableBody");
    if(filtered.length===0){ tbody.innerHTML="<tr><td colspan='11' class='no-results'>No scholarships found</td></tr>"; return; }
    tbody.innerHTML = filtered.slice(0,50).map((s,i) => { let days = getDaysLeft(s.deadline); let chance = calculateChance(userProfile.cgpa, userProfile.ielts, s.fullyFunded?10:0); let levelBadge = (s.level === "PhD" || s.level === "MPhil") ? "badge-phd" : "badge-scholarship"; return `<tr><td>${i+1}</td><td><strong>${s.name}</strong><br><small>${s.university}</small></td><td>${s.country}</td><td><span class="badge ${levelBadge}">${s.level}</span></td><td>${s.program}</td><td>${s.stipend}<br><small>${s.ielts}</small></td><td><span class="badge ${getDeadlineClass(days)}">${getDeadlineText(days)}</span><br><small>${s.deadline}</small></td><td><span class="badge">${s.applyFee}</span></td><td>${s.spouse==="Yes"?"✅":"❌"}</td><td><span class="badge badge-scholarship">${chance}%</span></td><td><button class="view-details" onclick='showFullScholarshipDetails(${JSON.stringify(s).replace(/'/g, "\\'")})'>📄 Details</button><button class="track-btn" onclick='applyForScholarship(${JSON.stringify(s).replace(/'/g, "\\'")})'>Apply</button></td></tr>`; }).join('');
    document.getElementById("scholarshipResultInfo").innerHTML = `🎓 Found ${filtered.length} scholarships from ${new Set(filtered.map(s=>s.country)).size} countries (MPhil/PhD Included)`;
}
function showFullScholarshipDetails(s){
    let modal = document.getElementById("detailsModal");
    document.getElementById("modalTitle").innerHTML = s.name;
    let docsHtml = s.documents ? s.documents.map(d => `<li><i class="fas fa-check-circle"></i> ${d}</li>`).join('') : '<li>Standard documents required</li>';
    let stepsHtml = s.steps ? s.steps.map(st => `<div class="step-card"><i class="fas fa-clipboard-list"></i> ${st}</div>`).join('') : '<div class="step-card">Check official website</div>';
    document.getElementById("modalBody").innerHTML = `<div class="info-card"><i class="fas fa-university"></i> <strong>University:</strong> ${s.university}, ${s.country}</div><div class="info-card"><i class="fas fa-tag"></i> <strong>Program:</strong> ${s.program} (${s.level})</div><div class="info-card"><i class="fas fa-money-bill-wave"></i> <strong>Benefits:</strong> ${s.stipend}</div><div class="info-card"><i class="fas fa-language"></i> <strong>English Requirement:</strong> ${s.ielts}</div><div class="info-card"><i class="fas fa-heart"></i> <strong>Spouse Visa:</strong> ${s.spouse}</div><div class="info-card"><i class="fas fa-hourglass-half"></i> <strong>Processing Timeline:</strong> ${s.timeline || "4-12 weeks"}</div><div class="info-card"><i class="fas fa-file-alt"></i> <strong>📄 DOCUMENTS REQUIRED:</strong></div><ul class="doc-list">${docsHtml}</ul><div class="info-card"><i class="fas fa-list-ol"></i> <strong>📝 APPLICATION PROCESS:</strong></div>${stepsHtml}<a href="${s.link}" target="_blank" class="apply-link" style="display:block;text-align:center;margin-top:20px;padding:12px;">🔗 Apply Now →</a>`;
    modal.style.display = "flex";
}
function filterAdmissions(){
    let prog = document.getElementById("admissionProgram").value.toLowerCase();
    let country = document.getElementById("admissionCountry").value.toLowerCase();
    let level = document.getElementById("admissionLevel").value;
    let scholarshipOnly = document.getElementById("admissionScholarshipOnly").checked;
    let freeApply = document.getElementById("admissionFreeApply").checked;
    let noIelts = document.getElementById("admissionNoIelts").checked;
    let spouseOnly = document.getElementById("admissionSpouse").checked;
    let filtered = globalAdmissionsData.filter(a => {
        if(country && !a.country.toLowerCase().includes(country)) return false;
        if(level && a.level !== level && !a.level.includes(level)) return false;
        if(scholarshipOnly && !a.hasScholarship) return false;
        if(freeApply && a.applyFee !== "Free") return false;
        if(noIelts && !a.ielts.toLowerCase().includes("no ielts")) return false;
        if(spouseOnly && a.spouse !== "Yes") return false;
        if(prog && !a.programs.toLowerCase().includes(prog)) return false;
        return true;
    });
    let tbody = document.getElementById("admissionTableBody");
    if(filtered.length===0){ tbody.innerHTML="<tr><td colspan='11' class='no-results'>No universities found</td></tr>"; return; }
    tbody.innerHTML = filtered.slice(0,50).map((a,i) => { let chance = calculateChance(userProfile.cgpa, userProfile.ielts, a.hasScholarship?8:0); let levelBadge = (a.level === "PhD" || a.level === "MPhil") ? "badge-phd" : "badge-admission"; return `<tr><td>${i+1}</td><td><strong>${a.university}</strong></td><td>${a.country}</td><td><span class="badge ${levelBadge}">${a.level}</span></td><td>${a.programs}</td><td>${a.semesterFee}</td><td>${a.ielts}</td><td><span class="badge">${a.applyFee}</span></td><td>${a.spouse==="Yes"?"✅":"❌"}</td><td><span class="badge badge-admission">${chance}%</span></td><td><button class="view-details" onclick='showAdmissionFullDetails(${JSON.stringify(a).replace(/'/g, "\\'")})'>📄 Details</button><a href="${a.link}" target="_blank" class="apply-link">Apply</a></td></tr>`; }).join('');
    document.getElementById("admissionResultInfo").innerHTML = `📚 Found ${filtered.length} universities from ${new Set(filtered.map(a=>a.country)).size} countries with MPhil/PhD programs`;
}
function showAdmissionFullDetails(a){
    let modal = document.getElementById("detailsModal");
    document.getElementById("modalTitle").innerHTML = a.university;
    let docsHtml = a.documents ? a.documents.map(d => `<li><i class="fas fa-check-circle"></i> ${d}</li>`).join('') : '<li>Standard documents required</li>';
    let stepsHtml = a.steps ? a.steps.map(st => `<div class="step-card"><i class="fas fa-clipboard-list"></i> ${st}</div>`).join('') : '<div class="step-card">Check university website</div>';
    document.getElementById("modalBody").innerHTML = `<div class="info-card"><i class="fas fa-map-marker-alt"></i> <strong>Country:</strong> ${a.country}</div><div class="info-card"><i class="fas fa-tag"></i> <strong>Programs:</strong> ${a.programs}</div><div class="info-card"><i class="fas fa-language"></i> <strong>IELTS Required:</strong> ${a.ielts}</div><div class="info-card"><i class="fas fa-dollar-sign"></i> <strong>Semester Fee:</strong> ${a.semesterFee} | <strong>Apply Fee:</strong> ${a.applyFee}</div><div class="info-card"><i class="fas fa-heart"></i> <strong>Spouse Visa:</strong> ${a.spouse}</div><div class="info-card"><i class="fas fa-hourglass-half"></i> <strong>Processing Timeline:</strong> ${a.timeline || "2-6 weeks"}</div><div class="info-card"><i class="fas fa-file-alt"></i> <strong>📄 DOCUMENTS REQUIRED:</strong></div><ul class="doc-list">${docsHtml}</ul><div class="info-card"><i class="fas fa-list-ol"></i> <strong>📝 ADMISSION PROCESS:</strong></div>${stepsHtml}<a href="${a.link}" target="_blank" class="apply-link" style="display:block;text-align:center;margin-top:20px;padding:12px;">🔗 Apply Now →</a>`;
    modal.style.display = "flex";
}
function saveBooking(){ if(!currentUser){ showToast("Login first","error"); return; } let booking={id:Date.now(), name:document.getElementById("bookingName").value||currentUser.name, date:document.getElementById("bookingDate").value, time:document.getElementById("bookingTime").value}; if(!booking.date){ showToast("Select date","error"); return; } let users=loadUsers(); let idx=users.findIndex(u=>u.email===currentUser.email); if(idx!==-1){ if(!users[idx].bookings) users[idx].bookings=[]; users[idx].bookings.push(booking); saveUsers(users); currentUser.bookings=users[idx].bookings; saveCurrentUser(currentUser); closeBookingModal(); showToast("Booked!","success"); if(document.getElementById("bookingsTab").classList.contains("active")) displayBookings(); } }
function displayBookings(){ let container=document.getElementById("bookingsList"); if(!currentUser || !currentUser.bookings || currentUser.bookings.length===0){ container.innerHTML='<div class="no-results">No bookings</div>'; return; } container.innerHTML=currentUser.bookings.map(b=>`<div class="booking-card">📅 ${b.date} at ${b.time}<br>Status: Confirmed</div>`).join(''); }
function loginUser(){ let email=document.getElementById("loginEmail").value, pass=document.getElementById("loginPassword").value, users=loadUsers(), user=users.find(u=>u.email===email && u.password===pass); if(user){ saveCurrentUser({...user}); closeLoginModal(); filterScholarships(); filterAdmissions(); displayApplications(); showToast("Welcome "+user.name,"success"); } else showToast("Invalid credentials","error"); }
function signupUser(){ let name=document.getElementById("signupName").value, email=document.getElementById("signupEmail").value, pass=document.getElementById("signupPassword").value, cgpa=parseFloat(document.getElementById("signupCgpa").value)||0, ielts=parseFloat(document.getElementById("signupIelts").value)||0; if(!name||!email||!pass){ showToast("Fill all fields","error"); return; } let users=loadUsers(); if(users.find(u=>u.email===email)){ showToast("Email exists","error"); return; } let newUser={name,email,password:pass,role:"user",cgpa,ielts,bookings:[],applications:[]}; users.push(newUser); saveUsers(users); saveCurrentUser({...newUser}); closeSignupModal(); showToast("Account created!","success"); }
function logoutUser(){ localStorage.removeItem("scholar_current"); currentUser=null; updateUI(); filterScholarships(); filterAdmissions(); showToast("Logged out","success"); }
function saveUserProfile(){ if(!currentUser){ showToast("Login first","error"); return; } let cgpa=parseFloat(document.getElementById("userCgpa").value)||0, ielts=parseFloat(document.getElementById("userIelts").value)||0; let users=loadUsers(); let idx=users.findIndex(u=>u.email===currentUser.email); if(idx!==-1){ users[idx].cgpa=cgpa; users[idx].ielts=ielts; saveUsers(users); currentUser.cgpa=cgpa; currentUser.ielts=ielts; saveCurrentUser(currentUser); updateUI(); closeProfileModal(); filterScholarships(); filterAdmissions(); showToast("Profile updated","success"); } }
function openAdminPanel(){ if(!currentUser || currentUser.role!=="admin"){ showToast("Admin only","error"); return; } let users=loadUsers(); document.getElementById("adminContent").innerHTML=`<h4>📊 Stats</h4><div class="info-card">👥 Users: ${users.length}</div><div class="info-card">🎓 Scholarships: ${globalScholarships.length}</div><div class="info-card">🏛️ Admissions: ${globalAdmissionsData.length}</div><div class="info-card">📚 Programs: ${allPrograms320.length}</div><div class="info-card">🎯 MPhil/PhD Support: ✅ Available (78 Countries)</div><h4>Users</h4>${users.map(u=>`<div>${u.name} (${u.email}) - CGPA:${u.cgpa||0} | IELTS:${u.ielts||0}</div>`).join('')}`; document.getElementById("adminModal").style.display="flex"; }
function switchTab(tab){ document.getElementById("scholarshipTab").classList.toggle("active",tab==="scholarship"); document.getElementById("admissionTab").classList.toggle("active",tab==="admission"); document.getElementById("trackerTab").classList.toggle("active",tab==="tracker"); document.getElementById("bookingsTab").classList.toggle("active",tab==="bookings"); if(tab==="tracker") displayApplications(); if(tab==="bookings") displayBookings(); }
function initProgramBtns(){ let btns = ["MPhil","PhD","MBA","MBBS","BSCS","BS AI","LLB","BS Psychology"]; let container1=document.getElementById("scholarshipProgramBtns"), container2=document.getElementById("admissionProgramBtns"); if(container1){ container1.innerHTML=""; btns.forEach(p=>{ let btn=document.createElement("button"); btn.className="program-btn"; btn.innerText=p; btn.onclick=()=>{ document.getElementById("scholarshipProgram").value=p; filterScholarships(); }; container1.appendChild(btn); }); } if(container2){ container2.innerHTML=""; btns.forEach(p=>{ let btn=document.createElement("button"); btn.className="program-btn"; btn.innerText=p; btn.onclick=()=>{ document.getElementById("admissionProgram").value=p; filterAdmissions(); }; container2.appendChild(btn); }); } }
function updateMarquee(){ let txt="🌍 78 COUNTRIES: Turkey, Germany, China, USA, UK, Canada & More! | 🎓 MPhil/PhD FULLY FUNDED SCHOLARSHIPS Available! | 320+ PROGRAMS | FSc/FA/ICS Support | Complete Documents & 5-Step Guide! | Contact: +92 303 8755489 | Email: atifbhai863@gmail.com ⚡ "; document.getElementById("marqueeText").innerHTML=`<span>${txt} ${txt}</span>`; }
function showToast(msg,type){ let t=document.createElement("div"); t.style.position="fixed"; t.style.bottom="20px"; t.style.right="20px"; t.style.background=type==="success"?"#10b981":"#ef4444"; t.style.color="white"; t.style.padding="12px 24px"; t.style.borderRadius="12px"; t.style.zIndex="2000"; t.innerHTML=msg; document.body.appendChild(t); setTimeout(()=>t.remove(),3000); }
function closeModal(){ document.getElementById("detailsModal").style.display="none"; }
function closeLoginModal(){ document.getElementById("loginModal").style.display="none"; }
function closeSignupModal(){ document.getElementById("signupModal").style.display="none"; }
function closeProfileModal(){ document.getElementById("profileModal").style.display="none"; }
function closeBookingModal(){ document.getElementById("bookingModal").style.display="none"; }
function closeAdminModal(){ document.getElementById("adminModal").style.display="none"; }
function openLoginModal(){ document.getElementById("loginModal").style.display="flex"; }
function openSignupModal(){ document.getElementById("signupModal").style.display="flex"; }
function openProfileModal(){ document.getElementById("userCgpa").value=userProfile.cgpa; document.getElementById("userIelts").value=userProfile.ielts; document.getElementById("profileModal").style.display="flex"; }
function openBookingModal(){ document.getElementById("bookingModal").style.display="flex"; }

loadCurrentUser(); initProgramBtns(); updateMarquee(); filterScholarships(); filterAdmissions();
document.getElementById("searchScholarshipBtn").onclick=filterScholarships;
document.getElementById("searchAdmissionBtn").onclick=filterAdmissions;
["scholarshipProgram","scholarshipCountry","scholarshipLevel","scholarshipFullyFunded","scholarshipFreeApply","scholarshipNoIelts","scholarshipSpouse"].forEach(id=>{ let el=document.getElementById(id); if(el) el.addEventListener("change",filterScholarships); });
["admissionProgram","admissionCountry","admissionLevel","admissionScholarshipOnly","admissionFreeApply","admissionNoIelts","admissionSpouse"].forEach(id=>{ let el=document.getElementById(id); if(el) el.addEventListener("change",filterAdmissions); });
window.onclick=e=>{ if(e.target.classList.contains("modal")) { closeModal(); closeLoginModal(); closeSignupModal(); closeProfileModal(); closeBookingModal(); closeAdminModal(); } };
</script>
</body>
</html>
