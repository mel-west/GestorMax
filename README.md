# Exported from Render on 2025-04-26T12:30:17Z
services:
- type: web
  name: GestorMax
  runtime: static
  repo: https://github.com/mel-west/GestorMax
  envVars:
  - key: resumo
    sync: false
  - key: tipo
    sync: false
  - key: h_fim
    sync: false
  - key: h_inicio
    sync: false
  - key: c_custo
    sync: false
  - key: data
    sync: false
  - key: nome
    sync: false
  staticPublishPath: build
  rootDir: public/
version: "1"
