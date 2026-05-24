# EmotiWave — Quality Assurance & Compliance

## Integrantes

- Lucas José Lima - RM561160
- Rangel Bernardi Jordao - RM560547
- Jhonatta Lima Sandes De Oliveira - RM560277

## Plano de Testes Manuais — Nível de Sistema

Repositório de entrega da atividade de **Compliance & Quality Assurance**.

---

## 📋 Parte A — Testes Manuais (Azure Boards)

Os testes manuais foram cadastrados no Azure Boards e cobrem as principais funcionalidades do sistema EmotiWave.

🔗 **Link Azure Boards:** `https://dev.azure.com/MR560547/EmotiWave/_workitems/recentlyupdated/`

### Funcionalidades cobertas

| Módulo | Casos de Teste |
|---|---|
| Autenticação | TC-001, TC-002, TC-003 |
| Segurança / JWT | TC-004 |
| Música | TC-005, TC-006, TC-007 |
| Estatísticas | TC-008 |
| Usuário-Música | TC-009, TC-014, TC-015 |
| Admin | TC-010, TC-011, TC-012, TC-013 |
| **Total** | **15 casos de teste** |

---

## 🛠️ Sobre o Sistema

O **EmotiWave** é uma plataforma de análise de música e emoção integrada ao Spotify, Genius Lyrics e HuggingFace AI.

- **Backend:** Spring Boot 3.5.7 / Java 21
- **Banco de dados:** Oracle 12c
- **Autenticação:** JWT Bearer Token
- **Documentação da API:** Swagger UI em `/swagger-ui/index.html`
