# Coletar Dados de CPFs

Bem-vindo ao nosso repositório de código aberto dedicado à coleta de dados de CPFs. Esta API foi desenvolvida para facilitar a coleta eficiente e automatizada de informações associadas a números de CPF.

**Lembrete:** Devido ao sistema de coleta estar em andamento e processando continuamente novos dados, pode ser que alguns CPFs não estejam disponíveis imediatamente. Se você deseja contribuir para a expansão dos dados disponíveis, visite nossa rota:
```/api/consultarCPFS.```

---

#### URL de produção

```http
  https://coleta-de-cpfs.onrender.com
```

## Rotas da API

#### Coletar dados de um CPF

```http
  GET /api/consultar?cpf={cpf}
```

| Parametro | Tipo     | Valor                |
| :-------- | :------- | :------------------------- |
| `cpf` | `string` | CPF a ser pesquisado |

#### Coletar dados de varios CPFs

```http
  GET /api/consultarCPFS?quantidade={quantidade}
```

| Parametro | Tipo     | Valor                |
| :-------- | :------- | :------------------------- |
| `quantidade` | `number` | Quantidade de CPFs |

