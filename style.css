/* --- BASE STYLES --- */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: #1e1e1e;
  color: #ecf0f1;
  margin: 0;
  padding: 0 20px 20px 20px;
  transition: all 0.3s ease;
}

/* --- STICKY TOOLBAR --- */
.top-bar {
  display: flex;
  align-items: center;
  gap: 15px;
  background: #2c3e50;
  padding: 10px 20px;
  border-bottom: 1px solid #555;
  flex-wrap: wrap;
  position: sticky;
  top: 0;
  z-index: 100;
  margin-bottom: 20px;
}

.top-bar h1 { margin: 0; font-size: 20px; color: #16a085; }
.control-group { display: flex; align-items: center; gap: 8px; }
.top-bar label { font-size: 12px; font-weight: bold; color: #bdc3c7; }

/* --- HELP ICON & MODAL --- */
.help-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 22px;
  height: 22px;
  background-color: #16a085;
  color: white;
  border-radius: 50%;
  cursor: pointer;
  font-weight: bold;
}

.modal {
  display: none; 
  position: fixed; 
  z-index: 200; 
  left: 0; top: 0; width: 100%; height: 100%; 
  background-color: rgba(0,0,0,0.8);
}

.modal-content {
  background-color: #2c3e50;
  margin: 10% auto;
  padding: 25px;
  width: 50%;
  border-radius: 10px;
  color: #ecf0f1;
  border: 1px solid #555;
}

.close-btn { float: right; font-size: 24px; cursor: pointer; color: #aaa; }
.close-btn:hover { color: #e74c3c; }

/* --- UI ELEMENTS --- */
input[type="file"], select, button {
  padding: 5px 8px;
  font-size: 12px;
  border-radius: 4px;
  background-color: #34495e;
  color: #ecf0f1;
  border: 1px solid #555;
  cursor: pointer;
}

button#clearCsv { background-color: #e74c3c; border: none; }
button#toggleTheme { background-color: #16a085; border: none; }

/* --- TABLE STYLING --- */
.table-section { margin-bottom: 30px; }
.main-table-title { font-size: 22px; color: #16a085; text-transform: uppercase; margin-bottom: 5px; }
.table-total { font-size: 18px; font-weight: bold; margin-left: 10px; color: #2ecc71; }

.table-container {
  overflow: auto;
  max-height: 500px;
  background: #2c3e50;
  border-radius: 6px;
  border: 1px solid #555;
}

table { width: 100%; border-collapse: collapse; font-size: 12px; }
th, td { border: 1px solid #555; padding: 8px; text-align: left; white-space: nowrap; }
th { background-color: #34495e; text-align: center; }

tr:nth-child(even) { background-color: #3c4a5a; }

/* TOTALS ROW - DARK SHADING */
tr.totals-row td {
  font-weight: bold;
  background-color: #1a242f !important;
  color: #f1c40f;
}

.highlight-col { background-color: #2c3e50 !important; }
.group-divider { border-right: 2px solid #16a085 !important; }

/* --- LIGHT MODE --- */
body.light-mode { background: #f4f4f4; color: #2c3e50; }
body.light-mode .top-bar, body.light-mode .modal-content { background: #fff; color: #2c3e50; }
body.light-mode .table-container { background: #fff; }
body.light-mode tr.totals-row td { background-color: #dcdde1 !important; color: #2c3e50; }
