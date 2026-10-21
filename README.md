<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,30,45&height=185&section=header&text=Emre%20Kaçar&fontSize=42&fontColor=fff&fontAlignY=38&desc=Database%20Administrator%20%26%20PL/SQL%20Specialist&descSize=18&descAlignY=62&animation=fadeIn" alt="Header" />
</p>

<h3 align="center">
  <img src="https://komarev.com/ghpvc/?username=emrkacar2&color=0e76a8&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />
</h3>

<div align="center">
  <p><i>⚡ "Architecting high-performance data pipelines, tuning execution plans, and scaling enterprise-grade databases."</i></p>
</div>

<hr/>

### `> whoami`

```sql
-- =====================================================================
-- SESSION CONNECTED TO: ORACLE ENTERPRISE DATABASE 19c/21c
-- USER: EMRKACAR2 (COMPUTER ENGINEER & DATABASE ADMINISTRATOR)
-- =====================================================================

SET SERVEROUTPUT ON SIZE UNLIMITED;

DECLARE
    v_developer_name  VARCHAR2(50) := 'Emre Kaçar';
    v_core_title      VARCHAR2(60) := 'Database Administrator & PL/SQL Specialist';
    v_optimization    VARCHAR2(50) := 'Execution Plan Tuning & Indexing';
BEGIN
    DBMS_OUTPUT.PUT_LINE('--------------------------------------------------');
    DBMS_OUTPUT.PUT_LINE('>>> INITIALIZING PROFILE EXECUTION... SUCCESS.');
    DBMS_OUTPUT.PUT_LINE('>>> NAME: ' || v_developer_name);
    DBMS_OUTPUT.PUT_LINE('>>> ROLE: ' || v_core_title);
    DBMS_OUTPUT.PUT_LINE('>>> FOCUS: ' || v_optimization);
    DBMS_OUTPUT.PUT_LINE('--------------------------------------------------');
END;
/

> cat profile.env
NAME="Emre Kaçar"
ROLE="Database Administrator & PL/SQL Specialist"
DEGREE="Computer Engineer"
FOCUS=("Oracle Database" "PostgreSQL" "PL/SQL Optimization" "ETL Pipelines" "Data Architecture")
