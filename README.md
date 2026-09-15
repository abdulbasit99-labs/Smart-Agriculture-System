# Smart-Agriculture-System
# IoT-Based Smart Plant Health & Soil Monitoring System

An ESP32-based IoT system for real-time monitoring of plant growing
conditions and automatic irrigation.

## Overview

The IoT-Based Smart Plant Health & Soil Monitoring System monitors
important environmental parameters affecting plant growth.

The system uses an ESP32 microcontroller together with soil moisture,
temperature, humidity, and light sensors.

Based on sensor readings, the system calculates an environmental
Plant Health Index and automatically controls a water pump when the
soil becomes too dry.

## Features

- Real-time soil moisture monitoring
- Temperature monitoring
- Humidity monitoring
- Light intensity monitoring
- Plant Health Index
- Automatic irrigation
- Water pump control
- OLED live display
- RGB LED status indication
- Wi-Fi connectivity
- IoT-ready architecture

## System Architecture

```text
Soil Moisture ─┐
DHT22 ─────────┤
BH1750 ────────┤
               ↓
             ESP32
               │
      ┌────────┼─────────┐
      ↓        ↓         ↓
    OLED      RGB       Wi-Fi
   Display     LED        │
                          ↓
                    IoT Dashboard
                          │
                          ↓
                       Control
                          │
                          ↓
                       Relay
                          │
                          ↓
                     Water Pump
