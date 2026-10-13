# stap 1

- code schrijven op: NUCLEO-WL55JC met SB Components USB-C to LoRa Dongle (EU868) dongle aan pc.
- nucleo kan dongle bereiken en visa versa
- NUCLEO-WL55JC1 ==> https://be.farnell.com/en-BE/stmicroelectronics/nucleo-wl55jc1/dev-board-arm-cortex-m0-m4-mcu/dp/3605811?gross_price=true&CMP=KNC-GBE-GEN-SHOPPING-PMAX&gad_source=1&gad_campaignid=20158569059&gclid=CjwKCAjwirLWBhBBEiwAlItbErK-0cR8KBJYM_NjPleuHZTHkG8-3_uUCu8g58XvMMSh-qmo9rarzxoCJ-UQAvD_BwE
- EU868 ==> https://shop.sb-components.co.uk/products/usb-type-c-to-lora-dongle?variant=41026476769363

# stap 2

- eigen antenne ontwerpen(pcb met alleen antenne op) om aan nucleo te hangen
- eventueel code hieraan aanpassen
- nucleo kan dongle bereiken en visa versa

# stap 3

- pcb met STM32WL55JC mc, antenne, scherm,..("receiver-pcb")
- pcb kan nucleo bereiken en visa versa

# stap 4

- nieuwe pcb met gps op (send-pcb)
- code aanpassen
- send-pcb kan receiver-pcb bereiken
