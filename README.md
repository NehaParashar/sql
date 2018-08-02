# sql
COLUMN report_date_col NEW_VALUE report_date
col report_date_col noprint
SELECT TO_CHAR ( SYSDATE ,'DD-Mon-YYYY:HH:MI') AS report_date_col FROM dual;

TTitle left "*** Rollback Information ( Date: &report_date ) ***" skip 2
