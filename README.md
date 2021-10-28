# SPEL electronic speed controller for BLDC motors 

Open-source hardware and software for BLDC motor electronic speed controller.

### About
Yet another open-source BLDC motor controller, developed primarily as a learning project. 

The end-goal is to create a controller that would be compact, flexibla and cheap to manufacture (design rules compliant with the ones from JLCPCB - 
same goes for most of the electronic components available at their SMD/SMT parts library). 


### Specification:
- Rated voltage: 60 [VDC]
- Rated current: 60 [ADC]
- Communication interfaces: CAN, I2C, UART, USB
- Debugging interface: SWD
- Control methods: through comm. interfaces, STEP/DIRECTION
- Feedback: Encoder inputs (reprogrammable to HAL sensor inputs), current sensing, back-EMF measurement. 
- CPU: STM32F103C8Tx/STM32F103CBTx series 
- Motor driver: Texas Instrument's DRV8301 
- Protection: DRV8301's built-in overcurrent/overvoltage protection modules, braking resistor.

![image](https://user-images.githubusercontent.com/48156138/138562456-54088d2b-c0a0-4f65-85c4-9c497f19e726.png)

### Hardware renders 

![image](https://user-images.githubusercontent.com/48156138/139263360-2c158ee8-6ec6-4491-96f2-1af07be96c41.png)
*SWD - IRL would be a pin header, not a socket, 3D model used for a footprint that happened to fit pin numeration accurately

![image](https://user-images.githubusercontent.com/48156138/139263418-484be6c0-f3b1-411a-b18d-25be368aaa19.png)



![image](https://user-images.githubusercontent.com/48156138/138562720-e20d98e0-bbe8-4986-a477-3c2fc53e3972.png)



### TODO: 
- BOM
- Manufacturing outlines (listing cheapest options, and possible part substitutes)
- Append calculations (somewhere)
