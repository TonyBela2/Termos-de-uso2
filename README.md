# Sistema de Gerenciamento de Termos e Condições

Este projeto contém um conjunto de códigos para gerenciar Termos e Condições de Uso em um aplicativo, garantindo conformidade com políticas de privacidade e registros de consentimento dos usuários. O sistema também inclui funcionalidades de notificações automáticas e monitoramento de consentimentos.

## Funcionalidades

1. **Atualização Automática dos Termos e Condições**:
   - Permite a atualização e armazenamento de versões dos Termos e Condições.
   - Mantém um histórico de atualizações com data e detalhes.

2. **Envio de Notificações Automáticas**:
   - Envia e-mails de notificação quando os Termos de Uso são atualizados.

3. **Registro de Consentimento dos Usuários**:
   - Armazena o consentimento dos usuários em um arquivo JSON.
   - Permite consultar o consentimento de um usuário específico.

4. **Exibição e Solicitação de Consentimento no Aplicativo**:
   - Exibe os termos e condições no aplicativo Android.
   - Registra o consentimento do usuário ao aceitar os termos.

5. **Auditoria de Registros de Consentimento**:
   - Realiza a auditoria dos registros de consentimento, exibindo data, versão e detalhes.

6. **Testes de Usabilidade**:
   - Simula testes de usabilidade em relação à aceitação dos Termos de Uso no app.

7. **Monitoramento de Logs de Consentimento**:
   - Registra os consentimentos em um arquivo de log para monitoramento contínuo.

8. **Notificações Push com Firebase**:
   - Envia notificações push automáticas utilizando Firebase Cloud Messaging.

9. **Integração de Backend para Termos de Uso**:
   - Endpoints de API com Flask para obter e registrar o consentimento dos usuários.

10. **Testes de Conformidade**:
    - Testes unitários para validar a atualização dos Termos e o registro de consentimentos.

## Instalação

### Pré-requisitos

- **Python 3.x** (para rodar o backend e scripts de consentimento)
- **Flask** (para o backend)
- **Firebase** (para notificações push)
- **Android Studio** (para rodar o aplicativo Android)

