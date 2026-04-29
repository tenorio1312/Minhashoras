🕒 Minhas Horas - Gestão de Serviços
Minhas Horas é uma solução inteligente e minimalista para o controle de jornada de trabalho e despesas de deslocamento, focada na transparência entre Prestadores de Serviço e Tomadores (Responsáveis).
🚀 Funcionalidades Principais
Para o Prestador (Controle Total)
* Cronômetro em Tempo Real: Registro de jornada com contador visual de horas, minutos e segundos.
* Gestão de Tarifas: Configuração de valor por hora e custo fixo de transporte (sujeito à aprovação).
* Extrato Detalhado: Histórico completo de lançamentos com status de pagamento e cálculos automáticos.
* Vínculo Direto: Conexão simples com o tomador via código de grupo.
Para o Tomador (Gestão e Auditoria)
* Aprovações em Tempo Real: Fluxo de revisão para novas horas lançadas.
* Controle de Custos: Aprovação obrigatória de alterações nas tarifas (valor/hora e transporte) do prestador.
* Visão Financeira: Dashboard com total pendente e total aprovado para pagamento.
* Extrato Compartilhado: Acesso visual a todos os logs do prestador vinculado.
Para o Administrador
* Painel de Controle: Gestão global de usuários e monitoramento de todos os registros do sistema.
🛠️ Tecnologias Utilizadas
* React.js: Biblioteca principal para a interface.
* Tailwind CSS: Estilização moderna e responsiva.
* Lucide React: Conjunto de ícones minimalistas.
* Context API: Gestão de estado global da aplicação.
📦 Como Instalar e Rodar
1. Clone o repositório:
git clone [https://github.com/seu-usuario/minhas-horas.git](https://github.com/seu-usuario/minhas-horas.git)

2. Entre na pasta do projeto:
cd minhas-horas

3. Instale as dependências:
npm install

4. Inicie o servidor de desenvolvimento:
npm run dev

🌐 Próximos Passos (Roadmap para Produção)
Para colocar esta aplicação "em produção" para usuários reais, as seguintes etapas são recomendadas:
   1. Persistência com Firebase: Substituir o estado em memória pelo Cloud Firestore para salvar os dados permanentemente.
   2. Autenticação Real: Implementar Firebase Auth para logins seguros com e-mail/senha ou Google.
   3. Exportação de Relatórios: Adicionar funcionalidade para gerar PDFs de fechamento mensal.
   4. Notificações Push: Avisar o tomador quando houver novas horas para aprovar.
📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para detalhes.
Desenvolvido com foco em simplicidade e confiança.
