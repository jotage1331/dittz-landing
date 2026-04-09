

## Passo 4: Inicializar e Subir o Site

No terminal, entre na **nova pasta** `dittz-landing` e execute:

```bash
# 1. Iniciar o Git nesta pasta
git init

# 2. Adicionar os arquivos
git add .

# 3. Primeiro commit
git commit -m "first commit: landing page finalizada"

# 4. Conectar ao novo repositório (Substitua SEU_USUARIO pelo seu nome no GitHub)
git remote add origin https://github.com/SEU_USUARIO/dittz-landing.git

# 5. Criar a branch main e subir
git branch -M main
git push -u origin main
```

---

## Passo 5: Ativar o Site (GitHub Pages)

No novo repositório `dittz-landing` no GitHub:

1.  Vá em **Settings** > **Pages**.
2.  Em **Build and deployment** > **Branch**:
    - Selecione **main**.
    - Onde diz `/ (root)`, **mantenha `/ (root)`** (já que o `index.html` agora está na raiz do novo repo).
3.  Clique em **Save**.

---

## Passo 6: Excluir a pasta antiga (Opcional)

Agora que tudo está no novo repositório, você pode apagar com segurança a pasta `docs/` que está dentro do seu projeto original `projeto_dittz` para manter o projeto limpo.

> [!TIP]
> **Resultado Final:**
> - Seu repositório `projeto_dittz` é **Privado** e contém o ERP.
> - Seu repositório `dittz-landing` é **Público** e contém apenas o site de vendas.
