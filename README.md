<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Oracle Licence Measurement Service</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f4f6f9;
}

.container {
    display: flex;
    min-height: 100vh;
}

/* Sidebar */

.sidebar {
    width: 260px;
    background: #1f2937;
    color: white;
    padding: 20px;
}

.sidebar h2 {
    margin-bottom: 25px;
}

.sidebar ul {
    list-style: none;
}

.sidebar li {
    padding: 12px;
    margin-bottom: 8px;
    border-radius: 8px;
    cursor: pointer;
}

.sidebar li:hover {
    background: #374151;
}

/* Main Content */

.main {
    flex: 1;
    padding: 20px;
}

.header {
    background: white;
    padding: 20px;
    border-radius: 12px;
    margin-bottom: 20px;
}

.header h1 {
    color: #1f2937;
}

/* KPI Cards */

.kpi-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
    margin-bottom: 20px;
}

.card {
    background: white;
    border-radius: 12px;
    padding: 20px;
    box-shadow: 0 1px 3px rgba(0,0,0,0.1);
}

.card h3 {
    color: #6b7280;
    font-size: 14px;
}

.card .value {
    font-size: 28px;
    font-weight: bold;
    margin-top: 10px;
}

/* Departments */

.departments {
    background: white;
    padding: 20px;
    border-radius: 12px;
    margin-bottom: 20px;
}

.department-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
    margin-top: 15px;
}

.department {
    background: #eef2ff;
    padding: 15px;
    border-radius: 10px;
    text-align: center;
    font-weight: bold;
}

/* Dashboard Layout */

.dashboard-grid {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 20px;
}

.powerbi {
    background: white;
    border-radius: 12px;
    padding: 20px;
}

.powerbi-placeholder {
    height: 450px;
    border: 2px dashed #cbd5e1;
    border-radius: 12px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #64748b;
    margin-top: 15px;
}

/* Side Panel */

.side-panel {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

/* Table */

table {
    width: 100%;
    border-collapse: collapse;
}

th {
    background: #f3f4f6;
    text-align: left;
    padding: 12px;
}

td {
    padding: 12px;
    border-bottom: 1px solid #e5e7eb;
}

.status-green {
    color: green;
    font-weight: bold;
}

.status-red {
    color: red;
    font-weight: bold;
}

/* Buttons */

.btn {
    background: #2563eb;
    color: white;
    border: none;
    padding: 10px 15px;
    border-radius: 8px;
    cursor: pointer;
}

.btn:hover {
    background: #1d4ed8;
}
</style>
</head>

<body>

<div class="container">

    <!-- Sidebar -->

    <div class="sidebar">
        <h2>Oracle Licence Platform</h2>

        <ul>
            <li>Overview</li>
            <li>Data Sources</li>
            <li>Licensing Models</li>
            <li>ETL Engine</li>
            <li>Power BI Reports</li>
            <li>Governance</li>
            <li>Audit Trail</li>
        </ul>
    </div>

    <!-- Main -->

    <div class="main">

        <div class="header">
            <h1>Oracle Licence Measurement Service</h1>
            <p>Enterprise Compliance & Cost Optimisation Platform</p>
        </div>

        <!-- KPI Cards -->

        <div class="kpi-grid">

            <div class="card">
                <h3>Oracle Databases</h3>
                <div class="value">128</div>
            </div>

            <div class="card">
                <h3>Processor Licences</h3>
                <div class="value">1,024</div>
            </div>

            <div class="card">
                <h3>Compliance Risks</h3>
                <div class="value">12</div>
            </div>

            <div class="card">
                <h3>Cost Exposure</h3>
                <div class="value">£2.4M</div>
            </div>

        </div>

        <!-- Departments -->

        <div class="departments">

            <h2>Oracle Licence Usage by Department</h2>

            <div class="department-grid">

                <div class="department">
                    Finance<br>
                    ERP / Reporting
                </div>

                <div class="department">
                    HR<br>
                    HCM / Payroll
                </div>

                <div class="department">
                    IT Operations<br>
                    Database & Middleware
                </div>

                <div class="department">
                    Customer Apps<br>
                    CRM & Integration
                </div>

            </div>

        </div>

        <div class="dashboard-grid">

            <!-- Power BI Section -->

            <div class="powerbi">

                <h2>Power BI Embedded Dashboard</h2>

                <div class="powerbi-placeholder">
                    Power BI Embedded Report Area
                </div>

            </div>

            <!-- Right Panel -->

            <div class="side-panel">

                <div class="card">
                    <h2>ETL Engine</h2>
                    <br>
                    <p><strong>Status:</strong> Successful</p>
                    <p><strong>Last Run:</strong> Today 02:00 AM</p>
                    <p><strong>Records:</strong> 1.2M</p>
                    <br>
                    <button class="btn">Run ETL</button>
                </div>

                <div class="card">
                    <h2>Governance</h2>
                    <br>
                    <p>✔ Rule Version Control</p>
                    <p>✔ Data Ownership</p>
                    <p>✔ Approval Workflow</p>
                    <p>✔ Audit Traceability</p>
                </div>

            </div>

        </div>

        <br>

        <!-- Licence Position -->

        <div class="card">

            <h2>Oracle Licence Position</h2>

            <br>

            <table>

                <thead>
                    <tr>
                        <th>Product</th>
                        <th>Licence Type</th>
                        <th>Required</th>
                        <th>Entitled</th>
                        <th>Gap</th>
                        <th>Status</th>
                    </tr>
                </thead>

                <tbody>

                    <tr>
                        <td>Database EE</td>
                        <td>Processor</td>
                        <td>120</td>
                        <td>100</td>
                        <td>-20</td>
                        <td class="status-red">Risk</td>
                    </tr>

                    <tr>
                        <td>WebLogic</td>
                        <td>Processor</td>
                        <td>40</td>
                        <td>50</td>
                        <td>+10</td>
                        <td class="status-green">Compliant</td>
                    </tr>

                    <tr>
                        <td>Oracle ERP</td>
                        <td>Named User Plus</td>
                        <td>850</td>
                        <td>900</td>
                        <td>+50</td>
                        <td class="status-green">Compliant</td>
                    </tr>

                </tbody>

            </table>

        </div>

    </div>

</div>

</body>
</html>
