# Programadores Instável

Plataforma de contactos de programação (nacionais e internacionais) da Instável.

- **Este repositório (público)** tem só a página. Não tem dados nenhuns.
- **O repositório `programadores-dados` (privado)** tem o ficheiro `dados.json` com todos os contactos. Só tu o vês.
- A página lê e grava nesse ficheiro com uma chave de acesso (token) que fica guardada só no teu navegador.

⚠️ **Nunca coloques o `dados.json` neste repositório público.**

## Instalação (uma vez)

### 1. Repositório privado com os dados
1. GitHub → **New repository** → nome `programadores-dados` → **Private** → **Create repository**.
2. **uploading an existing file** → arrasta o `dados.json` → **Commit changes**.

### 2. Repositório público com a página
1. **New repository** → nome `programadores` → **Public** → **Create repository**.
2. **uploading an existing file** → arrasta `index.html`, `LEIA-ME.md` e `.nojekyll` → **Commit changes**.
3. **Settings** → **Pages** → *Source*: **Deploy from a branch** → *Branch*: `main` e `/(root)` → **Save**.
4. Ao fim de 1–2 minutos o endereço aparece no topo dessa página: `https://O-TEU-UTILIZADOR.github.io/programadores/`.

### 3. Criar a chave de acesso (token)
1. Abre https://github.com/settings/personal-access-tokens/new
2. **Token name**: `Plataforma programadores` · **Expiration**: escolhe a mais longa que aparecer (até 1 ano).
3. **Repository access**: **Only select repositories** → escolhe **programadores-dados**.
4. **Permissions** → **Repository permissions** → **Contents** → **Read and write**.
5. **Generate token** e copia a chave (começa por `github_pat_`). Só aparece uma vez.

### 4. Entrar
1. Abre o endereço do passo 2.
2. Preenche o teu utilizador do GitHub, o repositório (`programadores-dados`) e cola a chave → **Ligar**.
3. Devem aparecer os 418 espaços.

## No dia a dia

- As alterações gravam-se sozinhas no GitHub (ao fim de 2–3 segundos). No topo aparece "Guardado no GitHub".
- **Descarregar Excel**: gera um .xlsx com os espaços que estão filtrados no momento (folhas Espaços, Contactos e Histórico).
- **Sair**: apaga a chave deste navegador.
- Num computador ou telemóvel novo, basta abrir o endereço e ligar com a chave outra vez.
- Cada alteração fica guardada como uma versão em `programadores-dados` → **Commits**. Dá para ver ou recuperar qualquer versão antiga.

## Quando a chave expirar
A página avisa que a chave já não é válida. Cria uma nova (passo 3), carrega em **Sair** e liga-te com a chave nova.
