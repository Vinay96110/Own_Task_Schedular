# Own_Task_Schedular
Task Schedular from Scratch 

# Creating my own schedular 3 ways 
1. Via Systick Hanlder switch to other task (Initial)
2. Via Pendsv 
3. Via CMSIS 


# Issues 
1. Systick Context switch is going for halrd - faults 
2. LDMIA, STMDB, ! - assembly 
3. SP to MSP switch need to verify 
4. LR is showing Junk Value (In systick Handler execution -- may causing default handler )

# Board used for this project
STM32F767ZI  -- Contex M7 
