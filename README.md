# PLC_LD_Projects
Practice Projects for Ladder Logic

## Motor
![Motor Ladder Program](images/motor.png)

In function this is a simple motor control program. It mixes the Input Mapping, Start/Stop, and 5 Rung patterns. Map global inputs into local logic. Create a safe state based on the emergency stop and an overheating fault. Use a start stop pattern on the motor and output the state to a global struct of the motor state. 

This seems like a big program for just a motor. I could simplify it by moving my input mappings to their own program, but I'm not sure if that makes it more confusing. I will probably update the two stopping buttons to work as if they were wired NC instead of NO.