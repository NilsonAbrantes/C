# FILE
Função para trabalhar com arquivos dentro da linguagem C, onde o mesme será manipulado por um ponteiro.

## fopen
Função para abrir um arquivo.

sintaxe

```

FILE *file;   -->ponteiro
file = fopen("C:\\Users\Nilson Abrantes\\Desktop\\teste.txt", "w");  // a função irá abrir um arquivo chamado teste do tipo txt e escrever algo com a função ("w").
obs:1.Se não existir esse arquivo, se possivel o programa irá cria-la.
2.Se já houver algo escrito o programa irá sobreescrever.

```

## fprintf
Função para escrever em determinado arquivo.
```
fprintf(file,"teste de arquivos.");
```

## fclose
Função para fechar e salvar as alteraçôes.
```
fclose(file);
```


