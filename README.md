# 🎓 CarreiraHub — Frontend

Frontend (React + Vite) da plataforma CarreiraHub.

## ✨ Destaques

- ✅ **Candidatura com Currículo** — Upload automático e envio do link para a empresa
- ✅ **Status Visual da Vaga** — Vaga aplicada fica com tonalidade diferente e botão desabilitado
- ✅ **Rotas da Empresa** — Página de candidatos em `/candidatos`

## 🚀 Execução (dev)

```powershell
cd "C:\Users\a92207984\Desktop\Projeto feito com Valnei e Wesley\Desigualdade-frontend"
$env:DISABLE_ELECTRON="true"
npx vite
```

Abra a URL exibida pelo Vite (ex: `http://localhost:5173`).

## 🔧 Variáveis de Ambiente

Crie um arquivo `.env` na raiz com:

```
VITE_API_URL=http://localhost:4000
```

## 🔗 Rotas principais

- `/vagas` — Vagas disponíveis
- `/candidatos` — Candidatos (empresa)

## 🧪 Teste rápido (fluxo de candidatura)

1) Logue como estudante
2) Em `/vagas`, clique **Candidatar-se**
3) Selecione o currículo
4) A vaga aplicada ficará destacada e o botão será desabilitado
