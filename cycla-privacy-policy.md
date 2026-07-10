# Política de Privacidade — Cycla

**Última atualização:** 10 de julho de 2026

Esta Política de Privacidade descreve como o aplicativo **Cycla** ("Cycla", "aplicativo", "nós") coleta, usa, armazena e protege os dados das pessoas que o utilizam ("você", "usuária"), em conformidade com a Lei Geral de Proteção de Dados Pessoais (Lei nº 13.709/2018 — LGPD).

## 1. Quem é o responsável pelo tratamento dos dados

O Cycla é desenvolvido e mantido por **André Lucas** ("controlador"), pessoa responsável pelas decisões referentes ao tratamento dos dados pessoais coletados pelo aplicativo.

**Contato:** andrelucassvt99@gmail.com

## 2. Quais dados coletamos

### 2.1 Dados de conta e autenticação

Ao criar uma conta, coletamos, por meio do Firebase Authentication:

- Nome
- E-mail
- Data de nascimento
- Método de autenticação utilizado (e-mail/senha, Google ou Apple)
- Data de criação da conta

Se você entrar com Google ou Apple, recebemos do provedor apenas o nome e o e-mail associados à sua conta nesses serviços, conforme as permissões que você concede no momento do login.

### 2.2 Dados de perfil

Os dados acima ficam armazenados em nosso banco de dados na nuvem (Firestore), e também em cache local no seu dispositivo para uso da sessão e da interface.

### 2.3 Dados de ciclo menstrual e saúde

O Cycla é **local-first**: os dados a seguir são armazenados **somente no seu dispositivo** (por meio de armazenamento local), e não são enviados aos nossos servidores nem à nuvem, salvo quando você mesma optar por exportá-los (ver seção 6):

- Datas de início e fim das menstruações
- Duração do ciclo, da menstruação e da fase lútea configuradas por você
- Registros diários de fluxo, sintomas físicos, humor e anotações livres
- Respostas ao checklist de atraso menstrual

Esses dados são considerados **dados sensíveis de saúde** nos termos do art. 5º, II, da LGPD, e recebem o nível de proteção correspondente.

### 2.4 Dados técnicos e do dispositivo

- Identificador de instalação/dispositivo necessário para o envio de notificações (token do Firebase Cloud Messaging)
- Fuso horário do dispositivo, usado para agendar notificações e cálculos de ciclo
- Versão do aplicativo e do sistema operacional

Atualmente o Cycla **não utiliza** ferramentas de analytics, rastreamento de comportamento ou publicidade de terceiros.

## 3. Como coletamos os dados

- Diretamente de você, quando preenche formulários de cadastro, perfil, configurações de ciclo e registros diários.
- Automaticamente pelo provedor de autenticação escolhido (Google ou Apple), com o seu consentimento no momento do login.
- Automaticamente pelo dispositivo, para fins técnicos (fuso horário, token de notificação).

## 4. Para que usamos seus dados

| Finalidade | Dados envolvidos | Base legal (LGPD) |
|---|---|---|
| Criar e autenticar sua conta | Nome, e-mail, data de nascimento, provedor de login | Execução de contrato (art. 7º, V) |
| Calcular fases do ciclo, previsões, janela fértil e atraso | Dados de ciclo e registros diários | Consentimento (art. 11, I — dado sensível de saúde) |
| Exibir histórico, padrões e alertas personalizados | Registros diários, períodos, configurações | Consentimento (art. 11, I) |
| Enviar notificações sobre o ciclo (locais e push) | Token de notificação, fuso horário, dados de ciclo | Consentimento (art. 7º, I) |
| Permitir exportação/compartilhamento dos seus dados | Todos os dados de ciclo, a seu critério | Execução de solicitação da titular |
| Corrigir falhas e manter a segurança do aplicativo | Dados técnicos do dispositivo | Legítimo interesse (art. 7º, IX) |

Não usamos seus dados de saúde para publicidade direcionada, venda a terceiros ou qualquer finalidade além das descritas acima.

## 5. Com quem compartilhamos dados

- **Firebase / Google Cloud (Firebase Authentication e Cloud Firestore):** operador que hospeda os dados de conta e perfil. Os servidores podem estar localizados fora do Brasil, sujeitos às garantias contratuais da Google para tratamento de dados.
- **Google Sign-In e Apple Sign-In:** utilizados apenas se você optar por entrar com essas contas; nesse caso, o provedor escolhido processa a autenticação conforme suas próprias políticas de privacidade.
- **Ninguém mais.** Não vendemos, alugamos ou compartilhamos seus dados de ciclo/saúde com anunciantes, corretores de dados ou qualquer outro terceiro.

## 6. Exportação e compartilhamento pelos seus próprios meios

O Cycla permite exportar seus dados de ciclo em formato JSON, a partir da tela de perfil. Ao usar essa função, o compartilhamento (por e-mail, aplicativos de mensagem, armazenamento em nuvem pessoal, etc.) é feito por meio do recurso nativo de compartilhamento do seu sistema operacional, e o destino final é escolhido exclusivamente por você. Não temos acesso nem controle sobre o que acontece com o arquivo após a exportação.

## 7. Notificações

Se você autorizar, enviamos notificações locais e push relacionadas ao seu ciclo (por exemplo, previsão de menstruação ou fase fértil). Você pode revogar essa permissão a qualquer momento nas configurações do seu dispositivo.

## 8. Retenção e exclusão dos dados

- **Dados de conta/perfil (Firestore):** mantidos enquanto sua conta existir. Ao excluir sua conta, os dados correspondentes são removidos do Firestore.
- **Dados de ciclo (locais):** permanecem no seu dispositivo até que você os apague manualmente (nas configurações do aplicativo) ou desinstale o aplicativo. Como não há cópia em nuvem desses dados, a desinstalação ou perda do dispositivo resulta na perda definitiva desses registros, salvo se você os tiver exportado previamente.

## 9. Segurança

Adotamos medidas técnicas razoáveis para proteger seus dados, incluindo autenticação via Firebase e armazenamento local restrito ao próprio aplicativo. Nenhum sistema é 100% livre de riscos; caso identifique uma vulnerabilidade, entre em contato pelo e-mail indicado na seção 1.

## 10. Seus direitos como titular de dados (art. 18 da LGPD)

Você pode, a qualquer momento:

- Confirmar a existência de tratamento de dados;
- Acessar seus dados;
- Corrigir dados incompletos, inexatos ou desatualizados (diretamente na tela de perfil e configurações do aplicativo);
- Solicitar anonimização, bloqueio ou eliminação de dados desnecessários;
- Solicitar a portabilidade dos seus dados (via exportação em JSON, descrita na seção 6, ou mediante solicitação por e-mail);
- Solicitar a eliminação dos dados de conta, encerrando sua conta pelo aplicativo ou por solicitação ao contato da seção 1;
- Revogar o consentimento dado, a qualquer momento;
- Opor-se a tratamento realizado com base em outras hipóteses legais.

Para exercer esses direitos, entre em contato pelo e-mail informado na seção 1.

## 11. Uso por menores de idade

O Cycla pode ser utilizado por pessoas a partir de 13 anos. Usuárias entre 13 e 18 anos incompletos devem utilizar o aplicativo com o consentimento e a supervisão de um pai, mãe ou responsável legal, que também poderá exercer os direitos da titular descritos na seção 10 em nome da menor. Não coletamos intencionalmente dados de crianças menores de 13 anos; se identificarmos esse caso, os dados serão excluídos.

## 12. Transferência internacional de dados

Como o Firebase/Firestore é operado pela Google, seus dados de conta e perfil podem ser processados em servidores localizados fora do Brasil. Essa transferência ocorre com base nas garantias contratuais e de conformidade oferecidas pela Google para operações internacionais de dados.

## 13. Alterações nesta Política

Podemos atualizar esta Política periodicamente para refletir mudanças no aplicativo ou na legislação. A data no topo deste documento indica a versão mais recente. Alterações relevantes poderão ser comunicadas dentro do próprio aplicativo.

## 14. Contato

Dúvidas, solicitações ou reclamações sobre esta Política ou sobre o tratamento dos seus dados podem ser enviadas para:

**E-mail:** andrelucassvt99@gmail.com
