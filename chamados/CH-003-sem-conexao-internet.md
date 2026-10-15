# CH-003 — Computador sem conexão com a internet

**Tipo:** Estudo de caso simulado  
**Categoria:** Suporte técnico N1 / Redes  
**Ambiente:** Windows 11  
**Status:** Investigação simulada

## 1. Descrição do problema

Usuário relata que o computador está conectado à rede Wi-Fi, mas não consegue acessar sites.

## 2. Sintomas relatados

- Navegador não carrega páginas.
- Ícone de rede indica conexão Wi-Fi.
- Problema relatado em mais de um site.
- Não foi confirmado se outros dispositivos conseguem acessar a internet.

## 3. Verificações iniciais

- [ ] Confirmar se outros dispositivos acessam a internet.
- [ ] Verificar se o Wi-Fi está conectado à rede correta.
- [ ] Testar mais de um site e navegador.
- [ ] Verificar se há mensagens de erro no Windows.
- [ ] Confirmar se existe VPN ou proxy configurado.
- [ ] Verificar o endereço IP usando `ipconfig`.

## 4. Hipóteses iniciais

- Falha na conexão do roteador ou provedor.
- Problema na configuração de IP.
- Falha de resolução DNS.
- Interferência de VPN ou proxy.
- Problema no adaptador de rede.

As hipóteses ainda não foram confirmadas.

## 5. Plano de diagnóstico

1. Verificar se o problema ocorre em outros dispositivos.
2. Executar `ipconfig` e observar a configuração de rede.
3. Testar a comunicação com o gateway padrão, se identificado.
4. Caso necessário, testar a resolução de nomes com `nslookup`.
5. Registrar os resultados antes de alterar configurações.

## 6. Possíveis ações corretivas

As ações serão escolhidas de acordo com os resultados dos testes. Não redefinir configurações de rede nem alterar DNS antes de identificar evidências que justifiquem a intervenção.

## 7. Validação

Após uma eventual correção:

- [ ] Confirmar que o computador consegue acessar sites.
- [ ] Testar mais de um endereço.
- [ ] Confirmar que a conexão permanece estável.
- [ ] Registrar o resultado final.

**Resultado:** Não executado. Cenário fictício para fins de estudo.

**Observação:** Este documento não representa um atendimento real nem resultados de testes realizados.
