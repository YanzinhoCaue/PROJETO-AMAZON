# 🛍️ Página de Livros da Amazon com Tailwind CSS

Este projeto é um clone front-end da página de livros da Amazon.com.br, desenvolvido com o objetivo de praticar e demonstrar habilidades avançadas em **HTML5 semântico** e **Tailwind CSS**. O foco foi recriar a complexa interface da Amazon, garantindo uma experiência visualmente fiel e totalmente responsiva.

---

### **🎬 Demonstração**

![amazom](https://github.com/YanzinhoCaue/PROJETO-AMAZON/assets/127339610/d71f68bd-bb7f-4c56-9940-c1676230f38f)

---

### **✨ Features em Destaque**

**🎨 Desenvolvimento Utility-First com Tailwind CSS**
* A interface foi construída inteiramente com o framework **Tailwind CSS**, utilizando uma abordagem *utility-first*. Isso permitiu a criação de um design complexo e customizado diretamente no HTML, sem a necessidade de escrever CSS tradicional.
* O projeto utiliza a configuração padrão do Tailwind e também classes customizadas com a diretiva `@apply` para componentes reutilizáveis.

**📱 Interface Totalmente Responsiva**
* O layout foi pensado para ser flexível e se adaptar a múltiplos tamanhos de tela, desde dispositivos móveis pequenos até monitores grandes, utilizando as variantes responsivas do Tailwind (`sm`, `md`, etc.).
* Componentes como o header e as barras de navegação se transformam para garantir a usabilidade em qualquer dispositivo.

**🔎 Recriação Fiel de Componentes Complexos**
* O projeto recria com alta fidelidade os componentes da página original da Amazon, incluindo:
    * O header com três níveis de navegação.
    * A barra de busca com filtro de categorias.
    * O grid de produtos e a barra lateral de filtros.
    * O rodapé detalhado.

---

### **🛠️ Tecnologias Utilizadas**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white)

---

### **▶️ Como Executar o Projeto**

Existem duas maneiras de visualizar o projeto:

**1. Visualização Direta (Sem Build)**
Você pode simplesmente baixar o repositório e abrir o arquivo `index.html` diretamente no seu navegador.

**2. Ambiente de Desenvolvimento (Com Build do Tailwind)**
Para modificar os estilos e recompilar o CSS, siga os passos:

**1️⃣ Clone o repositório**
```bash
git clone [https://github.com/YanzinhoCaue/projeto-amazon.git](https://github.com/YanzinhoCaue/projeto-amazon.git)
````

**2️⃣ Instale as dependências**

```bash
cd projeto-amazon
npm install
```

**3️⃣ Execute o script de build do Tailwind**
Para compilar o arquivo `css/style.css` e gerar o `css/build.css`, execute o comando (pode ser necessário adicioná-lo ao `package.json`):

```bash
npx tailwindcss -i ./css/style.css -o ./css/build.css --watch
```

-----

### **🧠 Principais Aprendizados**

  * Domínio do paradigma **Utility-First** e seus benefícios em produtividade e manutenibilidade.
  * Aplicação prática de conceitos de **Design Responsivo** em um layout complexo.
  * Estruturação de um projeto HTML/CSS de forma limpa e semântica.
  * Configuração e extensão do **Tailwind CSS** para atender a um design específico.

-----

### **💬 Contato**

**Yan Cauê**

**LinkedIn:** [linkedin.com/in/yancue](https://linkedin.com/in/yancue)

**GitHub:** [github.com/YanzinhoCaue](https://github.com/YanzinhoCaue)
