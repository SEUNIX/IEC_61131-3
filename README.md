## 1.[Training: IEC 61131-3 Basics with MotionWorks IEC](https://www.youtube.com/playlist?list=PLNAENlyEDCkzMwkIpWNwX0DeJdlVFwyB0)
## 2.[IEC61131-3编程语言及应用基础笔记](./IEC61131-3编程语言及应用基础)
---
### 1.address_define
- ![address_define](./image/address_define.png)

### 2.[Using I/O](https://www.youtube.com/watch?v=qalVIKTNn8M&list=PLNAENlyEDCkzMwkIpWNwX0DeJdlVFwyB0&index=7)
- Using I/O
- ![Using_IO](./image/Using_IO.png)
- 1.Project Update Checklist
	- Global Variables in Code
		- G_Sensor
		- G_OpenForBusiness
		- G_GateOpen
	- Global IO Variables
		- DI_00, DI_01
		- DO_00
	- LD program POUs
		- Q_PcSim
		- I_PcSim
		- Instance in Task
- Execution_Sequence
- ![Execution_Sequence](./image/Execution_Sequence.png)
- IO In Task List
- IO Task Assignment
	- Assign IO to the task in which they are used
		- Physical Hardware -> IO_Configuration: Properties -> task
- IO_Execution_Timing
- ![IO_Execution_Timing](./image/IO_Execution_Timing.png)

### 3.Force I/O Variables
- Only variables with I/O address can be forced
- Force status
- ![Force_status](./image/Force_status.png)
- Force I/O Variable
- ![Force_IO_Variable](./image/Force_IO_Variable.png)
- Force List
- ![Force_List](./image/Force_List.png)
- PLC Force State
- ![PLC_Force_State](./image/PLC_Force_State.png)
- LREAL Value Display
- ![LREAL_Value_Display](./image/LREAL_Value_Display.png)
- Watch Window
- ![Watch_Window](./image/Watch_Window.png)
- Cross Reference
- ![Cross_Reference](./image/Cross_Reference.png)

### 4.Programming Overview
- Reusable code
- ![4.1](./image/Reusable_Code.png)
- Languages
- ![4.2](./image/Languages.png)
- SFC
- ![4.3](./image/SFC.png)
- 20 data types
- ![4.4](./image/Data_Types.png)
- Software Model
- ![4.5](./image/Software_Model.png)
- ![4.6](./image/Software_Model_2.png)
- POU Execution
- ![4.7](./image/POU_Execution.png)

### 5.Multi Task
- Overview
- ![5.1](./image/Multi-Task_Overview.png)
- Task Types
- ![5.2](./image/Task_Types.png)
- Create Default Task
- ![5.3](./image/Create_Default_Task.png)
- Slow Task Setting
- ![5.4](./image/Slow_Task_Setting.png)
- Task Priority
- ![5.5](./image/Task_Priority.png)
- Maximun time allowed for task to complete
- ![5.6](./image/Watchdog_Time.png)
- Interval and Priority
- ![5.7](./image/Interval_and_Priority.png)
- ![5.8](./image/Interval_and_Priority_2.png)
- IO Task Assignment
- ![5.9](./image/IO_Task_Assignment.png)
- IO Execution Timing
- ![5.10](./image/IO_Execution_Timing_2.png)
- Task Execution
- ![5.11](./image/Task_Execution.png)

### 6.Logic Analyzer
- Overview
- ![6.1](./image/Logic_Analyzer_Overivew.png)
- Add Variables
- ![6.2](./image/Add_Variables.png)
- Trigger Configuration
- ![6.3](./image/Trigger_Configuration.png)
- Record Data
- ![6.4](./image/Record_Data.png)

