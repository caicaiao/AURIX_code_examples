学习路径->TC397


基本理解

Blinky_LED_1_KIT_TC397_TFT 熟悉 ADS/HighTec 工具链、编译下载流程、iLLD 工程结构

GPIO_LED_Button_1_KIT_TC397_TFT GPIO 输入输出、按键中断，理解 Port 模块

STM_Interrupt_1_KIT_TC397_TFT 系统定时器 STM + 中断机制，理解 TC3xx 中断体系（SRC/IR）是核心基础

Interrupt_Prio_1_KIT_TC397_TFT 中断优先级管理，深入理解 ICU/中断路由


定时器系统

STM_System_Time_1_KIT_TC397_TFT STM 做系统时基（类似 SysTick）

GPT12_Timer_Interrupt_1_KIT_TC397_TFT GPT12 通用定时器中断

GPT12_Timer_Concatenation_1_KIT_TC397_TFT GPT12 级联，长周期定时


通信接口

ASCLIN_UART_1_KIT_TC397_TFT UART 串口通信，调试必备

ASCLIN_Shell_UART_1_KIT_TC397_TFT Shell 命令行交互，方便后续调试

UART_VCOM_1_KIT_TC397_TFT 虚拟串口（通过 DAP/调试器）

UART_DMA_Transfer_1_KIT_TC397_TFT UART + DMA 传输，高效数据搬运

ASCLIN_SPI_Master_1_KIT_TC397_TFT ASCLIN 模块做 SPI 主机

SPI_CPU_1_KIT_TC397_TFT QSPI CPU 模式

SPI_DMA_1_KIT_TC397_TFT QSPI + DMA，高速 SPI

SPI_TLF_1_KIT_TC397_TFT SPI 驱动 TLF35584 电源芯片（量产项目必用）

ASCLIN_LIN_Master_1_KIT_TC397_TFT LIN 主节点通信

I2C_Read_Ext_Device_1_KIT_TC397_TFT I2C 读外部器件


ADC模数转换

ADC_Single_Channel_1_KIT_TC397_TFT ADC 单通道采集，先从这个开始

ADC_Filtering_1_KIT_TC397_TFT ADC 硬件滤波

ADC_Queued_Scan_1_KIT_TC397_TFT 队列扫描模式，多通道

EDSADC_1_KIT_TC397_TFT 增强型 Delta-Sigma ADC


PWM与GTM 电机电控方向重点

GTM_TOM_PWM_1_KIT_TC397_TFT GTM TOM 输出 PWM（最常用的 PWM 方式）

GTM_TOM_Interrupt_1_KIT_TC397_TFT TOM 中断

GTM_ATOM_PWM_1_KIT_TC397_TFT GTM ATOM 输出 PWM（更灵活）

GTM_ATOM_Interrupt_1_KIT_TC397_TFT ATOM 中断

GTM_TIM_Capture_1_KIT_TC397_TFT GTM TIM 输入捕获（测频率/占空比）

CCU6_PWM_Generation_1_KIT_TC397_TFT CCU6 产生 PWM（传统方式）

CCU6_PWM_Capture_1_KIT_TC397_TFT CCU6 捕获

CCU6_Interrupt_1_KIT_TC397_TFT CCU6 中断

CCU6_ADC_1_KIT_TC397_TFT CCU6 触发 ADC 采样

GPT12_PWM_Generation_1_KIT_TC397_TFT GPT12 PWM 输出

GPT12_PWM_Capture_1_KIT_TC397_TFT GPT12 PWM 捕获

PWM_Buzzer_1_KIT_TC397_TFT PWM 驱动蜂鸣器（轻松小项目）


CAN通信

MCMCAN_1_KIT_TC397_TFT MCMCAN 基础收发（TC3xx 用 MCMCAN，不是 MultiCAN）

MCMCAN_FD_1_KIT_TC397_TFT CAN FD 通信

MCMCAN_Filtering_1_KIT_TC397_TFT CAN 报文过滤/接收


DMA与系统级

DMA_Mem_to_Mem_1_KIT_TC397_TFT DMA 内存搬运基础

DMA_ADC_Transfer_1_KIT_TC397_TFT DMA + ADC 自动搬运

DMA_Linked_List_Mode_1_KIT_TC397_TFT DMA 链表模式

Multicore_1_KIT_TC397_TFT 多核编程（TC397 有6核，车载项目必用）

CCU_Clock_1_KIT_TC397_TFT 时钟系统配置

Assembly_C_Code_1_KIT_TC397_TFT 内联汇编，理解 TriCore 指令集


安全与系统保护

Watchdog_1_KIT_TC397_TFT 看门狗

ERU_Interrupt_1_KIT_TC397_TFT ERU 外部请求单元（外部中断）

CPU_Perf_Counters_1_KIT_TC397_TFT CPU 性能计数器

CPU_Trap_Recognition_1_KIT_TC397_TFT Trap 异常处理

MPU_Memory_Protection_1_KIT_TC397_TFT 内存保护 MPU

BUS_Register_Protection_1_KIT_TC397_TFT 寄存器写保护（Safety Endinit）

SCU_Reset_Detection_1_KIT_TC397_TFT 复位源检测

SCU_Die_Temp_Sensor_1_KIT_TC397_TFT 芯片温度传感器

SCU_Emergency_Stop_1_KIT_TC397_TFT 紧急停止

SMU_Emergency_Stop_Alarm_1_KIT_TC397_TFT SMU 安全管理 - 紧急报警

SMU_Fault_Signaling_1_KIT_TC397_TFT SMU 故障信号

SMU_IR_Alarm_1_KIT_TC397_TFT SMU 中断报警

SMU_Reset_Alarm_1_KIT_TC397_TFT SMU 复位报警

FCE_CRC_1_KIT_TC397_TFT 硬件 CRC 校验

MTU_MBIST_1_KIT_TC397_TFT 内存自检 MBIST

Flash_Programming_1_KIT_TC397_TFT Flash 编程（OTA/Bootloader 基础）

RAM_Run_Function_1_KIT_TC397_TFT 从 RAM 执行代码

Memory_Access_Performance_1_KIT_TC397_TFT 存储器访问性能对比


低功耗与以太网（特定场景）

PMS_Power_Down_Idle_1_KIT_TC397_TFT Idle 低功耗模式

PMS_Power_Down_Sleep_1_KIT_TC397_TFT Sleep 模式

PMS_Power_Down_Standby_1_KIT_TC397_TFT Standby 模式

Ethernet_1_KIT_TC397_TFT 以太网通信

IOM_Signals_Comparison_1_KIT_TC397_TFT IOM 信号比较监控


TC397 专属 iLLD 进阶例程

iLLD_TC397_ADS_CAN_Gateway_ISR CAN 网关 + 中断（和你的矩阵工作直接相关！）

iLLD_TC397_ADS_SD_Read_To_Serial SD 卡读取 + 串口输出 

iLLD_TC397_3V3_ADS_SDCard_SDMMC_Read_Write SDMMC 读写

iLLD_TC397_ADS_SENT_Redundancy_SPC_Trig_TLE5012_GTM_TOM SENT 协议 + 冗余传感器

iLLD_TC397_TFT_ADS_LMU_Memory_Protection LMU 内存保护

iLLD_TC397_ADS_PORT_LOOPBACK 端口回环测试

iLLD_TC397_ADS_PORT_REDUNDANCY 端口冗余

iLLD_TC397_ADS_ESM_SW_CLOCK_PLAUSIBILITY 时钟合理性检查

iLLD_TC397X_ADS_SPU_Basics SPU 信号处理单元（雷达方向）
