# Binary-Search-Tree
Dieses Projekt ist eine Implementierung eines Binary Search Tree in Java.
Der Baum unterstützt das Einfügen, Suchen und Traversieren von Werten.



Funktionen:
- Werte einfügen (insert)
- Prüfen, ob ein Wert existiert (contains)
  
  Traversierungen:
  - Preorder
  - Inorder
  - Postorder
    
- printTree zur Konsolenausgabe
- Zugriff auf linke und rechte Teilbäume




Ein Binary Search Tree folgt dieser Regel:

Linke Seite: kleinere Werte
Rechte Seite: größere Werte

Dadurch können Werte effizient gespeichert und gesucht werden.


Beispiel:

        
        BinaryTree tree = new BinaryTree();
        
        // Baum wird sauber als BST aufgebaut
        tree.insert(8);
        tree.insert(4);
        tree.insert(12);
        tree.insert(2);
        tree.insert(6);
        tree.insert(10);
        tree.insert(14);


        // Ausgabe
        tree.printTree(tree, "", true);

      Ausgabe:
      
        ├── 8
        │   ├── 4
        │   │   ├── 2
        │   │   └── 6
        │   └── 12
        │       ├── 10
        │       └── 14





Was ich gelernt habe: 

- Implementierung von Datenstrukturen
- Rekursion (Traversierungen)
- Objektorientierte Programmierung
- Umgang mit Bäumen (Binary Search Tree)


Autor: Khaled El Amri
        
