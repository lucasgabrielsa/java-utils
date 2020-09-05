# Java Utils 

## Multíplas estruturas em um arquivo

Em java, é possível definir mais de uma classe/interface em um mesmo
arquivo java, embora devamos seguir algumas regras:

- Podem ser definidos em qualquer ordem
- Se existir alguma classe/interface pública, o nome do arquivo deve ser o mesmo dessa classe/interface;
- Só pode existir uma classe/interface pública por arquivo;
- Se não houver nenhuma classe/interface pública, o arquivo pode ter qualquer nome.

Logo, são válidos:

```java
1 // file1.java
2 interface First {}
3
4 class Second {}

1 // Third.java
2 public class Third {}
3
4 interface Fourth {}
```
