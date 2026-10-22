# TruckSave Studio — Releases

Repositório oficial de distribuição do **TruckSave Studio**, editor de savegame
para **Euro Truck Simulator 2** e **American Truck Simulator**.

> O código-fonte do projeto é privado. Este repositório hospeda apenas os
> artefatos de download e o manifesto de versão consultado pelo
> auto-atualizador.

---

## Download

| Versão | Arquivo |
|---|---|
| 0.00.1 | `TruckSave Studio-0.00.1-Setup.exe` |

**Requisitos:** Windows 7 ou superior (roda nativo em 64 bits) e
.NET Framework 4.7.2.

**Instalação:** execute o `.exe` e escolha a pasta de destino. O instalador é
autoextrativo e não depende de ferramentas externas.

---

## Como o auto-atualizador encontra as versões

O aplicativo consulta o arquivo `manifest.txt` na raiz deste repositório:

```
TruckSave Studio-0.00.1-Setup.exe<TAB><SHA-512 em hexadecimal maiusculo>
```

O primeiro campo é o nome do instalador publicado e o segundo é o SHA-512
usado para verificar a integridade do pacote antes de aplicar a atualização.

---

## Integridade

confira a autenticidade do pacote conferindo o SHA-512:

```
Get-FileHash ".\TruckSave Studio-0.00.1-Setup.exe" -Algorithm SHA512
```

O valor deve ser idêntico ao do `manifest.txt`.

---

## Licença

Apache License 2.0. O código-fonte do projeto é privado e essa licença
aplica-se ao software distribuído aqui.

