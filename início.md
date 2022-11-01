---
cssclass: dashboard
banner: "![[dashboard_de_avião.jpg]]"
banner_x: 0.5
banner_y: 0.52516
---

> [!Principal]+ # Estudos
> - 🗓️ [[Estudos/Planejamento|Planejamento da Semana]]
>	- [[Estudos/Planejamento/00 - Planejamento|Planejamento]]
>	- [[Estudos/Planejamento/Semana43|Semana 43]]
>	- [[Estudos/Planejamento/Semana44|Semana 44]]
> -  📄 [[Estudos/Disciplina|Assuntos da semana]] 
>	- [[Analytics e Gestão de Riscos]]
>	- [[Legislação no Ambiente Digital (LGPD)]]
>	- [[Social Network Analysis]]
>	- [[Analytical Hierarchy Process (AHP)]]
> - ⏲️ [[Estudos/Revisões|Agenda de Revisões]] 
>	- [[Estudos/Revisões/PT/vírgula|Português: uso da vírgula]]  
>	- [[Estudos/Revisões/PT/orações|Português: orações]]  
>	- [[Estudos/Revisões/DAD/poderes|Direito Administrativo: poderes]]  
> -  📚 [[Estudos/Biblioteca|Leituras]]
>	- [[Estudos/Biblioteca/Sharpe's Siege|Sharpe's Siege]]
>	- [[Estudos/Biblioteca/The Killer Angels|The Killer Angels]]
>	- [[Estudos/Biblioteca/Manual de Direito Administrativo|Manual de Direito Administrativo]]

> [!warning]+ # Trabalho
> - 💼 Projetos ativos
>	- [[Trabalho/Projetos/06-revisão do projeto T|Revisão do 06T]]
>	- [[Trabalho/Projetos/07-atualização das visitas técnicas|Visitas Técnicas]]
>	- [[Trabalho/Projetos/08-MoC prospectivo|Moc Prospectivo]]
> - 🕚 Sprints
>	- [[Trabalho/Sprints/43|Sprint 43]]
>	- [[Trabalho/Sprints/44|Sprint 44]]
>	- [[Trabalho/Sprints/45|Sprint 45]]
>	- [[Trabalho/Sprints/46|Sprint 46]]
> - 👥 Reuniões marcadas
>	- [[Trabalho/Reuniões/revisão43|2022/10/28: Revisão S43]]
>	- [[Trabalho/Reuniões/Planejamento44|2022/10/31: Planejamento S44]]
>	- [[Trabalho/Reuniões/marketing01|2022/10/31: marketing]]
>	- [[Trabalho/Reuniões/entrevistaPaulo|2022/11/01: Entrevista Paulo José]]

> [!tip]+ # Pessoal
> - 💸 Contas e Pagamentos
>	- [[Pesssoal/Dinheiro/Lista de contas|Lista de Contas]]
>	- [[Pessoal/Dinheiro/plano de celular|Escolher outro plano de celular]]
>	- [[Pessoal/Dinheiro/férias|Revisar férias]] 
> - ✍️ Blog
>	- [[Pessoal/Blog/posts pendentes|Posts Pendentes]]
>	- [[Pessoal/Blog/post sobre dashboards|Post sobre painéis]]
> -  🍝 [[Pessoal/Receitas|Receitas]]
>	- [[tiramisu|Tiramisu]]
>	- [[Pessoal/Receitas/bolo de laranja|Bolo de Laranja|]]

> [!Exemple]- # Compras
> `$=dv.taskList(dv.pages('"Tarefas/Compras"').file.tasks .where (t => !t.completed))`


> [!danger]+ # Informações
> - 🗄️ Anotações alteradas recentemente
 `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)`
> - 🔖 Tag:  importante 
 `$=dv.list(dv.pages('#importante').sort(f=>f.file.name,"desc").limit(4).file.link)`
> - 〽️ Estatística
>	-  Total de arquivos: `$=dv.pages().length`
>	-  Semanas de estudo planejadas: `$=dv.pages('"Estudos/Planejamento"').length`
>	- Tarefas concluídas: `$=dv.span(dv.pages('"Tarefas"').file.tasks.where(t => t.completed).length);`
>	-  Tarefas em aberto: `$=dv.span(dv.pages('"Tarefas"').file.tasks.where(t => !t.completed).length);`