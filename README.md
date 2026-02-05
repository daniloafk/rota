# 🚚 Sistema de Rotas Shopee

Sistema completo para gerenciamento de rotas de entrega, permitindo que administradores importem rotas e entregadores escolham suas preferências em tempo real.

---

## 🌟 Características

- ✅ **Interface moderna** e responsiva
- ✅ **Realtime** - atualizações instantâneas sem refresh
- ✅ **Gratuito** - Supabase + Vercel/Netlify
- ✅ **Escalável** - suporta 700+ usuários simultâneos
- ✅ **Seguro** - autenticação e RLS (Row Level Security)
- ✅ **Mobile-friendly** - funciona em celulares

---

## 📁 Estrutura do Projeto

```
📁 shopee-rotas/
├── index.html                    # Sistema completo
├── vercel.json                   # Configuração Vercel
├── package.json                  # Info do projeto
├── 01-setup-database.sql         # Script do banco de dados
├── ETAPA-01-INSTRUCOES.md        # Guia: Configurar Supabase
├── ETAPA-02-INSTRUCOES.md        # Guia: Configurar Frontend
├── ETAPA-03-DEPLOY-VERCEL.md     # Guia: Deploy Vercel
├── ETAPA-03-DEPLOY-NETLIFY.md    # Guia: Deploy Netlify (alternativa)
├── ETAPA-04-TESTES-PRODUCAO.md   # Guia: Testes e Go-Live
└── README.md                     # Este arquivo
```

---

## 🚀 Início Rápido

### 1. Configurar Supabase
Siga o guia: `ETAPA-01-INSTRUCOES.md`

### 2. Configurar Frontend
Siga o guia: `ETAPA-02-INSTRUCOES.md`

### 3. Fazer Deploy
Siga o guia: `ETAPA-03-DEPLOY-VERCEL.md`

### 4. Testar
Siga o guia: `ETAPA-04-TESTES-PRODUCAO.md`

---

## 🔗 URLs do Sistema

| Função | URL |
|--------|-----|
| Admin (login) | `https://seu-site.vercel.app` |
| Formulário público | `https://seu-site.vercel.app/#form` |

---

## 💰 Custos

| Serviço | Plano | Custo |
|---------|-------|-------|
| Supabase | Free | R$ 0 |
| Vercel | Hobby | R$ 0 |
| **Total** | | **R$ 0/mês** |

> Para mais de 200 conexões simultâneas, considere Supabase Pro ($25/mês)

---

## 🛠️ Tecnologias

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Backend:** Supabase (PostgreSQL + Realtime + Auth)
- **Hospedagem:** Vercel ou Netlify
- **Bibliotecas:** SheetJS (Excel), html2canvas (Imagens)

---

## 📊 Funcionalidades

### Painel Admin
- Dashboard com estatísticas
- Importação de rotas (Excel/CSV)
- Gerenciamento de rotas
- Gerenciamento de entregadores
- Exportação para Excel
- Geração de imagem (lista)
- Controle de horário do formulário
- Visualização em tempo real

### Formulário Público
- Lista de rotas disponíveis
- Filtros por cidade e veículo
- Cadastro simplificado
- Validação de placa única
- Validação de rota disponível
- Atualização em tempo real

---

## 🔒 Segurança

- Autenticação via Supabase Auth
- Row Level Security (RLS) habilitado
- HTTPS obrigatório
- Senhas criptografadas
- API keys públicas (anon) são seguras

---

## 📞 Suporte

Em caso de problemas:
1. Consulte a seção "Problemas Comuns" em cada guia de etapa
2. Verifique os logs no Supabase Dashboard
3. Verifique os logs na Vercel/Netlify

---

## 📝 Licença

MIT License - Uso livre para fins comerciais e pessoais.

---

*Desenvolvido com ❤️ para a Shopee*
