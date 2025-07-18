# Latest versions

Current version: 0.9990

The files listed here are from the latest release. Old versions can be found at the old folder.


## Keeper 3 model A (kp3a)

| Board Revision  | Firmware |
| ------------- | ------------- |
| R1B  | kp3a-r1b-r1c  |
| R1C  | kp3a-r1b-r1c  |
| R1D  | kp3a-r1d or kp3a-r1d-fram  |
| R1E  | kp3a |

</br>

## Keeper 3 model B (kp3b)

| Board Revision  | Firmware |
| ------------- | ------------- |
| R1A  | kp3b  |
| R1B  | kp3b  |
| R1C  | kp3b  |


## changelog
### 0.9990
- Adicionado GPS para linha A7608
- Novas funções no mhoJS (JSON.compare cloud.send_asset)

### 0.9989
- Pequenas otimizações de memória e funcionamento

### 0.9987
- Depurador de boot
- Depurador de erros para mhoJS reestruturado

### 0.9981
- Novas funções para calculo de logaritmo via mhoJS
- Pequenas otimizações de memória e funcionamento

### 0.9978
- Nova tela de depuração modbus
- Corrigido erro de reconexão de APN em alguns modelos após TTL

### 0.9976
- Erro de reconexão modem em rede celular em alguns tipos de rede LTE (bug de reconexão da versão KP3B e alguns modelos de modem da versão KP308A)

### 0.9969
- [NEW] mhoWAVE - Sistema de comunicação local entre dispositivos baseado em Wi-Fi [Docs](https://docs.mhoeng.com/docs/2keeper/config_adv/mhojs/functions/7a-wave);
- Correção de bug de envio via trigger de tempo nas DIs e DOs;

### 0.9968
- Melhoria na reconexão via rede celular;


### 0.9967
- Melhoria na reconexão via rede celular;


### 0.9966
- BETA: novo debugador de modbus via webserver em '/mbrtu';
- otimização de FOTA (firmware), apenas via MHO Cloud;
- otimização de fileOTA (js, modbus...), apenas via MHO Cloud.

### 0.9965
- funções de horímetros nativos nas DIs;
- funções de contador de pulso nativos nas DIs;

### 0.9964
- Nova organização dos menus de configurações;
