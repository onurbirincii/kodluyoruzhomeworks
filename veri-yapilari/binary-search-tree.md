# binary seacrh tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1. 7 root olarak atanır
2. 5 root'un soluna atanır
3. 1 sol child'ın soluna atanır
4. 8 root'un sağına atanır
5. 3 3.adımın sağ child'ına atanır
6. 6 5.adımın sağ child'ına atanır
7. 0 3.adımın sol child'ına atanır
8. 9 4.adımın sağ child'ına atanır
9. 4 5.adımın sağ child'ına atanır
10. 2 5.adımın sol child'ına atanır


Bu şekilde, Binary Search Tree oluşturulmuş olur. Bu yapı, verilerin hızlı bir şekilde aranmasını ve sıralanmasını sağlar. Binary Search Tree, herhangi bir durumda en fazla log(n) adımda arama işlemini tamamlar ve bu nedenle Big-O gösterimi olarak O(log(n)) olarak kabul edilir.
