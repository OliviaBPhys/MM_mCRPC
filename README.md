In cell 1 line 15: Enter the csv name of the Data set you would like to see the fit for 
                   patient_df = pd.read_csv("PatientData-Elife.csv")        for example

In cell 10 line 50: Enter the patient IDs you would like fits for 
                    patient_list = [1004,1005,1006,1007,2004,2005,2006,2007]    for example

Note:               For data set 1 (within PatientData.csv), patient IDs are simply the patient  number, e.g. Patient 3 is 3
                    For data set 2 (within PatientData-Elife.csv), patient IDs are prefixed by ‘10’, e.g. Patient 3 is 1003.
                    For data set 3 (within PatientData-Elife.csv, patient IDs are prefixed by ‘20’, e.g. Patient 3 is 2003.

                    When using patient_list, do not include patient IDs 2008, 2013, and 2019 as they are not within the csv, and the code wont work
