# Polvo — releases

Downloads do **Polvo**, gerenciador de perfis de navegador. Este repositório só guarda os instaladores; o app instalado procura atualizações aqui sozinho (a cada hora) e mostra **“Reiniciar para atualizar”** quando a nova versão já foi baixada e verificada.

## Download

| Sistema | Arquivo |
|---|---|
| **Windows 10/11 (64 bits)** | [Polvo-Setup-x64.exe](https://github.com/luizguil99/polvo-release/releases/latest/download/Polvo-Setup-x64.exe) |
| **macOS (Apple Silicon M1/M2/M3/M4)** | [Polvo-arm64.dmg](https://github.com/luizguil99/polvo-release/releases/latest/download/Polvo-arm64.dmg) |

Todas as versões: [Releases](https://github.com/luizguil99/polvo-release/releases).

### Windows
1. Baixe e abra `Polvo-Setup-x64.exe`.
2. Se aparecer **“O Windows protegeu o computador”** (SmartScreen), clique em **Mais informações → Executar assim mesmo**.
3. A instalação é só para o seu usuário (não pede administrador). O Polvo abre no fim e fica no Menu Iniciar.

### macOS
1. Abra o `Polvo-arm64.dmg` e arraste o **Polvo** para **Aplicativos**.
2. Abra o Polvo normalmente: o app é assinado com Developer ID e notarizado pela Apple.

## Atualizações
- **macOS:** o Polvo baixa a atualização em segundo plano, confere o checksum e a assinatura, e ao reiniciar uma janelinha nativa mostra o progresso enquanto o app é trocado (se a nova versão não abrir, a anterior é restaurada).
- **Windows:** ao reiniciar, o instalador roda com uma barra de progresso e abre o Polvo atualizado.
- Fechar o Polvo com uma atualização baixada também instala.

Cada atualização é assinada (minisign/Ed25519); o app recusa arquivos sem a assinatura do Polvo.
