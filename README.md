# Projeto Virada ServiceNow Bootcamp

![GitHub repo size](https://img.shields.io/github/repo-size/vitoriasa/Toy-Store-4MATT-Bootcamp-SN?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/vitoriasa/Toy-Store-4MATT-Bootcamp-SN?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/vitoriasa/Toy-Store-4MATT-Bootcamp-SN?style=for-the-badge)

Projeto final do **Virada ServiceNow Bootcamp** realizado pela [**4MATT**](www.linkedin.com/company/4matttecnologia/).

<img width="700" alt="ToySP" src="https://github.com/user-attachments/assets/10b17d11-ab7b-4123-b6d7-e14928d34737" />

>
> Imagem da página inicial do portal Toy Store.

## 💻 ServiceNow - Instalação da Aplicação 

Para instalar a aplicação deste repositório em sua intância ServiceNow, siga os seguintes passos:

1. Crie sua credencial de acesso seguindo os passos `Gerando um Token de Acesso e Configurando a Conexão` do vídeo [Conectando Instancia ServiceNow® com GitHub](https://www.youtube.com/watch?v=4rl_apblEZo).
1. Abra o ServiceNow Studio.
1. Acesse `Create > Import APP > Import app from source control`.
1. Preencha o campo **URL** com o link do repositório, preencha campo **Credential** com o registro gerado no primeiro passo e siga com a importação. </br> OBS.: No campo **Branch** é recomendado que siga com a que foi gerada.

## :sparkles: Projeto

A criação de todas as funcionalidades foi realizada para a loja de brinquedos fictícia: "**TOY STORE**" :gift:.

### :small_blue_diamond: Aplicação Toy Store
<img align="center" width="700" alt="Aplicacao" src="https://github.com/user-attachments/assets/a5a70760-d53b-4442-99a0-3f2e322d6c43" />

>
> Aplicação Toy Store no ServiceNow Studio.

A Aplicação foi criada dentro do escopo global com as seguintes tabelas: 

| Tabelas | Forma de Criação |
|--- |--- |
| Categoria | From Scratch |
| Produto | Import Table | 
| Pedido | Estendida da Task |
| Ouvidoria | Estendida da Task |

Também foram criadas as roles `toy_admin` e `toy_user`.

### :small_blue_diamond: Application Menu e módulos

<img align="center" width="388" height="572" alt="Menu" src="https://github.com/user-attachments/assets/8a0174a7-7eb8-4ce9-acca-d443153bf740" />

>
> Application Menu Toy Store.

### :small_blue_diamond: Flow

<img align="center" width="688" height="857" alt="Flow" src="https://github.com/user-attachments/assets/8fcd712d-2937-4fd7-90dd-4bfc6cda573f" />

>
> Flow de Pedidos.

### :small_blue_diamond: Workspace e Dasboard

<img align="center" width="700" alt="WorkspaceEDashboard" src="https://github.com/user-attachments/assets/2a718a4b-120b-48a5-8ed7-d1fccb2ef1f6" />

>
> Workspace e Dasboard.

Indicadores: 

| Indicadores | Tipo |
|--- |--- |
| Produtos | Horizontal Bar |
| Todos os pedidos | Single Score | 
| Pedidos completos | Single Score |
| Pedidos sem atribuição | Single Score |
| Pedidos por marca | Donut |
| Reclamações | List |

### :small_blue_diamond: Portal Toy
<img width="700" alt="ToySPIndex" src="https://github.com/user-attachments/assets/b0eb53bb-face-438f-a701-cce6d832e3f1" />

>
> Página inicial do Portal Toy.

<br/>

<img width="700" alt="ToySPProdutos" src="https://github.com/user-attachments/assets/4dda9dd1-a883-4bc9-a11e-6e1887ab59fc" />

>
> Página de produtos do Portal Toy.

<br/>

<img width="700" alt="ToySPInfoProdutos" src="https://github.com/user-attachments/assets/6e751ff0-90d0-4bf0-a3cb-2d896faa3c13" />

>
> Página de detalhes dos produtos do Portal Toy.

<br/>

#### Itens de Catálogo

<img width="700" alt="Catalogo" src="https://github.com/user-attachments/assets/2d320c88-9869-4779-81f3-2ecd929bd827" />

>
> Itens de Catálogo.

##### Nova Categoria
<img width="700" alt="CatalogoNovaCategoria" src="https://github.com/user-attachments/assets/94b0d97e-ea1f-48d0-90cc-c1e737d3500d" />


##### Solicitar Brinquedo

Record Producer destinado à tabela Pedido.

<img width="700" alt="CatalogoSolicitarBrinquedo" src="https://github.com/user-attachments/assets/cf652fb6-a88a-4792-8019-e7a0dc556b59" />

<br/>

##### Integração API ViaCEP

Integração realizada para quando preencher o campo CEP, tazer as informações do endereço.

<img width="700" alt="IntegracaoCEP" src="https://github.com/user-attachments/assets/8d4f26eb-5a04-4a56-8952-318b0e6f2688" />

>
> Integração ViaCEP.

### :small_blue_diamond: Grupos e Usuários

<img width="700" alt="Entregas" src="https://github.com/user-attachments/assets/ab2be5c5-7e7f-4121-9d01-c0a054c1bdb2" />

>
> Grupo Entregas.

<br/>

<img width="700" alt="Atendimento" src="https://github.com/user-attachments/assets/1084c5fd-b1fb-4920-9559-a53f00d4eb3a" />

>
> Grupo Atendimento.

<br/>

<img width="700" alt="Gestao" src="https://github.com/user-attachments/assets/26c76629-ed0d-4b5c-9e14-1e53126d328d" />

>
> Grupo Gestão.

<br/>

## 🤝 Colaboradores

Projeto criado por:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/VitoriaSA" title="defina o título do link">
        <img src="https://github.com/user-attachments/assets/63594952-5647-49b9-a873-ae1a612676ce" width="100px;" alt="FotoVitoriaSimoes"/><br>
        <sub>
          <b>Vitória Simões</b>
        </sub>
      </a>
    </td>
  </tr>
</table>






