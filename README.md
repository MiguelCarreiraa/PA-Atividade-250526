1. Explique com suas palavras o que é Spring Security.
   R: Spring Security é um framework do java focado em autentificação e controle de acesso.

2. Para que serve o método csrf().disable()?
   R: Esse método serve para desativar o Spring Security.

3. Explique o que significa SessionCreationPolicy.STATELESS.
   R: O stateless serve para não guardar as informações do usuario.

 4. Qual a função do permitAll()?
    R: Essa função permite que qualquer usuario possa usar uma determinada requisição como POST, GET, PUT.

 5. Explique o que faz o requestMatchers().
    R:Serve para selecionar quais requisiçoes terão regras de segurança. 

6. Qual a função do anyRequest().authenticated()?
    R: Bloqueia qualquer requisição pra usuarios não autentificados.
   
7. O que é uma API Stateless?
   R: Modelo usado para não salvar o registro de requisição do usuario.

8. Explique o que a lambda abaixo faz:
session -> session.sessionCreationPolicy(SessionCreationPolicy.STATELESS)
  R: O stateless serve para não guardar as informações do usuario.
