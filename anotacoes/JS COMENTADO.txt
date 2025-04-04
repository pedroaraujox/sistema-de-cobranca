// Seleciona o elemento com a classe 'wrapper' (geralmente um container principal)
const wrapper = document.querySelector('.wrapper');

// Seleciona o link de registro dentro do formulário (elemento com a classe 'register-link')
const registerLink = document.querySelector('.register-link');

// Seleciona o link de login dentro do formulário (elemento com a classe 'login-link')
const loginLink = document.querySelector('.login-link');

// Adiciona um evento de clique no link de registro
registerLink.onclick = () => {

    // Adiciona a classe 'active' ao wrapper, geralmente para ativar um efeito de transição
    // (ex: alternar entre formulário de login e cadastro)

    wrapper.classList.add('active');
}



// Adiciona um evento de clique no link de login
loginLink.onclick = () => {

    // Remove a classe 'active' do wrapper, voltando ao estado inicial
    // (ex: retornar ao formulário de login)
    
    wrapper.classList.remove('active');
}