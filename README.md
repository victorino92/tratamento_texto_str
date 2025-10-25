# Projeto: Limpador de Listas de Texto (Python)
Este repositório contém uma classe Python simples, LimpaListaTextos, desenhada para processar e "limpar" listas de strings. Ela permite aplicar uma série de transformações comuns de forma encadeada (method chaining).

# Objetivo:
Em uma lista de frases ou textos e normalizá-los através da aplicação de vários métodos de limpeza, como converter para minúsculas, remover espaços em branco e remover dígitos numéricos.

# Funcionalidades:
Métodos classe LimpaListaTextos:

    converte_minusculo(): Converte todas as strings na lista para letras minúsculas.

    remove_espacos(): Remove todos os espaços em branco de cada string (não apenas no início ou fim).

    remove_numeros(): Remove todos os caracteres numéricos (dígitos de 0 a 9) de cada string.

Todos os métodos retornam self (a própria instância da classe), permitindo o encadeamento de métodos (Method Chaining).

Usando:
Para usar, basta instanciá-la passando a sua lista de textos e, em seguida, chamar os métodos de limpeza que desejar.
