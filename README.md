# deploy-grupo11

Deploy das três aplicações do **Grupo 11** da disciplina Provisionamento e Operação de
Infraestrutura (POI/UFCG, 2026.2) com **Docker Compose**, na VM `vm-grupo-11` da Nuvem do LSD.

Cada aplicação tem seu próprio repositório, com o código e o `Dockerfile`. As imagens são
publicadas no Docker Hub, e este repositório guarda apenas a configuração de deploy, que vale
para as três.

## Aplicações

| Aplicação | Perfil | Repositório | Imagem (Docker Hub) |
|---|---|---|---|
| Image Restoration | CPU-bound | [image-restoration](https://github.com/poi-ufcg-2026-2/image-restoration) | `<usuario>/image-restoration` |
| RAMdex API | Memory-bound | [ramdex-api](https://github.com/poi-ufcg-2026-2/ramdex-api) | `csabrina/ramdex-api` |
| ByteSum API | I/O-bound | [bytesum-api](https://github.com/poi-ufcg-2026-2/bytesum-api) | `<usuario>/bytesum-api` |
