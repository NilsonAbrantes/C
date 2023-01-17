# Estruturas

## Sintaxe

```
struct <var>{

  int <var>;
  float <var>;
  
}
```

Exemplo:
```
struct horario{
  int horas;
  int minutos;
  int segundos;
 
 }
 ```
 ## Modificando structs
 
 struct horario agora;
 
 agora.horas = 15;
 agora.minustos = 17;
 agora.segundos = 30;
 
 printf("%i:%i:%i", agora.horas, agora.minutos, agora.segundos);
 
 ---->15:17:30
