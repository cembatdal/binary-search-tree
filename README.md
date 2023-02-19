# binary-search-tree
www.patika.dev için yapılan ödev.

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

root 6'dır.

6'dan küçük sayılar sola, büyük sayılar ise sağa yazılır.

                6
              /   \ 
             5     7      = 5 < 6 - sola, 7 > 6 - sağa yazılır.
           /        \
          1          8    = 1 < 5 - sola, 8 > 7 - sağa yazılır.
        /   \         \
       0     3         9  = 0 < 1 - sola, 3 > 1 - sağa, 9 > 8 - sağa yazılır.
            / \
           2   4          = 2 < 3 - sola, 4 > 3 - sağa yazılır.
