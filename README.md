# Kernel AMD - Driver de Vídeo

Repositório contendo kernels Linux compilados com driver AMD para múltiplas distribuições.

## Objetivo

Este projeto faz parte do **DistroForge Studio**, uma iniciativa para manter um banco de kernels atualizados e otimizados para sistemas com placas de vídeo AMD. O objetivo principal é fornecer kernels pré-compilados que possam ser utilizados pelo instalador Calamares nas distribuições criadas pelo projeto.

## Especificações

- **Driver de Vídeo:** AMD (Kernel Linux com drivers AMD pré-instalados)
- **Arquitetura:** amd64 (x86_64)

## Distribuições Suportadas

| Distribuição | Pasta |
|--------------|-------|
| Arch Linux | `arch/` |
| Debian | `debian/` |
| Fedora | `fedora/` |
| Gentoo | `gentoo/` |
| openSUSE | `opensuse/` |
| Ubuntu | `ubuntu/` |

## Instalação

Os arquivos estão no formato `.tar.gz` e podem ser extraitos diretamente para o diretório de kernels do seu sistema.

```bash
# Exemplo para Ubuntu
tar -xzvf ubuntu/linux-ubuntu-hwe-6.12.tar.gz -C /caminho/para/kernels/
```

## Download

O arquivo completo foi dividido em partes devido à limitação de tamanho do GitHub:

- `kernels-amd-part-aa` (parte 1)
- `kernels-amd-part-ab` ( parte 2)

Para recombinar e extrair:

```bash
cat kernels-amd-part-* > kernels-amd.tar.bz2
tar -xjf kernels-amd.tar.bz2
```

## Sobre o Projeto

**DistroForge Studio** é um projeto dedicado à criação de distribuições Linux personalizadas, com foco em:

- Kernels atualizados
- Suporte otimizado para hardware AMD
- Integração com Calamares para instalação facilitada

## Licença

Consulte o arquivo LICENSE para mais informações.