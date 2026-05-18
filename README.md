# Academia Gado Certo

Plataforma de treinamento interno da Gado Certo, hospedada gratuitamente no GitHub Pages.

---

## Como adicionar a logo

Antes de publicar, salve o arquivo da logo como:

```
academia-gado-certo/assets/logo.png
```

A imagem deve ser PNG com fundo transparente ou branco, altura recomendada de 80px.

---

## Como publicar no GitHub Pages (passo a passo)

### 1. Criar conta no GitHub
Acesse https://github.com e crie uma conta gratuita com o e-mail da Academia GC.

### 2. Criar um repositório novo
- Clique em **"New repository"**
- Nome sugerido: `academia-gado-certo`
- Marque como **Public**
- Clique em **"Create repository"**

### 3. Instalar o Git (se ainda não tiver)
Abra o Terminal e rode:
```bash
git --version
```
Se não estiver instalado, acesse https://git-scm.com/download/mac

### 4. Publicar os arquivos

No Terminal, rode os comandos abaixo **um por um**:

```bash
cd ~/academia-gado-certo
```

```bash
git init
```

```bash
git add .
```

```bash
git commit -m "Academia Gado Certo - lançamento"
```

```bash
git branch -M main
```

```bash
git remote add origin https://github.com/SEU_USUARIO/academia-gado-certo.git
```
> Substitua `SEU_USUARIO` pelo seu nome de usuário do GitHub.

```bash
git push -u origin main
```

### 5. Ativar o GitHub Pages
- No repositório do GitHub, clique em **Settings**
- No menu lateral, clique em **Pages**
- Em "Branch", selecione **main** e clique em **Save**
- Aguarde 1-2 minutos
- O site estará disponível em: `https://SEU_USUARIO.github.io/academia-gado-certo`

---

## Como atualizar o conteúdo no futuro

Sempre que editar um arquivo, rode no Terminal:

```bash
cd ~/academia-gado-certo
git add .
git commit -m "Descrição do que foi alterado"
git push
```

O site atualiza automaticamente em até 1 minuto.

---

## Estrutura dos arquivos

```
academia-gado-certo/
├── index.html          → Home (grade curricular + links de teste)
├── modulo-1.html       → Módulo 1: O DNA da Pecuária (completo)
├── modulo-2.html       → Módulo 2: Em breve
├── modulo-3.html       → Módulo 3: Em breve
├── modulo-4.html       → Módulo 4: Em breve
└── assets/
    ├── style.css       → Identidade visual (cores, fonte Montserrat)
    └── logo.png        → Logo da Gado Certo (adicionar manualmente)
```

---

## Cores oficiais

| Cor | Hex |
|-----|-----|
| Laranja (primária) | `#D25E14` |
| Terra (secundária) | `#584e41` |
| Preto | `#0b0c0e` |
| Branco | `#FFFFFF` |

Fonte: **Montserrat** (Google Fonts, carregada automaticamente)

---

## Link do teste (App Script)

```
https://script.google.com/macros/s/AKfycbxOD1wcf5c_QdRE5Ip-GUxKuM74ZlF1mr5jHVO_xcgZ3W2bMSboMw-E0bTqbYvNx8rB/exec
```
