# Custom Captcha em JavaScript
Este é um exemplo de implementação de um Captcha personalizado em JavaScript. O Captcha é utilizado para verificar se o usuário é um humano ou um robô antes de enviar um formulário. Neste caso, o Captcha consiste em exibir uma sequência de caracteres aleatórios e o usuário precisa digitar corretamente essa sequência para passar na verificação.

## Funcionamento
1. Ao carregar a página, uma sequência de caracteres aleatórios é gerada e exibida como o Captcha na forma de texto.
2. O usuário precisa digitar corretamente a sequência de caracteres exibida no Captcha no campo de entrada.
3. Ao clicar no botão "Check", o sistema verifica se a sequência digitada pelo usuário corresponde à sequência do Captcha.
4. Se a sequência digitada estiver correta, uma mensagem de sucesso é exibida e o Captcha é regenerado após 2 segundos.
5. Se a sequência digitada estiver incorreta, uma mensagem de erro é exibida e o usuário pode tentar novamente.

## Como usar
1. Copie o código HTML para o seu projeto.
2. Certifique-se de ter os arquivos CSS (style.css) e JavaScript (script.js) referenciados corretamente.
3. Personalize o estilo CSS conforme necessário para se adequar ao seu design.
4. Execute o projeto e teste o funcionamento do Captcha.

## Pontos importantes
 O código utiliza caracteres alfanuméricos maiúsculos e minúsculos como possíveis opções para o Captcha. Você pode personalizar essa lista de caracteres no array allCharacters do JavaScript.
 O código utiliza a biblioteca Font Awesome para exibir o ícone de recarregar o Captcha. Certifique-se de incluir o link para a biblioteca no arquivo HTML, ou substitua-o por outro ícone de sua preferência.
 O código não inclui integração com um backend para validar o Captcha. É necessário implementar essa validação no backend antes de prosseguir com o processamento do formulário.
