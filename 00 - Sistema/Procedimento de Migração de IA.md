# Procedimento de Migração de IA

## Objetivo
Permitir que outro modelo, conta ou ambiente assuma a Redação Fla10 com o menor custo de contexto possível, usando o repositório como fonte persistente.

## Antes de iniciar
1. Confirmar que o repositório correto está acessível e atualizado.
2. Ler `AGENTS.md` e `README.md`.
3. Ler [[Índice]], [[Protocolo de Operação da IA]] e [[Protocolo de Colaboração e Aprendizado]].
4. Ler [[Identidade Editorial]], [[Apuração e Integridade Factual]], [[Estilo e Formatação]] e [[Revisão e Controle de Qualidade]].
5. Ler [[Painel de Pautas]], [[Projetos e Pautas Reservadas]] e [[Registro de Decisões]].
6. Abrir o manual específico do formato da primeira tarefa.
7. Identificar documentos citados que estejam ausentes e não presumir seu conteúdo.

## Primeira resposta da nova IA
A IA deve resumir brevemente:
- missão e voz da Redação Fla10;
- regras de factualidade e hierarquia de instruções;
- convenções de formatação, SEO e Resumo para IA;
- procedimento para pautas e prevenção de redundância;
- limites de acesso a histórico, CMS e plataformas externas;
- dúvidas de estado que precisam de confirmação.

Não deve recitar todos os manuais nem afirmar que tem memória da conta anterior.

## Na execução diária
- Atualizar a cópia local antes de trabalhar e resolver conflitos de Git com cuidado.
- Consultar os documentos relevantes à tarefa, sem carregar todo o vault desnecessariamente.
- Pesquisar informações atuais quando o assunto depender de atualização.
- Ao receber confirmação de mudança de estado de pauta, atualizar o painel.
- Registrar novas regras apenas quando forem duradouras ou explicitamente solicitadas.
- Versionar as mudanças e verificar o resultado do commit.

## Teste de aceitação
Executar [[Teste de Migração e Aceitação]] antes de considerar a migração operacionalmente validada.

## Limitações reais
O repositório preserva diretrizes e contexto documentado, mas não transfere automaticamente pesos de modelo, ferramentas, permissões, conectores, histórico não registrado ou capacidades de pesquisa. A equivalência deve ser testada com tarefas representativas.
