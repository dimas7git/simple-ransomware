# Simple Ransomware

Este repositório contém um código simples de ransomware criado com fins educacionais para entender o funcionamento básico desse tipo de malware.

## Atenção

**Não execute este ransomware em nenhum sistema ou arquivo sem autorização explícita e legal do proprietário dos arquivos. O uso deste código para fins maliciosos é ilegal e prejudicial.**

## Descrição

Este ransomware utiliza o algoritmo AES (Advanced Encryption Standard) com o modo de operação CTR (Counter) para criptografar arquivos. O código é dividido em duas partes: `encrypt.py` e `decrypt.py`.

### `encrypt.py`

O arquivo `encrypt.py` criptografa um arquivo específico fornecido pelo usuário. O arquivo original é lido em modo binário, criptografado usando a chave fornecida e salvo com a extensão `.ransomware`. Certifique-se de fornecer a chave adequada para descriptografizar o arquivo posteriormente.

### `decrypt.py`

O arquivo `decrypt.py` é usado para descriptografar arquivos que foram previamente criptografados pelo ransomware. Ele lê o arquivo criptografado em modo binário, descriptografa-o usando a chave fornecida e salva o arquivo descriptografado. É importante ter uma cópia do arquivo original e fornecer a chave correta para realizar a descriptografia com sucesso.

## Aviso Legal

Este projeto é estritamente para fins educacionais e de pesquisa. O autor não se responsabiliza pelo uso indevido ou ilegal do código fornecido neste repositório. Sempre respeite a privacidade e os direitos dos outros, e cumpra as leis e regulamentos locais, estaduais e internacionais aplicáveis.
