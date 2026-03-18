<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CV Ayoub </title>


<style>
body {
    margin:0;
    font-family:'Lato','Helvetica Neue',Helvetica,Arial,sans-serif;
    background:#f0f2f5;
    color:#1f2937;
}

/* BUTTONS */
.actions {
    position:fixed;
    top:20px;
    right:20px;
    z-index:100;
}
.btn {
    background:#0a66c2;
    color:white;
    padding:10px 18px;
    border-radius:25px;
    cursor:pointer;
    margin-left:10px;
    font-weight:bold;
}

/* CV CONTAINER */
#cv {
    max-width:900px;
    margin:60px auto;
    padding:20px;
    display:flex;
    flex-direction:column;
    gap:20px;
}

/* CARD */
.card {
    background:white;
    border-radius:12px;
    padding:30px;
    box-shadow:0 10px 5px rgba(0,0,0,0.1);
}
/* HEADER */
.header {
    display:flex;
    align-items:center;
    justify-content:space-between;
    text-align:left;
    gap:20px;
}

.header-left {
    display:flex;
    align-items:center;
    gap:20px;
}

.header-left img {
    width:110px;
    height:110px;
    border-radius:50%;
    border:4px solid #0a66c2;
}

.header-info h1 {
    margin:0;
    font-size:26px;
}

.header-info p {
    margin:5px 0;
    color:#64748b;
}

.contact-info div {
    font-size:13px;
    margin:2px 0;
}

.qr {
    text-align:center;
}

.qr img {
    width:90px;
    height:90px;
}

.qr span {
    font-size:11px;
    color:#64748b;
}

/* SECTION TITLES */
.card h2 {
    font-size:18px;
    color:#0a66c2;
    border-bottom:2px solid #0a66c2;
    padding-bottom:6px;
    margin-bottom:12px;
}

/* CONTENT */
p, li {
    font-size:14px;
    line-height:1.6;
}
ul {
    padding-left:20px;
}

/* SKILLS */
.skill {
    display:inline-block;
    background:#22c55e;
    color:white;
    padding:6px 12px;
    border-radius:20px;
    margin:4px 4px 4px 0;
    font-weight:500;
    transition: transform 0.2s;
}
.skill:hover {
    transform: scale(1.1);
}

/* CENTRES D'INTERET */
.interests {
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    margin-top:10px;
}
.interest {
    background:#e5f1ff;
    color:#0a66c2;
    padding:6px 12px;
    border-radius:20px;
    font-size:14px;
}

/* PRINT */
@media print {
    .btn, .actions {
        display:none;
    }
    #cv {
        width:100%;
        margin:0;
        padding:0;
    }
    .card {
        box-shadow:none;
        border-radius:0;
        padding:20px;
        margin-bottom:5px;
    }

}
</style>
</head>
<body>

<div class="actions">
    <div class="btn" onclick="downloadPDF()">📄 Télécharger PDF</div>
    <div class="btn" onclick="window.print()">🖨️ Print</div>
</div>
<div id="cv">


    <!-- HEADER -->
<div class="card header">

    <!-- LEFT SIDE -->
    <div class="header-left">
        <img src="tof.jpeg" alt="Photo de profil">

        <div class="header-info">
        <h1>Ay</h1>
        <p>HSSE Specialist | Risk Management | Onshore/ Offshore Construction & Oil&Gas Safety</p>

            <div class="contact-info">
                <div>📞 +212 xxxxxxxx</div>
                <div>📧 test@gmail.com</div>
                <div>🔗 linkedin.com/in/b</div>
            </div>
        </div>
    </div>

    <!-- RIGHT SIDE QR -->
    <div class="qr">
        <img src="qr.jpeg" alt="QR LinkedIn"><BR>
        <span>Scan LinkedIn</span>
    </div>
 </div>


    <!-- PROFIL -->
    <div class="card">
        <h2>Profil</h2>
        <p>HSSE Specialist expérimenté en gestion des risques, audits et supervision chantier. Leadership terrain et réduction d’incidents. Capacité à influencer et motiver les équipes pour atteindre les objectifs HSE.</p>
    </div>
    <!-- EXPÉRIENCE -->
    <div class="card">
        <h2>Expérience Professionnelle</h2>
        <p><b>Project HSE Lead – JESA Group</b> (2023 – Présent)</p>


        <p><b>August 2025- Present:</b> Project 2: Renovation of Campus UM6P Terraces in Casablanca</p>
        <p><b>May 2023- July 2025:</b> Project 1: Construction of new Phosphate Port in
         Laayoune</p>

        <ul>
         <li>Review HSE Plans, Procedures, Method Statements, Risk assessments for
          the projects, & all Health, Safety & Environment related documentation to
         ensure compliance with the company requirements and regulations ;</li>
          <li>Monitor implementation of environmental mitigation measures during
           construction phases;</li>
           <li>Participate in regular site audits & inspections, and follow up actions plans.</li>
           <li>Participate in investigations of incidents, and issue related HSE reports.</li>
           <li>Collect and report relevant information as per the standard reporting in
           place.</li>
           <li>Regular meeting with client and contractors;</li>
            <li>Follow-up of HSE KPIs.</li>
             <li>Follow-up with contractors the regulatory verifications of equipment & its
           compliance ;</li>

        </ul>

        <p><b>IMS/HSSE Coordinator – HTTSA/ ENOC"Emirate National oil&Gas company</b> (2011 – 2023)</p>
      
         <ul>
         <li>HSSE support to HTTSA Employees and ensure that all practices are
         compliance to HTTSA’s EHSSQ & En policy & Requirements;</li>
         <li>Participate in the implementation and improvement of IMS System: ISO
         14001:2015, 45001:2018, ISO50001: 2018 and other certifications;</li>
       <li>Health/Safety Risk assessment and Environmental Impact Assessment;</li>
        <li>HSE projects follow up;</li>
        <li>Follow-up of regulatory verifications of equipment;</li>
        <li>Follow-up of environmental studies, surveys and the application of the
         environmental monitoring and surveillance plan “PSSE”.</li>
       <li>Participate in the investigation and analysis of incidents as and when
       required;</li>
       <li>Acting as Security correspondent, coordinate with public or port
       authorities since required;</li>
      <li>Conduct EHS Inspections/ HSE Contractors Audit;</li>
      <li>Conduct safety induction and EHS Campaigns;</li>
      <li>Ensure the implementation of trainings Programme;</li>
      <li>Supervision of security teams and CCTV teams.</li>
      <li>Firefighting incident controler</li>

        </ul>

    </div>
    <!-- COMPÉTENCES -->
    <div class="card">
        <h2>Compétences</h2>
        <span class="skill">Risk Management</span>
        <span class="skill">ISO 45001/ISO1400</span>
        <span class="skill">Audit HSE</span>
        <span class="skill">Leadership</span>
        <span class="skill">Incident Analysis</span>
        <span class="skill">Construction Safety</span>
        <span class="skill">Marine Construction Safety</span>
        <span class="skill">Asset & Oil&Gas Safety</span>
        <span class="skill">Firefighting Management</span>
    </div>
    <!-- FORMATION -->
    <div class="card">
        <h2>Formation</h2>
        <p><b>Inprogress 2026/2027: NEBOSH International Diploma L6</b> for Occupational Health and Safety
        Management Professionals (Bachelor degree equivalent)         /UK E-learning</p> 
        <p><b>2021: NEBOSH International generale Certificate L3</b> for Occupational health and safety management/ Hazards and control measures /ISCollege Casablanca</p>  
        <p><b>2020/2022: Master degree </b>: Management of quality, safety and environmental</p>
        <p>Project theme: Implementation of the occupational health and safety management system ISO45001 /FST Settat</p> 
        <p><b>2018: </b>Leading Safety Performance  /Conducted by Mr Daryl WAKE, Senior consultant in DEKRA</p>
        <p><b>2015: </b>Oil&Gas Terminal Supervisors Course  / The Centre for Maritime & Industrial Safety Technology Limited in UAE</p>
        <p><b>2010: Bachelor degree </b>: in Electrical Engineering  /FST Settat</p>
        <p><b>2007: Bac (scientific)</b>  /Sidi kacem</p>
   
    </div>
    <!-- CENTRES D'INTERET -->
    <div class="card">
        <h2>Centres d'intérêt</h2>
        <div class="interests">
            <span class="interest">Coding & Creativity</span>
            <span class="interest">Voyage</span>
            <span class="interest">Lecture</span>
            <span class="interest">Sports</span>
            <span class="interest">Technologies</span>
        </div>
    </div>
</div>

<script>
function downloadPDF() {
    const element = document.getElementById("cv");

    const opt = {
        margin: 10,
        filename: 'CV_Ayoub.pdf',
        image: { type: 'jpeg', quality: 0.98 },
        html2canvas: { scale: 2, useCORS: true, allowTaint: true },
        jsPDF: { unit: 'mm', format: 'a4', orientation: 'portrait' }
    };

    html2pdf().from(element).set(opt).save();
}
</script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>

</body>
</html>
