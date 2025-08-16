# Development-of-ADRC-for-Mobile-Robot-Using-Interval-Type-2-Fuzzy-Controller
An improved ADRC approach that swaps out the  conventional PD controller with the Interval Type-2 Fuzzy PD  (IT2FPD) controller. Unlike classical PD, the IT2FPD controller  utilizes fuzzy logic to dynamically adjust the proportional gain  based on the system’s error, allowing for improved adaptability  and disturbance rejection. 

# Abstract
Designing an effective control system is a cornerstone of robotics, but it’s no easy task, especially when it comes to ensuring reliable performance and managing unexpected disturbances. Active Disturbance Rejection Control (ADRC) has earned notable attention for its strength in tackling system uncertainties and external disruptions. Despite its popularity, traditional ADRC systems often rely on fixed gain Proportional Derivative (PD) controller, which can struggle to adapt in dynamic or unpredictable environments. To address this limitation, this paper introduces an improved ADRC approach that swaps out the conventional PD controller with the Interval Type-2 Fuzzy PD (IT2FPD) controller. Unlike classical PD, the IT2FPD controller utilizes fuzzy logic to dynamically adjust the proportional gain based on the system’s error, allowing for improved adaptability and disturbance rejection. The effectiveness of this technique is tested through trajectory tracking simulations on MATLAB. The results demonstrate that the ADRC based on IT2FPD (ADRC-IT2FPD) outperforms classical ADRC as well as Type-1 Fuzzy Logic PD (IT1FPD) controller, with enhanced stability, less trajectory tracking error and improved control on high magnitude disturbances

# Robot
Pioneer 3DX
<img width="514" height="485" alt="Picture1-removebg-preview" src="https://github.com/user-attachments/assets/ac5eac52-fafc-4328-94c1-0a5dce6df674" />


# Gallery
Block Diagram
![blockdiagram](https://github.com/user-attachments/assets/62862db9-9fa5-4068-b129-55ca24a26b7f)

Controller Structure
![controller](https://github.com/user-attachments/assets/2a09a240-674f-4948-8b21-f72fe3fc1e38)

# Conlusion
An enhanced ADRC system is proposed by integrating an IT2FPD controller in place of the traditional fixed gain PD controller. Additionally, the suggested controller is contrasted with ADRC rooted on IT1FPD. This approach leverages the flexibility of fuzzy logic to adapt the control gains in real time based on system errors, enabling better handling of uncertainties and external disturbances. MATLAB simulation results validated the efficacy of the suggested approach, showing significant improvements in trajectory tracking accuracy, robustness, and disturbance rejection in control signal and robot itself. These findings highlight the potential of the ADRC-IT2FPD approach in developing more reliable and adaptive control systems for dynamic robotic applications.

# Authors

Usama Habib
Ashraf Elnagar
Raouf Fareh
Ahmad M. El-Nagar
