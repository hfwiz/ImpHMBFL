# ImpHMBFL
The code for higher-order mutation and dataset.

## How to use CHMBFL
***Program Under Test***
- Put the Program under test into "./cdata/version", name it as "v*",*should be it's version num
- "./cdata/version/v*/test_data/true_root/source/tcas.c"should be the true version c program
- "./cdata/version/v*/test_data/defect_root/source/tcas.c"should be the fault version c program
- "./cdata/version/v*/test_data/inputs"should be the test cases
- "./cdata/version/v*/test_data/defect_root/Fault_Record"should be the Fault line in fault program
***Configuration***
- vc_path in CHMBFL.py is the path of excel,it record the version that we want to Test
- sheet in ChMBFL.py is the sheet that we want to read in vc_path
- the A line in sheet is the version name "v*",B line in sheet is the fault line.
- function main() in main_flow.py contains a parameter "ip_list", this is a Remote Environment Configuration

***Start***
- Run CHMBFL.py.
