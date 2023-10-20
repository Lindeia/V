# una-lista-07-csharp
Lista e Pilha são coleções que armazenam elementos. Uma lista é uma coleção de elementos ordenados, onde cada elemento é acessado por seu índice. Ela permite adicionar, remover e acessar elementos em qualquer posição. Uma pilha é uma coleção de elementos onde o último elemento adicionado é o primeiro a ser removido, seguindo o princípio "LIFO" (Last-In, First-Out), sendo possível apenas adicionar e remover elementos no topo da pilha.
# Exemplo de lista em c#
List<int> listaExemplo = new List<int>();

        // Adiciona os elementos à lista
        listaExemplo.Add(5);
        listaExemplo.Add(25);
        listaExemplo.Add(2);

        // Acessa os elementos por índice
        Console.WriteLine(listaExemplo[0]); // Saída: 5

        // Remove os elementos
        listaExemplo.Remove(2);
  
  
# Exemplo de pilha em c#
Stack<string> pilhaExemplo = new Stack<int>();

        // Adiciona os elementos à pilha
        pilhaExemplo.Push(2);
        pilhaExemplo.Push(5);
        pilhaExemplo.Push(1);

        // Remove o elemento do topo
        pilhaExemplo.Pop();

        // Acessa o elemento do topo
        int elementoTopo = pilhaExemplo.Peek(); // Elemento: 2
# Integrantes: Carolina Flavia Furtado, Luiz Felipe Ribeiro da Cruz, Ernane Geraldo Silva, Lindeia Karoline Lima do Carmo, João Ricardo Cirilo e Rayla Bernadino
