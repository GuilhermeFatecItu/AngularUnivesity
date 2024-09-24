# Projeto Angular! 🌟

> 🎓 Projeto criado em sala na faculdade Fatec Itu/SP

> 👨‍🏫 Aula ministrada por: Glauco Toledo

## 📝 Anotações:
    node -v
    ng version
    visualizar se na raiz no gitBash está em master/main - (se sim, deletar o .git)
    git config --global user.name "yLottus" --replace-all
    git config --global user.email "gvebooksofc@gmail.com" --replace-all
    git pull para trazer a versão mais recente
    instalar o Json Server - npm install -g json-server@0.17.4
    iniciar o JsonServer: json-server --watch db.json --port 3000
    chamadas do Angular para o back-end usamos o Observable ( não bloqueante - Asyncrono )

    No vsCode:
      Códigos Angular:
      - ng new (NOME) --no-standalone
      - ng s -o
      - ng g c (NOME) --skip-test
      - ng g s (NOME DO SERVER)

      No código:
      - Em app criado o product.ts para usar o interface em product/product.component.ts dentro do export class:
      products: Product[] = [];

    BOOTSTRAP:
    ng add @ng-bootstrap/ng-bootstrap

#

#### 🎉 Créditos dos emojis:
> <a href="https://emojipedia.org" target="_blank">https://emojipedia.org</a>






## De hoje:

- ng g c music-form (Terminal)
- no html principal a renderização da tabela - no app.component.html
- colocar um h1 escrito: Cadastro de Produtos
- colocar o: <router-outlet></router-outlet>
- vai em ( app-routing.module.ts ) e em const routes: Routes = [] adicionar dois objetos
- ficando assim: 
    {path: 'products', component: ProductsTableComponent},
    {path: 'product/:id', component: ProductFormComponent}
- no musics-table.component colocar a tag <a> no nome, ficando:
    <a [routerLink]="['/music', music.id]"{{music.name}} a>
- em product-form > no HTML: Criou uma section com h1 (cadastro de música) e adicionar o form dentro form com label e input para cada coluna.

Perfil principal: GuilhermeFranciscoPereira
