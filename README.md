<h1 align="center">Padrões de commits</h1>

## Tipo de commits e descrição

O commit semântico possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit no seu código.

- `feat`- Commits do tipo feat indicam que seu trecho de código está incluindo uma nova funcionalidade.

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está
solucionando um problema.

- `style` - Commits do tipo style indicam que houveram alterações referentes a formatações de código que não afetam o funcionamento.

- `refactor` - Commits do tipo refactor referem-se a alterações que melhoram a estrutura do código sem mudar sua funcionalidade.

- `docs` - Commits do tipo docs indicam que houveram mudanças na documentação.

- `test` - Commits do tipo test são utilizados quando são realizadas alterações em testes, seja criando, alterando ou excluindo testes unitários e de integração.

- `chore` - Commits do tipo chore indicam atualizações de build, configurações de administrador e pacotes.

- `build` - Commits do tipo build são utilizados quando são realizadas modificações em arquivos de build e dependências.

- `ci` - Commits do tipo ci indicam mudanças relacionadas a integração contínua.

- `perf` - Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a performance.

<br/>
<h2 align="center">Exemplos</h2>

<table>
  <thead>
    <tr>
      <th>Comando Git</th>
      <th>Resultado no GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m "initial commit"</code>
      </td>
      <td>initial commit</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "feat: add new feature"</code>
      </td>
      <td>feat: add new feature</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "fix: fix bug"</code>
      </td>
      <td>fix: fix bug</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "style: tailwind css code formatting"</code>
      </td>
      <td>style: tailwind css code formatting</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "refactor: change default functions to arrow functions"</code>
      </td>
      <td>refactor: change default functions to arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "docs: update README.md"</code>
      </td>
      <td>docs: update README.md</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "test: add unit tests to users"</code>
      </td>
      <td>test: add unit tests to users</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "chore: add a package to .gitignore"</code>
      </td>
      <td>chore: add a package to .gitignore</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "build: change in dependencies"</code>
      </td>
      <td>build: change in dependencies</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "ci: change in Dockerfile"</code>
      </td>
      <td>ci: change in Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "perf: Improvement in response time"</code>
      </td>
      <td>perf: Improvement in response time</td>
    </tr>
  </tbody>
</table>
