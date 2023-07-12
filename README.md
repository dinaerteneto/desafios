# Desafio de Desenvolvimento Web

Olá! Este é um desafio de desenvolvimento web para você praticar suas habilidades em PHP, HTML e CSS.

## Descrição do Desafio

Seu objetivo é criar uma página da web que exiba informações de usuários em uma tabela. A página deve conter os seguintes requisitos:

1. Use PHP para obter os dados dos usuários de uma fonte de dados (por exemplo, um array ou um banco de dados fictício).
2. Exiba os dados dos usuários em uma tabela HTML.
3. A tabela deve ter colunas para Nome, E-mail e Função.
4. Estilize a tabela usando CSS para torná-la visualmente atraente.

## Dicas

- Comece criando um arquivo HTML básico e adicione os elementos necessários para exibir a tabela.
- Em seguida, use PHP para obter os dados dos usuários (você pode usar um array com dados fictícios para facilitar o desenvolvimento).
- Use loops em PHP para percorrer os dados dos usuários e gerar as linhas da tabela.
- Por fim, aplique estilos CSS à tabela para melhorar a aparência visual.

Divirta-se e boa sorte!

## Dados dos Usuários

Aqui estão alguns dados fictícios de usuários que você pode usar para preencher a tabela:

```php
<?php
$usuarios = [
    [
        'nome' => 'João Silva',
        'email' => 'joao.silva@example.com',
        'funcao' => 'Desenvolvedor'
    ],
    [
        'nome' => 'Maria Santos',
        'email' => 'maria.santos@example.com',
        'funcao' => 'Designer'
    ],
    [
        'nome' => 'Pedro Almeida',
        'email' => 'pedro.almeida@example.com',
        'funcao' => 'Analista de Dados'
    ]
  // Adicione mais usuários, totalizando 15.
];

// exemplo de como percorrer o array de usuários
foreach ($usuarios as $usuario) {
    echo 'Nome: ' . $usuario['nome'] . '<br>';
    echo 'Email: ' . $usuario['email'] . '<br>';
    echo 'Função: ' . $usuario['funcao'] . '<br><br>';
}
?>
```

## Entrega

Após concluir o desafio, você deve subir o código em seu github.

## Fazendo meus olhos brilharem

Faça vários commits, não termine o código por completo, para só então fazer o primeiro commit.
A cada vez que observar que tem uma entrega válida, faça um commit.
O push pode ser apenas 1.
