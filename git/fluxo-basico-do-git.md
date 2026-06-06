# O fluxo básico do Git: Add, Commit e Push

**Contexto:** Para manter meu repositório de estudos e projetos de Ciência de Dados atualizado, precisei entender o fluxo correto para enviar arquivos locais para o GitHub.

**Solução:** O envio de arquivos pelo terminal não acontece de uma vez só. Ele segue uma sequência de três etapas: **preparar**, **empacotar** e **enviar**.


#### 1. Prepara as alterações (o ponto final indica "adicione tudo que mudou")
<mark>git add .</mark>

#### 2. Salva o estado atual localmente com uma mensagem descritiva
<mark>git commit -m "mensagem da atualizacao"</mark>

#### 3. Envia o histórico salvo para a branch principal no GitHub
<mark>git push origin main</mark>