# ATALAIA

Sistema Inteligente de Vigilância Perimetral para Instalações Nucleares, desenvolvido para o desafio proposto pela Amazul na FIAP.

A ATALAIA combina drones autônomos, sensores IoT, visão computacional e Edge Computing para detectar, verificar e registrar situações anômalas no perímetro de instalações nucleares. Um sensor ou câmera detecta um evento, a IA classifica a imagem, um drone vai até o local para confirmar e o operador recebe no painel um alerta com imagem, posição e criticidade.

## Integrantes

| Nome | RM |
| --- | --- |
| João Vitor Anunciação Oliveira | RM567539 |
| Miguel Silva Bezerra | RM566763 |
| Paulo Ribeiro Marinho | RM567459 |

## Status

| Sprint | Entrega | Situação |
| --- | --- | --- |
| Sprint 1 | Documento de Visão e Definição da Solução | Em andamento |

## Tecnologias previstas

Drones com MAVLink (PX4/ArduPilot), ESP32 e sensores IoT via MQTT, OpenCV e YOLO para visão computacional, NVIDIA Jetson ou Raspberry Pi para Edge Computing, back-end em Java (Spring Boot) ou Python (FastAPI) com PostgreSQL/PostGIS e painel web em React com Leaflet.
