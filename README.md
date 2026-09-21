# Calendar.io IT - Calendário Inteligente & Planejamento Anual de TI

Aplicação executiva e operacional de produtividade de TI, com 6 visualizações dinâmicas, SLA de prazos, checklist de Definition of Done (DoD), Drag & Drop, dashboard de métricas, modo escuro/claro e persistência automática no navegador.

---

## 🚀 Como Fazer o Deploy Gratuito na Vercel

O projeto foi estruturado como uma SPA estática de alta velocidade em arquivo único, perfeitamente compatível com a Vercel.

### Método 1: Deploy via GitHub (Recomendado)
1. Crie um repositório no seu GitHub (ex: `calendar-io-ti`).
2. Suba os arquivos desta pasta para o repositório:
   ```bash
   git init
   git add .
   git commit -m "feat: Calendário Inteligente de TI"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/calendar-io-ti.git
   git push -u origin main
   ```
3. Acesse [vercel.com](https://vercel.com) e faça login.
4. Clique em **"Add New..."** > **"Project"**.
5. Importe o repositório `calendar-io-ti`.
6. Como o projeto é HTML estático, **não é necessário configurar nenhum Framework ou Build Command**.
7. Clique em **"Deploy"**. Em menos de 10 segundos sua aplicação estará online com certificado HTTPS gratuito!

### Método 2: Deploy Direto via Terminal (Vercel CLI)
Se tiver o Node.js instalado, você pode fazer o deploy diretamente do terminal nesta pasta:
```powershell
npx -y vercel
```
- Siga as instruções rápidas no terminal (aceite os valores padrão).
- Para publicar em produção definitiva:
```powershell
npx -y vercel --prod
```

---

## 💾 Como Funciona a Persistência na Vercel?
- Todas as tarefas que você criar, editar, mover ou marcar como concluídas são **salvas automaticamente no LocalStorage do seu navegador**, associadas ao domínio da Vercel (ex: `https://seu-projeto.vercel.app`).
- **Privacidade Total**: Seus dados corporativos não são enviados para nenhum servidor externo; ficam 100% seguros na máquina do usuário.
- **Backup & Restauração**: Você pode exportar seus dados a qualquer momento em arquivo `.json` (no botão de opções `⋮`) e importá-los em outro computador.

---

## 🛠️ Tecnologias Utilizadas
- **HTML5 & Vanilla JavaScript**: Sem dependências complexas ou compilações lentas.
- **Tailwind CSS**: Design responsivo com suporte nativo a Dark Mode e Light Mode.
- **Lucide Icons**: Ícones vetoriais modernos.
- **HTML5 Drag & Drop API**: Movimentação fluida entre raias do Kanban.
