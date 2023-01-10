# Veri-Yap-lar-ve-Algoritmalar-Binary-Search-Tree-Projesi
Binary Search Tree Projesi

Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Root 7 olarak seçtim.
- 5, (7) ile karşılaştırılır. 5<7 bu yüzden rootun soluna gelir,
- 1, (7) ile karşılaştırılır. 1<7 ve 5 ten 5'in soluna gelir,
- 8, (7) ile karşılaştırılır. 8>7 bu yüzden 7'nin sağına gelir,
- 3, (7) ile karşılaştırılır. 3<7 ve 3<5 ve 3>1 bu yüzden 1'in sağına gelir,
- 6, (7) ile karşılaştırılır. 6<7 ve 6>5 bu yüzden 5'in sağına gelir ,
- 0, (7) ile karşılaştırılır. 0<7 ve 0<5 ve 0<1 bu yüzden1'in soluna gelir,
- 9, (7) ile karşılaştırılır. 9>7 ve 9>8 Bu yüzden 8'in sağına gelir,
- 4, (7) ile karşılaştırılır. 4<7 ve 4<5 ve 4>3 bu yüzden 3'ün sağına gelir, 
- 2, (7) ile karşılaştırılır. 2<7 ve 2<5 ve 2<3'ün soluna gelir.
      
    
    
    
        7
       / \
      5   8
     / \   \
    1   3   9
   /     \
  0       6
           \
            4
             \
              2


