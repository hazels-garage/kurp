![GitHub](https://img.shields.io/github/license/hazels-garage/battpack?label=%20&logo=creativecommons&logoColor=%23ffffff&style=flat-square)
<a href="https://discord.gg/jP6hvgNN8r">
  ![Discord](https://img.shields.io/discord/989552667330228374?color=%237289da&label=%20&logo=discord&logoColor=%23fff&style=flat-square)
</a>
<a href="https://shop.hazel.cc/products/kurp">
 ![Hazel's Garage](https://img.shields.io/badge/-Purchase-%23000?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAABGdBTUEAALEQa0zv0AAAACBjSFJNAACHDwAAjA8AAP1SAACBQAAAfXkAAOmLAAA85QAAGcxzPIV3AAABCGlDQ1BJQ0MgUHJvZmlsZQAAKM9jYGBckZOcW8wkwMCQm1dSFOTupBARGaXAfoeBkUGSgZlBk8EyMbm4wDEgwIcBJ/h2DagaCC7rgsxiIA1wpqQWJwPpD0Acn1xQVAJ0E8gunvKSAhA7AsgWKQI6CsjOAbHTIewGEDsJwp4CVhMS5Axk8wDZDulI7CQkNtQuEGBNNkrORHZIcmlRGZQpBcSnGU8yJ7NO4sjm/iZgLxoobaL4UXOCkYT1JDfWwPLYt9kFVaydG2fVrMncX3v58EuD//9LUitKQJqdnQ0YQGGIHjYIsfxFDAwWXxkYmCcgxJJmMjBsb2VgkLiFEFNZwMDA38LAsO08APD9Tdt4gbWmAAAACXBIWXMAABJ0AAASdAHeZh94AAABC0lEQVQ4T2MAgv9kYqyCxGBMQUtFVwwxLBhVwEDG+n934PL/HQFLUMSxYEzBJp85/8td+/97aUf9jzcv+s/HIQgWZ2JkQlaH0MDOwgG2rcJtAhjXek773+G/+D8POz9QEzOyJhBGcMwVnf83es+GawThNr8FYDlGBka4OihGcEzlHcEaS1x6wJoq3Sf9L3PtQ1aMjBEcNTH9/xoShv9jzPL/13lOB2tKta76b6vihawBhhEcER7J/yxMrECF3v8TLEr+V7lP/t/qu+C/grAGsgYYRhUABUiD10ywJpCtDV6z/ksLKKKogWJUgXb/RcAAWQjEi/6HG2dhC00YxhTkZOXGEMOCsQoSwAz/AUZL+dIX/BrCAAAAAElFTkSuQmCC)        
</a>

# Kurp
## 36 Key unibody split ortholinear

![build](images/kurp.jpg)

## PCB Render
![top](renders/kurp-top.png)
![bottom](renders/kurp-bottom.png)

Kurp is a choc-spaced unibody split ortholinear keyboard.

## Materials

| Description | Part | Count | Notes |
| :---: | :---: | :---: | :---: |
| PCBs | [Main](pcbs/pcb/jlcpcb/production_files) | 1 | |
|| [Switchplate](pcbs/switchplate/jlcpcb/production_files) | 1 | Optional |
|| [Backplate](pcbs/backplate/jlcpcb/production_files) | 1 | Optional |
|| [Centerplate](pcbs/centerplate/jlcpcb/production_files) | 1 | Optional |
| Controller | ProMicro footprint | 1 |  | 
| Diodes | 1N4148 SOD-123  | 36 |  |
| Switches | Choc v1 | 36 |  | 
| Keycaps | 1u | 36 | |
| Reset | TL3342F260QG | 1 | |
| Display | SSD1306 | 1 | Optional |
| | nice!view |  | Wireless Only |
| Power Switch |  MSK-12C02 | 1 | Wireless Only | 
| Battery Connector | TBD | 1 | Optional, Wireless Only | 
| Battery | TBD | 1 | Wireless Only |
| 3mm M2 Standoff ||8||
| 9mm M2 Standoff ||4||
| 3mm M2 Screw ||24||

## Firmware
QMK : https://github.com/jasonhazel/qmk_firmware/tree/hazel/kurp
