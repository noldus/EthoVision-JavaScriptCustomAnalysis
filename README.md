# EthoVision-JavaScriptCustomAnalysis
This repository contains JavaScript scripts for processing EthoVision XT data.

Types of variables

Activity: These scripts process the Activity data, that is, the sample-by-sample change in pixel value. You can use them to analyze general movement and immobility in the arena (freezing, shoal activity). They do not focus on specific subjects.

Single-subject: These scripts process the data of focal subjects. You can use them with single-subject trials but also with multi-subject trials. In the latter case each subject is processed separately.

Multi-subject: These scripts analyze interactions between subjects, or produce arena-level results (e.g. when counting subjects in a zone). 


Instructions
1. Choose a script file, and copy the code to the clipboard.
2. In EthoVision XT, open an Analysis profile.
3. Choose one of the JavaScript options under **Custom Variables**. Make sure it corresponds to the last part pf the name of the script file (e.g. Continuous).
4. Delete the text in the window and paste your code.
5. Run analysis.

