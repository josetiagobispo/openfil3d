# OpenFil3D

**O plástico de hoje é o filamento de amanhã.**

Extrusora open source para reciclagem de resíduos de impressão 3D — purgas, suportes, peças defeituosas — transformando-os de volta em filamento utilizável. Feche o ciclo dentro do seu próprio laboratório.

🌐 [openfil3d.com.br](https://openfil3d.com.br)

---

## O Problema

Quem trabalha com impressão 3D convive com desperdício constante: falhas de calibração, suportes descartados, testes que não deram certo. Com a evolução das impressoras multicoloridas, o problema se agravou — a cada troca de filamento, a máquina purga material que vai direto pro lixo. Em muitos casos, o volume descartado é igual ou maior que o da peça final.

O filamento segue sendo um dos maiores custos operacionais, e todo esse resíduo plástico simplesmente não tem destino.

## A Proposta

A OpenFil transforma resíduos de impressão 3D em matéria-prima reutilizável. Em vez de descartar, você tritura, processa e re-extruda o material em filamento novo — reduzindo custos em até 90% e eliminando o desperdício na origem.

## Ecossistema

O projeto é composto por módulos independentes que juntos formam uma linha completa de reciclagem descentralizada:

| Módulo | Descrição | Status |
|--------|-----------|--------|
| **Extrusora** | Núcleo de aquecimento otimizado para fluxo constante e controle dimensional do filamento | ✅ v1 disponível |
| **Tracionador** | Sistema de engrenagens para tração sincronizada com a velocidade de extrusão | 🔜 Em desenvolvimento |
| **Enrolador** | Enrolamento automático no carretel, sem nós e sem intervenção manual | ✅ v1 disponível |
| **Triturador (Shredder)** | Tritura resíduos plásticos em grânulos prontos para a extrusora | 🔜 Em desenvolvimento |

## Ciclo Fechado

```
Impressão 3D → Resíduo Coletado → Trituração → Extrusora OpenFil → Novo Filamento ↩
```

O material não precisa sair do seu ambiente de criação. Ele é reutilizado, reprocessado e volta como filamento — pronto para a próxima impressão.

## Origem

A OpenFil nasceu em **2014** como um projeto DIY de extrusão de filamento. A v1 provou que reciclagem descentralizada era viável. Agora, com uma década de aprendizado, a **v2** está sendo desenvolvida com foco em estabilidade térmica, precisão dimensional e velocidade de extrusão.

## Roadmap

- [x] **Comunidade & Presença** — Canais no Instagram, Facebook, YouTube e Reddit
- [ ] **Protótipo v2** — Construção física e testes intensivos da extrusora v2
- [ ] **Plataforma v2** — STLs, BOM e guias de montagem atualizados para membros
- [ ] **Ecossistema Completo** — Enrolador automático v2 + triturador

## Estrutura do Repositório

```
/
├── docs/           # Documentação e guias de montagem
├── stl/            # Arquivos STL para impressão das peças
├── bom/            # Lista de materiais (Bill of Materials)
├── firmware/       # Código do controlador (se aplicável)
├── images/         # Fotos e diagramas do projeto
└── README.md
```

> ⚠️ **Nota:** Ajuste a estrutura acima conforme o conteúdo real do seu repositório.

## Para Quem

- **Makers e hobbyistas** que imprimem com frequência e querem reduzir custos
- **Pequenas empresas** com alto volume de impressão 3D
- **Escolas, labs e fablabs** que precisam de sustentabilidade orçamentária
- **Usuários de impressoras multicoloridas** que geram alto volume de purga
- **Comunidades** que buscam fabricação digital circular

## Licença

A **v1** do projeto é disponibilizada gratuitamente como open source para quem quiser montar por conta própria.

A **v2** e conteúdos premium (guias detalhados, suporte, atualizações) são disponibilizados através da [Comunidade Premium OpenFil](https://openfil3d.com.br).

> 📄 Consulte o arquivo [LICENSE](LICENSE) para os termos completos.

## Contribuindo

Contribuições são bem-vindas! Abra uma issue para reportar problemas ou sugerir melhorias. Pull requests são avaliados pelos mantenedores do projeto.

## Links

- 🌐 **Site:** [openfil3d.com.br](https://openfil3d.com.br)
- 📧 **Lista de espera:** [Acesso antecipado](https://openfil3d.com.br)

---

Criada por brasileiros. Construída pelo mundo. 🇧🇷🌍
