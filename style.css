document.addEventListener('DOMContentLoaded', function () {
    const botaoDeAcessibilidade = document.getElementById('botao-acessibilidade');
    const opcoesDeAcessibilidade = document.getElementById('opcoes-acessibilidade');

    botaoDeAcessibilidade.addEventListener('click', function () {
        botaoDeAcessibilidade.classList.toggle('rotacao-botao');
        opcoesDeAcessibilidade.classList.toggle('apresenta-lista');

        const botaoSelecionado = botaoDeAcessibilidade.getAttribute('aria-expanded') === 'true';
        botaoDeAcessibilidade.setAttribute('aria-expanded', !botaoSelecionado);
    });

    const aumentaFonteBotao = document.getElementById('aumentar-fonte');
    const diminuiFonteBotao = document.getElementById('diminuir-fonte');
    const alternaContraste = document.getElementById('alterna-contraste');
    const corpo = document.body;

    let tamanhoAtualFonte = 1;

    aumentaFonteBotao.addEventListener('click', function () {
        tamanhoAtualFonte += 0.1;
        corpo.style.fontSize = `${tamanhoAtualFonte}rem`;
    });

    diminuiFonteBotao.addEventListener('click', function () {
        if (tamanhoAtualFonte > 0.5) {
            tamanhoAtualFonte -= 0.1;
            corpo.style.fontSize = `${tamanhoAtualFonte}rem`;
        }
    });

    alternaContraste.addEventListener('click', function () {
        corpo.classList.toggle('alto-contraste');
    });

});

const sr = ScrollReveal({
    origin: 'top',
    distance: '50px',
    duration: 1000,
    easing: 'ease-in-out',
    reset: true
});

sr.reveal('#inicio', { delay: 500 });
sr.reveal('#tropicalia', { delay: 500 });
sr.reveal('#galeria', { delay: 500 });
sr.reveal('#contato', { delay: 500 });
