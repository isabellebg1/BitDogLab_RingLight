# RingLight feita com BitDogLab
Projeto para utilizar a matriz de LED 5x5 presentes na placa BitDogLab como uma RingLight, utilizando os botões A e B para alternar entre diferentes tons de iluminação.

# Lista de componentes usados
Componentes presentes na placa:
- 1 Microprocessador Raspberry Pi Pico W;
- 1 Microcontrolador RP2040;
- 1 Matriz módulo 5x5 LEDs RGB ws2812b 5050;
- 2 Botões push button 6x6x5 mm;
- 1 Bateria Li-ion 18.650 3.600 mAh 3,7V recarregável;
- 1 Case de bateria 18650.

# Pinagem usada 
- Botão A - GPIO 05;
- Botão B - GPIO 06;
- Matriz de LED - GPIO 07.

# Características
- Controle de matriz de LEDs WS2818B (NeoPixel) de 5x5;
- Utiliza PIO (Programmable I/O) para comunicação eficiente com os LEDs;
- Três padrões de exibição pré-definidos com diferentes cores;
- Interface com dois botões para navegação entre os padrões;
- Mapeamento otimizado para matrizes de LED em formato "serpentina".

# Exibição de Padrões
O projeto inclui três padrões pré-definidos:
- Padrão branco;
- Padrão amarelo;
- Padrão laranja.

# Controle por Botões
- Botão A: Avança para o próximo padrão;
- Botão B: Retorna ao padrão anterior.

# Compilação e Instalação
- Configure o ambiente de desenvolvimento para Raspberry Pi Pico; 
- Clone este repositório;
- Compile o projeto usando CMake;
- Conecte o Raspberry Pi Pico enquanto mantém o botão BOOTSEL pressionado;
- Copie o arquivo .uf2 gerado para o drive do Pico.

# Fotos
- Branco
![br](https://github.com/user-attachments/assets/6b4d71e7-a56d-4361-9840-4d4fea808ec5)
![br2](https://github.com/user-attachments/assets/aff094d7-c533-46e7-9f4e-930ca390d97e)
- Amarelo
![am](https://github.com/user-attachments/assets/7327471d-a11a-44a2-8701-b76b97d2021c)
![am2](https://github.com/user-attachments/assets/68e208dc-cade-4432-80e0-e9d12c55af40)
- Laranja
![lr](https://github.com/user-attachments/assets/15234f84-764d-43d8-80b4-6211a37dfd14)
![lr2](https://github.com/user-attachments/assets/1c37de8d-14ed-4ba4-8fd9-d7dc0458949a)




