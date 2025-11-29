# 🤝 Contribuindo para o Retro Badges

Obrigado pelo interesse em contribuir! Este projeto cresce graças à comunidade.

---

## 🪄 Comece por aqui (Download do Template)

Para facilitar sua vida, disponibilizamos o arquivo editável oficial do **Affinity**. Ele já está configurado com as fontes, sombras e tamanhos corretos.

📂 **[Baixar Template Oficial (.af)](/docs/template.af)**

**Como usar:**
1. Abra o arquivo no Affinity.
2. Copie uma badge existente.
3. Altere apenas a **Cor**, **Texto** e **Ícone**.
4. Ajuste a largura conforme necessário, mas **MANTENHA A ALTURA FIXA DE 28px**.

---

## 🛠️ Guia de Design (Regras Técnicas)

Se você não usa o Affinity, siga esta receita para criar a badge do zero:

### 1. Dimensões (A Regra de Ouro 📏)
* **Altura:** A badge deve ter **exatamente 28 pixels de altura**. Isso é obrigatório.
* **Largura:** Variável. Você deve aumentar ou diminuir a largura para caber o texto, mas nunca mexer na altura.

### 2. O Ícone
* **Fonte:** Acesse o site [Simple Icons](https://simpleicons.org/).
* **Download:** Baixe o ícone da tecnologia desejada no formato **SVG**.
* **Tamanho:** Redimensione o ícone para **15x15 pixels**.
* **Cor:** Aplique no FX uma **Sobreposição de Cor** (Color Overlay) definida como **BRANCA** (#FFFFFF).
* **Sombra:** Adicione no FX uma **Sombra Externa** na cor preta, com raio de **0.3px**.

### 3. O Texto (Tipografia)
* **Fonte Oficial:** Utilize a fonte **VT323**.
* **Tamanho:** **19 pt**.
* **Cor:** Sempre **BRANCO** (#FFFFFF).
* **Alinhamento:** Centralizado verticalmente com o ícone.

### 4. As Cores
* **Cor Principal (Face):** Use a cor **HEX** oficial listada no [SimpleIcons.](https://simpleicons.org/).
* **Borda e Sombra:** A borda (contorno) e a sombra inferior (relevo) devem ser da mesma cor: um **tom mais escuro** da cor principal.
* **Fundo:** Transparente.

### 5. Exportação
* **Resolução:** Exporte o arquivo final em **4x PNG** (escala 400%).
    * *Exemplo: Se desenhou com 28px de altura, a imagem final terá 112px de altura.*
    * *Isso garante a nitidez máxima em telas Retina/High-DPI.*

---

## 📜 Convenção de Nomes

Para manter a organização, o nome do arquivo deve seguir este padrão estrito:

1.  **Extensão:** `.png`
2.  **Formato:** `NOME-DA-TECH-button.png`
    * Tudo em **MAIÚSCULAS**.
    * Use **hífens** `-` no lugar de espaços.

**Exemplos Corretos:**
* ✅ `BLENDER-button.png`
* ✅ `REACT-NATIVE-button.png`
* ✅ `C-SHARP-button.png`

---

## 📫 Como Enviar

1.  Faça um **Fork** deste repositório.
2.  Adicione sua imagem `.png` na pasta **`assets`**.
3.  Faça o Commit (`git commit -m "Adiciona nova badge: NOME"`).
4.  Abra um **Pull Request**.

---

<div align="center">
    <b>Divirta-se!</b>
</div>
