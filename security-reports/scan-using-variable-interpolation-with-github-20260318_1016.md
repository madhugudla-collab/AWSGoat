# Security Analysis: Using variable interpolation `${{...}}` with `github` contex

**Tool:** semgrep | **Language:** javascript
**Findings:** 8

## Affected Locations

- `.github\workflows\tf-apply-main.yml` line 60: Using variable interpolation `${{...}}` with `github` context data in a `run:` s
- `.github\workflows\tf-apply-main.yml` line 74: Using variable interpolation `${{...}}` with `github` context data in a `run:` s
- `.github\workflows\tf-apply-main.yml` line 84: Using variable interpolation `${{...}}` with `github` context data in a `run:` s
- `.github\workflows\tf-apply-main.yml` line 92: Using variable interpolation `${{...}}` with `github` context data in a `run:` s
- `.github\workflows\tf-apply-main.yml` line 98: Using variable interpolation `${{...}}` with `github` context data in a `run:` s
- `.github\workflows\tf-destroy-main.yml` line 47: Using variable interpolation `${{...}}` with `github` context data in a `run:` s
- `.github\workflows\tf-destroy-main.yml` line 53: Using variable interpolation `${{...}}` with `github` context data in a `run:` s
- `.github\workflows\tf-destroy-main.yml` line 58: Using variable interpolation `${{...}}` with `github` context data in a `run:` s
