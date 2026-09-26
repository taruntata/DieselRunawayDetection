# Diesel Engine Runaway Detection 
An STM32 based project that simulates, detects and stops runaway in diesel engines.

## How a Diesel Engine Works
A typical engine spins the wheels of a car by using the energy that is released from combustion of a flammable fuel like petrol or diesel. The engine consists of cylindrical cavities know as piston chambers and these chambers have pistons which are connected to the wheel, the pistons chambers are enclosed and mixture of air and fuel is sent into these enclosed chambers. Mixture of fuel, air causes a miniature explosion making the pistons bounce and transfer all of the rotational energy to the crankshaft and ultimately the wheels
In case of petrol engines combustion is made possible by igniting the air and fuel mixture, whereas in diesel engines combustion occurs when the air and fuel mixture is compressed enough, meaning there is no external spark provided. 
Compression of the air and fuel mixture makes the engine run, and in diesel engine cars the amount of fuel going into the engine is controlled by the accelerator whereas the air is not controlled in any way. This is where a major problem may arise in few particular cases, known as runaway.

## What does Runaway mean in Diesel Engine?
Runaway is the occurrence of uncontrollable revving of a diesel engine when fuel vapor or oil leaks into the engine chambers. As the only parameter controlled by a human in an engine is the fuel, when the engine has vast amount of fuel available, runaway occurs. Runaway is a very dangerous phenomenon and if not stopped, can cause explosions and be fatal.

## How to stop runaway in a car?
There are several ways to stop a runaway engine.
  - Stop the airflow by obstructing
  - Put the transmission in the highest gear possible and dump the clutch
  - Choke the engine of oxygen by pumping CO2 into the engine
The most reliable method is to block the air flowing into the engine, but doing this manually may be risky. Hence this project aims at simulating a runaway condition and automating the sensing and air intake choking using an STM32 board.
