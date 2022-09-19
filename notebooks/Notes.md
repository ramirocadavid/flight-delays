Context
- Metadata (from other source), could be helpful: http://stat-computing.org/dataexpo/2009/
- From dataset creator
    - for taxing-in, taxing-out, diverting, and other delay reason columns, the unit is minutes - meaning how many minutes they spend on this delay reason. I hope that clears your question.
    - NAS: National Air System
    - CANCELLATION_CODE: A: Carrier, B: Weather, C: NAS (National Air System, as someone asked before), D: Security
    - Cancelled Flight Indicator and Diverted Flight Indicator, the numerical 1 means Yes to delay


Questions
- Is delayed caused by a late departure from dock or from waiting in the runway (wheels off), or diversion (or other causes)?

ML
- Forecast probability of delay
- Forecast delay time
- Predict probability of cancelation
- What factors contribute the most to delays