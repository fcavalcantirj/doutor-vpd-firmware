# Doutor VPD firmware

Signed firmware releases for **Doutor VPD** (in English the device calls itself **VPD Gennie**): a pocket air-VPD monitor for growing cannabis, built on an **M5Stack StickS3** with the **ENV III** sensor. Binaries only.

**Português** · [English](#english)

## O que ele faz

Mede temperatura e umidade, calcula o VPD do ar, compara com o alvo da fase da planta (muda, vegetativo, floração) e diz o próximo ajuste na tela. Funciona sozinho: sem conta, sem nuvem, sem app e sem Wi-Fi para medir.

- **Instalar pelo navegador:** [doutorvpd.com.br/firmware](https://www.doutorvpd.com.br/firmware), num computador com Chrome ou Edge e um cabo USB-C de dados. Num StickS3 novo, segure o botão lateral **pequeno** até a luz verde piscar (modo de gravação) e escolha **Instalação limpa**.
- **Atualizar pelo celular:** o aparelho baixa a versão nova sozinho pelo hotspot do celular, Android ou iPhone. O firmware e as atualizações são grátis.
- **Manual:** [doutorvpd.com.br/manual](https://www.doutorvpd.com.br/manual)
- **Tabela de VPD e calculadora:** [doutorvpd.com.br/tabela-vpd](https://www.doutorvpd.com.br/tabela-vpd)
- **Kit pronto (StickS3 + ENV III, montado e testado):** [doutorvpd.com.br](https://www.doutorvpd.com.br/)

## English

The device measures temperature and humidity, works out the air VPD, compares it with the target of your plant's stage (seedling, veg, flower) and tells you the next adjustment on screen. It works on its own: no account, no cloud, no app and no Wi-Fi needed to measure.

- **Install from your browser:** [doutorvpd.com.br/firmware](https://www.doutorvpd.com.br/firmware) on a computer with Chrome or Edge and a USB-C data cable. On a StickS3 straight from the box, hold the **small** side button until the green light flashes (download mode), then choose **Instalação limpa** (clean install).
- **Update over your phone:** the device downloads the new version by itself over your phone's hotspot, Android or iPhone. The firmware and its updates are free.
- **Manual:** [doutorvpd.com.br/manual/en](https://www.doutorvpd.com.br/manual/en)
- **Hardware:** M5Stack StickS3 + ENV III unit on the Grove port (Port A).

## Releases

Each release carries a `manifest.json` signed with ECDSA P-256 (`manifest.sig`). The device and the install page check the signature and every file's SHA-256 before writing. Releases named `test-*` are throwaway test builds signed with a test key: do not install them.
