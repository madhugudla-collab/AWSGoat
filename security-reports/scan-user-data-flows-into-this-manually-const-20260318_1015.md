# Security Analysis: User data flows into this manually-constructed SQL string. U

**Tool:** semgrep | **Language:** javascript
**Findings:** 51

## Affected Locations

- `modules\module-2\src\src\admin\admin-complaint.php` line 8: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\admin-complaint.php` line 17: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\admin-index.php` line 31: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\admin-index.php` line 32: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\admin-index.php` line 39: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\admin-index.php` line 63: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\admin-index.php` line 91: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\leave-approve.php` line 8: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\leave-approve.php` line 14: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\payslips.php` line 31: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\payslips.php` line 32: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\payslips.php` line 39: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\payslips.php` line 63: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\payslips.php` line 95: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\reimbursment-approve.php` line 8: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\admin\reimbursment-approve.php` line 14: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\adduser.php` line 13: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\adduser.php` line 27: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\adduser.php` line 35: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\deleteuser.php` line 7: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\deleteuser.php` line 8: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\leave-approve-super.php` line 8: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\leave-approve-super.php` line 14: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\reimbursment.php` line 32: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\reimbursment.php` line 33: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\reimbursment.php` line 40: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\superadmin-index.php` line 32: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\superadmin-index.php` line 33: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\superadmin-index.php` line 40: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\updateuser.php` line 17: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\updateuser.php` line 18: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\updateuser.php` line 25: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\user-settings.php` line 32: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\user-settings.php` line 33: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\superadmin\user-settings.php` line 40: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\complaint-apply.php` line 11: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\complaints.php` line 34: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\complaints.php` line 35: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\complaints.php` line 42: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\complaints.php` line 66: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\complaints.php` line 95: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\index.php` line 34: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\index.php` line 35: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\index.php` line 42: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\index.php` line 66: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\index.php` line 95: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\payslips.php` line 34: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\payslips.php` line 35: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\payslips.php` line 42: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\payslips.php` line 66: User data flows into this manually-constructed SQL string. User data can be safe
- `modules\module-2\src\src\user\payslips.php` line 95: User data flows into this manually-constructed SQL string. User data can be safe
