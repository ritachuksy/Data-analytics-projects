# Medical Appointment Dataset Analysis (noshowappointment)


In this project I analyzed Medical Appointment **No Shows Dataset** using Python libraries NumPy, pandas, and communicated my findings with Matplotlib and seaborn. The dataset contained approximatly 111k appointments, about 20% of the patients didn't show up for their appointments while about 80% asummed showing up. Based on my analysis result I can say that gender has no effect on the no show variable. SMS_received variable has the highest correlation on the chart but needed more data for more exploration. Furthermore, there was no direct correlation among most of the independent variables and with the no-show variable. Even patients with scholarship missed their apointment with about 4% margin than patients without scholarship. On average, 20% of appointments were missed. Patients with health conditions are likely to turn up for their appointment.

**Out of 38685 appointments made by males, 7723 were missed with the ratio of 20%. Out of 71831 appointments made by females, 14588 were missed with the ratio of 20%.


## Limitations and suggestions:

One limitation that affected my analysis is the absence of relevant or backkgound data, the independent variables in the dataset provided has no clear correlation with the dependent varible.

**Providing Data like:** Time the sms was sent and the demographic information about patients that recieved them. The severity of patience with special condition.

## Requirement 
import numpy
import pandas
import matplotlib.pyplot
import seaborn 

%matplotlib inline
