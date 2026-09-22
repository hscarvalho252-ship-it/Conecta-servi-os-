# Conecta Serviços

Protótipo PWA de marketplace local de serviços.

## Como executar
1. Extraia os arquivos.
2. Abra `index.html` em um navegador ou publique no GitHub Pages.
3. Para instalar como aplicativo, acesse pelo navegador compatível e escolha "Adicionar à tela inicial".

## Avisos importantes
- Esta versão usa `localStorage`, portanto os dados ficam apenas no navegador/dispositivo.
- O login é demonstrativo e não deve ser usado com senhas reais.
- Para produção, conecte Supabase/Firebase ou outro backend com:
  - autenticação segura;
  - banco de dados;
  - regras de acesso por função;
  - chat em tempo real;
  - pagamentos recorrentes;
  - proteção contra fraude e recuperação de senha.
- A conta administrativa de demonstração é criada localmente com:
  - e-mail: `jefersoncarvalho252@gmail.com`
  - senha: `ben2018`
  Altere o sistema antes de qualquer uso real. Não publique credenciais reais.

## Fluxo de pagamento profissional
- Mensalidade: R$ 4,99.
- Contato para confirmação: WhatsApp (79) 99905-5301.
- O profissional permanece pendente até o ADM ativar a assinatura.
- O ADM ativa ou suspende a assinatura no painel administrativo.

## Aprovação e exclusão
- Ao cadastrar um profissional, o sistema abre o WhatsApp do ADM para análise.
- O profissional fica pendente até o ADM ativar a assinatura.
- O ADM pode suspender, reativar ou excluir clientes e profissionais.
- A exclusão pede o código `26` nesta versão demonstrativa.
- Não use o código fixo em produção; substitua por autorização segura no backend.
