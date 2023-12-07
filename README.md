# Oyster-Reports
PROJECT DESCRIPTION: <br>
Project for housing code for generating FWRI Oyster reports.  RMarkdown scripts exist for each Report type and funding agency, but their method of use varies based on current data source and compilation method. Please refer to the "File Structure" and "File Use" sections. 
Data managers are currently the only FWRI staff who will be able to execute these scripts. Code is still being written and revised.

GETTING STARTED: <br>
You will need:<br> 
1. Microsoft SQL Server Management Studio (SSMS)
2. R/RStudio
3. Git
4. (Optional) GitHub Desktop or other GUI git tool
<br>
SUGGESTED WORKFLOW:

1. If you need to make changes, "Create an Issue" in GitHub describing what changes, additions, or issues need to be addressed.
2. Pull a current copy of this repo to your local machine.
3. Create a new branch to address the issue. Please use format: issue-#-Example when naming a new branch where # is the issue number and Example briefly describes the issue. Alternatively, on GitHub, on the Issues page: Development > Create a branch.
4. Work on the issue in your local branch.
5. Commit changes to save your work.
6. If more time or contributions from others is needed, publish your branch back to the GitHub repo.
7. When the issue is resolved, issue a pull request to have the changes merged into the main branch and close the outstanding issue.
8. Once a branch is merged, delete that branch.
<br> 
FILE STRUCTURE: <br>
/CERP - RMarkdown scripts for Comprehensive Everglades Restoration Plan project - Current versions: Monthly.<br>
/PBC - RMarkdown scripts for Plam Beach County project - Current versions: Monthly.<br>
/DMFM - RMarkdown scripts for sharing with the Division of Marine Fisheries Management  - Current versions: .<br>
/FLTIG - RMarkdown scripts for the Florida Trustees Implementation Group Data Gaps project  - Current versions: .<br>
/NFWF2 - RMarkdown scripts for the National Fish and Wildlife Foundation 2.0 project - Current versions: .<br>
<br>
FILE USE:<br>
/CERP - Compiling monthly reports from Excel data files into Word doucument outputs on the Molluscs network using RMarkdown. Code will need to be downloaded Oysters\CERP\R\Reports to ensure file mappings are accurate.<br>
/PBC - Compiling monthly reports from Excel data files into Word doucument outputs on the Molluscs network using RMarkdown. Code will need to be downloaded OOysters\Palm Beach County\Analyses\Reportsto ensure file mappings are accurate.<br>
/DMFM - .<br>
/FLTIG - .<br>
/NFWF2 - .<br>
<br>

REPORT TYPES: <br>
**CERP and PBC monthly reports consist of reporting obervations of mean salinity, recruitment, and dermo for the specified monthly and most recent month prior. PBC reports also include reporting of mean sedimentation rate and percent organic content for stations north and south of the C-51 output. When applicable, mean live and dead counts from oyster surveys are included. 
