# Extração de Frames JPG de Vídeos

## Contexto e Necessidade

Em diversas situações, recebemos evidências em formato de vídeo que precisam ser analisadas como imagens estáticas (fotos). Isso é comum em monitoramento, auditoria, investigações e outras áreas que demandam análise visual detalhada de momentos específicos capturados em vídeos.

No entanto, vídeos são arquivos grandes e complexos, e nem sempre é prático ou eficiente trabalhar diretamente com eles. Por isso, extrair frames (imagens) em intervalos regulares torna-se uma solução simples e eficaz para transformar vídeos em sequências de fotos que possam ser facilmente consultadas, compartilhadas ou processadas.

---

## Sobre este projeto

Este notebook/script em Python permite extrair frames de vídeos automaticamente, salvando imagens no formato JPG a cada intervalo de tempo definido (por exemplo, a cada 5 segundos). Isso facilita o trabalho de análise, arquivamento e compartilhamento das evidências visuais.

---

## Funcionalidades

- Upload de múltiplos vídeos para processamento (no Colab).
- Extração automática de frames em intervalos regulares (configurável).
- Salva todas as imagens extraídas em uma pasta organizada.
- Compacta as imagens em um arquivo ZIP para facilitar o download.
- Evita duplicação de nomes usando prefixos com o nome do vídeo.

---

## Como usar (no Google Colab)

1. Faça upload dos vídeos diretamente no notebook.
2. Execute o código para extrair frames (o padrão é a cada 5 segundos).
3. Aguarde o processamento — as imagens serão salvas e compactadas.
4. Baixe o arquivo ZIP com todas as imagens para seu computador.

---

## Requisitos

- Python 3.x
- Biblioteca OpenCV (`opencv-python`)
- Ambiente Google Colab ou ambiente local configurado para rodar Python e OpenCV

---

## Extensões e Melhorias Futuras

- Customização do intervalo de extração pelo usuário.
- Suporte para outros formatos de imagem (PNG, BMP).
- Interface simples para selecionar vídeos e configurar parâmetros.
- Suporte para extração baseada em eventos específicos do vídeo.

---

## Contato

Para dúvidas, sugestões ou contribuições, abra uma issue ou entre em contato!

---

**Este projeto facilita a transformação de vídeos em evidências fotográficas, agilizando processos de análise e documentação.**
