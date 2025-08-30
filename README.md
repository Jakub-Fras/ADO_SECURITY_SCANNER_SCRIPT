# ADO_SECURITY_SCANNER_SCRIPT
Quickly scan an Azure DevOps organization & projects for security posture issues.  

The script is designed to:
- Quickly scan an Azure DevOps organization & projects for security posture issues
- Support read-only PATs (personal access tokens) so it works in restricted environments where read, write and manage PATs are not permitted
- Auto-generate timestamped reports with findings that are already saved by the OG tool
- Keep configuration lightweight – you only edit your org name and project name(s)

The heavy lifting is powered by [AzSK.ADO](https://github.com/azsk/ADOScanner-docs) (credit to the Microsoft CSE team / original AzSK.ADO maintainers).  
This repo only adds a minimal, ready-to-run script to save you from fighting with repeated prompts or setup quirks.

🔗 Related links:  
- [GitHub: AzSK ADOScanner](https://github.com/azsk/ADOScanner)  
- [Marketplace: ADO Security Scanner](https://marketplace.visualstudio.com/items?itemName=azsdktm.ADOSecurityScanner)
