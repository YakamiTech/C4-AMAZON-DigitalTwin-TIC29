# 🛰️ C4-AMAZON: Gêmeo Digital e Comando DePIN (VR)

**Residência em TIC 29 - Web 3.0 | Projeto Final: Meu Primeiro Ambiente VR**
**Autor:** Erick de Araújo Mattos

## 📖 Sobre o Projeto
Este projeto em Realidade Virtual funciona como um Gêmeo Digital (*Digital Twin*) do Centro de Comando e Controle (C4) da Yakami Tech. O ambiente simula a recepção de telemetria do nanossatélite YAKAMI-SAT1 e a comunicação via rádio (LoRaWAN) com as ECO Stations na floresta amazônica.

O utilizador explora uma base de monitoramento de alta tecnologia na selva, interagindo com hologramas do satélite, placas de hardware (RP2040) e um terminal Web3 focado no conceito de redes DePIN (*Decentralized Physical Infrastructure Networks*).

## 🛠️ Especificações Técnicas
* **Motor Gráfico:** Unity (Universal Render Pipeline - URP)
* **SDK VR:** Meta XR SDK e XR Interaction Toolkit
* **Plataforma Alvo:** Android (Otimizado para Meta Quest)
* **Locomoção:** Continuous Move Provider
* **Interações:** XR Grab Interactable com Sockets (para simulação de manutenção de hardware embarcado) e XR Ray Interactor (para UI).

## 📁 Estrutura do Repositório
Para manter o projeto otimizado e limpo, este repositório contém apenas os ficheiros essenciais do Unity (pastas pesadas foram ignoradas via `.gitignore` padrão):

* `/Assets`: Contém todos os Modelos 3D (CubeSat 6U, Antena LoRaWAN, Console, RP2040), Prefabs interactivos, Scripts (C#) e Materiais.
* `/ProjectSettings`: Configurações globais do projeto, mapeamento de Input (XR) e definições de Build.
* `/Packages`: Manifestos de dependências do Unity Package Manager.

## 🎮 Como Executar o Projeto
1. Clone este repositório para o seu computador:
   `git clone https://github.com/SEU-USUARIO/C4-AMAZON-DigitalTwin-TIC29.git`
2. Abra o Unity Hub e clique em **Add** para selecionar a pasta clonada.
3. Certifique-se de que possui os módulos de *Android Build Support* instalados.
4. Abra a cena principal localizada em `Assets/Scenes/C4_Amazon_Main.unity`.
5. Utilize o **XR Device Simulator** integrado no projeto para testar no PC, ou faça o *Build and Run* (.apk) para o headset Meta Quest.

## 🔗 Ficheiro de Submissão
O documento com o link deste repositório (`link_repositorio.txt`) e o Relatório Técnico detalhado foram submetidos através da plataforma da Residência TIC 29 conforme as diretrizes da atividade.
