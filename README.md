# GPIO_External_Interrupts
This repository has three applications using GPIO External Interrupts on STM32F401RE.
## Introduction
These projects were developed as a work in the discipline of Embedded Systems Programming at UFMG - Prof. Ricardo de Oliveira Duarte - Department of Electronic Engineering.

## Disabling IRQ: disable_it/
Simple application to show how to disable external interruptions with the NVIC API. Requires two buttons, a led and some resistors, jumpers and a protoboard.

## Preemption testing: EXTI_priority/
This application describes how to set preemptive priority levels to interrupts. It consists of two push buttons, which will make a LED blink 5 times, but each of them will provide a different blinking frequency for the LED.

## Time count: tim_an/
Interesting application for timing actions. This application counts the time between two interruption requests made by the same source and displays the result on an LCD display. To use it, it is necessary to have an LCD display (20x4), a potentiometer, a protobord, an LED and some registers and jumpers.
