# "surfs up" Temperature Analysis

## Overview of the Analysis  
The purpose of this analysis is to evaluate weather trends in the months of June and December to determine if a sruf and ice cream shop is a viable business venture in Hawaii.  Using Python, pandas functions, and SQLAlchemy, we were able to query a database of temperatures to gather this information.

## Results  
    - Anecdotally, Hawaii is considered to be quite temperate, meaning there is little fluctuation in temperature year round.  Our analysis confirm this to be the case:    
    june_temps_df = pd.DataFrame(june_temps_list, columns=['temps']) Screen Shot 2022-07-04 at 4.40.21 PM.png  
    As we see in the screen shots above, the average temperature varies by about 3 dgrees from June to December.