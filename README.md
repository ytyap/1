# 1

### Goals:
### Merge 3 tables on a common PK
### At the same  time, add a new column to record today's date

import xls
import pandas as pd

info = pd.read_excel('ProjectInfo.xls')
info.head()

#ALTER TABLE `ProjectInfo.xls` RENAME COLUMN "column 1" TO "Project_Name";
  
  
