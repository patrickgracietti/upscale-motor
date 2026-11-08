# upscale-motor

Este repositório guarda **só o motor de IA** do programa Upscale (ampliação de imagens no seu computador): um Python 3.11 com PyTorch (CUDA 12.8) e as bibliotecas que o motor usa. **O instalador do Upscale baixa estes arquivos sozinho** na primeira instalação e confere o SHA-256 de cada parte. Sozinho, este conteúdo não faz nada: não contém o programa, nem modelos de IA, nem dados de ninguém.

- Os arquivos das *Releases* são partes de um mesmo zip (`.001`, `.002`, `.003`), divididas por causa do limite de tamanho por arquivo.
- Não precisa baixar nada à mão. Se baixar, a ordem das partes importa e o instalador é quem junta e confere.
- Licenças dos componentes (PyTorch BSD-3-Clause, NumPy BSD-3-Clause, OpenCV Apache-2.0, spandrel MIT e outros): estão dentro do próprio pacote, em `Lib\site-packages\<pacote>.dist-info\`.
- Requer placa de vídeo NVIDIA com CUDA e Windows 10/11.
