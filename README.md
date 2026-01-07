# Hackintosh EFI -- Lenovo ThinkCentre M910q

Este é um **projeto simples de EFI para Hackintosh**, criado a partir de
uma base genérica e adaptado para o **Lenovo ThinkCentre M910q**.

Não se trata de uma EFI "perfeita" ou totalmente otimizada. O objetivo
principal é **servir como ponto de partida funcional**, algo que "já
quebra um galho" para quem deseja instalar o macOS neste modelo
específico.

Recomendo fortemente que cada usuário **adapte o `config.plist`, kexts e
demais ajustes** de acordo com o seu próprio hardware e necessidades.

------------------------------------------------------------------------

## ⚠ Aviso Importante

-   Esta EFI **não está totalmente bem construída**.\
-   Possui **itens desnecessários** herdados da base genérica.\
-   Funciona corretamente **no contexto em que foi testada**, mas **não
    é garantido que funcione em todas as configurações** do mesmo
    modelo.\
-   Use por sua conta e risco.

Este projeto é voltado a **fins educacionais e experimentais**.

------------------------------------------------------------------------

## 💻 Especificações do Computador

-   **Modelo:** Lenovo ThinkCentre M910q\
-   **Processador:** Intel Core i7 série T (7ª geração)\
-   **Gráficos:** Intel HD Graphics 630\
-   **Saídas de Vídeo:**
    -   1× VGA\
    -   2× DisplayPort (DP)

------------------------------------------------------------------------

## 📦 Sobre a EFI

-   Baseada em uma **EFI genérica**.\
-   Ajustada para funcionar com:
    -   Intel HD Graphics 630\
    -   Plataforma Intel de 7ª geração\
-   Contém configurações e arquivos que **podem não ser necessários para
    todos os usuários**.

Em outras palavras: **funciona para o meu uso**, mas foi pensada para
ser **adaptada**, não apenas copiada.

------------------------------------------------------------------------

## 🔧 Recomendações

Antes de utilizar:

1.  **Edite o `config.plist`** conforme seu hardware:
    -   SMBIOS\
    -   DeviceProperties\
    -   Boot-args\
2.  Verifique e ajuste:
    -   Kexts carregados\
    -   ACPI (SSDTs)\
    -   Mapeamento de portas USB\
3.  Teste cuidadosamente após cada modificação.

------------------------------------------------------------------------

## 📌 Observações

-   Esta EFI não foi criada para ser "plug and play".\
-   Alguns componentes podem estar:
    -   Redundantes\
    -   Mal otimizados\
    -   Genéricos demais\
-   A ideia é fornecer uma **base funcional** que você possa melhorar.

------------------------------------------------------------------------

Projeto montado com base em **EFI genérica**, adaptado e testado
especificamente para o **Lenovo ThinkCentre M910q**.

> "Não é perfeito, mas já quebra um galho."
