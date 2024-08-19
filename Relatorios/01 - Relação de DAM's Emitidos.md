# ✅Relação de DAM's Emitidos:
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

<br>

<https://encurtador.com.br/vh5af> **| Voltar |** - **| Proxima página |** <https://abrir.link/eIzrg>  
#

## Observação: 
    Apenas Campo "Período" ou "Exercicio" sera campo obrigatorio, outros campos podem ser "NULL";
>   **Particularidades Filtros:** <br>
    -   Caso preenchendo "Período não podera colocar "Exercicio".  
    -   Caso preenchendo "exercicio" não podera colocar "Período".
    -   Caso não preechendo "Tributo", marcando "Divida Ativa", trazer todos os tributos que estão em "D.A.". 
    -   Caso não marcando "Tributo", marcando "Parcela", trazer todos os tributos que estão parcelados e suas. cotas. 
#### Filtros:
1.  **Período:** _(Not null - Campo obrigatorio)_ 
    >**Observação:** (Data - *type: Date* -Data da emissão do DAM'S) <br> 
    ![alt text](/Fotos/image.png)

2.  **Tributo:** 
    >**Observação:** <br>   *Multiplo* _select_ -- classificação de receita (tipo do tributo *IPTU, TFF, ...)*<br>
    ![alt text](/Fotos/image-1.png)<br>
    ![alt text](/Fotos/image-2.png)


3.  **Exercicio:**
    > **Observação:** Seleciona *Ano (2024, 2023, 2022, ...)* <br>
    Filtro da competencia<br>
    ![alt text](/Fotos/image-3.png)<br>
    ![alt text](/Fotos/image-4.png)

4.  **Divida Ativa:** 
    > **Observação:** _Select_ Vem marcado com "01 - Todos Tributos", podendo alterar. <br>
        01 - "Todos Tributos" <br> 
        02 - "Tributaria e Não tributaria"<br> 
        03 - "Tributaria" 
        04 - "Não Tributaria" <br> 
        05 - "Sem D.A." <br> 
5.  **Parcela:** 
    >**Observação:** *Checkbox* Marcado,<br>  *Texto ao lado:* _"Exibir Parcelas?"_<br>

6.  **Inscrição:**
    >**Observação:** *(Do lançamento do DAM)*, Campo digitavel, possibilidade de colocar apenas uma inscrição.
    <br> 
    Exemplo abaixo sistema antigo:<br> 

    ![alt text](/Fotos/inscrição.png)
    
7.  **Atividade Principal:** 
    >**Observação:** _Multipla opções_, podendo selecionar varios CNAES_PRINCIPAL. <br>

8.  **Situação:** 
    >**Observação:** _Multiplo select_, Filtrando as situação dos DAM's <br>
    *(Sem filtro[Todos], Pagos, aberto e vencidos)*
        1. Podendo Filtrar: Pagos + Aberto ou Abertos + vencidos

9.  **Faixa de valor:**
    > **Observação:** Filtro de valor_cota, Filtrando do menor valor até maior valor.<br>
    ![alt text](/Fotos/faixa_valor.png)

10. **Ordenar:** 
> **Observação:** Select para ordenar por (numero do DAM, contribuinte ou vencimento do DAM'S) apenas uma escolha de organização, 'orde by'.   


 ####   Layout PDF:
**Campos:** 
 ```
1.  Contribuinte - Nome do Contribuinte e CPF/CNPJ;
2.  N. Documento - Numero do DAM;
3.  Tributo      - Sigla do Tributo  (Trazendo D.A. caso seja uma D.A ou Parc de parcelamento );
4.  Emissão      - Data de emissão DAM;
5.  Parcela      - Caso tenha parcela, trazer quantidade, *exemplo:*"1/10" ou Unica.
6.  Valor        - Valor da cota original 
7.  Multa, juros e correção  - Campos valor de Juros, multa e correção da Cota;
8.  Valor Pao    - Valor pago da cota; 
9.  Venc.        - Vencimento original;
9.  Inscrição    - Inscrição armazenado no "lançamento" da cota;  
```
![alt text](/Fotos/emitidos.png)
<br>
<br>

#
<br>

<https://encurtador.com.br/vh5af> **| Voltar |** - **| Proxima página |** <https://abrir.link/eIzrg>  