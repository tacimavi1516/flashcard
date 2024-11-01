:root {
    --text-color: #DBE4EF;
    --card-front-color: #144480;
    --card-back-color: #00F4BF;
}
.cartao__conteudo h3 {
    color: var(--text-color);
    border: 1px solid var(--text-color);
    text-align: left;
    padding: 0.5rem;
    position: absolute;
    margin: 0.6rem;
    border-radius: 0.6rem;
    font-size: 1vw;
}
.cartao__conteudo {
    text-align: center;
    height: 100%;
    background-color: var(--card-front-color);
}
.cartao__conteudo__pergunta p{
    color: var(--text-color);
    font-weight: 500;
}
.cartao__conteudo__resposta p{
    color: var(--card-back-color);
    font-weight: 700;
}
