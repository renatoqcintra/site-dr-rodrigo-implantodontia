# Site institucional para clínica de implantodontia

Site institucional de uma página (one-page) para um consultório odontológico especializado em implantes dentários, feito com **HTML, CSS e JavaScript puro**, sem frameworks e sem etapa de build. O objetivo é passar segurança ao paciente, apresentar os tratamentos, mostrar o consultório e levar o visitante ao contato por WhatsApp.

🔗 **Site no ar:** [drrodrigocintra.com.br](https://drrodrigocintra.com.br/)

## Seções do site

- **Apresentação:** chamada principal sobre implantes com segurança, tecnologia e precisão.
- **Especialidades:** cartões com os tratamentos oferecidos (implante dentário, prótese sobre implante, carga imediata, planejamento digital e reabilitação oral).
- **Sobre o profissional:** apresentação e formação.
- **Laserterapia:** seção sobre o tratamento com laser.
- **Consultório:** galeria de fotos do espaço.
- **Localização:** mapa do Google Maps incorporado na página, com link para a rota.
- **Contato:** chamada final para agendamento por WhatsApp, e links para as redes sociais no rodapé.

## Destaques técnicos

- **Layout responsivo**, que se adapta a celular, tablet e computador.
- **Menu mobile** com ícone de hambúrguer que alterna entre abrir e fechar, e fecha ao clicar em um link.
- **Cabeçalho com sombra** ao rolar a página.
- **Animações de entrada (reveal)** ao rolar, feitas com `IntersectionObserver`, executadas uma única vez por elemento.
- **Google Maps incorporado** com `iframe`.
- **Botões de WhatsApp** em pontos estratégicos da página.
- **Google Tag Manager** instalado para medição de acessos.

## Tecnologias

- HTML5 e CSS3
- JavaScript (ES6+), sem bibliotecas
- Fonte Poppins (Google Fonts)
- Ícones Font Awesome

## Estrutura do projeto

```
├── index.html
├── scripts.js        # Menu mobile, efeito do cabeçalho e animações de rolagem
├── style.css         # Estilos e responsividade
└── img/              # Imagens do site
```

## Como rodar localmente

Não precisa instalar nada. Abra o `index.html` direto no navegador, ou rode um servidor local na pasta do projeto:

```bash
python -m http.server 8000
```

e acesse `http://localhost:8000`.

## Autor

Desenvolvido por **Renato Queiroz Cintra**, estudante de Técnico em Informática.

- GitHub: [@renatoqcintra](https://github.com/renatoqcintra)
