# ✅ - Ficha de cadastro ou Registro de inscrição municipal:
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)
#
**⚠️    Observações:**
-   Ficha de cadastro do contribuinte, ficara na tela da view.  <br> 
-   Adicionar botão ação na view: <br> 
    01 - Ficha de cadastro; <br>

    **local abaixo:** ⬇️

    ![alt text](/Fotos/exemploview.png)
    <br>
#
##  Relatório possui 4 variações:<br>
    -  Jurídica - Mobiliáario
       - ⚠️ Observação: Alteração no titulo do relatorio "Registro de inscrição municipal" 

    -  Jurídica - Titulo: Ficha de cadstro;

    -  Fisica   - Titulo: Ficha de cadastro;

    -  Fisica   - Profissional Liberal: 
        - ⚠️ Observação: Alteração no titulo do relatorio "Ficha de Cadastro Profissional Liberal".

 <br>



#
## ⚖️ - Jurídica - Mobiliário:<br>
>   **Observação I:** Titulo do relatorio sendo Jurídica - Mobiliário será: **"Registro de inscrição municipal"**. <br>

>   **Observação II:** Utilizar mesmo modelo da View do contribuinte. 
```
> ⚙️ - Campos do relatório:

✅ - Titulo                --> Jurídico do municipio: "Registro de inscrição municipal" ;

-   🌍  Dados Gerais:
1.  Tipo pessoa:            --> (Juridica);
2.  CNPJ:                   --> 
3.  Razão Social:           --> 
4.  Fantasia:               --> 
5.  Inscrição Estadual:     --> 
6.  Representante Legal     --> Caso possuir trazer campo "Nome contribuinte" cadastro como representante legal;
7.  Situação                --> 
8.  Data Criação            --> Data de cadastro da empresa no sistema; 

-   🗺️  Endereço:
1.  CEP                     --> 
2.  Estado                  --> Estado deve ser igual da entidade;
3.  Município               --> Municipio deve ser igual da entidade; 
4.  Bairro                  -->
5.  T.Logradouro            -->
6.  Logradouro              -->
7.  Nº                      -->
8.  Complemento             -->

-   📞  Contato:
1.  Telefone fixo           --> 
2.  Celular                 -->
3.  E-mail                  -->
4.  Site                    -->

-   📚  Atividade:
1.  Inscrição Municipal     -->
2.  Regime Especial Trib    -->
3.  Porte                   -->
4.  CNAE Principal          -->
5.  Início atividade        -->
6.  Data Baixa              -->
7.  Simples Nacional        -->
** 8.  Data                 --> Caso seja Simples Nacional trazer Data;
9.  Situação Atividade      --> 
10. Item de serviço         -->
11. Alíquota                -->
12. Imunidade/Isenção       -->
13. Natureza Jurídica       -->
14. Junta                   -->

-   📚  Cnaes Secundários:
>   Observação: Apenas atividades secundarias ativas.
1.  Codigo                  --> Codigo do CNAE;
2.  CNAE                    --> Descrição do CNAE;
3.  Data                    --> Data inicio atividade;

-   🤵🏻‍♀️  Sócios
1.  Sócio                   --> Nome do contribuinte;
2.  Data inscrição          -->

```
**Exemplo:** <br>

_Página 1/2_ <br>

![alt text](/Fotos/pag01-mobi.png)

<br>

_Página 2/2_ <br>

![alt text](/Fotos/pag02-mobi.png)

#   

## ⚖️ - Jurídica:<br>
>   **Observação I:** Titulo do relatorio sendo Jurídica do municipio será: "Ficha de cadastro". <br>

>   **Observação II:** Utilizar mesmo modelo da View do contribuinte. 
```
> Campos do relatório:
Titulo                      --> 

-   🌍  Dados Gerais:
1.  Tipo pessoa:            --> (Juridica);
2.  CNPJ:                   --> 
3.  Razão Social:           --> 
4.  Fantasia:               --> 
5.  Inscrição Estadual:     --> 
6.  Representante Legal     -->
7.  Situação                --> 
8.  Data Criação            --> Data de cadastro da empresa no sistema; 



-   🗺️  Endereço:
1.  CEP                     --> 
2.  Estado                  --> 
3.  Município               --> 
4.  Bairro                  -->
5.  T.Logradouro            -->
6.  Logradouro              -->
7.  Nº                      -->
8.  Complemento             -->

-   📞  Contato:
1.  Telefone fixo           --> 
2.  Celular                 -->
3.  E-mail                  -->
4.  Site                    -->

-   Sócios
1.  Sócio                   --> Nome do contribuinte;
2.  Data inscrição          -->

```
## 🙍🏻 - Fisica:<br>
>   **Observação I:** Titulo do relatorio sendo Fisica será: **"Ficha de Cadastro"**. <br>

>   **Observação II:** Utilizar mesmo modelo da View do contribuinte. 
```
> Campos do relatório:
Titulo                      --> 

-   🌍  Dados Gerais:
1.  Tipo pessoa:            --> (Física);
2.  CPF:                    --> 
3.  Nome:                   -->  
4.  Data Criação            --> Data de cadastro da empresa no sistema; 
5.  Situação                --> Caso contribuinte esteja com situação "Óbito" trazer campos abaixos: ⬇️
6.  Data Registro óbito     -->
7.  Reposanvel Legal Falecido->

-   🗺️  Endereço:
1.  CEP                     --> 
2.  Estado                  --> Estado deve ser igual da entidade;
3.  Município               --> Municipio deve ser igual da entidade; 
4.  Bairro                  -->
5.  T.Logradouro            -->
6.  Logradouro              -->
7.  Nº                      -->
8.  Complemento             -->

-   📞  Contato:
1.  Telefone fixo           --> 
2.  Celular                 -->
3.  E-mail                  -->
4.  Site                    -->
```
**Exemplo:** <br>

![alt text](/Fotos/FISICO.png)

#

## 🙍🏻 - Fisica - Profissional Liberal:<br>
>   **Observação I:** Titulo do relatorio sendo Fisica será: **"Ficha de Cadastro <br>  Profissional Liberal"**. <br>

>   **Observação II:** Utilizar mesmo modelo da View do contribuinte. 
```
> Campos do relatório:
Titulo                      --> 

-   🌍  Dados Gerais:
1.  Tipo pessoa:            --> (Física);
2.  CPF:                    --> 
3.  Nome:                   -->  
4.  Data Criação            --> Data de cadastro da empresa no sistema; 
5.  Situação                --> Caso contribuinte esteja com situação "Óbito" trazer campos abaixos: ⬇️
6.  Data Registro óbito     -->
7.  Reposanvel Legal Falecido->
8.  Registro Profissional   -->
9.  Profissão               -->

-   🗺️  Endereço:
1.  CEP                     --> 
2.  Estado                  --> Estado deve ser igual da entidade;
3.  Município               --> Municipio deve ser igual da entidade; 
4.  Bairro                  -->
5.  T.Logradouro            -->
6.  Logradouro              -->
7.  Nº                      -->
8.  Complemento             -->

-   📞  Contato:
1.  Telefone fixo           --> 
2.  Celular                 -->
3.  E-mail                  -->
4.  Site                    -->
```
**Exemplo:** <br>

![alt text](/Fotos/Profssional%20Lib.png)