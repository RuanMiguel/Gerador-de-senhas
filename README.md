🔑 Gerador de Senhas Simples
Um script Python simples para gerar senhas aleatórias e seguras com um comprimento definido pelo usuário, utilizando letras, números e caracteres especiais.

✨ Funcionalidades
Geração Aleatória: Cria senhas utilizando uma combinação aleatória de letras maiúsculas, minúsculas, dígitos e pontuações/símbolos.

Comprimento Definível: Permite ao usuário especificar o tamanho da senha desejada no momento da execução.

🚀 Como Usar
Pré-requisitos
Você precisa ter o Python 3 instalado em sua máquina.

Execução
Salve o código fornecido em um arquivo, por exemplo, gerador_senha.py.

Abra o terminal ou prompt de comando.

Navegue até o diretório onde você salvou o arquivo.

Execute o script com o comando:

python gerador_senha.py

O script pedirá que você insira o tamanho de senha desejado.

A senha gerada será exibida no console.

📚 Observações sobre o Código
Módulos Utilizados:

random: Usado para a função random.sample(), que garante que cada caractere na senha gerada seja único, aumentando a aleatoriedade e segurança (até o limite do tamanho ser menor ou igual ao número total de caracteres disponíveis).

string: Usado para fornecer conjuntos predefinidos de caracteres, como string.ascii_letters, string.digits e string.punctuation.

Segurança: A função random.sample() é uma boa prática para geração de senhas, pois seleciona caracteres sem repetição. No entanto, lembre-se de que a segurança da senha depende muito do comprimento (tamanho) escolhido. Recomenda-se um tamanho de, no mínimo, 12 a 16 caracteres.
