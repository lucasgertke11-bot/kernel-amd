# Kernel AMD - DistroForge Studio

Repositório de kernels Linux com driver AMD para múltiplas distribuições.

## Objetivo

Manter um banco de dados atualizado de kernels Linux para o projeto **DistroForge Studio**, dedicado à criação de distribuições Linux personalizadas com foco em suporte otimizado para hardware AMD.

## Distribuições Incluídas

| Distribuição | Pasta |
|--------------|-------|
| Arch Linux | `arch/` |
| Debian | `debian/` |
| Fedora | `fedora/` |

## Instalação

Os kernels estão no formato `.tar.gz` prontos para uso com o instalador Calamares.

```bash
tar -xzvf linux-<distro>-<versao>.tar.gz -C /caminho/para/kernels/
```

## Especificações

- **Driver:** AMD (pré-configurado)
- **Arquitetura:** amd64 (x86_64)
- **Formato:** `.tar.gz` (compatível com Calamares)

## Sobre o Projeto

**DistroForge Studio** é uma iniciativa para fornecer distribuições Linux atualizadas com kernels otimizados para hardware AMD.

## Licença

Consulte o arquivo LICENSE.
