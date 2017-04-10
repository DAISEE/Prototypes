# Prototype v0.1

![schema prototype](https://hackpad-attachments.imgix.net/hackpad.com_d55JBV5B1Vy_p.602889_1472755256932_14215184_10154001154263915_845143439_o.jpg)

See [HERE](https://github.com/DAISEE/UrbanEntrepreneurs/wiki)  the instructions (in FR, EN ASAP) to rebuild the prototype. Tag for sources is **v0.1-beta** (pre-release). 

## Hardware
- Citizen Watt sensors
- Pine64+ boards + Arduino
- Arduino + Relay shield
- Light bulbs

## Software
- CitizenWatt 
    - [Sensor sketch](https://github.com/CitoyensCapteurs/CitizenWatt-sensor)
    - Application
        - [PINE64](https://github.com/DAISEE/CitizenWatt-Base-PINE64)  
        - [Arduino](https://github.com/DAISEE/CitizenWatt-ArduinoBase)

- Ethereum   
    - [geth](https://github.com/ethereum/go-ethereum)
    - [Dapp](https://github.com/DAISEE/DApp)
   
- [Connection](https://github.com/DAISEE/DzScripts)

# Prototype v0.2
  
## Hardware
- Single computer boards
    - [x] Back to Raspberry Pi 3 board (#1)  
## Software
- Ethereum  
    - [x] Use of Parity instead of geth (#2) 
        - [ ] Implementation of 'Proof of Authority' (#6)
    - [ ] New algo for energy exchanges (#3)  
    - [ ] Modify the data storage (#4)  
    - [ ] Energy data display (#5)
